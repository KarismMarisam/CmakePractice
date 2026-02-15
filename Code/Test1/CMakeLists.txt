aux_source_directory(./ SRC)

INCLUDE_DIRECTORIES(../Calcu/Head)

link_directories(${LibPath})

link_libraries(${Calcu})

set(EXECUTABLE_OUTPUT_PATH ${ExePath})

add_executable(result1 ${SRC})