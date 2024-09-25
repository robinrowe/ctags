# Tmain_c-anon-counter.d/CMakeLists.txt
# Created by Robin Rowe 2024-09-24
# License GPL2 open source

set (MODULE_NAME Tmain_c-anon-counter.d)
message("Configuring ${MODULE_NAME} 2 source file(s)")
file(STRINGS sources.cmake SOURCES)
add_executable(${MODULE_NAME} ${SOURCES})
