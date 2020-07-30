add_library(LibTarget lib.cxx lib.h)
target_include_directories(LibTarget PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
