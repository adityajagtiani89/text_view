# Copyright (c) 2017, Tristan Brindle, Tom Honermann
#
# This file is distributed under the MIT License. See the accompanying file
# LICENSE.txt or http://www.opensource.org/licenses/mit-license.php for terms
# and conditions.

cmake_minimum_required(VERSION 3.0.2)

project(text_view_examples_tv-dump CXX)

find_package(text_view REQUIRED)

add_executable(
  tv-dump
  tv-dump.cpp)
target_link_libraries(
  tv-dump
  PRIVATE text-view)
