# STM32F4xx Bootloader DFU (Direct Firmware Update)

With this bootloader, you will be able to upload new firmware to an STM32F4xx CPU through USB. 
This bootloader is implemented for the WeAct Black Pill V2.0 - F411 but can be easily ported to other boards with an:

- STM32F401
- STM32F411
- Black Pill STM32F4 boards
- others 

To work with this bootloader, you will need:
-  A 25Mhz HSE external clock
-  A USB connector
-  A button on PA0

Please note that this bootloader limits the application sizes to 64Kb.

[Contact me](https://www.danielecortellazzi.it/contact/) if you need embedded customizations.

This bootloader is based on this [guide](https://www.st.com/resource/en/application_note/cd00264379-usb-dfu-protocol-used-in-the-stm32-bootloader-stmicroelectronics.pdf)
