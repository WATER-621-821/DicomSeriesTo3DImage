cmake_minimum_required(VERSION 2.8)
 
PROJECT(DicomSeriesReadW)
 
find_package(ITK REQUIRED)
include(${ITK_USE_FILE})
 
add_executable(DicomSeriesReadW MACOSX_BUNDLE DicomSeriesReadImageWrite2 )
target_link_libraries(DicomSeriesReadW  ${ITK_LIBRARIES})
