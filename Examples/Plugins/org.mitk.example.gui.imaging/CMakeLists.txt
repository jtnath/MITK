project(org_mitk_example_gui_imaging)

MACRO_CREATE_MITK_CTK_PLUGIN(
  EXPORT_DIRECTIVE EXAMPLES_EXPORT
  EXPORTED_INCLUDE_SUFFIXES src
  MODULE_DEPENDS QmitkExt Segmentation
)
