# misc_packcc_examples_ast-tinyc/CMakeLists.txt
# Created by Robin Rowe 2024-09-24
# License GPL2 open source

set (MODULE_NAME misc_packcc_examples_ast-tinyc)
message("Configuring ${MODULE_NAME} 5 source file(s)")
file(STRINGS sources.cmake SOURCES)
add_executable(${MODULE_NAME} ${SOURCES})
