
#头文件包含路径
include_directories(
    ./include
    )

#公共链接库目录
link_directories(
    ./lib
    )

set(EXECUTABLE_OUTPUT_PATH ${EXECUTABLE_OUTPUT_PATH}/gflags-2.2.2)

add_subdirectory(test)