# NES Emulator App (nofrendo) — ota_0
cmake_minimum_required(VERSION 3.16)
set(EXTRA_COMPONENT_DIRS "${CMAKE_CURRENT_LIST_DIR}/../../components")
include($ENV{IDF_PATH}/tools/cmake/project.cmake)
option(RETRO_NES_DIRECT_BUTTON_TEST "Temporary six-button NES test with quiet audio" ON)
project(nes_app)
