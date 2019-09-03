set(srcs "driver/bme280_support.c"
         "driver/bme280.c")

idf_component_register(SRCS "${srcs}"
                    INCLUDE_DIRS driver
                    REQUIRES driver)