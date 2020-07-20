add_executable(filterImage filterImage.c ../ppm-io/readImage.c ../ppm-io/writeImage.c)
target_link_libraries(filterImage ${OPENVX_LIBRARIES})

add_executable(filterImageROI filterImageROI.c ../ppm-io/readImage.c ../ppm-io/writeImage.c)
target_link_libraries(filterImageROI ${OPENVX_LIBRARIES})

add_executable(filterImageROIvxu filterImageROIvxu.c ../ppm-io/readImage.c ../ppm-io/writeImage.c)
target_link_libraries(filterImageROIvxu ${OPENVX_LIBRARIES} ${VXU_LIBRARIES})

