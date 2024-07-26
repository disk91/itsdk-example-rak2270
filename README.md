## RAK 2270 sticker tracker (RAK3172 SiP/STM32WLE5) ItSdk project template

This is a project template for Sigfox & LoRaWan communications on RAK3172 SiP based on STM32WLE5 chip. This template is based on [Disk91 IoT SDK repository](https://github.com/disk91/stm32-it-sdk).
The hardware configuration comes from CubeMX, project **ioc** file can be modified and source can be regenerated.

## Dependencies
* This template requires [ST CubeIDE](https://www.st.com/en/development-tools/stm32cubeide.html) the ST-Microelectronic free IDE based on Eclipse + GCC
* This template has been tested on [RAK2770 Sticker Tracker](https://www.rakwireless.com/en-us/products/rak2770)

## Installation

Get project and associated submodules
 
```
git clone --recurse-submodules git@github.com:disk91/itsdk-example-sigfox-seeedE5.git
```


## Getting started

- This example is based on [Disk91 IoT SDK](https://github.com/disk91/stm32-it-sdk) wher you can find the documentation and more examples.
- The main program is in [project_main.c](https://github.com/disk91/itsdk-example-sigfox-seeedE5/blob/master/Core/Src/project_main.c)
- The SDK is based on configuration file for most of it's behavior, starting with [it_sdk/config.h]()
- Interaction with device is made on serial console on LPUART, see [console documentation](https://github.com/disk91/stm32-it-sdk/blob/master/Doc/console.md)
- The console admin password is _changeme_, you can get the console command with commad **?** followed by [Enter] key

## Setup

