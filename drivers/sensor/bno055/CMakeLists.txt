zephyr_library()
zephyr_library_sources_ifdef(CONFIG_BNO055 bno055.c)