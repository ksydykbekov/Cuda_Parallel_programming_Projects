cmake_minimum_required(VERSION 3.6)
project(Cuda_Parallel_Programming)

find_package(CUDA QUIET REQUIRED)

cuda_add_executable(main main.cu)
