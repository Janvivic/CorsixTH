project(RncLib)

add_library(RncLib)

target_sources(RncLib PRIVATE
  ${CMAKE_CURRENT_SOURCE_DIR}/rnc.cpp
  ${CMAKE_CURRENT_SOURCE_DIR}/rnc.h
)

set_property(TARGET RncLib PROPERTY CXX_STANDARD 14)
set_property(TARGET RncLib PROPERTY CXX_EXTENSIONS OFF)
set_property(TARGET RncLib PROPERTY CXX_STANDARD_REQUIRED ON)
