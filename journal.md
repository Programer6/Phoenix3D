Made by: @codelife / @programmer6
# 3D Printer Design: CAD & PCB Documentation

**Project Status:** Awaiting funding 

**CAD:** https://a360.co/4kbavNb

**Time**  50 HOURS

**Respository link:**  https://github.com/Programer6/Phoenix3D



## Project Overview

Del-X is a custom‑designed 3D printer, fully OPEN Source.  
This build was my deep dive into printer mechanics,and  electronics, and is open‑source project you can replicate or remix made for [highway](https://highway.hackclub.com).


- **Print Volume:** 217 × 217 × 230 mm  
- **Frame:** 2020 & 2040 aluminum extrusion  
- **Motion:** CoreXY with linear rails  
  
Just a quick note i was rlly lazy to document the journal while making the 3D printer thus, I don't really remember the excate date of which I completed the making of the 3d printer model thus I have put the estimate of the time i spent on each of the task! Hope you enjoy going through my journal!
                                                                                                                                                                |

Here is some research that I did after reviwing AK printer's documentation which came in clutch:

- https://www.instructables.com/How-to-Design-and-Build-a-3D-Printer/
- https://kingroon.com/blogs/3d-print-101/cartesian-vs-corexy
- https://reprap.org/wiki/Build_A_RepRap
- https://www.instructables.com/Complete-newbie-step-by-step-3D-printer-with-all-p/
- https://www.drdflo.com/pages/Guides/How-to-Build-a-3D-Printer/FFF.html
- https://www.geeky-gadgets.com/mondrian-customisable-reprap-3d-printer-07-12-2015/
- https://reprap.org/wiki/Choosing_a_Power_Supply_for_your_RepRap

Overall, it helped me gathering references and brainstorming ideas and I also screenshot various reference images for the guides to help me out later while making my 3d printer. I did really need to do much research but i wanted to keep different compared the the bambu mini style printer that i designed during infill so I went for a CoreXY which is more challenging obviously due the nature of the need of extra extrusion this 3d printer will have to be design at a smaller size of build area of 217 * 217 * 230 mm which is a bit smaller than the bambu mini but it will be more than enough for my needs and I will be able to print at a higher speed and with more precision while also making it compact and later on if I can always add frame which will make it look super cool! This printer is largely inspired by the x301 serise of a open source 3d printer by the marker mashup with a 300*300*400 build area printer. My design mainly airms to make the over build area smaller and as well as replace the 20*80 which take a significat portion of the bom and are unnecessary.

## Build Log



- Then made a BOM:
- 5 hours !!!!!!
- Sourced AliExpress parts:  BMG extruder, linear rails, belts. Was extremely hard to stay in budget, hit $300. Some of the part are most like not going to brough such as the neopixels as at this poitn it seems as if i am going quite above my budget of 350$
  
##  Bill of Materials
I have not added aliexpress links as they expire or get moved quite quickly as well and the fulctuating nature of the price itself so i hava given a estimate for each section 

# Phoenix3D (x201) - Full Bill of Materials (Sourced Individually - see cost breakdown in csv)

## Frame & Mechanical
| Qty | Item                                        | Notes                                   |
|:---:|:--------------------------------------------|:----------------------------------------|
| 3   | Aluminum Extrusion 20x80mm                  | **300mm Long**                          |
| 7   | Aluminum Extrusion 20x20mm                  | **300mm Long**                          |
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
These parts are not strictly required for a functional printer but are highly recommended for better quality, reliability, and ease of use. I intend to pay for these out of my own pocket in the future.

| Qty | Item                                        | Notes                                                   |
|:---:|:--------------------------------------------|:--------------------------------------------------------|
| 1   | Aluminum Carriage Plate                     | `Rec:` Strongly Recommended for rigidity                |
| 1   | Dual Sided PEI Build Plate                  | `Opt:` ~235mm x 235mm to match the heat bed             |
| 1   | Switched Power Inlet (Square Improved Version) | `Opt:` Provides a cleaner, snap-in installation         |
| 1   | Hardened Steel Volcano Nozzles (0.4mm)      | `Opt:` Needed only for printing abrasive filaments      |
| 12  | Insulated Fork Spade Wire Connector         | `Opt:` For safer, more secure PSU wiring                |
| 3   | Insulated Wire Crimp Terminal (Female)      | `Opt:` For safer, more secure switch wiring             |
---


# Build Log

## Stage 0: Chossing the equipment MAY 19 - 25
- Motion: CoreXY with linear rails for speed and precision.
<img width="209" alt="Screenshot 2025-06-29 at 11 49 02 AM" src="https://github.com/user-attachments/assets/20033554-22fb-4990-aacb-00684fab1a29" />

- Extrusion: Bowden setup with a BMG extruder to keep the toolhead light.
<img width="460" alt="Screenshot 2025-06-29 at 11 49 50 AM" src="https://github.com/user-attachments/assets/701c6b5f-a275-41d1-b4b6-3b10ca1681dd" />

- Electronics: SKR 1.4 board for 32-bit processing and TMC2209s for sensorless homing.
<img width="383" alt="Screenshot 2025-06-29 at 11 51 17 AM" src="https://github.com/user-attachments/assets/98a64335-105f-466f-84df-7e58023adec9" />
<img width="476" alt="Screenshot 2025-06-29 at 11 51 42 AM" src="https://github.com/user-attachments/assets/cea6ba46-47d3-475d-a991-58ace48367ef" />


## Stage 1: Base Frame Setup MAY 19 - 25
I started with the base. modeling the bottom plate, attaching the main vertical extrusions, and designing the initial Z-axis motor mount. 
- 5 hour
  
![Stage 1](https://github.com/user-attachments/assets/812a07d3-a7af-42d6-bfeb-7ab74abc116c)


---

## Stage 2: Top Frame & Z-Axis Motion MAY 26 - 30 
Next, I added the top frame to complete the cube. I then on the Z-axis motion, adding the linear rails and the first parts of the bed carriage. This ensuring the vertical movement would be stable and that kinda stuff
- 6 hour

Putting it all together:
![Stage 2](https://github.com/user-attachments/assets/0a4f02e4-33bd-4537-953e-e8c11f572867)


---

## Stage 3: Motor & Pulley Mounts JUN 1 - 25        
I spent a solid few hours designing and positioning the complex 3D-printed corner mounts for the motors and idler pulleys. 
- 15+ hour
<br>
- bed bracket from scratch, to precisely place the mounting holes.
<img width="943" alt="Screenshot 2025-06-29 at 11 59 55 AM" src="https://github.com/user-attachments/assets/fa90e274-c035-46eb-a24b-5b68e37ed638" />
<br>
<img width="702" alt="Screenshot 2025-06-29 at 8 32 43 AM" src="https://github.com/user-attachments/assets/bbf2e040-cc63-4d6f-ad88-ce8ff7bdbfa5" />
<br>
Z-axis & XY motor mounts were designed from scratch to precisely align the stepper motors and lead screws with the vertical frame
<img width="934" alt="Screenshot 2025-06-29 at 8 33 37 AM" src="https://github.com/user-attachments/assets/4a157384-aa9a-455f-98d1-9b6ffa46dffa" />
<img width="489" alt="Screenshot 2025-06-29 at 12 39 36 PM" src="https://github.com/user-attachments/assets/3321287e-f145-4be9-a5d6-35d901b52a83" />

<br>
<img width="278" alt="Screenshot 2025-06-29 at 12 41 10 PM" src="https://github.com/user-attachments/assets/9663db9b-b0e5-4692-84d2-09b1bcc4175b" />

-  the feet designed to give the printer a stable stance
<img width="712" alt="Screenshot 2025-06-29 at 12 32 11 PM" src="https://github.com/user-attachments/assets/5c15139b-6449-46c2-a2db-2d8a3a0270d5" />

---

## Stage 4: Digital Assembly JUN 26- 28
With all the custom parts designed, the final step was the full digital assembly. I put everything together to check for collisions and ensure the mechanics worked.  
- 6 hour
![Stage 4](https://github.com/user-attachments/assets/8261fe7e-037a-48b3-b6c7-eeea36604f7b)


This is the low esitimate of the amout of time spent on desinging it took also qzuite a lot of time to desing as most of it was done during free time in school.

<img width="546" alt="Screenshot 2025-06-28 at 10 04 55 AM" src="https://github.com/user-attachments/assets/a4924b90-3da0-431e-af2f-77deec2937bc" />


##  Designed the part thoughout the process
<img width="399" alt="Screenshot 2025-06-28 at 9 38 35 PM" src="https://github.com/user-attachments/assets/3133e443-ede4-46ad-8a7a-69ff03b3a11d" />
<img width="300" alt="Screenshot 2025-06-28 at 9 50 45 PM" src="https://github.com/user-attachments/assets/c2aa1e1d-c7dc-4cbd-850f-b86fbbe94601" />

# Design the BOM 28
26-28
Since I already had my stuff decied in cad it didn't take that long about 5 - 6 houts. 



# Added toolhead
<img width="455" alt="Screenshot 2025-06-29 at 2 00 45 PM" src="https://github.com/user-attachments/assets/b8f06a08-e3cc-4904-aca0-3cf6845f45f6" />

# Design the BOM - Jul 8 
I was stuck doing a bunch of other YSWS as well as working on other highway projects so it took a bit of a while to actually make the changes after being reject for not having links in my BOM missing the some electronic component in the BOM, not the changes have been made updated! 

![screenshot_2025-07-08_at_8 16 12___pm_720](https://github.com/user-attachments/assets/67ec9dea-c231-4a44-9177-c425f30adf86)

<img width="498" alt="Screenshot 2025-07-08 at 8 59 34 PM" src="https://github.com/user-attachments/assets/f06b12fc-97b5-4786-b1c8-383b36b42748" />
