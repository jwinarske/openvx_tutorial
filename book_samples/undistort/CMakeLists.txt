add_executable(undistort undistort-remap.c)
target_link_libraries(undistort ${OpenCV_LIBS} ${VXA_LIBRARIES} ${OPENVX_LIBRARIES})

add_executable(undistortOpenCV undistortOpenCV.cpp)
target_link_libraries(undistortOpenCV ${OpenCV_LIBS})

