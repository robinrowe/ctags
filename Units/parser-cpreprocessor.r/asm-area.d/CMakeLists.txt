# Units_parser-cpreprocessor.r_asm-area.d/CMakeLists.txt
# Created by Robin Rowe 2024-09-24
# License GPL2 open source

set (MODULE_NAME Units_parser-cpreprocessor.r_asm-area.d)
message("Configuring ${MODULE_NAME} 8 source file(s)")
file(STRINGS sources.cmake SOURCES)
add_executable(${MODULE_NAME} ${SOURCES})
