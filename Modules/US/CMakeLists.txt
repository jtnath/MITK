MITK_CREATE_MODULE(MitkUS
  SUBPROJECTS
  INCLUDE_DIRS USControlInterfaces USFilters USModel USService
  INTERNAL_INCLUDE_DIRS ${INCLUDE_DIRS_INTERNAL}
  DEPENDS Mitk mitkOpenCVVideoSupport Qmitk QmitkExt
)

## create US config
#CONFIGURE_FILE(mitkUSConfig.h.in ${PROJECT_BINARY_DIR}/mitkUSConfig.h @ONLY)

ADD_SUBDIRECTORY(USHardwareTelemed)

ADD_SUBDIRECTORY(Testing)
