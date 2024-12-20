# Elegoo Neptune 4 OrcaSlicer Settings

## Current Status Summary
- Flow calibration completed (0.97 ratio)
- Bed leveling and Z-offset calibrated
- E-steps verified at factory settings
- Small feature quality issues identified
- Next: Cooling configuration testing

## Recent Calibration Progress
Chat #4 - Flow Calibration (Latest)
- Completed flow calibration using OrcaSlicer test
- Optimal flow ratio determined: 0.97 (-3% adjustment)
- Good results on main surfaces
- Issues identified with small feature quality
- Part cooling fan at 50% max, activating intermittently

## Next Steps
1. Cooling Configuration Testing
   - Option 1: No part cooling fan
   - Option 2: Constant 30% fan speed
   - Focus: Improving small feature quality while maintaining main surface quality

2. Temperature Calibration (Pending)
   - To be done after cooling optimization
   - Previous attempt: too brittle
   - Target range: 190°C - 220°C

3. Pressure Advance (Future)
   - Currently disabled (0.02)
   - To be enabled after cooling and temperature dialed in
   - Planned starting value: 0.025

## Current Settings

### Hardware Configuration
- Printer: Elegoo Neptune 4 with 0.4mm nozzle
- Firmware: Klipper v1.1.3.2
- Screen Firmware: v1.2.14
- Bed Leveling: Completed (±0.05mm variance)
- WebUI IP: 10.42.70.42

### Material Settings
- Type: Generic PLA
- Flow Ratio: 0.97 (newly calibrated)
- Diameter: 1.75mm
- Part Cooling: 50% max (under investigation)

### Temperature Settings
- Nozzle:
  - First Layer: 210°C
  - Other Layers: 205°C
- Bed: 60°C

### Retraction Settings
- Length: 0.8mm
- Speed: 35mm/s
- Deretraction: 35mm/s
- Z Hop: 0.4mm
- Minimum Travel: 1mm
- Wipe Distance: 1mm
- Retract before Wipe: 85%

### Quality Settings
- Wall Loops: 3
- Top Layers: 4
- Bottom Layers: 3
- Layer Height: 0.2mm
- First Layer Height: 0.2mm

### Speed Settings
- First Layer: 50mm/s
- Outer Wall: 120mm/s
- Inner Wall: 200mm/s
- Top Surface: 120mm/s
- Infill: 200mm/s
- Travel: 350mm/s

### Acceleration Settings
- Normal Print: 5000mm/s²
- Outer Wall: 3000mm/s²
- Inner Wall: 3000mm/s²
- First Layer: 1000mm/s²
- Travel: 5000mm/s²

## Notes
- Keep settings document updated after each calibration session
- Document all changes and their effects
- Current focus: Resolving small feature quality while maintaining excellent main surface quality