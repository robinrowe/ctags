# Tmain_option-exclude-including-fsep.d_input.d_labze-a/CMakeLists.txt
# Created by Robin Rowe 2024-09-24
# License GPL2 open source

set (MODULE_NAME Tmain_option-exclude-including-fsep.d_input.d_labze-a)
message("Configuring ${MODULE_NAME} 1 source file(s)")
file(STRINGS sources.cmake SOURCES)
add_executable(${MODULE_NAME} ${SOURCES})
