cmake_minimum_required(VERSION 3.25)
project(PAA_Trab1)

set(CMAKE_CXX_STANDARD 14)

include_directories(Implementacao/Headers)

add_executable(PAA_Trab1
        Implementacao/Headers/KnapSack.h
        Implementacao/Headers/load.h
        Implementacao/Headers/MatrizNormal.h
        Implementacao/Headers/MatrizStrassen.h
        Implementacao/Headers/Menu.h
        Implementacao/Headers/TesteKnapSack.h
        Implementacao/Headers/TesteMatrizNormal.h
        Implementacao/Headers/TesteMatrizStrassen.h
        Implementacao/Source/KnapSack.c
        Implementacao/Source/load.c
        Implementacao/Source/main.c
        Implementacao/Source/MatrizNormal.c
        Implementacao/Source/Menu.c
        Implementacao/Source/TesteKnapSack.c
        Implementacao/Source/TesteMatrizNormal.c
        Implementacao/Source/TesteMatrizStrassen.c
        Implementacao/Testes/KnapSack200x900.txt
        Implementacao/Testes/KnapSack4x10.txt
        Implementacao/Testes/KnapSack500x1200.txt
        Implementacao/Testes/teste16x16.txt
        Implementacao/Testes/teste2x2.txt
        Implementacao/Testes/teste64x64.txt)
