# Power Configurations for WhatsMiner Devices

`powers` - This directory contains bin configuration files related to the power settings of various MicroBT's WhatsMiner devices.

## Files

- `M3X.csv` - Contains bin power configurations for M3X series models like M30S/+/++, M31S/+/++, etc.
- `M5X.csv` - Contains bin power configurations for M5X series models like M50S/+/++, M56S/+/++, etc.
- `M6X.csv` - Contains bin power configurations for M6X series models like M60S/+/++, M66S/+/++, etc.

## Configuration Table Descriptions

| Field             | Description                                                  |
|-------------------|--------------------------------------------------------------|
| `freq`            | Operating frequency of the miner (MHz)                       |
| `voltage_target`  | Target operating voltage for the miner (mV)                  |
| `voltage_limit`   | Maximum allowable voltage for the miner (mV)                 |
| `chip_temp`       | Maximum temperature limit for the chips (°C)                 |
| `board_temp`      | Maximum temperature limit for the boards (°C)                |
| `ok_core_pct`     | Percentage of cores that must pass the test for operation    |
| `min_power`       | Minimum power consumption during operation (Watts)           |

## Examples of Configuration Entries

Each entry in the configuration files provides detailed settings applicable to specific models or bins within models. 

Below is an example of what these entries might look like in the `M6X.powers` file:

- **`bin1v1_A`**: 
  - `freq`: 527 MHz
  - `voltage_target`: 1200 mV
  - `voltage_limit`: 1400 mV
  - `chip_temp`: 87 °C
  - `board_temp`: 80 °C
  - `ok_core_pct`: 97%
  - `min_power`: 39.0 Watts