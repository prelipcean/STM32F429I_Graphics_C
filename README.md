# STM32F429I_Graphics_C

Repository for showing embedded graphics on STM32F429I-DISC1 using C language

# Description

This projects is work in progress starting from scratch (bare metal) and growing towards implementation of an RTOS and testing different graphical libraries.

Project will be entirely written in C, and linker script will be a custom one to define special sections. Maybe some assembly language will be required here and there TBD.

## Example of RTOS
- ZephyrOS
- Free RTOS
- NuttX
- RTX5 RTOS
- ThreadX
- VxWorks
- QNX

### Schdeduling approach clasification
- Cooperative Scheduling (Non-Preemptive Scheduling)
- Preemptive Priority-Based Scheduling
- Round-Robin Scheduling
- Cyclic Executive Scheduling (Time-Triggered / Timeline Scheduling)
- Rate Monotonic Scheduling (RMS)
- Earliest Deadline First (EDF) Scheduling
- Hardware-Based / Hardware-Assisted Scheduling

## Example of graphics libraries
- LVGL (Light and Versatile Graphics Library)
- emWin (SEGGER emWin)
- TouchGFX (STMicroelectronics TouchGFX)
- Slint
- uGFX
- µGUI (microGUI)
- Qt
- Embedded Wizard

# Resources

## Arm® Cortex®-M4 Processor Technical Reference Manual:
https://developer.arm.com/documentation/100166/0001/?lang=en

## ARM® Cortex®-M for Beginners
https://community.arm.com/cfs-file/__key/telligent-evolution-components-attachments/01-2142-00-00-00-00-52-96/White-Paper-_2D00_-Cortex_2D00_M-for-Beginners-_2D00_-2016-_2800_final-v3_2900_.pdf

## ARM Architecture Reference Manual Thumb-2 Supplement
https://developer.arm.com/documentation/ddi0308/latest/

## Cortex -M4 Devices Generic User Guide
https://developer.arm.com/documentation/dui0553/latest/

## Board STM32F429 Discovery kit (32F429IDISCOVERY):
https://www.st.com/en/evaluation-tools/32f429idiscovery.html

## MCU STM32F429ZIT6 Arm® Cortex®‑M4:
https://www.st.com/en/microcontrollers-microprocessors/stm32f429zi.html

## Datasheet MCU:
https://www.st.com/resource/en/datasheet/stm32f429zi.pdf

## User Manual MCU:
https://www.st.com/resource/en/user_manual/um3461-stm32f4-series-ulcsaiec-607301603351-selftest-library-user-guide-stmicroelectronics.pdf

## Reference Manual MCU:
https://www.st.com/resource/en/reference_manual/rm0090-stm32f405415-stm32f407417-stm32f427437-and-stm32f429439-advanced-armbased-32bit-mcus-stmicroelectronics.pdf

## Errata:
https://www.st.com/resource/en/errata_sheet/es0206-stm32f427437-and-stm32f429439-device-errata-stmicroelectronics.pdf

## Programming Manual:
https://www.st.com/resource/en/programming_manual/pm0214-stm32-cortexm4-mcus-and-mpus-programming-manual-stmicroelectronics.pdf

## Others:
https://www.st.com/resource/en/technical_note/tn1433-reference-device-marking-schematics-for-stm32-microcontrollers-and-microprocessors-stmicroelectronics.pdf
https://www.st.com/resource/en/application_note/an5054-how-to-perform-secure-programming-using-stm32cubeprogrammer-stmicroelectronics.pdf
