# Mechagrid Case

A case for the [mechatrellis_grid](https://github.com/okyeron/shieldXL/) by Denki Oto

<img src="images/promo_1.JPG" width=100%>

## DISCLAIMERS

This not supported by Denki Oto and they are not responsible for assisting with assembly or troubleshooting.

THIS PROJECT IS STILL UNDER CONSTRUCTION. Design and documentation is not finished and everything is subject to change.

| Table of Contents |
| - |
| Credits |
| BOM |
| Models & Printing |
| Assembly |
| Installation |
| Troubleshooting |

<img src="images/promo_2.JPG" width=60%>

## Credits

Major shout out to Steve from Denki Oto for designing and building the mechatrellis boards!

## BOM

<img src="images/bom_8x16.JPG" width=80%>

### Common Parts

- 1x assembled mechatrellis board (`8x8` or `8x16`) and dink-ii board (Boards are available at the [Denki Oto Shop](https://denki-oto.weebly.com/))
- 1x matching case part(s) for the mechatrellis board
- 3x 4mm M2.5 bolts
- 3x M2.5 heatset inserts (7x if building `8x16` grid)
- Key switches
  - Pictured grid assembled with Choc silver keyswitches
- Key switch caps
  - Pictured grid assembled with Chocfox CFX translucent caps
- *Optional:* ESD Tape

### 8x8 Parts

- 4x 20mm x 2mm circular rubber feet
- 12x 8mm M2.5 bolts (16x if building with `short_light_barrier`)
- 4x 10mm M2.5 bolts (none if building with `short_light_barrier`)

### 8x16 Parts

- 6x 20mm x 2mm circular rubber feet
- 24x 8mm M2.5 bolts (32x if building with `short_light_barrier`)
- 8x 10mm M2.5 bolts (none if building with `short_light_barrier`)
- 4x 4mm diameter 300mm long metal rods

## Models & Printing

STLs made with love in [Blender](https://www.blender.org/) and [CAD Sketcher](https://www.cadsketcher.com/).

gcode and prusa slicer files can be found in `/prints`, stls in `/models`. Tested with PLA on Prusa MK4 printers.

Depending on the size of the mechatrellis board, choose the right parts.

### 8x8 Case

This is a single print part.

- 8x8_case
- 8x8_light_barrier

### 8x16 Case

3D printable parts are broken down into multiple pieces. Make sure you print everything.

- 8x16_case_left
- 8x16_case_middle
- 8x16_case_right
- 8x8_light_barrier
- 8x16_light_barrier

### Light Barrier

While being entirely aestetic, there can be quite a bit of light bleed from key to key. Included are models for a light barrier that reduces bleed between keys.

| Without | With|
| - | - |
| <img src="images/no_light_barrier.JPG" width=100%> | <img src="images/light_barrier.JPG" width=100%> |

## Assembly

*Make sure to test your mechatrellis board and driver before assembling with the case. Once the boards are assembled in the case, troubleshooting will require removing the mechatrellis boards from the case!*

It is recommended to read instructions all the way through before following along with your case assembly.

<img src="images/8x16_caseless_powered.JPG" width=60%>

Any JCT port can be used for connecting dink-ii to the mechatrellis boards however, when viewing from the back, these case designs use the top right most board to connect the mechatrellis and dink-ii boards.

<img src="images/pcb_back_jct_connector.JPG" width=60%>

## 8x8 Case Assembly

1. Embed heat set inserts for dink-ii board. *Locations noted below*

<img src="images/8x8_heatset_inserts.JPG" width=60%>

2. Place the dink-ii board into the case and secure with 3x `4mm` M2.5 bolts *(If alignment isn't perfect, try lightly threading all three bolts before tightening until the `dink-ii` board doesn't move around.)*

<img src="images/8x8_dink-ii.JPG" width=80%>

### 8x16 Case  Assembly

<img src="images/8x16_pcb_back.JPG" width=60%>

1. Embed heat set inserts in all three case parts. *Locations noted below*

<img src="images/8x16_heatset_inserts.JPG" width=80%>

2. With the key switches facing up, attach the light barrier parts to the pcba using M2.5 bolts *(`8mm` if using short_light_barrier, `10mm` if using long_light_barrier.)*.

3. Carefully insert metal rods  into one of the end case parts.

<img src="images/8x16_metal_rods.JPG" width=80%>

4. Slide middle case part onto metal rods *(Ensure the heatset inserts and through holes are aligned, you may need to use a mallet to help align the parts. Use a towel or pad to reduce the chance of cracking or breaking case parts. I recommend more light taps rather than fewer hard smacks, harder smacks to align parts.)*
5. Insert and tighten 4x `8mm` M2.5 bolts to secure the three case parts together. *(Optional: Cover case bolts with ESD tape.)*

<img src="images/8x16_assembled_case.JPG" width=80%>

6. Place the dink-ii board into the case and secure with 3x `4mm` M2.5 bolts *(If alignment isn't perfect, try lightly threading all three bolts before tightening until the `dink-ii` board doesn't move around.)*

<img src="images/8x16_dink-ii.JPG" width=80%>

7. Set the mechagrid board face down (Recommended to place pcba on a protective cloth.)
8. Connect the `JCT` cable between dink-ii and mechagrid pcba.

<img src="images/8x16_dink-ii_mechagrid_connection.JPG" width=80%>

9. Place case onto mechagrid pcba.
10. Align and secure the case with `8mm` M2.5 bolts. *(Not all bolts are required, only one bolt per 4x4 board is necessary but all 3 are recommended for a super secure connection.)*
11. Apply rubber feet to inserts.

<img src="images/8x16_back_case_assembled.JPG" width=80%>

### Norns Setup

<img src="images/norns_device_setup.JPG" width=60%>

## Troubleshooting / FAQ

Under constuction