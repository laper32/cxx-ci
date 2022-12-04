find_package(Boost REQUIRED)

add_executable(main main.cpp)

target_link_libraries(main PUBLIC Boost::boost)