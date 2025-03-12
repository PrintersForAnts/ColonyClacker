## Colony Clacker

### A 'Clicky-Clack Fridge Door' inspired, clicky clacking door for the colony of Printers for Ants!

![](https://github.com/PrintersForAnts/ColonyClacker/blob/main/Images/1-Colony%20Clacker_Full.png)

Colony Clacker is a scaled down version of the awesome [Clicky-Clack Fridge Door](https://github.com/tanaes/whopping_Voron_mods/tree/main/clickyclacky_door) by tanaes.

Completely remodeled from scratch (not just resized), with added stealthy aesthetics, improved tolerances, and STLs that have been optimised for best slicer performance with standard Voron print settings.

Provides the same satisfying clack when closing the door, whilst also increasing chamber temps, and reducing noise.

Initially designed for Micron+, but will fit all 1515 based printers that use 3mm foam tape, with 3mm Panels.

1mm foam variants in the works... stay tuned.

[See the Clacky action here.](https://youtube.com/shorts/yi75DsFQ0eI?si=P8Z4A60wTr4WiRiI)

![](https://github.com/PrintersForAnts/ColonyClacker/blob/main/Images/2-ColonyClacker_Full_Handle.png)
![](https://github.com/PrintersForAnts/ColonyClacker/blob/main/Images/3-ColonyClacker_Full_Hinges.png)
![](https://github.com/PrintersForAnts/ColonyClacker/blob/main/Images/4-ColonyClacker_Handle.png)
![](https://github.com/PrintersForAnts/ColonyClacker/blob/main/Images/5-ColonyClacker_Bottom%20Hinge.png)

## BOM

### Hardware
Qty|Item|Notes|Links (Affiliate)
---|----|----|---
x14|M3x12 BHCS| |[Aliexpress](https://s.click.aliexpress.com/e/_Exdxtsp)
x4|M3X16 SHCS| |[Aliexpress](https://s.click.aliexpress.com/e/_EGPNidr)
x2|M3x20 SHCS| |[Aliexpress](https://s.click.aliexpress.com/e/_EGPNidr)
x14|M3 Hex Nut| |[Aliexpress](https://s.click.aliexpress.com/e/_EwEY3Rf) ~ [Amazon](https://amzn.to/3NtQHXi)
x4|M5 x 7mm x 8mm Split Bushing| |[Aliexpress](https://s.click.aliexpress.com/e/_EvcAzIV) ~ [Amazon](https://amzn.to/3Yrq8rT)
x4|5mm x 40mm Dowel Pin| |[Aliexpress](https://s.click.aliexpress.com/e/_Ex91QWD) ~ [Amazon](https://amzn.to/40eAuNr)
x8|6mm x 3mm N52 Magnet| |[Aliexpress](https://s.click.aliexpress.com/e/_EIDUzuD) ~ [Amazon](https://amzn.to/3YqHEga)
1.3M|3mm Foam Tape|2.5M for 2x seals on door|[Aliexpress](https://s.click.aliexpress.com/e/_EzqH685) ~ [Amazon](https://s.click.aliexpress.com/e/_EzqH685)
x4|Micron R1 Twist lock key|Printed key for `panel_corner_bracket.stl`|[[a]_twist_lock_key.stl](https://github.com/PrintersForAnts/Micron/blob/main/R1_Beta/STLs/Panels/%5Ba%5D_twist_lock_key_x50.stl)

### Micron+ Door
Qty|Item
---|---
x2|350mm 1515 Aluminium Extrusion
x2|280mm 1515 Aluminium Extrusion
1x|3mm Acrylic or PC Panel - 330mm x 290mm

Extrusions & hardware are also available from [DLLPDF](https://www.dllpdf.com/colony-clacker).



## Printing
All parts should be correctly orientated and should be printed with Standard Voron print settings.

There is an optional latch version with a larger surface area on the build plate if you get failed prints with the stock variant.

The print orientation of the latch is intentional to ensure larer lines aren't in the same direction as the latching mechanism, and to keep the printed aesthetic matiching the other printed parts.

## Assembly
Assembly is reletively self explanatory, the following images should help if you get stuck and can't access the CAD.

**Ensure you superglue your magnets into the latch and the corresponding handle piece.**

![](https://github.com/PrintersForAnts/ColonyClacker/blob/main/Images/7-ColonyClacker_Handle%20AB_Latch.png)
![](https://github.com/PrintersForAnts/ColonyClacker/blob/main/Images/8-ColonyClacker_Handle_No%20Top.png)
![](https://github.com/PrintersForAnts/ColonyClacker/blob/main/Images/ColonyClacker_Handle_AB_Hardware.png)
![](https://github.com/PrintersForAnts/ColonyClacker/blob/main/Images/ColonyClacker_Handle_C_Hardware.png)
![](https://github.com/PrintersForAnts/ColonyClacker/blob/main/Images/ColonyClacker_Handle_Latch_Hardware.png)
![](https://github.com/PrintersForAnts/ColonyClacker/blob/main/Images/ColonyClacker_HingeBottom_Hardware.png)
![](https://github.com/PrintersForAnts/ColonyClacker/blob/main/Images/ColonyClacker_HingeTop_Hardware.png)

## Optional Skirts
There are currently some extended skirts for the following PFA Printers.
Improving the overall aesthetic and screen access.
(Others will be added as they are created)

### Micron+ with G2Z
Stock BOM Hardware, with the following additions for display bezel accents pieces:
- 2x M3x5x4 Heatset Insert
- 2x M3x8 BHCS
![](https://github.com/PrintersForAnts/ColonyClacker/blob/main/Images/ColonyClacker_Micron_Skirts_cad.png)


## Version History

### 12-Mar-25
- Fixed Issue [#1](https://github.com/PrintersForAnts/ColonyClacker/issues/1)

### 17-Oct-24
- Added `Larger Surface Area Latch`
`[a]_LSA_Latch_Extra_Clearance_x1` & `[a]_LSA_Latch_Standard_x1`
Reduced fillet on corners to increase surface area on build plate, to reduce print failures due to intended print orientation
- Corrected text on exploded image: `ColonyClacker_Handle_Latch_Hardware.png`, from 'M3x12 SHCS' to 'M3x12 BHCS'
- Updated CAD to reflect above
- Updated readme

### 10-Oct-24
- Added missing chamfer to: `Top_Door_Mount_L_x2`
- Added missing chamfer to: `Top_Door_Mount_R_x2`
- Added STL: `[a]_Latch_Extra_Clearance`
- Corrected naming of `[a]_Latch_Standard`
- Corrected naming of `Top_Door_Mount_R_x2`
- Updated CAD to reflect above
- Updated readme

### 08-Oct-24
Initial Release
