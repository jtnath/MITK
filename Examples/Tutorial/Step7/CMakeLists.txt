include_directories(${CMAKE_CURRENT_SOURCE_DIR}/../Step6)

mitk_create_executable(Step7
  DEPENDS QmitkExt
  PACKAGE_DEPENDS ITK|ITKCurvatureFlow+ITKRegionGrowing
  )
