
include(FetchContent)

FetchContent_Declare(sqlpp11
    GIT_REPOSITORY  https://github.com/GCarneiroA/sqlpp11
    GIT_TAG         origin/dependencies
)

FetchContent_Declare(sqlpp_mysql
    GIT_REPOSITORY  https://github.com/GCarneiroA/mysql-connector
    GIT_TAG         origin/master
)

add_subdirectory(sqlpp_mysql)
#add_subdirectory(sqlpp11)
