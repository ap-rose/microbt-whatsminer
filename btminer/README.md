# Default Configurations for WhatsMiner

`btconfig` - This directory contains the default configuration files for various series of MicroBT's WhatsMiner devices, organized into subfolders for each series.

## Folder Structure

- `M30/` - M3X series models like M30S/+/++, M31S/+/++ etc.
- `M50/` - M5X series models like M50S/+/++ M56S/+/++ etc.
- `M60/` - M6X series models like M60S/+/++, M66S/+/++ etc.M60S/+/++

## Configuration Table Descriptions

| Field             | Description                                                  |
|-------------------|--------------------------------------------------------------|
| `miner_type`      | Model type of the miner                                      |
| `chip_id`         | Identifier for the chip used in the miner                    |
| `baud_rate`       | Communication speed between the computer and the miner       |
| `board_num`       | Number of boards in the miner                                |
| `chip_num`        | Total number of chips on all boards                          |
| `chip_column_num` | Number of chip columns per board                             |
| `cool_temp`       | Target temperature for optimal cooling (°C)                  |
| `pre_heat_temp`   | Temperature to pre-heat the miner before operation (°C)      |
| `pre_heat_end_freq` | Frequency setting after pre-heating completes (MHz)       |
| `pre_heat_timeout` | Timeout for pre-heating process (seconds)                  |
| `fan_size_cm`     | Diameter of the cooling fan in centimeters                   |
| `cooling_after_test` | Indicates if cooling is required after testing (1 = Yes) |
| `pass_cores0`     | Number of passing cores in the first test                    |
| `pass_cores1`     | Number of passing cores in the second test                   |
| `pass_cores2`     | Number of passing cores in the third test                    |
| `cool_mode`       | Cooling mode used by the miner                               |
| `btminer_test`    | Indicates if the miner passed the BTMiner test               |
| `slot_link`       | Connection status of the slots                               |
| `temp_slot1_map`  | Temperature mapping for slot 1                               |
| `temp_slot3_map`  | Temperature mapping for slot 3                               |
| `eeprom_slot1_map`| EEPROM data mapping for slot 1                               |
| `eeprom_slot3_map`| EEPROM data mapping for slot 3                               |
| `chip_num0`       | Number of chips in the first configuration                   |
| `chip_num1`       | Number of chips in the second configuration                  |
| `chip_num2`       | Number of chips in the third configuration                   |
| `chip_num3`       | Number of chips in the fourth configuration                  |
| `detect_extend`   | Additional detection settings or capabilities                |