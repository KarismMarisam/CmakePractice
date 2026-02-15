aux_source_directory(./ SRC)

INCLUDE_DIRECTORIES(../Print/Head)

link_directories(${LibPath})

link_libraries(${Print})

set(EXECUTABLE_OUTPUT_PATH ${ExePath})

add_executable(result2 ${SRC})