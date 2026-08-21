include_directories(
  ${qucs-core_CURRENT_SOURCE_DIR}
  ${qucs-core_SOURCE_DIR}/src/math
  ${qucs-core_SOURCE_DIR}/src/components
  ${qucs-core_SOURCE_DIR}/src/components/devices
  ${CMAKE_CURRENT_SOURCE_DIR}/misc
  ${CMAKE_CURRENT_SOURCE_DIR}/microstrip
  ${CMAKE_CURRENT_SOURCE_DIR}/CPW)

add_subdirectory(misc)
add_subdirectory(microstrip)
add_subdirectory(CPW)
