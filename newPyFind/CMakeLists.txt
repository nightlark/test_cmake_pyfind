cmake_minimum_required(VERSION 3.4)

cmake_policy(SET CMP0094 NEW)

#set(Python3_FIND_STRATEGY "LOCATION")

find_package(Python3 COMPONENTS Interpreter Development)
message(STATUS "Python3_EXECUTABLE ${Python3_EXECUTABLE}")
message(STATUS "Python3_STDLIB ${Python3_STDLIB}")
message(STATUS "Python3_STDARCH ${Python3_STDARCH}")
message(STATUS "Python3_INCLUDE_DIRS ${Python3_INCLUDE_DIRS}")
message(STATUS "Python3_LIBRARIES ${Python3_LIBRARIES}")
message(STATUS "Python3_LIBRARY_DIRS ${Python3_LIBRARY_DIRS}")
message(STATUS "Python3_RUNTIME_LIBRARY_DIRS ${Python3_RUNTIME_LIBRARY_DIRS}")
message(STATUS "Python3_VERSION ${Python3_VERSION}")
