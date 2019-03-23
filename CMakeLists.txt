cmake_minimum_required(VERSION 3.13)
project(nema_tode)
set(CMAKE_CXX_STANDARD 11)

add_library(nema_tode GPSFix.cpp GPSService.cpp NMEACommand.cpp NMEAParser.cpp NumberConversion.cpp Event.h GPSFix.h GPSService.h NMEACommand.h NMEAParser.h NumberConversion.h nmea.h)
