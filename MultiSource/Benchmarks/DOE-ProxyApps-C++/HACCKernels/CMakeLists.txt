set(FP_TOLERANCE 0.00001)
list(APPEND CPPFLAGS -ffast-math -DVERIFICATION_OUTPUT_ONLY=ON)
set(RUN_OPTIONS 450)
llvm_multisource(HACCKernels)
