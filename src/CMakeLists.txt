
add_executable(sss)
target_link_libraries(sss PUBLIC sqlpp-mysql::sqlpp-mysql)

target_sources(sss PRIVATE main.cpp)
