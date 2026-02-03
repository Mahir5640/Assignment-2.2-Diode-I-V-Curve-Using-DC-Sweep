# Assignment 2.2 – LTspice DC Sweep (Diode I–V)

## Student
**Mahir F Chowdhury**

## Files Included
- `diode_iv_schematic.asc` — LTspice schematic file
- `screenshots/schematic.png` — LTspice schematic screenshot
- `screenshots/diode_iv_plot.png` — Diode I–V simulation plot

## DC Sweep Settings
- **Source:** V1
- **Sweep range:** 0 V → 5 V
- **Step:** 0.01 V

## Description
The simulation plot shows the **current–voltage (I–V) characteristic** of a diode.  
At low voltages, the diode current is nearly zero. After the forward voltage (~0.6–0.7 V), current increases exponentially as expected from diode physics.

## How to Run
1. Open `diode_iv_schematic.asc` in LTspice.
2. Press **Simulate → Run**.
3. Select the wire at the diode anode for voltage.
4. Add trace `I(D1)` to view diode current.
