cmake_minimum_required(VERSION 3.11)

project(deepin-anything)

# Install settings
if (CMAKE_INSTALL_PREFIX_INITIALIZED_TO_DEFAULT)
    set(CMAKE_INSTALL_PREFIX /usr)
endif ()

add_subdirectory(${PROJECT_SOURCE_DIR}/src)
