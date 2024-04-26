cmake_minimum_required(VERSION 3.28)

project(vscode-cmd-truncated)

add_subdirectory(quefacemos)
add_subdirectory(quefacemos2)
add_subdirectory(quefacemos3)
add_subdirectory(quefacemos4)
add_subdirectory(quefacemos5)
add_subdirectory(quefacemos6)
add_subdirectory(quefacemos7)
add_subdirectory(quefacemos8)
add_subdirectory(quefacemos9)
add_subdirectory(quefacemos10)
add_subdirectory(quefacemos11)
add_subdirectory(quefacemos12)
add_subdirectory(quefacemos13)
add_subdirectory(quefacemos14)
add_subdirectory(quefacemos15)
add_subdirectory(quefacemos16)
add_subdirectory(quefacemos17)
add_subdirectory(quefacemos18)
add_subdirectory(quefacemos19)
add_subdirectory(quefacemos20)
add_subdirectory(quefacemos21)
add_subdirectory(quefacemos22)
add_subdirectory(quefacemos23)
add_subdirectory(quefacemos24/quefacemos25/quefacemos26/quefacemos27)
add_subdirectory(quefacemos25)


SET(CMAKE_EXPORT_COMPILE_COMMANDS ON)
add_executable(vscode-cmd-truncated main.cpp)
target_include_directories(vscode-cmd-truncated 
PRIVATE 
quefacemos/Include
quefacemos2/Include 
quefacemos3/Include 
quefacemos4/Include
quefacemos5/Include
#quefacemos6/Include
#quefacemos7/Include
#quefacemos8/Include
#quefacemos9/Include
#quefacemos10/Include
#quefacemos11/Include
#quefacemos12/Include
#quefacemos13/Include
#quefacemos14/Include
#quefacemos15/Include
#quefacemos16/Include
#quefacemos17/Include
#quefacemos18/Include
#quefacemos19/Include
#quefacemos20/Include
#quefacemos21/Include
#quefacemos22/Include
#quefacemos23/Include
#quefacemos24/Include
#quefacemos24/quefacemos25/quefacemos26/quefacemos27/Include
#quefacemos25/Include
) 

#target_link_libraries(concurrency_examples PRIVATE adder::adder)