cmake_minimum_required(VERSION 3.10)
project(cplayer CXX)

set(SOURCE_FILES src/cplayer.cpp)

add_executable(${PROJECT_NAME} ${SOURCE_FILES})

# mkdir cmake-build-debug
# cd cmake-build-debug
# cmake .. -G "MinGW Makefiles"
# mingw32-make