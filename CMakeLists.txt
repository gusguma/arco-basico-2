cmake_minimum_required(VERSION 3.23)
project(basico_2 CUDA)

set(CMAKE_CUDA_STANDARD 14)

add_executable(basico_2 main.cu)

set_target_properties(basico_2 PROPERTIES
        CUDA_SEPARABLE_COMPILATION ON)
