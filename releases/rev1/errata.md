# Errata

## Display

- Pin header orientation is reversed incorrectly.

## LED Driver

- VCC line is too thin.

## SW

- need to pull down

## I2C

- need to pull up

## IS31

- 2.2k -> 7.6k
  - workaround
    - set 0x13 to IS31FL3208A reg 0x14 ~ 0x25

## Rotary encoder

- Pin C (voltage base of rotary detection line) should be GND
- Pin 3 (push switch) should be pull down
