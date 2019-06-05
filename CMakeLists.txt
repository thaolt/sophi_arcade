# SPDX-License-Identifier: Apache-2.0

cmake_minimum_required(VERSION 3.13.1)

set(BOARD_ROOT "${CMAKE_SOURCE_DIR}")

message(${BOARD_ROOT})

include($ENV{ZEPHYR_BASE}/cmake/app/boilerplate.cmake NO_POLICY_SCOPE)


project(sophi-arcade)

target_sources(app PRIVATE src/main.c)
