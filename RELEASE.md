# KIT_T2G-B-E_2GO BSP Release Notes

The KIT_T2G-B-E_2GO, a 48-pin evaluation board is based on the TRAVEO™ T2G Body Entry family of devices. TRAVEO™ T2G Body Entry MCU is designed for  automotive and industrial applications. The evaluation board carries a TRAVEO™ T2G Body Entry microcontroller, and headers compatible with Arduino for  interfacing Arduino shields. In addition, the board features an on-board programmer/debugger (KitProg3),  CAN FD and LIN transceivers, a Shield2Go connector interface and MikroBUS connector interface, two user LEDs, one potentiometer,  and two user push buttons.     
**Note:**
Some additional setups will allow you to use more code examples than those shown on the next page. Click 
[here ](https://github.com/Infineon/TRAVEO_T2G_code_examples#how-to-setup)
for setup instructions.

NOTE: BSPs are versioned by family. This means that version 1.2.0 of any BSP in a family (eg: PSOC™ 6) will have the same software maturity level. However, not all updates are necessarily applicable for each BSP in the family so not all version numbers will exist for each board. Additionally, new BSPs may not start at version 1.0.0. In the event of adding a common feature across all BSPs, the libraries are assigned the same version number. For example if BSP_A is at v1.3.0 and BSP_B is at v1.2.0, the event will trigger a version update to v1.4.0 for both BSP_A and BSP_B. This allows the common feature to be tracked in a consistent way.

### What's Included?
The KIT_T2G-B-E_2GO library includes the following:
* BSP specific makefile to configure the build process for the board
* cybsp.c/h files to initialize the board and any system peripherals
* cybsp_types.h file describing basic board setup
* CM4 Linker script & startup code for GCC, IAR, and ARM toolchains
* CM0+ Linker script & startup code for GCC, IAR, and ARM toolchains
* Configurator design files (and generated code) to setup board specific peripherals
* .lib file references for all dependent libraries
* API documentation

### What Changed?
#### v6.0.0
* Added the BSP for KIT_T2G-B-E_2GO

### Supported Software and Tools
This version of the KIT_T2G-B-E_2GO BSP was validated for compatibility with the following Software and Tools:

| Software and Tools                        | Version |
| :---                                      | :----:  |
| ModusToolbox&trade; Software Environment  | 3.8.0   |
| GCC Compiler                              | 14.2.1  |
| IAR Compiler                              | 9.50.2  |
| ARM Compiler                              | 6.22    |

Minimum required ModusToolbox™ Software Environment: v3.8.0

### More information
* [KIT_T2G-B-E_2GO BSP API Reference Manual][api]
* [KIT_T2G-B-E_2GO Documentation](https://www.infineon.com/evaluation-board/KIT-T2G-B-E-2GO)
* [Infineon Technologies AG](http://www.infineon.com)
* [Infineon GitHub](https://github.com/infineon)
* [ModusToolbox™](https://www.infineon.com/design-resources/development-tools/sdk/modustoolbox-software)

[api]: https://infineon.github.io/TARGET_KIT_T2G-B-E_2GO/html/modules.html

---
© Infineon Technologies AG or an affiliate of Infineon Technologies AG, 2026.