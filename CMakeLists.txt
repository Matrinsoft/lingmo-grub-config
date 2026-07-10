cmake_minimum_required(VERSION 3.20)
project(lingmo-grub-config VERSION 1.0.0 DESCRIPTION "Lingmo Grub Config" LANGUAGES NONE)


install(DIRECTORY ${CMAKE_SOURCE_DIR}/boot

        DESTINATION / )


