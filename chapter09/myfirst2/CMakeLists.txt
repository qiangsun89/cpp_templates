cmake_minimum_required(VERSION 3.16)
project(myfirst2)
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)
add_executable(${PROJECT_NAME} myfirstmain.cpp)
# target_sources(${PROJECT_NAME} PRIVATE
#                 myfirst.cpp 
#                 myfirstmain.cpp)