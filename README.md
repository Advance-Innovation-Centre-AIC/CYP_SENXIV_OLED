# This is hardware command for easy use

This is a minimal starter application for Infineon MCU devices.
which include
- CY8CKIT-062s2-43012
- CY8CKIT-028-SENSE.

## Requirements

- [ModusToolbox&trade; software](https://www.infineon.com/modustoolbox) v3.0 or later (tested with v3.0)
- CY8CKIT-062s2-43012
- CY8CKIT-028-SENSE.
- Programming language: C
- Associated parts: All [PSoC&trade; 6 MCU](https://www.infineon.com/cms/en/product/microcontroller/32-bit-psoc-arm-cortex-microcontroller/psoc-6-32-bit-arm-cortex-m4-mcu) parts, [XMC7000 MCU](https://www.infineon.com/cms/en/product/microcontroller/32-bit-industrial-microcontroller-based-on-arm-cortex-m/), and [AIROC&trade; CYW20829 Bluetooth&reg; LE SoC](https://www.infineon.com/cms/en/product/promopages/airoc20829)

## Supported toolchains (make variable 'TOOLCHAIN')

- GNU Arm&reg; embedded compiler v10.3.1 (`GCC_ARM`) - Default value of `TOOLCHAIN`
- Arm&reg; compiler v6.16 (`ARM`)
- IAR C/C++ compiler v9.30.1 (`IAR`)

## OLED functions
Thess functions will print text on OLED on CY8CKIT-028-SENSE fllowing this

### lcd_print_top(const char * s)
This function will let you print on top-left of the screen
char * s = text you want to print on OLED

### lcd_print_bot(const char * s)
This function will let you print on bottom-left of the screen
char * s = text you want to print on OLED

### lcd_print_line_n(const char * s,int linenum)
This function will let you print on selected line of the screen (from 1-6)
char * s = text you want to print on OLED
linenum = selected line
