cmake_minimum_required(VERSION 3.5)

set(Adafruit_NeoPixel_COMPONENT_SRC_DIRSCMakeLists.txt
    .
)

set(Adafruit_NeoPixel_COMPONENT_INCLUDE_DIRS
    .
)

idf_component_register(SRC_DIRS ${Adafruit_NeoPixel_COMPONENT_SRC_DIRS}
                       INCLUDE_DIRS ${Adafruit_NeoPixel_COMPONENT_INCLUDE_DIRS}
                       REQUIRES arduino)

project(Adafruit_NeoPixel)