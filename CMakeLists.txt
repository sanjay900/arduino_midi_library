cmake_minimum_required(VERSION 3.13)
project(arduino_midi_library CXX)

add_subdirectory(builder)

setup_builder()

add_subdirectory(src)
