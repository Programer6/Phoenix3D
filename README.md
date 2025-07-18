# Phoenix3D


**Phoenix 3D** is a *Compact CoreXY 3D Printer Design*.  
**Status:**: Awaiting Funding


<p align="center">
 <img width="507" alt="Screenshot 2025-07-08 at 9 00 15 PM" src="https://github.com/user-attachments/assets/8e949027-7de7-4986-beab-6edf46830ba2" />
</p>

  
---

## Specifications

- **X/Y Axis Travel:** 217 mm × 217 mm  
- **Z-Axis Travel:** 230 mm  
- Aluminum extrusion (2020/2040)
- CoreXY kinematics  
- Linear rails on X and Y axes


## Why I designed this 3D printer:

Building on the experience from bambu mini-style design 3d printer for infill (even tho i could not get it approved in time), designing a CoreXY felt like the natural progression to challenge myself with more advanced printer kinematics.


## Full Bill of Materials ( - see cost breakdown in csv)

## Frame & Mechanical
| Qty | Item                                        | Notes                                   |
|:---:|:--------------------------------------------|:----------------------------------------|
| 10   | Aluminum Extrusion 20x20mm                  | **300mm Long**                          |
| 3   | Aluminum Extrusion 20x20mm                  | **200mm Long** (Cross Members)          |
| 2   | Aluminum Extrusion 20x40mm                  | **300mm Long**                          |
| 1   | Aluminum Sheet .063" thickness              | **300mm x 340mm** (Bottom Plate)        |
| 12  | Aluminum Alloy T Slot L-Shape Joining Plate | Comes with M5x8 Screws & T-Nuts         |
| 10  | Inside Connector L-Bracket                  | For internal frame connections          |
| 1   | Gates Powergrip® GT2-6MM Belt               | 5 Meters I will have extra)             |
| 1   | Bowden Tube                                 | Cut to fit the smaller frame            |
| 1   | M10 Fitting                                 | For Bowden tube mount                   |

## Motion System
| Qty | Item                                        | Notes                                   |
|:---:|:--------------------------------------------|:----------------------------------------|
| 5   | MGN12H Linear Rail                          | **300mm long**, single block            |
| 2   | Stainless Steel Lead Screw (T8)             | **300mm long**, 2mm pitch, 2mm lead     |
| 2   | Flexible Shaft Coupling                     | 5mm to 8mm bore                         |
| 4   | Nema 17 Stepper Motors (High Torque)        | 1.8 degree step angle                   |
| 1   | Pancake Stepper Motor                       | For extruder assembly                   |
| 6   | GT2 Idler Pulley (Toothed)                  | 5mm Bore, 6mm Width                     |
| 2   | GT2 Idler Pulley (Toothless/Smooth)         | 5mm Bore, 6mm Width                     |
| 2   | GT2 Pulley (For Steppers)                   | 20 Teeth, 5mm bore, 6mm Width           |

## Electronics & Wiring
| Qty | Item                              | Notes                                   |
|:---:|:----------------------------------|:----------------------------------------|
| 1   | SKR V1.4 Mainboard                |                                         |
| 2   | TMC2209 Stepper Driver            | For X and Y axes (enables sensorless homing) |
| 2   | TMC2225 Stepper Driver            | For Z and Extruder axes                 |
| 1   | TFT 2.4 Inch Touch Screen Display |                                         |
| 1   | 24v 360w Power Supply             |                                         |
| 1   | V6 Style Hot End Nozzle (24v)     |                                         |
| 1   | BMG Style Geared Extruder         | Right-hand opening version              |
| 1   | Ender 3 Style Heat Bed (24v)      | ~235mm x 235mm                          |
| 1   | Stepper Wires (4 Pack)            |                                         |
| 1   | 5015 Blower Fan                   | For part cooling                        |
| 1   | Mechanical Endstop Limit Switch   | For Z-axis homing                       |
| 1   | USB Mount Panel                   | For rear of printer                     |
| 1   | Switched Power Inlet              |                                         |
| 1   | JST Connector Kit Assortment      |                                         |
| 1   | 1/2" Wire Wrap                    | For cable management                    |
| 1   | Shrink Tubing Assortment          |                                         |
| 1   | 16 Gauge Silicone Wire            | For power connections                   |
| 1   | Zip Tie Assortment                |                                         |

## 3D Printing Materials
| Qty | Item                      | Notes                                          |
|:---:|:--------------------------|:-----------------------------------------------|
| 1   | Pro PLA or PETG Filament  | ~1kg, for printing structural & cosmetic parts | - I already have this 


## Fasteners & Hardware
| Qty | Item                      | Notes                                   |
|:---:|:--------------------------|:----------------------------------------|
| 53  | M5x8mm Socket Head Screw  |                                         |
| 56  | M5 T-Nut                  |                                         |
| 6   | M5x12mm Socket Head Screw |                                         |
| 2   | M5x35 Button Head Screw   | For idler towers                        |
| 4   | M5x40mm Socket Head Screw | For front pulley stacks                 |
| 5   | M5x20mm Button Head Screw | For display panel                       |
| 2   | M5 Washer                 | For rear idler pulleys                  |
| 68  | M3x8mm Socket Head Screw  |                                         |
| 13  | M3x8mm Button Head Screw  |                                         |
| 1   | M3x8mm Flat Head Screw    |                                         |
| 6   | M3x12mm Socket Head Screws|                                         |
| 4   | M3x40mm Flat Head Screw   | For securing the bed to the mounts      |
| 34  | M3 T-Nut                  |                                         |
| 8   | M3 Nut                    |                                         |
| 8   | M3 Washer                 |                                         |
| 6   | M4x8mm Button Head Screw  | For power supply fan shroud             |
| 2   | M4x20mm Socket Head Screw | For part cooling fan                    |
| 1   | Silicone Leveling Column  | Set of 4, replaces bed springs          |

---
## End Cost Estimate
Section	Lower Estimate (USD)
1. Frame & Mechanical	$110
2. Motion System	$150
3. Electronics & Wiring	$150
4. Fasteners & Hardware	$35
Grand Total Estimate	$445 - This a high estimate 

## Optional Upgrades
 I intend to pay for these out of my own pocket in the future.

| Qty | Item                                        | Notes                                                   |
|:---:|:--------------------------------------------|:--------------------------------------------------------|
| 1   | Aluminum Carriage Plate                     | `Rec:` Strongly Recommended for rigidity                |
| 1   | Dual Sided PEI Build Plate                  | `Opt:` ~235mm x 235mm to match the heat bed             |
| 1   | Switched Power Inlet (Square Improved Version) | `Opt:` Provides a cleaner, snap-in installation         |
| 1   | Hardened Steel Volcano Nozzles (0.4mm)      | `Opt:` Needed only for printing abrasive filaments      |
| 12  | Insulated Fork Spade Wire Connector         | `Opt:` For safer, more secure PSU wiring                |
| 3   | Insulated Wire Crimp Terminal (Female)      | `Opt:` For safer, more secure switch wiring             |
---


<p align="center">
  <img src="https://hc-cdn.hel1.your-objectstorage.com/s/v3/0bbcca68ffa3845300bb76940f8ad91fd53d2d68_06-30-2025-1618.png" alt="A badge of a Cerberus and a raccoon laughing together, with the text 'HIGHWAY' and 'HACK CLUB' beside them." />
</p>

---

## 📄 License

This project is licensed under the **MIT License**.  
See the `LICENSE` file for more details.
