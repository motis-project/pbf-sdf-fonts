cmake_minimum_required(VERSION 3.0)
project(pbf-sdf-fonts)

file(GLOB_RECURSE pbf-sdf-fonts-res "${CMAKE_CURRENT_SOURCE_DIR}/res/*.*")
create_resource("${CMAKE_CURRENT_SOURCE_DIR}/res/" "${pbf-sdf-fonts-res}" pbf_sdf_fonts_res)
