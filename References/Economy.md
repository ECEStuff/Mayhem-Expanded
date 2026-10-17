# Economy Tables for Mayhem 3 Renegades + Add-Ons

Note: Data based on 100% solar per sector and asteroid yields of 60/Ore and 30/Silicon.

## Factory Production and Consumption Rates

| Factory Name                     | Produces (Per Min)          | Consumes (Per Min)     | Produces (Per Hr)            | Consumes (Per Hr)      |
| -------------------------------- | --------------------------- | ---------------------- | ---------------------------- | ---------------------- |
| Solar Power Plant                | 12 Energy Cells             | -                      | 720 Energy Cells             | -                      |
| Crystal Fab                      | 6 Crystals                  | 24 Energy Cells        | 360 Crystals                 | 1440 Energy Cells      |
| Computer Plant                   | 6 Computer Chips            | 12 Microchips          | 360 Computer Chips           | 720 Microchips         |
| Chip Plant                       | 12 Microchips               | 24 Energy Cells        | 720 Microchips               | 1440 Energy Cells      |
| Hull Plating Production Facility | 20 Hull Plating             | 20 Teladianium         | 1200 Hull Plating            | 1200 Teladianium       |
| Teladianium Foundry              | 20 Teladianium              | 40 Chemicals           | 1200 Teladianium             | 2400 Chemicals         |
| Chemical Lab                     | 30 Chemicals                | 60 Waste               | 1800 Chemicals               | 3600 Waste             |
| Raster Refinery                  | 12 Rastar Oil               | 24 Chelt Meat          | 720 Rastar Oil               | 1440 Chelt Meat        |
| Chelt Space Aquarium             | 20 Chelt Meat               | 20 Energy Cells        | 1200 Chelt Meat              | 1200 Energy Cells      |
| Food Preparation Facility        | 30 C-Rations                | 30 Protein Paste       | 1800 C-Rations               | 1800 Protein Paste     |
| Protein Paste Blending Facility  | 30 Protein Paste            | 60 Waste               | 1800 Protein Paste           | 3600 Waste             |
| Quantum Tube Fab                 | 20 Quantum Tubes            | 40 Ore                 | 1200 Quantum Tubes           | 2400 Ore               |
| Ore Mine                         | 60 Ore                      | 60 C-Rations           | 3600 Ore                     | 3600 C-Rations         |
| Silicon Mine                     | 15 Silicon Wafers           | 15 Energy Cells        | 900 Silicon Wafers           | 900 Energy Cells       |
| Jumpdrive Core Factory           | 1 Jumpdrive Core / 8:32     | 32 Crystals / 8:32     | ~7 Jumpdrive Cores / Hr      | ~224 Crystals / Hr     |
| Advanced Satellite Factory       | 1 Advanced Satellite / 2:08 | 32 Energy Cells / 2:08 | ~28 Advanced Satellites / Hr | ~896 Energy Cells / Hr |

---

## Factory Ratio Chart (Supporting Factories Needed)

| Consuming Factory                | Consumed Resource | Rate Consumed | Supplying Factory               | Rate Produced | Ratio Needed (Consumer:Supplier) |
| -------------------------------- | ----------------- | ------------- | ------------------------------- | ------------- | -------------------------------- |
| Crystal Fab                      | Energy Cells      | 24/Min        | Solar Power Plant               | 12/Min        | 1 : 2                            |
| Computer Plant                   | Microchips        | 12/Min        | Chip Plant                      | 12/Min        | 1 : 1                            |
| Chip Plant                       | Energy Cells      | 24/Min        | Solar Power Plant               | 12/Min        | 1 : 2                            |
| Hull Plating Production Facility | Teladianium       | 20/Min        | Teladianium Foundry             | 20/Min        | 1 : 1                            |
| Teladianium Foundry              | Chemicals         | 40/Min        | Chemical Lab                    | 30/Min        | 1 : 1.33 = 3 : 4                 |
| Chemical Lab                     | Waste             | 60/Min        | -                               | -             | -                                |
| Raster Refinery                  | Chelt Meat        | 24/Min        | Chelt Space Aquarium            | 20/Min        | 1 : 1.2 = 5 : 6                  |
| Chelt Space Aquarium             | Energy Cells      | 20/Min        | Solar Power Plant               | 12/Min        | 1 : 1.67 = 3 : 5                 |
| Food Preparation Facility        | Protein Paste     | 30/Min        | Protein Paste Blending Facility | 30/Min        | 1 : 1                            |
| Protein Paste Blending Facility  | Waste             | 60/Min        | -                               | -             | -                                |
| Quantum Tube Fab                 | Ore               | 40/Min        | Ore Mine                        | 60/Min        | 1 : 0.67 = 3 : 2                 |
| Ore Mine                         | C-Rations         | 60/Min        | Food Preparation Facility       | 30/Min        | 1 : 2                            |
| Silicon Mine                     | Energy Cells      | 15/Min        | Solar Power Plant               | 12/Min        | 1 : 1.25 = 4 : 5                 |
| Jumpdrive Core Factory           | Crystals          | 32/8:32       | Crystal Fab                     | 6/Min         | 1 : 0.62 ~ 5 : 3                 |
| Advanced Satellite Factory       | Energy Cells      | 32/2:08       | Solar Power Plant               | 12/Min        | 1 : 1.25 = 4 : 5                 |

Note: For factories with non-integer minute cycles, ratios are calculated using per-minute equivalents.
