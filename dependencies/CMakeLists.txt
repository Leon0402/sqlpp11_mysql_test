
include(FetchContent)

FetchContent_Declare(sqlpp_mysql
     GIT_REPOSITORY https://github.com/Leon0402/sqlpp11-connector-mysql.git
     GIT_TAG master
)

add_subdirectory(sqlpp_mysql)
