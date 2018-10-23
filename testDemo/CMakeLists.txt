

set(SOURCE_FILES test.cpp)

#include_directory()

link_libraries("/usr/lib/x86_64-linux-gnu/libGL.so"
"/usr/lib/x86_64-linux-gnu/libGLU.so"
"/usr/lib/x86_64-linux-gnu/libglut.so")


add_executable(opengltest ${SOURCE_FILES})