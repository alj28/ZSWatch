# TODO:
# Weird compilation issue when not using
# zephyr_library()
# zephyr_library_sources(apds9306.c)
#
# -> ..add_library cannot create target "..__app__drivers__sensor" because another
# -> target with the same name already exists.  The existing target is a static...
#
add_subdirectory_ifdef(CONFIG_INPUT_MODIFIED_CST816S cst816s)