set(LLVM_LINK_COMPONENTS
  Demangle
  Support
)

add_llvm_unittest(DemangleTests
  DemangleTest.cpp
  ItaniumDemangleTest.cpp
  OutputStreamTest.cpp
  PartialDemangleTest.cpp
  RustDemangleTest.cpp
  StringViewTest.cpp
)
