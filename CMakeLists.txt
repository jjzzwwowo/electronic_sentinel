cmake_minimum_required(VERSION 3.10)
project(electronic_sentinel LANGUAGES CXX)

# 设置使用现代 C++17 标准（自动驾驶/机器人通用）
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# 指定头文件搜索路径为 include 文件夹
include_directories(include)

# 自动扫描 src 目录下的所有 .cpp 源码文件
file(GLOB_RECURSE SOURCES "src/*.cpp")

# 生成可执行文件
add_executable(electronic_sentinel ${SOURCES})
