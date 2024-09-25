# Units_parser-cxx.r_import-5.d/CMakeLists.txt
# Created by Robin Rowe 2024-09-24
# License GPL2 open source

set (MODULE_NAME Units_parser-cxx.r_import-5.d)
message("Configuring ${MODULE_NAME} 9 source file(s)")
file(STRINGS sources.cmake SOURCES)
add_executable(${MODULE_NAME} ${SOURCES})
