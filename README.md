# FootCube
<p align="center">
  <img src="images/footCube.png" width="30%" alt="FootCube">
</p>
Modification for the Voron Trident 300Cube printed parts to fit 1"x1" extrusion.

To maintain the belt path the A and B drive pulleys use four M5x30 SCHS in place of the M5x30 BHCS. 
There is a long shaft motor version of the A_Drive_Frame_Lower part that does not require supports. If the long shaft stepper motor is not used the motor must be set into the A_Drive_Frame_Lower part to maintain belt path.
I tried to keep everything as close to the original as possible. Below are a list of the BOM Changes.
# FRAME
| New Length | Machining | Qty | Equivalent LDO Part | Equivalent Misumi Part | Description | Machining Key |
|------------:|-----------|----:|---------------------|------------------------|-------------|---------------|
| 22.25 | LCP, RCP, AV16.5 | 4 | LDO-VTDF300C-2020T-550-LCP-RCP-AV (B) | Misumi HFSB5-2020-550-LCP-RCP-AV430 | Vertical extrusions with blind joint access holes pre-drilled | AV (Distance from the Left End Plane) = Vertical Wrench Hole Machining |
| 16.625 | TPW | 9 | LDO-VTDF300C-2020T-420-TPW (A) | Misumi HFSB5-2020-420-TPW | Horizontal extrusions for outer frame and Gantry | LCP = 1 Row Wrench Hole Crisscross from Left End Face |
| 16.625 | TPW, AH8.3125 | 1 | LDO-VTDF300C-2020T-420-AH-TPW (C) | Misumi HFSB5-2020-420-AH210-TPW | Lower rear horizontal extrusion | TPW = Both End Tapped |
| 15 | LTP | 1 | LDO-VTDF300C-2020T-380-LTP (E) | Misumi HFSB5-2020-380-LTP | Vertical rear center extrusion | LTP = Left End Tapped |
| 16.625 | AH8.3125 | 1 | LDO-VTDF300C-2020T-420-AH (F) | Misumi HFSB5-2020-420-AH210 | Front bed extrusion | AH (Distance from the Left End Plane) = Horizontal Wrench Hole Machining |
| 11 | LTP | 1 | LDO-VTDF300C-2020T-282-LTP (G)\* | Misumi HFSB5-2020-282-LTP | Rear bed extrusion | RCP = 1 Row Wrench Hole Crisscross from Right End Face |
| 11.5 | - | 1 | LDO-VTDF300C-2020T-290 (D)\* | Misumi HFSB5-2020-290 | Rear Cross Bar for Gantry: X Spec Dimension − 10 mm | |
| 15 | - | 1 | LDO-VTDF300C-2020T-380 (H) | Misumi HFSB5-2020-380 | X Axis Extrusion: X Spec Dimension + 80 mm | |
