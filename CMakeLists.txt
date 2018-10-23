

#cmake min version
cmake_minimum_required(VERSION 3.5)

#project name
project(OpengGLTest)

set(CAMEK_BUILD_TYPE DEBUG)

#设置编译器的类型
set(CMAKE_CXX_FLAGS_DEBUG "-g -Wall")

#包含原程序,即把给定目录下的源程序复制给变量DIR_SRC
#aux_source_directory (./ DIR_SRC)

add_subdirectory(testDemo)

