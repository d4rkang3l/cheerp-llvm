add_llvm_library(LLVMCheerpWriter
  SourceMaps.cpp
  CheerpWriter.cpp
  CheerpWastWriter.cpp
  JSInterop.cpp
  LinearMemoryHelper.cpp
  NameGenerator.cpp
  Relooper.cpp
  Types.cpp
  Opcodes.cpp
  CommandLine.cpp
  )

add_dependencies(LLVMCheerpWriter intrinsics_gen)
