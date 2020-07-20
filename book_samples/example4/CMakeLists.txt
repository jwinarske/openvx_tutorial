add_executable(example4 example4.c)
target_link_libraries(example4 ${VXU_LIBRARIES} ${OPENVX_LIBRARIES})

add_executable(example4a example4a.c ../ppm-io/writeImage.c)
target_link_libraries(example4a ${VXU_LIBRARIES} ${OPENVX_LIBRARIES})

add_executable(changeImage changeImage.c ../ppm-io/writeImage.c ../ppm-io/readImage.c)
target_link_libraries(changeImage ${VXU_LIBRARIES} ${OPENVX_LIBRARIES})

