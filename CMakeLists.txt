# CMakeLists.txt
cmake_minimum_required(VERSION 3.10)
project(cpark)

# 设置 C 标准
set(CMAKE_C_STANDARD 99)

# 包含头文件目录
include_directories(include)

# 添加可执行文件
add_executable(cpark src/main.c src/hello.c)