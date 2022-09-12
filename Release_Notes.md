---
pagetitle: STM32 USB-C Power Delivery Embedded Tracer
lang: en
header-includes: <link rel="icon" type="image/x-icon" href="_htmresc/favicon.png" />
---

::: {.row}
::: {.col-sm-12 .col-lg-4}


<center>
# Release Notes for STM32 USB-C Power Delivery embedded Tracer
Copyright &copy; 2018(-2021) STMicroelectronics\

[![ST logo](_htmresc/st_logo_2020.png)](https://www.st.com){.logo}
</center>

# Purpose

This driver is used for the embedded USB-PD tracer used to debug USB-PD application.
:::

::: {.col-sm-12 .col-lg-8}
# Update History

::: {.collapse}
<input type="checkbox" id="collapse-section12" checked aria-hidden="true">
<label for="collapse-section12" aria-hidden="true">V1.7.1 / 01-Dec-2021</label>
<div>

## Main Changes

### Maintenance release

## Contents

  Headline
  --------
  [Licensing] Update the way to declare licenses in Cube and X-CUBE components
  Trace not working on STM32L476 and L4 without DMAMUX

  : Fixed bugs list

## Known limitations

## Development Toolchains and Compilers

- IAR Embedded Workbench for ARM (EWARM) toolchain V8.50.6
- RealView Microcontroller Development Kit (MDK-ARM) toolchain V5.31
- STM32CubeIDE v1.7.0

## Supported Devices and boards

## Backward compatibility

## Dependencies

</div>
:::

::: {.collapse}
<input type="checkbox" id="collapse-section11" aria-hidden="true">
<label for="collapse-section11" aria-hidden="true">V1.7.0 / 30-April-2021</label>
<div>

## Main Changes

### Maintenance release

## Contents

  Headline
  --------
  Update to manage the case where USART_CR3_RTSE is not handled by the LPUART IP

  : Fixed bugs list

## Known limitations

## Development Toolchains and Compilers

- IAR Embedded Workbench for ARM (EWARM) toolchain V8.32.3
- RealView Microcontroller Development Kit (MDK-ARM) toolchain V5.27
- STM32CubeIDE v1.4.0

## Supported Devices and boards

## Backward compatibility

## Dependencies

</div>
:::

::: {.collapse}
<input type="checkbox" id="collapse-section10" aria-hidden="true">
<label for="collapse-section10" aria-hidden="true">V1.6.1 / 01-Feb-2021</label>
<div>

## Main Changes

### Maintenance release

## Contents

  Headline
  --------
  Minor corrections in Tracer_Emb configuration file template

  : Fixed bugs list

## Known limitations

## Development Toolchains and Compilers

- IAR Embedded Workbench for ARM (EWARM) toolchain V8.32.3
- RealView Microcontroller Development Kit (MDK-ARM) toolchain V5.27
- STM32CubeIDE v1.4.0

## Supported Devices and boards

## Backward compatibility

## Dependencies

</div>
:::

::: {.collapse}
<input type="checkbox" id="collapse-section9" aria-hidden="true">
<label for="collapse-section9" aria-hidden="true">V1.6.0 / 24-Nov-2020</label>
<div>

## Main Changes

### Maintenance release

## Contents

  Headline
  --------
  Adapatations to support GPDMA (U5)
  CodeSpell and MCUAStyle corrections
  MISRA C2012 corrections

  : Fixed bugs list

## Known limitations

## Development Toolchains and Compilers

- IAR Embedded Workbench for ARM (EWARM) toolchain V8.32.3
- RealView Microcontroller Development Kit (MDK-ARM) toolchain V5.27
- STM32CubeIDE v1.4.0

## Supported Devices and boards

## Backward compatibility

## Dependencies

</div>
:::

::: {.collapse}
<input type="checkbox" id="collapse-section8"  aria-hidden="true">
<label for="collapse-section8" aria-hidden="true">V1.5.0 / 2-Jul.-2020</label>
<div>

## Main Changes

### Maintenance release

## Contents

  Headline
  --------
  Code aligned to support U5
  update for GPDMA link with LL update
  Ticket 84212 - Trace non functional with STM32F4
  Remove TRACER_EMB_TX_Process prototype in tracer_emb.h
  remove the TX processing

  : Fixed bugs list

## Known limitations

## Development Toolchains and Compilers

- IAR Embedded Workbench for ARM (EWARM) toolchain V8.32.3
- RealView Microcontroller Development Kit (MDK-ARM) toolchain V5.27
- STM32CubeIDE v1.2.0

## Supported Devices and boards

## Backward compatibility

## Dependencies

</div>
:::

::: {.collapse}
<input type="checkbox" id="collapse-section7" aria-hidden="true">
<label for="collapse-section7" aria-hidden="true">V1.4.1 / 16-Apr.-2020</label>
<div>

## Main Changes

### Maintenance release

## Contents

  Headline
  --------
  Remove reference to USBPD

  : Fixed bugs list

## Known limitations

## Development Toolchains and Compilers

- IAR Embedded Workbench for ARM (EWARM) toolchain V8.32.3
- RealView Microcontroller Development Kit (MDK-ARM) toolchain V5.27
- STM32CubeIDE v1.2.0

## Supported Devices and boards

## Backward compatibility

## Dependencies

</div>
:::

::: {.collapse}
<input type="checkbox" id="collapse-section6" aria-hidden="true">
<label for="collapse-section6" aria-hidden="true">V1.4.0 / 14-Apr.-2020</label>
<div>

## Main Changes

### Maintenance release

## Contents

  Headline
  --------
  * Ticket 84461 Indicate when trace is lost

  : Fixed bugs list

## Known limitations

## Development Toolchains and Compilers

- IAR Embedded Workbench for ARM (EWARM) toolchain V8.32.3
- RealView Microcontroller Development Kit (MDK-ARM) toolchain V5.27
- STM32CubeIDE v1.2.0

## Supported Devices and boards

## Backward compatibility

## Dependencies

</div>
:::

::: {.collapse}
<input type="checkbox" id="collapse-section5" aria-hidden="true">
<label for="collapse-section5" aria-hidden="true">V1.3.0 / 26-March-2020</label>
<div>

## Main Changes

### Maintenance release


## Contents

  Headline
  --------
  Improve Usart IRQ Handler execution time in tracer_emb_hw.c
  Remove commented code sections
  Update the hardware layer to handle GPDMA
  Ticket 77333 - DMA usage in tracer_emb_hw needs to be under switch
  Add 2 macros TRACER_EMB_ENABLECHANNEL and TRACER_EMB_DISABLECHANNEL to be compliant with STM32H7

  : Fixed bugs list

## Known limitations

## Development Toolchains and Compilers

- IAR Embedded Workbench for ARM (EWARM) toolchain V8.32.3
- RealView Microcontroller Development Kit (MDK-ARM) toolchain V5.27
- STM32CubeIDE v1.2.0

## Supported Devices and boards

## Backward compatibility

## Dependencies

</div>
:::

::: {.collapse}
<input type="checkbox" id="collapse-section3" aria-hidden="true">
<label for="collapse-section3" aria-hidden="true">V1.2.0 / 17-June-2019</label>
<div>

## Main Changes

### Maintenance release


## Contents

  Headline
  --------
  Ticket 66638 - [FOSS-Audit] SLA0044 headers in Utilities files

  : Fixed bugs list

## known limitations

## Development Toolchains and Compilers

- IAR Embedded Workbench for ARM (EWARM) toolchain V8.20.2
- RealView Microcontroller Development Kit (MDK-ARM) toolchain V5.25
- System Workbench STM32 (SW4STM32) toolchain V2.7.2

## Supported Devices and boards

## backward compatibility

## Dependencies

</div>
:::

::: {.collapse}
<input type="checkbox" id="collapse-section2" aria-hidden="true">
<label for="collapse-section2" aria-hidden="true">V1.1.0 / 10-April-2019</label>
<div>

## Main Changes

### Maintenance release


## Contents

  Headline
  --------
  Add new defines in tracer_emb_conf_template.h (as done in projects tracer_emb_conf.h files)
  Update tracer file
  remove dependence with USBPD Application
  Update for low power management
  call DPM_TraceWakeUp after added message
  Move macro definition about USART/LPUART inside tracer_em_hw.c
  Change emb_conf to be able to have trace independent of USART or LPUART
  Add LPUART files
  Add management of LPUART1

  : Fixed bugs list

## known limitations

## Development Toolchains and Compilers

- IAR Embedded Workbench for ARM (EWARM) toolchain V8.20.2
- RealView Microcontroller Development Kit (MDK-ARM) toolchain V5.25
- System Workbench STM32 (SW4STM32) toolchain V2.7.2

## Supported Devices and boards

## backward compatibility

## Dependencies

</div>
:::

::: {.collapse}
<input type="checkbox" id="collapse-section1" aria-hidden="true">
<label for="collapse-section1" aria-hidden="true">V1.0.0 / 18-Dec.-2018</label>
<div>			

## Main Changes

### Maintenance release

Maintenance release

## Contents

  Headline
  --------
  tracer embedded creation
  
  : Fixed bugs list

## known limitations

## Development Toolchains and Compilers

- IAR Embedded Workbench for ARM (EWARM) toolchain V8.20.2
- RealView Microcontroller Development Kit (MDK-ARM) toolchain V5.25
- System Workbench STM32 (SW4STM32) toolchain V2.7.2

## Supported Devices and boards

## backward compatibility

## Dependencies

</div>
:::

:::
:::

<footer class="sticky">
For complete documentation on STM32,visit: [[www.st.com/stm32](http://www.st.com)]

*This release note uses up to date web standards and, for this reason, should not be opened with Internet Explorer but preferably with popular browsers such as Google Chrome, Mozilla Firefox, Opera or Microsoft Edge.*
</footer>
