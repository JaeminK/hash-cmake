cmake_minimum_required(VERSION 3.5)

project(hash_header_src_sep_directory)

set(SOURCE_CODE src/main.cpp src/testcase.cpp)

add_executable(output ${SOURCE_CODE})

target_include_directories(output PRIVATE 
            ${PROJECT_SOURCE_DIR}/include)