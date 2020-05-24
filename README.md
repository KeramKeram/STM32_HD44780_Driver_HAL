# STM32_HD44780_Driver_HAL
This version of driver is based on driver from
https://stm32f4-discovery.net/2014/06/library-16-interfacing-hd44780-lcd-controller-with-stm32f4/
Instead of use internal API created by Tilen Majerle which is controling GPIO etc. I ported this to pure STM32 HAL.
Pin configuration was changed, please check hd44780.h.
in example directory there is generated(from stm32 cube) main.c file with example of usage in main() function. 
