cmake_minimum_required(VERSION 3.27)
project(udp_test)

set(CMAKE_CXX_STANDARD 17)

add_executable(server server.cpp)
add_executable(client1 client1.cpp)
add_executable(client2 client2.cpp)
