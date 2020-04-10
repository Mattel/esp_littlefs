set(COMPONENT_SRCDIRS
        "src"
        "src/littlefs"
)

set(COMPONENT_ADD_INCLUDEDIRS
        "include"
        "src"
)

set(COMPONENT_REQUIRES
        "spi_flash"
)

register_component()
