# STM32CubeF3 CMSIS Device MCU Component

![latest tag](https://img.shields.io/github/v/tag/STMicroelectronics/cmsis_device_f3.svg?color=brightgreen)

## Overview

**STM32Cube** is an STMicroelectronics original initiative to ease the developers life by reducing efforts, time and cost.

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

This **cmsis_device_f3** MCU component repo is one element of the STM32CubeF3 MCU embedded software package, providing the **cmsis device** part.

## Release note

Details about the content of this release are available in the release note [here](https://htmlpreview.github.io/?https://github.com/STMicroelectronics/cmsis_device_f3/blob/master/Release_Notes.html).

## Compatibility information

In this table, you can find the successive versions of this CMSIS Device component, in-line with the corresponding versions of the full MCU package:

CMSIS Device F3 | CMSIS Core | Was delivered in the full MCU package
--------------- | ---------- | -------------------------------------
Tag v2.3.4 | Tag v5.4.0_cm4 | Tag v1.11.0
Tag v2.3.4 | Tag v5.4.0_cm4 | Tag v1.11.1
Tag v2.3.5 | Tag v5.4.0_cm4 | Tag v1.11.2
Tag v2.3.6 | Tag v5.4.0_cm4 | Tag v1.11.3

The full **STM32CubeF3** MCU package is available [here](https://github.com/STMicroelectronics/STM32CubeF3).

## Troubleshooting
If you have any issue with the **Software content** of this repo, you can [file an issue on Github](https://github.com/STMicroelectronics/cmsis_device_f3/issues/new).

For any other question related to the product, the tools, the environment, you can submit a topic on the [ST Community/STM32 MCUs forum](https://community.st.com/s/topic/0TO0X000000BSqSWAW/stm32-mcus).