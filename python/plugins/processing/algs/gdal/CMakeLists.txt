file(GLOB PY_FILES *.py)

add_subdirectory(ui)

PLUGIN_INSTALL(processing ./algs/gdal ${PY_FILES})
