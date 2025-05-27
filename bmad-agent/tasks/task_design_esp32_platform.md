# Task: Design ESP32 Hardware Platform

## Objective
Design the fundamental hardware platform for an ESP32-based product, including basic power supply, ESP32 module integration, and essential I/O breakouts.

## Input
*   **Product Requirements:** High-level overview of the ESP32 product's physical form factor and intended functionality.
*   **Core Components:** Identification of the primary ESP32 module (e.g., ESP32-WROOM-32, ESP32-S3-WROOM-1).
*   **Peripheral Needs:** Initial list of required sensors, actuators, or other external components.

## Workflow

1.  **Module Selection & Integration:**
    *   Confirm the specific ESP32 module to be used.
    *   Identify minimum required support circuitry for the chosen ESP32 module (e.g., pull-ups, pull-downs, strapping pins).
2.  **Power Supply Design:**
    *   Determine power source (e.g., battery, USB, wall adapter) and voltage requirements.
    *   Design a stable power supply circuit suitable for the ESP32 and connected peripherals (e.g., LDO, switching regulator).
3.  **Basic I/O & Connectors:**
    *   Allocate GPIOs for essential functions and required peripherals.
    *   Specify necessary connectors (e.g., USB, power jack, JTAG, sensor interfaces).
4.  **Initial Schematic Draft:**
    *   Create a preliminary schematic capturing the ESP32 module, power supply, and key I/O.
    *   Review for basic functionality and potential issues.
5.  **Component Sourcing List:**
    *   Begin compiling a list of primary components with preliminary part numbers.

## Output
Markdown document containing:
*   Block diagram of the hardware platform.
*   Conceptual schematic of the ESP32 integration and power supply.
*   Initial Bill of Materials (BOM) with critical components.
*   Key design considerations and recommendations for PCB layout.