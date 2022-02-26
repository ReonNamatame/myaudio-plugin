cmake_minimum_required(VERSION 3.0.0)
project(myaudio-plugin LANGUAGES CXX VERSION 0.0.1)

# include(CTest)
# enable_testing()
add_subdirectory(libs/JUCE)
add_subdirectory(src)
