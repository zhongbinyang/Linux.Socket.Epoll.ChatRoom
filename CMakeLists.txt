cmake_minimum_required(VERSION 3.16)
project(test_socket)

set(CMAKE_CXX_STANDARD 14)

add_executable(test_socket_client Client.cpp ClientMain.cpp)
add_executable(test_socket_server Server.cpp ServerMain.cpp)