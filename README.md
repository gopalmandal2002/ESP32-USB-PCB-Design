# ESP32-USB-PCB-Design
Custom ESP32 USB PCB designed in KiCad with schematic capture, PCB routing, antenna keep-out zone, copper pours, Gerber fabrication files, and 3D visualization.
# ESP32 USB PCB Design using KiCad

A custom ESP32-based USB PCB designed using KiCad, covering the
complete PCB development workflow from schematic and component
placement to PCB routing, copper zones, antenna keep-out design,
Gerber generation, and 3D visualization.

## Project Overview

The objective of this project was to understand and implement a
complete PCB design workflow using KiCad.

The project includes:

- ESP32-based PCB design
- Component placement and footprint management
- PCB trace routing
- Power and ground routing
- Copper zone implementation
- Antenna keep-out region
- Design Rule Check (DRC)
- Gerber file generation
- Gerber verification
- 3D PCB visualization

## PCB Layout

![PCB Layout](images/Layout.png)

The PCB layout was created in KiCad PCB Editor with appropriate
component placement, signal routing, power connections, and board
geometry.

## PCB Routing

![PCB Routing](images/pcb-routing.png)

Signal and power traces were routed while considering electrical
connectivity, trace clearance, and PCB design rules.

## ESP32 Antenna Keep-Out Zone

![Antenna Keepout](images/antenna-keepout.png)

A keep-out region was maintained around the ESP32 antenna section
to minimize interference from copper traces, planes, and components.

## Gerber Verification

![Gerber View](images/gerber-view.png)

Manufacturing files were generated and inspected using the KiCad
Gerber Viewer before fabrication.

## 3D PCB Visualization

![3D PCB]([images/pcb-3d-view.png](https://github.com/gopalmandal2002/ESP32-USB-PCB-Design/blob/main/PCB%203D.png)

The completed PCB was inspected using KiCad's 3D Viewer to verify
board geometry, component placement, and overall mechanical layout.

## Tools & Technologies

- KiCad
- PCB Design
- Schematic Capture
- PCB Layout
- Component Placement
- Trace Routing
- Copper Pour / Ground Plane
- Design Rule Check (DRC)
- Gerber Generation
- Gerber Viewer
- 3D PCB Visualization

## Design Workflow

1. Created the circuit schematic
2. Assigned component footprints
3. Defined PCB board geometry
4. Placed components
5. Routed signal and power traces
6. Added copper zones
7. Defined ESP32 antenna keep-out region
8. Performed design-rule verification
9. Generated Gerber and drill files
10. Verified fabrication outputs
11. Inspected the final PCB using the 3D Viewer

## Project Status

PCB design and fabrication-file preparation completed.

## Author

Gopal Mandal
