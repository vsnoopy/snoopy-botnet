cmake_minimum_required(VERSION 3.19)
project(Priv_Snoopy C)

set(CMAKE_C_STANDARD 99)

add_library(Priv_Snoopy cnc.c bot_snoopy.c mysort.c)