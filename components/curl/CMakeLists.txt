idf_component_register(
    SRC_DIRS "lib" "lib/vauth" "lib/vtls"
    INCLUDE_DIRS "include"
    PRIV_INCLUDE_DIRS "lib"
    REQUIRES libssh2
    REQUIRES zlib
)
add_definitions(-DHAVE_CONFIG_H -DBUILDING_LIBCURL)