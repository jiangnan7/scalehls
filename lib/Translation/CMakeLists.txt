add_mlir_library(MLIRScaleHLSEmitHLSCpp
  EmitHLSCpp.cpp

  LINK_LIBS PUBLIC
  MLIRHLS
  MLIRScaleHLSSupport
  )
