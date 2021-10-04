# Caution Hot PCB Sign
Just a simple heat resistant "Caution Hot" sign made out of two PCBs.

> :warning: **This board was created with KiCad Nightly (5.99).** Exported gerbers are in `CautionHot_gerber/`, so you can order PCBs without installing this version of KiCad.

| ![Layout in KiCad](doc/PCB_screenshot.jpg) | ![Finished sign](doc/soldered_sign.jpg) | ![Sign in use](doc/sign_in_use.jpg) |
| ------------------------------------------ | --------------------------------------- | ----------------------------------- |
| Layout in KiCad                            | Finished sign                           | Sign in use                         |

## How to Order
Simply upload the .zip file in the gerber folder to you favourite PCB manufacturing website.  

> :warning: The JLCPCB preview doesn't detect the outline correctly. This isn't a problem, it will still be manufactured correctly. But you need to input the PCB size manually.

The parameters I used for my order at JLC:
- 35 x 60 mm
- 2 layers
- 1.6mm PCB thickness
- Yellow solder mask
- LeadFree HASL surface finish

## How to Solder
It's best to lay one PCB flat, hold the other one above it at an angle and just flood the lower pad with solder. It'll then wick in between the PCBs and solder them together quite well.
![How to solder the PCBs](doc/how_to_solder.jpg)