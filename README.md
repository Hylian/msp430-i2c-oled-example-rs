# `msp430-i2c-oled-example`

An example project to talk to an SSD1306 OLED (Adafruit PiOLED) with an MSP430G2553 Launchpad via I2C.

See: https://github.com/rust-embedded/msp430-quickstart

## Requirements

* Rust nightly
* TI MSP430 GCC Toolchain(http://www.ti.com/tool/MSP430-GCC-OPENSOURCE)

## Build

`cargo build -Zbuild-std=core --release`


## Debug

`msp430-elf-gdb -x gdbproxydebug.gdb target/msp430-none-elf/release/msp430-oled-example`
