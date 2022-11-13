cmake_minimum_required(VERSION 3.2)

set(ProjectName "te_output")
# set(ProjectName "unary_poly_link")

project(${ProjectName})

# set_target_properties(/include)
# set_source_files_properties(./src)
set(CMAKE_EXPORT_COMPILECOMMANDS ON)

include_directories(${CMAKE_CURRENT_SOURCE_DIR}/../include)
add_executable(${ProjectName} ./main.cpp ./src/xxx.cpp ./src/xxx.cpp)