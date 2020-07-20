add_executable(hough houghLines.c)
target_link_libraries(hough ${OpenCV_LIBS} ${VXA_LIBRARIES} ${OPENVX_LIBRARIES})

add_executable(houghEx houghLinesEx.c)
target_link_libraries(houghEx ${OpenCV_LIBS} ${VXA_LIBRARIES} ${OPENVX_LIBRARIES})

