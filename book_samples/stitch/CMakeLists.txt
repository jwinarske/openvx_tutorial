add_executable(stitch stitch.c)
target_link_libraries(stitch ${OpenCV_LIBS} ${VXA_LIBRARIES} ${OPENVX_LIBRARIES})

add_executable(stitch-debug stitch-debug.c)
target_link_libraries(stitch-debug ${OpenCV_LIBS} ${VXA_LIBRARIES} ${OPENVX_LIBRARIES})

add_executable(stitch-multiband stitch-multiband.c)
target_link_libraries(stitch-multiband ${OpenCV_LIBS} ${VXA_LIBRARIES} ${OPENVX_LIBRARIES})

add_executable(homography homography-opencv.cpp)
target_link_libraries(homography ${OpenCV_LIBS})

add_executable(homography-multiband homography-multiband-opencv.cpp)
target_link_libraries(homography-multiband ${OpenCV_LIBS})

