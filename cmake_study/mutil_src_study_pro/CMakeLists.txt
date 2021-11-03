cmake_minimum_required(VERSION 2.8)

project(Demo)

aux_source_directory(. SRc_LIST)

add_executable(test ${SRc_LIST})
