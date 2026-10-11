# Rectifier Lab

Interactive simulator for single-phase and three-phase rectifiers: diode bridge, half-controlled and fully controlled thyristor bridges, with a live schematic and voltage/current waveforms.

**Author:** Trivedi Rishi Tejas  
**Roll No.:** 24EE10103

## Features
- 6 configurations: 1-phase / 3-phase × diode / half-controlled / fully controlled
- Adjustable firing angle α, load R and L
- Schematic highlights conducting devices at the chosen ωt
- Waveforms: source voltage, output voltage (with V_avg), load current, source current
- Simulated V_avg compared against the ideal continuous-conduction formula; CCM/DCM indicator

## Model
Ideal switches, series R–L load (no back-EMF), 325 V peak, 50 Hz. The load equation is stepped for 40 cycles to reach steady state and the last cycle is plotted.

## Run
Open `index.html` in any browser. No build step or dependencies.

## Deploy (GitHub Pages)
Repo Settings → Pages → Deploy from branch → `main` / root.
