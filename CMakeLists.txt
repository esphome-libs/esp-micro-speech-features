file(GLOB SRC_FILES "src/*.c")

idf_component_register(
    SRCS ${SRC_FILES}
    INCLUDE_DIRS "include"
    PRIV_INCLUDE_DIRS "src"
)
