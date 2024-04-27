# Default Configurations for WhatsMiner

`btminer` - This directory contains the default configuration files for various series of MicroBT's WhatsMiner devices, organized into subfolders for each series.

## Files

- `M30.csv` - M3X series models like M30S/+/++, M31S/+/++ etc.
- `M50.csv` - M5X series models like M50S/+/++ M56S/+/++ etc.
- `M60.csv` - M6X series models like M60S/+/++, M66S/+/++ etc.M60S/+/++

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


## Examples

|miner_type |chip_id|baud_rate|board_num|chip_num|chip_column_num|cool_temp|pre_heat_temp|pre_heat_end_freq|pre_heat_timeout|fan_size_cm|cooling_after_test|pass_cores0|pass_cores1|pass_cores2|cool_mode|btminer_test|slot_link|temp_slot1_map|temp_slot3_map|eeprom_slot1_map|eeprom_slot3_map|chip_num0|chip_num1|chip_num2|chip_num3|detect_extend|
|-----------|-------|---------|---------|--------|---------------|---------|-------------|-----------------|----------------|-----------|------------------|-----------|-----------|-----------|---------|------------|---------|--------------|--------------|----------------|----------------|---------|---------|---------|---------|-------------|
|M30V10     |0x1930 |12000000 |3        |105     |3              |38       |25           |210              |300             |14         |1                 |314        |209        |105        |         |            |         |              |              |                |                |         |         |         |         |             |
|M50VJ30    |0x1973 |12000000 |3        |117     |3              |38       |25           |210              |300             |14         |1                 |314        |209        |105        |         |            |         |              |              |                |                |         |         |         |         |             |
|M50S++VK10 |0x1978 |12000000 |3        |117     |3              |38       |25           |210              |300             |14         |1                 |314        |209        |105        |         |            |         |              |              |                |                |         |         |         |         |             |
|M60S+VL30  |0x1980 |6000000  |3        |225     |5              |35       |             |                 |                |14         |                  |           |           |           |         |            |         |              |              |                |                |         |         |         |         |12000000     |
|M66SVK40   |0x1978 |6000000  |4        |240     |5              |30       |             |                 |                |14         |                  |           |           |           |2        |            |"0:1 2:3"|0             |2             |0               |2               |         |         |         |         |12000000     |
