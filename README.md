libBlinkStick
=============

A [blinkstick](http://www.blinkstick.com/) library in C with few dependencies.

## Requirements
- [hidapi](https://github.com/signal11/hidapi)
- [clang](https://clang.llvm.org/)
- [cmake](https://cmake.org/)

## Getting Started
- `cmake .` to generate the Makefiles for your system
- `make` to build the library and CLI tool

## Running tests
- `make run_test`

## The CLI tool
Mostly a proof of concept for the library, the blinkstick CLI allows you to turn on and off any number of connected devices, set their colors, or target specific LEDs.

After running make, you'll have a `blinkstick` binary in target/
