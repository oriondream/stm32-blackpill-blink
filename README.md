# Introduction
This is a basic blink project for STM32F411CEU6 with SWD debug.

# Target MCU
STM32F411CEU6 - Blackpill

# Debugging in the IDE

Before clicking Debug button, boot the device to Boot0 by the following sequence:
1. Press and hold BOOT0 for 1 second
2. While holding BOOT0, press and hold NRST
3. Release NRST and wait 1 second
4. Release BOOT0

# Troubleshooting

- When loading firmware using STM32CubeProgrammer, it complains 'Error: flash loader cannot be loaded. FlashLoaderPath = .../bin/FlashLoader/0x
Two line above the error message in the Log should there Device ID value 0x431. Note this value and copy it to '0x' to use as flash loader.
