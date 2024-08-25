cmake_minimum_required(VERSION 3.20)
project(printos c)

set(CNAME_C_STANDARD 99)
include_dictionaries(src src/lab)


add_executable(pintos main.c)