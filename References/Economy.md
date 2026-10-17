# Economy Tables for Mayhem 3 Renegades + Add-Ons

Notes: 
- Data based on 200% suns per sector and asteroid yields of 60/Ore and 30/Silicon.
- Outpost waste production assumes 100 population. Each pop produces 18 waste per 10 minutes, so an average of 180 waste per minute at 100 pops.
- Jumpdrive Cores and Advanced Satellites are produced in discrete cycles of 8:32 and 2:08, respectively.
- Ratios show both the supplier capacity required per consuming factory and the smallest exactly balanced whole-number combinations of standard factories.
  - Decimal ratios are useful when planning Mobile Factories, which produce at 50% of a standard factory's rate.
  - Mobile Factories can help fill production gaps, although exact balance is not always possible.
  - Production and consumption rates are expressed as per-minute and per-hour averages.
  - For example, one Teladianium Foundry requires approximately 1.33 Chemical Labs' worth of production; three Foundries require exactly four Chemical Labs.
  - Ratios do not account for resources shared with other production chains.
- If Solar Panels is unlocked at the Outpost, it produces Energy Cells equal to Suns * 3 every 10 minutes. At 200% suns, this is 600 Energy Cells per 10 minutes (60/min).

## Factory Production and Consumption Rates

| Factory Name                     | Produces (Per Min)          | Consumes (Per Min)     | Produces (Per Hr)            | Consumes (Per Hr)      |
| -------------------------------- | --------------------------- | ---------------------- | ---------------------------- | ---------------------- |
| Outpost (Waste)                  | 180 Waste                   | -                      | 10800 Waste                  | -                      |
| Outpost (Solar Panels)           | 60 Energy Cells             | -                      | 3600 Energy Cells            | -                      |
| Solar Power Plant                | 24 Energy Cells             | -                      | 1440 Energy Cells            | -                      |
| Chemical Lab                     | 30 Chemicals                | 60 Waste               | 1800 Chemicals               | 3600 Waste             |
| Teladianium Foundry              | 20 Teladianium              | 40 Chemicals           | 1200 Teladianium             | 2400 Chemicals         |
| Hull Plating Production Facility | 20 Hull Plating             | 20 Teladianium         | 1200 Hull Plating            | 1200 Teladianium       |
| Protein Paste Blending Facility  | 30 Protein Paste            | 60 Waste               | 1800 Protein Paste           | 3600 Waste             |
| Food Preparation Facility        | 30 C-Rations                | 30 Protein Paste       | 1800 C-Rations               | 1800 Protein Paste     |
| Ore Mine                         | 60 Ore                      | 60 C-Rations           | 3600 Ore                     | 3600 C-Rations         |
| Quantum Tube Fab                 | 20 Quantum Tubes            | 40 Ore                 | 1200 Quantum Tubes           | 2400 Ore               |
| Chelt Space Aquarium             | 20 Chelts Meat              | 20 Energy Cells        | 1200 Chelts Meat             | 1200 Energy Cells      |
| Raster Refinery                  | 12 Rastar Oil               | 24 Chelts Meat         | 720 Rastar Oil               | 1440 Chelts Meat       |
| Chip Plant                       | 12 Microchips               | 24 Energy Cells        | 720 Microchips               | 1440 Energy Cells      |
| Computer Plant                   | 6 Computer Components       | 12 Microchips          | 360 Computer Chips           | 720 Microchips         |
| Crystal Fab                      | 6 Crystals                  | 24 Energy Cells        | 360 Crystals                 | 1440 Energy Cells      |
| Silicon Mine                     | 15 Silicon Wafers           | 15 Energy Cells        | 900 Silicon Wafers           | 900 Energy Cells       |
| Jumpdrive Core Factory           | 0.1171875 Jumpdrive Cores   | 3.75 Crystals          | 7.03125 Jumpdrive Cores      | 225 Crystals           |
| Advanced Satellite Factory       | 0.46875 Advanced Satellites | 15 Energy Cells        | 28.125 Advanced Satellites   | 900 Energy Cells       |

---

## Factory Ratio Chart (Supporting Factories Needed)

| Consuming Factory                | Consumed Resource | Rate Consumed | Supplying Factory               | Rate Produced | Ratio Needed (Consumer:Supplier) |
| -------------------------------- | ----------------- | ------------- | ------------------------------- | ------------- | -------------------------------- |
| Chemical Lab                     | Waste             | 60/Min        | Outpost (Waste)                 | 180/Min       | 3 : 1                            |
| Teladianium Foundry              | Chemicals         | 40/Min        | Chemical Lab                    | 30/Min        | 1 : 1.33 = 3 : 4                 |
| Hull Plating Production Facility | Teladianium       | 20/Min        | Teladianium Foundry             | 20/Min        | 1 : 1                            |
| Protein Paste Blending Facility  | Waste             | 60/Min        | Outpost (Waste)                 | 180/Min       | 3 : 1                            |
| Food Preparation Facility        | Protein Paste     | 30/Min        | Protein Paste Blending Facility | 30/Min        | 1 : 1                            |
| Ore Mine                         | C-Rations         | 60/Min        | Food Preparation Facility       | 30/Min        | 1 : 2                            |
| Quantum Tube Fab                 | Ore               | 40/Min        | Ore Mine                        | 60/Min        | 1 : 0.67 = 3 : 2                 |
| Chelt Space Aquarium             | Energy Cells      | 20/Min        | Solar Power Plant               | 24/Min        | 1 : 0.83 = 6 : 5                 |
| Raster Refinery                  | Chelts Meat       | 24/Min        | Chelt Space Aquarium            | 20/Min        | 1 : 1.2 = 5 : 6                  |
| Chip Plant                       | Energy Cells      | 24/Min        | Solar Power Plant               | 24/Min        | 1 : 1                            |
| Computer Plant                   | Microchips        | 12/Min        | Chip Plant                      | 12/Min        | 1 : 1                            |
| Crystal Fab                      | Energy Cells      | 24/Min        | Solar Power Plant               | 24/Min        | 1 : 1                            |
| Silicon Mine                     | Energy Cells      | 15/Min        | Solar Power Plant               | 24/Min        | 1 : 0.625 = 8 : 5                |
| Jumpdrive Core Factory           | Crystals          | 3.75/Min      | Crystal Fab                     | 6/Min         | 1 : 0.625 = 8 : 5                |
| Advanced Satellite Factory       | Energy Cells      | 15/Min        | Solar Power Plant               | 24/Min        | 1 : 0.625 = 8 : 5                |
