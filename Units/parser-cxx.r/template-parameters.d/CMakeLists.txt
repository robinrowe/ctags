# Units_parser-cxx.r_template-parameters.d/CMakeLists.txt
# Created by Robin Rowe 2024-09-24
# License GPL2 open source

set (MODULE_NAME Units_parser-cxx.r_template-parameters.d)
message("Configuring ${MODULE_NAME} 1 source file(s)")
file(STRINGS sources.cmake SOURCES)
add_executable(${MODULE_NAME} ${SOURCES})
