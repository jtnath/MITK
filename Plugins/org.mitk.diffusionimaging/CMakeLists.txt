project(org_mitk_diffusionimaging)

MACRO_CREATE_MITK_CTK_PLUGIN(
  EXPORT_DIRECTIVE ORG_MITK_DIFFUSIONIMAGING_EXPORT
  EXPORTED_INCLUDE_SUFFIXES src
  MODULE_DEPENDS DiffusionCore Quantification FiberTracking Connectomics QmitkExt
)
