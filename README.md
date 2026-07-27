# TSP-1X-16-

TSP-1X — Thermal Sensor Platform

A 16-inch hexacopter built as a stable, large-scale platform for testing sensors 
and autonomous flight systems. The first real-world application: using a thermal 
imaging camera to locate fawns hiding in tall grass before agricultural mowers 
put them at risk — with autonomous, AI-based detection (via Jetson Nano/Orin) 
planned for a later stage.

**Status:** Early build phase — frame and remaining motors not yet acquired. 
Currently focused on the electronics, starting with a custom-designed 
Power Distribution Board (PDB).

## Specs
- Frame: ZD850 (16")
- Motors: 6x Tarot 4114
- Power: 6S Li-Ion
- Current sensing: ACS770xCB-200U-PSF
- Custom PDB with integrated temperature sensing

## Roadmap
- [x] Frame & motor selection
- [x] PDB design (Gerbers ready)
- [ ] Electronics assembly
- [ ] Maiden flight
- [ ] Thermal camera integration
- [ ] Jetson Orin onboard object detection

![Frame](TSP-1X-16-/FRAME.png)
