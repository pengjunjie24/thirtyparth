
#头文件包含路径
include_directories(
    ./include
    )

#公共链接库目录
link_directories(
    ./lib64
    )

set(EXECUTABLE_OUTPUT_PATH ${EXECUTABLE_OUTPUT_PATH}/googletest-1.10.0)

add_subdirectory(samples)