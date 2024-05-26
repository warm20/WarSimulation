cmake_minimum_required(VERSION 3.0)

project(WarSimulation)

aux_source_directory(${PROJECT_BINARY_DIR}/../src SRC_LIST)

add_executable(${PROJECT_NAME} ${SRC_LIST})