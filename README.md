# Configurable-AVR-device-drivers
I implemented all drivers in a configurable way.

1) timer 0,1,2
the driver consist of init function that takes the address of configuration structure, with configuration structure the user can choose timer number, the timer mode, clock speed and initial value.
2) external interrupt driver IN0-INT1-INT2.
3) Keypad driver (3x4)-(4x4).
4) Lcd driver 4-bit mode and 8-bit mode.
5) UART communication protocol driver.
6) I2C driver
7) External EEPROM driver
8) ICU driver
