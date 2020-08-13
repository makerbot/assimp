
cmake_minimum_required(VERSION 3.1)

project(Assimp CXX)
find_package(MBCMakeTools REQUIRED)

if(CMAKE_COMPILER_IS_GNUCC OR CMAKE_COMPILER_IS_GNUCXX)
    add_definitions(-fPIC)
    add_definitions(-std=c++11)
    add_definitions(-fvisibility=hidden)
endif()

CONFIGURE_FILE(
  ${CMAKE_CURRENT_LIST_DIR}/include/assimp/config.h.in
  ${CMAKE_CURRENT_BINARY_DIR}/include/assimp/config.h
)
include_directories(
  include
  ${CMAKE_CURRENT_BINARY_DIR}/include
)

set(CMAKE_MODULE_PATH "${CMAKE_CURRENT_SOURCE_DIR}/cmake-modules")
set(ENABLE_BOOST_WORKAROUND OFF CACHE BOOL
    "If a simple implementation of the used Boost functions is used.
    Slightly reduces functionality,
    but enables builds without Boost available.")

if(ENABLE_BOOST_WORKAROUND)
    include_directories(code/BoostWorkaround)
    add_definitions(-DASSIMP_BUILD_BOOST_WORKAROUND)
    message(STATUS "Building a non-boost version of Assimp.")
else()
    set(Boost_DETAILED_FAILURE_MSG ON)
    find_package(Boost REQUIRED MODULE)
    if(NOT Boost_FOUND)
        message(FATAL_ERROR
        "Boost libraries(http://www.boost.org/) not found. "
        "You can build a non-boost version of Assimp with slightly reduced "
        "functionality by specifying -DENABLE_BOOST_WORKAROUND=ON.")
    endif()
    include_directories(${Boost_INCLUDE_DIRS})
endif()

set(NO_EXPORT OFF CACHE BOOL
    "Disable Assimp's export functionality.")
if(NO_EXPORT)
    add_definitions(-DASSIMP_BUILD_NO_EXPORT)
    message(STATUS "Build an import-only version of Assimp.")
endif()

add_subdirectory(code/)
