cmake_minimum_required(VERSION 3.10)
set(CMAKE-CXX-STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

set(SOURCES
    main.cpp
)
set (HEADERS
    color.h
    vec3.h
    ray.h
)

include_directories(${PROJECT_SOURCE_DIR}/include)

project(RayTracing)
add_executable(main ${SOURCES} ${$HEADERS})

