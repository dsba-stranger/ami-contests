cmake_minimum_required(VERSION 3.15)
project(contest1)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall -Wextra -Werror --std=c++17 -g")

add_executable(A A.cpp)
add_executable(B C.cpp)
add_executable(C C.cpp)

add_executable(D D.cpp)

add_executable(F F.cpp)

add_executable(G G.cpp)

add_executable(I I.cpp)

add_executable(J J.cpp)

add_executable(K K.cpp)

add_executable(L L.cpp)

add_executable(M M.cpp)

add_executable(E E.cpp)

add_executable(H H.cpp)
add_executable(N N.cpp)