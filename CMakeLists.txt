cmake_minimum_required(VERSION 3.10)

project(fila_dinamica C)

set(CMAKE_C_STANDARD 11)

include_directories(include)

add_executable(fila_dinamica
        src/main.c
        src/pilha_lista.c
        src/no.c
)