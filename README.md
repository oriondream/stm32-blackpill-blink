# Target MCU
STM32F411CEU6

# Troubleshooting
## STM32CubeProgrammer complains 'Error: flash loader cannot be loaded. FlashLoaderPath = .../bin/FlashLoader/0x
Two line above the error message in the Log should there Device ID value 0x431. Note this value and copy it to '0x' to use as flash loader.