cmake_minimum_required(VERSION 3.29)
project(Gestion_de_Memoria_Ignacio_de_Rojas C)

set(CMAKE_C_STANDARD 11)

add_executable(Gestion_de_Memoria_Ignacio_de_Rojas
    main.c
    sys/mman.h
    sys/wait.h
)
