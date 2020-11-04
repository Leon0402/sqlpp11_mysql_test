
FetchContent_GetProperties(sqlpp_mysql)
if (NOT sqlpp_mysql_POPULATED)
    FetchContent_Populate(sqlpp_mysql)
    add_subdirectory(${sqlpp_mysql_SOURCE_DIR} ${sqlpp_mysql_BINARY_DIR})
endif()
