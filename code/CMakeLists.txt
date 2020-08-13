set(libassimp_sources
    # 3DS/3DSConverter.cpp
    # 3DS/3DSExporter.cpp
    # 3DS/3DSLoader.cpp
    # 3MF/D3MFExporter.cpp
    # 3MF/D3MFImporter.cpp
    # 3MF/D3MFOpcPackage.cpp
    # AC/ACLoader.cpp
    # AMF/AMFImporter.cpp
    # AMF/AMFImporter_Geometry.cpp
    # AMF/AMFImporter_Material.cpp
    # AMF/AMFImporter_Postprocess.cpp
    # ASE/ASELoader.cpp
    # ASE/ASEParser.cpp
    Assbin/AssbinExporter.cpp
    Assbin/AssbinLoader.cpp
    # Assjson/json_exporter.cpp
    # Assjson/mesh_splitter.cpp
    # Assxml/AssxmlExporter.cpp
    # B3D/B3DImporter.cpp
    # BVH/BVHLoader.cpp
    # Blender/BlenderBMesh.cpp
    # Blender/BlenderCustomData.cpp
    # Blender/BlenderDNA.cpp
    # Blender/BlenderLoader.cpp
    # Blender/BlenderModifier.cpp
    # Blender/BlenderScene.cpp
    # Blender/BlenderTessellator.cpp
    # C4D/C4DImporter.cpp
    CApi/AssimpCExport.cpp
    CApi/CInterfaceIOWrapper.cpp
    # COB/COBLoader.cpp
    # CSM/CSMLoader.cpp
    # Collada/ColladaExporter.cpp
    # Collada/ColladaLoader.cpp
    # Collada/ColladaParser.cpp
    Common/Assimp.cpp
    Common/BaseImporter.cpp
    Common/BaseProcess.cpp
    Common/Bitmap.cpp
    Common/CreateAnimMesh.cpp
    Common/DefaultIOStream.cpp
    Common/DefaultIOSystem.cpp
    Common/DefaultLogger.cpp
    # Common/Exporter.cpp
    Common/Importer.cpp
    Common/ImporterRegistry.cpp
    Common/PostStepRegistry.cpp
    # Common/RemoveComments.cpp
    # Common/SGSpatialSort.cpp
    Common/SceneCombiner.cpp
    Common/ScenePreprocessor.cpp
    # Common/SkeletonMeshBuilder.cpp
    Common/SpatialSort.cpp
    Common/SplitByBoneCountProcess.cpp
    # Common/StandardShapes.cpp
    # Common/Subdivision.cpp
    # Common/TargetAnimation.cpp
    Common/Version.cpp
    Common/VertexTriangleAdjacency.cpp
    Common/ZipArchiveIOSystem.cpp
    Common/scene.cpp
    Common/simd.cpp
    # DXF/DXFLoader.cpp
    # FBX/FBXAnimation.cpp
    # FBX/FBXBinaryTokenizer.cpp
    # FBX/FBXConverter.cpp
    # FBX/FBXDeformer.cpp
    # FBX/FBXDocument.cpp
    # FBX/FBXDocumentUtil.cpp
    # FBX/FBXExportNode.cpp
    # FBX/FBXExportProperty.cpp
    # FBX/FBXExporter.cpp
    # FBX/FBXImporter.cpp
    # FBX/FBXMaterial.cpp
    # FBX/FBXMeshGeometry.cpp
    # FBX/FBXModel.cpp
    # FBX/FBXNodeAttribute.cpp
    # FBX/FBXParser.cpp
    # FBX/FBXProperties.cpp
    # FBX/FBXTokenizer.cpp
    # FBX/FBXUtil.cpp
    # HMP/HMPLoader.cpp
    # Importer/IFC/IFCBoolean.cpp
    # Importer/IFC/IFCCurve.cpp
    # Importer/IFC/IFCGeometry.cpp
    # Importer/IFC/IFCLoader.cpp
    # Importer/IFC/IFCMaterial.cpp
    # Importer/IFC/IFCOpenings.cpp
    # Importer/IFC/IFCProfile.cpp
    # Importer/IFC/IFCReaderGen1_2x3.cpp
    # Importer/IFC/IFCReaderGen2_2x3.cpp
    # Importer/IFC/IFCReaderGen_4.cpp
    # Importer/IFC/IFCUtil.cpp
    # Importer/STEPParser/STEPFileEncoding.cpp
    # Importer/STEPParser/STEPFileReader.cpp
    # Importer/StepFile/StepFileGen1.cpp
    # Importer/StepFile/StepFileGen2.cpp
    # Importer/StepFile/StepFileGen3.cpp
    # Importer/StepFile/StepFileImporter.cpp
    # Irr/IRRLoader.cpp
    # Irr/IRRMeshLoader.cpp
    # Irr/IRRShared.cpp
    # LWO/LWOAnimation.cpp
    # LWO/LWOBLoader.cpp
    # LWO/LWOLoader.cpp
    # LWO/LWOMaterial.cpp
    # LWS/LWSLoader.cpp
    # MD2/MD2Loader.cpp
    # MD3/MD3Loader.cpp
    # MD5/MD5Loader.cpp
    # MD5/MD5Parser.cpp
    # MDC/MDCLoader.cpp
    # MDL/MDLLoader.cpp
    # MDL/MDLMaterialLoader.cpp
    # MMD/MMDImporter.cpp
    # MMD/MMDPmxParser.cpp
    # MS3D/MS3DLoader.cpp
    Material/MaterialSystem.cpp
    # NDO/NDOLoader.cpp
    # NFF/NFFLoader.cpp
    # OFF/OFFLoader.cpp
    # Obj/ObjExporter.cpp
    Obj/ObjFileImporter.cpp
    Obj/ObjFileMtlImporter.cpp
    Obj/ObjFileParser.cpp
    # Ogre/OgreBinarySerializer.cpp
    # Ogre/OgreImporter.cpp
    # Ogre/OgreMaterial.cpp
    # Ogre/OgreStructs.cpp
    # Ogre/OgreXmlSerializer.cpp
    # OpenGEX/OpenGEXExporter.cpp
    # OpenGEX/OpenGEXImporter.cpp
    # Ply/PlyExporter.cpp
    # Ply/PlyLoader.cpp
    # Ply/PlyParser.cpp
    PostProcessing/CalcTangentsProcess.cpp
    PostProcessing/ComputeUVMappingProcess.cpp
    PostProcessing/ConvertToLHProcess.cpp
    PostProcessing/DeboneProcess.cpp
    PostProcessing/DropFaceNormalsProcess.cpp
    PostProcessing/EmbedTexturesProcess.cpp
    PostProcessing/FindDegenerates.cpp
    PostProcessing/FindInstancesProcess.cpp
    PostProcessing/FindInvalidDataProcess.cpp
    PostProcessing/FixNormalsStep.cpp
    PostProcessing/GenBoundingBoxesProcess.cpp
    PostProcessing/GenFaceNormalsProcess.cpp
    PostProcessing/GenVertexNormalsProcess.cpp
    PostProcessing/ImproveCacheLocality.cpp
    PostProcessing/JoinVerticesProcess.cpp
    PostProcessing/LimitBoneWeightsProcess.cpp
    # PostProcessing/MakeVerboseFormat.cpp
    PostProcessing/OptimizeGraph.cpp
    PostProcessing/OptimizeMeshes.cpp
    PostProcessing/PretransformVertices.cpp
    PostProcessing/ProcessHelper.cpp
    PostProcessing/RemoveRedundantMaterials.cpp
    PostProcessing/RemoveVCProcess.cpp
    PostProcessing/ScaleProcess.cpp
    PostProcessing/SortByPTypeProcess.cpp
    PostProcessing/SplitLargeMeshes.cpp
    PostProcessing/TextureTransform.cpp
    PostProcessing/TriangulateProcess.cpp
    PostProcessing/ValidateDataStructure.cpp
    # Q3BSP/Q3BSPFileImporter.cpp
    # Q3BSP/Q3BSPFileParser.cpp
    # Q3D/Q3DLoader.cpp
    # Raw/RawLoader.cpp
    # SIB/SIBImporter.cpp
    # SMD/SMDLoader.cpp
    # STL/STLExporter.cpp
    STL/STLLoader.cpp
    # Step/StepExporter.cpp
    # Terragen/TerragenLoader.cpp
    # Unreal/UnrealLoader.cpp
    # X/XFileExporter.cpp
    # X/XFileImporter.cpp
    # X/XFileParser.cpp
    # X3D/FIReader.cpp
    # X3D/X3DExporter.cpp
    # X3D/X3DImporter.cpp
    # X3D/X3DImporter_Geometry2D.cpp
    # X3D/X3DImporter_Geometry3D.cpp
    # X3D/X3DImporter_Group.cpp
    # X3D/X3DImporter_Light.cpp
    # X3D/X3DImporter_Metadata.cpp
    # X3D/X3DImporter_Networking.cpp
    # X3D/X3DImporter_Postprocess.cpp
    # X3D/X3DImporter_Rendering.cpp
    # X3D/X3DImporter_Shape.cpp
    # X3D/X3DImporter_Texturing.cpp
    # X3D/X3DVocabulary.cpp
    # XGL/XGLLoader.cpp
    # glTF/glTFCommon.cpp
    # glTF/glTFExporter.cpp
    # glTF/glTFImporter.cpp
    # glTF2/glTF2Exporter.cpp
    # glTF2/glTF2Importer.cpp

    ${PROJECT_SOURCE_DIR}/contrib/clipper/clipper.cpp
    ${PROJECT_SOURCE_DIR}/contrib/irrXML/irrXML.cpp

    ${PROJECT_SOURCE_DIR}/contrib/poly2tri/poly2tri/sweep/cdt.cc
    ${PROJECT_SOURCE_DIR}/contrib/poly2tri/poly2tri/sweep/sweep_context.cc
    ${PROJECT_SOURCE_DIR}/contrib/poly2tri/poly2tri/sweep/advancing_front.cc
    ${PROJECT_SOURCE_DIR}/contrib/poly2tri/poly2tri/sweep/sweep.cc
    ${PROJECT_SOURCE_DIR}/contrib/poly2tri/poly2tri/common/shapes.cc

    ${PROJECT_SOURCE_DIR}/contrib/zlib/adler32.c
    ${PROJECT_SOURCE_DIR}/contrib/zlib/compress.c
    ${PROJECT_SOURCE_DIR}/contrib/zlib/crc32.c
    ${PROJECT_SOURCE_DIR}/contrib/zlib/deflate.c
    ${PROJECT_SOURCE_DIR}/contrib/zlib/inffast.c
    ${PROJECT_SOURCE_DIR}/contrib/zlib/inflate.c
    ${PROJECT_SOURCE_DIR}/contrib/zlib/inftrees.c
    ${PROJECT_SOURCE_DIR}/contrib/zlib/trees.c
    ${PROJECT_SOURCE_DIR}/contrib/zlib/uncompr.c
    ${PROJECT_SOURCE_DIR}/contrib/zlib/zutil.c)

    set(assim_src ${libassimp_sources})
    set(LIMITEDASSIMPDEFINES
        "\"-DASSIMP_BUILD_NO_X_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_3DS_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_MD3_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_MDL_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_MD2_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_PLY_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_ASE_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_HMP_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_SMD_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_MDC_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_MD5_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_LWO_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_DXF_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_NFF_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_RAW_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_OFF_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_AC_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_BVH_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_IRRMESH_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_IRR_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_Q3D_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_B3D_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_COLLADA_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_TERRAGEN_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_CSM_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_3D_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_LWS_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_OGRE_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_MS3D_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_COB_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_BLEND_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_Q3BSP_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_NDO_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_IFC_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_M3_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_XGL_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_C4D_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_MMD_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_SIB_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_D3M_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_GLTF_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_OPENGEX_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_STEP_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_FBX_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_X3D_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_3MF_IMPORTER\""
        "\"-DASSIMP_BUILD_NO_AMF_IMPORTER\""
        "\"-DASSIMP_BUILD_BOOST_WORKAROUND\""
        "\"-D_CRT_SECURE_NO_WARNINGS\"")
    add_definitions(${LIMITEDASSIMPDEFINES})

include_directories(
    ${CMAKE_CURRENT_SOURCE_DIR}/..
    ${CMAKE_CURRENT_SOURCE_DIR}
    "../contrib/zlib/"
    "../contrib/irrXML/"
    )

find_package(FopenHack REQUIRED)

add_library(assimp STATIC ${assim_src})

target_link_libraries(assimp FopenHack::fopen_hack)

use_standard_flags(assimp)

# assimp can #include "unzip.h"
if(UNZIP_FOUND)
    include_directories(${UNZIP_INCLUDE_DIRS})
    target_link_libraries(assimp ${UNZIP_LIBRARIES})
else()
    include_directories("../contrib/unzip")
endif()

install(
    DIRECTORY ${PROJECT_SOURCE_DIR}/include/
    DESTINATION ${HEADER_INSTALL_DIR})

#export_api(assimp ASSIMP_API)
export_and_install_targets(TARGETS assimp)
generate_and_install_config(NAME Assimp)
