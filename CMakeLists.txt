cmake_minimum_required (VERSION 3.5.0)

add_subdirectory(console_test)

if (WIN32)
  add_subdirectory(window_test)
endif()