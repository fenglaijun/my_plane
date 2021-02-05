idf_component_register(SRCS "bmp280.c" "bstdr_comm_support.c"
                       INCLUDE_DIRS "." "include"
                        REQUIRES i2c_bus
                        PRIV_REQUIRES utils platform config)