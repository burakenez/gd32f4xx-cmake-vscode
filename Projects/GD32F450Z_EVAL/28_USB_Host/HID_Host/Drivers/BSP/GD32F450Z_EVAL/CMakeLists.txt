project(GD32F450Z_EVAL LANGUAGES C CXX ASM)

add_library(GD32F450Z_EVAL INTERFACE)

target_include_directories(GD32F450Z_EVAL INTERFACE
    ${DRIVERS_DIR}/BSP/GD32F450Z_EVAL
    )

target_link_libraries(GD32F450Z_EVAL INTERFACE GD32F4xx_standard_peripheral)
