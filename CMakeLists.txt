cmake_minimum_required(VERSION 3.16)

# Nombre del proyecto
project(SistemaMonitoreo VERSION 1.0)

# Estándar de C++
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Crear el ejecutable
add_executable(${PROJECT_NAME}
    src/main.cpp
)