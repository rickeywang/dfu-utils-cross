# Forked Notes

This fork has added delays to make it work on STM32L4 devices. For more details, see commit 4e058c737da74091e3f39e2ea45041a83cb128e6

# dfu-utils-cross

This repo contains the scripts to compile (and cross-compile from a Linux machine) `dfu-utils` package for Linux (x86_64, x86, arm), OSX and Windows.

For doing so it also compiles `libusb` statically so the resulting binary has zero external dependencies.

Prerequisites:
[osxcross](https://github.com/tpoechtrager/osxcross)
mingw32-w64

Some patches were added to target a bunch of problems with [Arduino101](https://www.arduino.cc/en/Main/ArduinoBoard101) upload procedure

# License

The bash scripts are GPLv2 licensed. Every other software used by these bash scripts has its own license. Consult them to know the terms.
