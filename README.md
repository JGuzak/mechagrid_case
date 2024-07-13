# Mechagrid Case

A case for the [mechatrellis_grid](https://github.com/okyeron/shieldXL/) by Denki Oto

<img src="images/promo_1.JPG" width=100%>

- [Mechagrid Case](#mechagrid-case)
- [DISCLAIMERS](#disclaimers)
- [Credits](#credits)
- [BOM](#bom)
  - [Common Parts](#common-parts)
  - [8x8 Parts](#8x8-parts)
  - [8x16 Parts](#8x16-parts)
- [Models \& Printing](#models--printing)
  - [8x8 Case](#8x8-case)
  - [8x16 Case](#8x16-case)
  - [Light Barrier](#light-barrier)
- [Assembly](#assembly)
  - [8x16 Case Assembly](#8x16-case-assembly)
  - [8x16 Full Assembly](#8x16-full-assembly)
  - [8x8 Assembly](#8x8-assembly)
  - [Norns Setup](#norns-setup)
- [Troubleshooting / FAQ](#troubleshooting--faq)

# DISCLAIMERS

This not supported by Denki Oto and they are not responsible for assisting with assembly or troubleshooting.

THIS PROJECT IS STILL UNDER CONSTRUCTION. Design and documentation is not finished and everything is subject to change.

<img src="images/promo_2.JPG" width=60%>

# Credits

Major shout out to Steve from Denki Oto for designing and building the mechatrellis boards!

# BOM

<img src="images/bom_8x16.JPG" width=80%>

## Common Parts

- 1x assembled mechatrellis board (`8x8` or `8x16`) and dink-ii board (Boards are available at the [Denki Oto Shop](https://denki-oto.weebly.com/))
- 1x matching case part(s) for the mechatrellis board
- 3x 4mm M2.5 bolts
- 3x M2.5 heatset inserts (7x if building `8x16` grid)
- Key switches
  - Pictured grid assembled with Choc silver keyswitches
- Key switch caps
  - Pictured grid assembled with Chocfox CFX translucent caps
- *Optional:* ESD Tape

## 8x8 Parts

- 4x 20mm x 2mm circular rubber feet
- 12x 8mm M2.5 bolts (16x if building with `short_light_barrier`)
- 4x 10mm M2.5 bolts (none if building with `short_light_barrier`)

## 8x16 Parts

- 6x 20mm x 2mm circular rubber feet
- 24x 8mm M2.5 bolts (32x if building with `short_light_barrier`)
- 8x 10mm M2.5 bolts (none if building with `short_light_barrier`)
- 4x 4mm diameter 300mm long metal rods

# Models & Printing

STLs made with love in [Blender](https://www.blender.org/) and [CAD Sketcher](https://www.cadsketcher.com/).

gcode and prusa slicer files can be found in `/prints`, stls in `/models`. Tested with PLA on Prusa MK4 printers.

Depending on the size of the mechatrellis board, choose the right parts.

## 8x8 Case

This is a single print part.

- 8x8_case
- 8x8_light_barrier

## 8x16 Case

3D printable parts are broken down into multiple pieces. Make sure you print everything.

- 8x16_case_left
- 8x16_case_middle
- 8x16_case_right
- 8x8_light_barrier
- 8x16_light_barrier

## Light Barrier

While being entirely aestetic, there can be quite a bit of light bleed from key to key. Included are models for a light barrier that reduces bleed between keys.

| Without | With|
| - | - |
| <img src="images/no_light_barrier.JPG" width=100%> | <img src="images/light_barrier.JPG" width=100%> |

# Assembly

It is recommended to read instructions all the way through before following along with your case assembly.

*Make sure to test your mechatrellis board and driver before assembling with the case. Once the boards are assembled in the case, troubleshooting will require removing the mechatrellis boards from the case!*

*Be careful when dry fitting case parts (perticularly the metal rods), go slow, use small taps with a soft headed mallet if necessisary.*

<img src="images/8x16_caseless_powered.JPG" width=60%>

Any JCT port can be used for connecting dink-ii to the mechatrellis boards however, when viewing from the back, these case designs use the top right most board to connect the mechatrellis and dink-ii boards.

<img src="images/pcb_back_jct_connector.JPG" width=60%>

## 8x16 Case Assembly

1. Insert metal rods into each case part one at a time. The ideal fit for the rods are when they can't freely slide around but can be removed by bare hand.

*If segments get stuck, use a hand clamp and twist the rod while pulling until the rod can be removed by hand.*

<img src="images/8x16_metal_rods_1.JPG" width=40%><img src="images/8x16_metal_rods_2.JPG" width=40%>

<img src="images/8x16_metal_rods_3.JPG" width=40%><img src="images/8x16_metal_rods_4.JPG" width=40%>

2. Apply all 7 heatset inserts into the three case parts.

<img src="images/8x16_heatset_inserts_1.JPG" width=80%>

*When add the two inserts next to the usb c port, some soldering irons will touch the edge of the wall. When fully assembled this blemish is almost entirely hidden.*

<img src="images/8x16_heatset_inserts_2.JPG" width=80%>

3. Insert all 4 rods into `8x16_case_left` or `8x16_case_right`.

<img src="images/8x16_case_assembly_1.JPG" width=80%>

4. Ensure the middle is oriented correctly and slide it onto the metal rods.
5. Loosly insert a `8mm` M2.5 bolt into one of the case connection holes.

<img src="images/8x16_case_assembly_2.JPG" width=80%>

6. Add the final case piece and carefuly ensure that there isn't a gap between the case parts.

*If needed, use a soft mallet and a towel to gentily tap the case parts together. Make sure to tap the edge closer to the bottom of the case rather than the free floating wall, this will reduce the chance of accidentally cracking the side of the case.*

| Gap | No gap |
| - | - |
| <img src="images/8x16_case_assembly_gap.JPG" width=45%> | <img src="images/8x16_case_assembly_no_gap.JPG" width=45%> |

7. Insert and tighten the remaining `8mm` M2.5 bolts into the case.
8. *(Optional: Cover case bolts with ESD tape.)*

<img src="images/8x16_case_assembled.JPG" width=80%>

## 8x16 Full Assembly

<img src="images/8x16_case_assembled_1.JPG" width=60%>

1. With the key switches facing up, attach the light barrier parts to the pcba using M2.5 bolts *(`8mm` if using short_light_barrier, `10mm` if using long_light_barrier.)*.

<img src="images/8x16_light_barrier.JPG" width=80%>

2. Place the dink-ii board into the case and secure with 3x `4mm` M2.5 bolts *(If alignment isn't perfect, try lightly threading all three bolts before tightening until the `dink-ii` board doesn't move around.)*

<img src="images/8x16_dink-ii.JPG" width=80%>

3. Set the mechagrid bord face down (Recommended to place pcba on a protective cloth.)
4. Connect the `JCT` cable between dink-ii and mechagrid pcba.

<img src="images/8x16_dink-ii_mechagrid_connection.JPG" width=80%>

5. *(Optional: Connect the dink-ii to a norns via USB and load up a test script that uses grid. Make sure to follow the Norns Setup section.)*

<img src="images/8x16_sanity_check.JPG" width=80%>

6. Place case onto mechagrid pcba.
7. Align and secure the case with `8mm` M2.5 bolts. *(Not all bolts are required, only one bolt per 4x4 board is necessary but all 3 are recommended for a super secure connection.)*

<img src="images/8x16_back_case_bolts.JPG" width=80%>

8. Apply rubber feet to the bottom.

<img src="images/8x16_back_case_assembled.JPG" width=80%>

## 8x8 Assembly

1. Embed heat set inserts for dink-ii board. *Locations noted below*

<img src="images/8x8_heatset_inserts.JPG" width=60%>

2. Place the dink-ii board into the case and secure with 3x `4mm` M2.5 bolts *(If alignment isn't perfect, try lightly threading all three bolts before tightening until the `dink-ii` board doesn't move around.)*

<img src="images/8x8_dink-ii.JPG" width=80%>

3. Set the mechagrid bord face down (Recommended to place pcba on a protective cloth.)
4. Connect the `JCT` cable between dink-ii and mechagrid pcba.

<img src="images/8x8_dink-ii_mechagrid_connection.JPG" width=80%>

5. *(Optional: Connect the dink-ii to a norns via USB and load up a test script that uses grid. Make sure to follow the Norns Setup section.)*
6. Insert and tighten `8mm` M2.5 bolts *(Only 1 per trellis board is required but it's recommended to use as many bolts as possible.)*

<img src="images/8x8_case_assembled_2.JPG" width=80%>

## Norns Setup

<img src="images/norns_device_setup.JPG" width=60%>

1. Navigate to `System->Devices->Grid`.
2. Select `neo-monome-m{some set of numbers}`. *(If you compiled custom firmware, make sure this entry matches the firmware name.)*
3. Load up a test script to make sure the grid is working.

# Troubleshooting / FAQ

Under constuction.