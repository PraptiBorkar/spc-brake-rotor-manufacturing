# SPC Analysis — Automotive Brake Rotor Manufacturing

## Overview
A Statistical Process Control (SPC) study of brake 
rotor thickness measurements in an automotive 
manufacturing process using X-bar and R control charts.

## Methodology
- X-bar and R Control Charts (n=5, 25 subgroups)
- Control limit constants: A2=0.577, D3=0, D4=2.114
- Process Capability Analysis (Cp and Cpk)
- AIAG SPC Reference Manual (2nd Edition)

## Dataset
- 125 measurements (25 subgroups × 5 readings)
- Target thickness: 25.00 mm ± 0.15 mm
- USL: 25.15 mm | LSL: 24.85 mm

## Key Findings
| Parameter | Value | Assessment |
|-----------|-------|------------|
| X-double-bar | 25.008 mm | Centered near target |
| Cp | 2.77 | Excellent capability |
| Cpk | 2.75 | Well centered |
| Out-of-control signals | 4 | Samples 13,14,15,21 |

## Out-of-Control Events
- Samples 13–15: Furnace temperature drift → 
  sustained upward mean shift above UCL
- Sample 21: Non-conforming material batch → 
  sudden downward mean shift below LCL

## Key Insight
R chart showed all points in control while X-bar 
chart detected 4 signals — confirming process 
disturbances caused mean shifts without increasing 
variation. Critical distinction for root cause 
investigation.

## Tools Used
- Microsoft Excel — data analysis and chart construction
- X-bar and R control charts
- Cp and Cpk process capability indices

## Author
Prapti Borkar
B.Tech Metallurgical & Materials Engineering, Second Year
Indian Institute of Technology, Ropar

## Reference
AIAG SPC Reference Manual, 2nd Edition (2005)
