# Units_parser-cpreprocessor.r_skip-newlines-in-literals.d/CMakeLists.txt
# Created by Robin Rowe 2024-09-24
# License GPL2 open source

set (MODULE_NAME Units_parser-cpreprocessor.r_skip-newlines-in-literals.d)
message("Configuring ${MODULE_NAME} 3 source file(s)")
file(STRINGS sources.cmake SOURCES)
add_executable(${MODULE_NAME} ${SOURCES})
