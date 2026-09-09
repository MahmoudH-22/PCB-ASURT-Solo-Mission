# ASURT LV Solo Mission — PCB Project

Custom PCB designed in Altium Designer as part of the ASURT (Ain Shams University Racing Team)
Low Voltage sub-team Solo Mission. The board was built by following a complete Altium Designer
PCB design walkthrough — schematic capture, component/footprint sourcing (SnapEDA), PCB layout,
and full fabrication output generation (Gerbers + NC drill file) for manufacturing.

## Contents

- `PCB_Project/schematic.SchDoc` — full schematic
- `PCB_Project/Main.PcbDoc` — PCB layout
- `PCB_Project/parts/` — component libraries (schematic symbols + footprints)
- `PCB_Project/Project Outputs for PCB_Project/` — fabrication outputs (Gerber layers + NC drill file)

## Tools Used

- **Altium Designer** — schematic capture and PCB layout
- **SnapEDA** — component footprint/symbol libraries

## Schematic

STM32F411 MCU, MPU-6050 IMU, and USB/3V3 power regulation.

![Schematic overview](PCB/schematic-overview.png)
![MCU section](PCB/schematic-mcu.png)
![IMU section](PCB/schematic-imu.png)
![USB / power section](PCB/schematic-power-usb.png)

## PCB Layout

![PCB layout - top copper](PCB/pcb-layout-top.png)
![PCB layout - rotated view](PCB/pcb-layout-top-rotated.png)
![PCB layout - detail view](PCB/pcb-layout-detail.png)
![PCB silkscreen / GND pour view](PCB/pcb-silkscreen-view.png)
![PCB board outline view](PCB/pcb-outline-view.png)

## 3D View

![3D render](PCB/pcb-3d-view.png)
