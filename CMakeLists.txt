cmake_minimum_required(VERSION 2.8)

project ( display )

find_package( OpenCV 3.3.0 REQUIRED )

include_directories( ${OpenCV_INCLUDE_DIRS} )

add_executable( display main.cpp)

target_link_libraries( display ${OpenCV_LIBS})




