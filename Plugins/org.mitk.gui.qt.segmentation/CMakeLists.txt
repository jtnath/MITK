project(org_mitk_gui_qt_segmentation)

include_directories(${CTK_INCLUDE_DIRS})

MACRO_CREATE_MITK_CTK_PLUGIN(
  EXPORT_DIRECTIVE MITK_QT_SEGMENTATION
  EXPORTED_INCLUDE_SUFFIXES src
  MODULE_DEPENDS QmitkExt ClippingTools Segmentation SegmentationUI
)
