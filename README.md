# BSP B-U585I-IOT02a Component

![latest tag](https://img.shields.io/github/v/tag/STMicroelectronics/b-u585i-iot02a.svg?color=brightgreen)

## Overview

**STM32Cube** is an STMicroelectronics original initiative to ease developers' life by reducing efforts, time and cost.

**STM32Cube** covers the overall STM32 products portfolio. It includes a comprehensive embedded software platform delivered for each STM32 series.
   * The CMSIS modules (core and device) corresponding to the ARM(tm) core implemented in this STM32 product.
   * The STM32 HAL-LL drivers, an abstraction layer offering a set of APIs ensuring maximized portability across the STM32 portfolio.
   * The BSP drivers of each evaluation, demonstration or nucleo board provided for this STM32 series.
   * A consistent set of middleware libraries such as RTOS, USB, FatFS, graphics, touch sensing library...
   * A full set of software projects (basic examples, applications, and demonstrations) for each board provided for this STM32 series.

Two models of publication are proposed for the STM32Cube embedded software:
   * The monolithic **MCU Package**: all STM32Cube software modules of one STM32 series are present (Drivers, Middleware, Projects, Utilities) in the repository (usual name **STM32Cubexx**, xx corresponding to the STM32 series).
   * The **MCU component**: each STM32Cube software module being part of the STM32Cube MCU Package, is delivered as an individual repository, allowing the user to select and get only the required software functions.

## Description

This **b-u585i-iot02a** MCU component repository is one element of the **STM32CubeU5** MCU embedded software package, providing the **B-U585I-IOT02a** BSP BOARD component part.

## Release note

Details about the content of this release are available in the release note [here](https://htmlpreview.github.io/?https://github.com/STMicroelectronics/b-u585i-iot02a/blob/main/Release_Notes.html).

## Compatibility information

Below is the list of the BSP *component* drivers to be used with this BSP *board* driver. It is **crucial** that you use a consistent set of CMSIS - HAL - BSP versions, as mentioned in [this](https://htmlpreview.github.io/?https://github.com/STMicroelectronics/STM32CubeU5/blob/master/Release_Notes.html) release note.

* [stm32-bsp-common](https://github.com/STMicroelectronics/stm32-bsp-common)
* [stm32-aps6408](https://github.com/STMicroelectronics/stm32-aps6408)
* [stm32-hts221](https://github.com/STMicroelectronics/stm32-hts221)
*  stm32-iis2mdc *To be published soon*
*  stm32-ism330dhcx *To be published soon*
*  stm32-lps22hh *To be published soon*
* [stm32-m24lr64](https://github.com/STMicroelectronics/stm32-m24lr64)
* [stm32-mx25lm51245g](https://github.com/STMicroelectronics/stm32-mx25lm51245g)
* [stm32-ov5640](https://github.com/STMicroelectronics/stm32-ov5640)
* [stm32-tcpp0203](https://github.com/STMicroelectronics/stm32-tcpp0203)
* [stm32-veml6030](https://github.com/STMicroelectronics/stm32-veml6030)

## Troubleshooting

Please refer to the [CONTRIBUTING.md](CONTRIBUTING.md) guide.
