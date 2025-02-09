# 生成可执行文件
add_executable(cpark_main main.c)

# 链接 hello 库
target_link_libraries(cpark_main PRIVATE hello_lib)