# BOM

## Non-printed parts

### Fasteners
| Part                          | Qty |
| ----------------------------- | --: |
| M3 lock nut                   | 115 |
| M3 x 6 button head            |  15 |
| M3 x 8 button head            |  10 |
| M3 x 10 button head           |  80 |
| M3 x 12 button head           |  20 |
| M3 x 16 button head           |   4 |
| M3 x 20 button head           |   8 |
| M3 x 25 button head           |   7 |
| M3 x 30 button head           |  10 |
| M3 x 45 (bed leveling screws) |   3 |
| Bed leveling knobs            |   3 |
| Bed springs/silicone spacers  |   3 |

### Notes
- The design uses common bolt lengths. A simple way to get all of these in a cost effective way is as follows:
  1. Get an M3 button head bolt kit, 6-30mm lengths ([Amazon](https://www.amazon.com/dp/B0F7LK7WGS), [Aliexpress](https://www.aliexpress.us/item/3256805285897325.html))
  2. Grab a 100 pack of M3x10mm bolts ([Amazon](), [Aliexpress](https://www.aliexpress.us/item/3256805282614111.html)).
  3. Grab a bulk pack of M3 lock nuts ([Amazon](https://www.amazon.com/Yinpecly-Stainless-Self-Locking-Industrial-Construction/dp/B0F1MSSVQP), [Aliexpress - need at least 2](https://www.aliexpress.us/item/2251832802681129.html)).
- The bed leveling items (last 3) can usually be purchased together as a complete leveling kit. Get the type with the smallest plastic knobs or metal thumbscrews - larger sizes will not fit.


### Motion
| Part                                                  |  Qty |
| ----------------------------------------------------- | ---: |
| LM8LUU bearing                                        |    2 |
| 200mm steel linear rod, 8mm diameter                  |    2 |
| 150mm MGN9 rail with MGN9C carriage                   |    3 |
| F623 bearing                                          |   24 |
| 150mm T8 leadscrew, 2mm lead, with nut                |    1 |
| 5mm to 8mm Z coupler (plum type or rigid recommended) |    1 |
| 2GT belt, 6mm wide                                    | ~3m  |
| 16T 2GT pulley for 6mm width belt                     |    2 |


### Heating and extrusion
| Part                                                                  |    Qty |
| --------------------------------------------------------------------- | -----: |
| Voron 0 heat bed assembly (MIC6 plate, silicone heater, magnetic PEI) |      1 |
| Bambu X1/P1 hotend or clone (TZ hotend, etc.)                         |      1 |
| Bowden tubing                                                         | <0.5 m |
| Bowden coupler, PC4-M6                                                |      1 |
| Bowden extruder for NEMA 17 motor (e.g. BMG or clones)                |      1 |


### Electrical
| Part                                                                     | Qty |
| ------------------------------------------------------------------------ | --: |
| 2510 fan (if not provided with hotend)                                   |   1 |
| 7515 blower (optional)                                                   |   2 |
| 4015 blower                                                              |   1 |
| Controller board                                                         |   1 |
| 24V LED power supply, 6A (AliExpress generic or Meanwell LRS-150-24)     |   1 |
| Nema 17 stepper motor (~43mm max body length for extruder, 64mm for X/Y) |   3 |
| Nema 17 pancake stepper motor (~26mm max body length)                    |   1 |
| PCB mechanical endstop, MakerBot style (the rectangular red ones)        |   3 |
| IEC power switch with fuse, rectangular snap fit                         |   1 |
| IEC power cord                                                           |   1 |

Notes:
- Current files provide mounting for an Ender 3 footprint mainboard. I'm currently using a Mellow Fly E3 Pro V3 RRF board. More mounting options to come.


## Printed parts

Notes:
- All parts should fit on a printer with a 220mm build area. Max dimension is 218x220mm for the side panels. If printing on something like an Ender 3, you'll need to make sure that you're able to make use of the full build area as there's no extra room to spare.
- I used PETG for all my parts and they've held up nicely, but I also don't print ABS/ASA/etc. If printing those higher bed temp filaments, I'd recommend printing all the carriage parts as well as the bed support bracket in ASA/ABS.
- Print settings:
  - Layer height: 0.2mm
  - Walls: >4
  - Top/bottom layers: >4
  - Infill: >30%
  - Supports off

### Gantry
| Part                    | Qty |
| ----------------------- | --: |
| Top chassis             |   1 |
| Left mid brace          |   1 |
| Right mid brace         |   1 |
| Front left idler block  |   1 |
| Front right idler block |   1 |
| Rear left idler block   |   1 |
| Rear right idler block  |   1 |
| Rear idler spacer       |   2 |
| Rear mid frame          |   1 |
| Gantry body             |   1 |
| Gantry left end         |   1 |
| Gantry right end        |   1 |
| Y endstop bracket       |   1 |

### Print head
| Part                | Qty |
| ------------------- | --: |
| Belt clamp          |   2 |
| Hotend clamp        |   1 |
| Print carriage body |   1 |
| Print fan duct      |   1 |

### Z axis
| Part                 | Qty |
| -------------------- | --: |
| Bed support bracket  |   1 |
| Z adjuster clamp     |   1 |
| Z bottom bracket     |   1 |
| Bottom z clamp left  |   1 |
| Bottom z clamp right |   1 |
| Z top bracket        |   1 |
| Z top clamp          |   2 |

### Enclosure
| Part         | Qty |
| ------------ | --: |
| Front panel  |   1 |
| Left panel   |   1 |
| Right panel  |   1 |
| Rear panel   |   1 |
| Bottom case  |   1 |
| Aux fan duct (optional) |   2 |

### Electronics
| Part                       | Qty |
| -------------------------- | --: |
| AC power input lower cover |   1 |
| Mainboard bracket          |   1 |
