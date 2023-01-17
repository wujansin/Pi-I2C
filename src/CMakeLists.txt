cmake_minimum_required(VERSION 2.6)
project(i2c_gpio_test)
add_executable(i2c_test i2c_test.cpp)
target_link_libraries(i2c_test wiringPi)
