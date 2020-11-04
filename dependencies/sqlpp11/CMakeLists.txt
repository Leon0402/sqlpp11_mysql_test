
FetchContent_GetProperties(sqlpp11)
if (NOT sqlpp11_POPULATED)
    FetchContent_Populate(sqlpp11)
    add_subdirectory(${sqlpp11_SOURCE_DIR} ${sqlpp11_BINARY_DIR})
endif()
