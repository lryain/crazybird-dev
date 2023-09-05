idf_component_register(SRCS "lps25h.c"
                       INCLUDE_DIRS "." "include"
                       REQUIRES i2c_bus 
                       PRIV_REQUIRES crazyflie platform)