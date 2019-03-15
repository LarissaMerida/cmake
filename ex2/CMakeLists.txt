#versão minima
cmake_minimum_required(VERSION 3.4)

#configura nome doprojeto
project(hello)

#determina que um exe é criado e o caminho FONTE para construir
add_executable(hello helloworld.cpp)