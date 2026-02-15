
file(GLOB SRC Srcs/*.cpp)

set(LIBRARY_OUTPUT_PATH ${LibPath})

INCLUDE_DIRECTORIES(Head)

add_library(${Calcu} STATIC ${SRC})