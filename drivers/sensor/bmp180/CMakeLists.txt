zephyr_library()
zephyr_library_sources_ifdef(CONFIG_BMP180 bmp180.c)