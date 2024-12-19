# Elegoo Neptune 4 OrcaSlicer Settings

## Hardware Configuration
- Printer: Elegoo Neptune 4 with 0.4mm nozzle
- Firmware: Klipper v1.1.3.2
- Screen Firmware: v1.2.14
- Bed Leveling: Completed with ±0.05mm variance
- WebUI IP: 10.42.70.42

## Basic Machine Settings
- Printable Height: 265mm
- Best Object Position: x: 0.50, y: 0.50
- G-code Flavor: Klipper
- G-code Thumbnails: 320x320, 160x160
- Format: ColPic
- Nozzle Type: Hardened Steel

## Extruder Configuration
- Nozzle Diameter: 0.4mm
- Layer Height Limits:
  - Min: 0.08mm
  - Max: 0.32mm
- Extruder Offset: x: 0, y: 0mm

## Retraction Settings
### Current Settings
- Length: 0.8mm
- Retraction Speed: 35mm/s
- Deretraction Speed: 35mm/s
- Z Hop When Retracting: 0.4mm
- Travel Distance Threshold: 1mm
- Wipe Distance: 1mm
- Retract Amount Before Wipe: 85%
- Retract on Layer Change: Enabled
- Wipe While Retracting: Enabled

### Previous Settings (For Reference)
- Length: 5mm
- Retraction Speed: 60mm/s
- Deretraction Speed: 45mm/s

## Speed Settings
- First Layer: 50mm/s
- First Layer Infill: 80mm/s
- Outer Wall: 120mm/s
- Inner Wall: 200mm/s
- Top Surface: 120mm/s
- Sparse Infill: 200mm/s
- Travel Speed: 350mm/s

## Acceleration Settings
- Normal Printing: 5000mm/s²
- Outer Wall: 3000mm/s²
- Inner Wall: 3000mm/s²
- First Layer: 1000mm/s²
- Travel: 5000mm/s²

## Temperature Settings
- Nozzle:
  - First Layer: 210°C
  - Other Layers: 205°C
- Bed: 60°C (both first layer and other layers)

## Quality Settings
- Wall Loops: 3
- Top Shell Layers: 4
- Top Shell Thickness: 0.8mm
- Bottom Shell Layers: 3

## Infill Settings
- Sparse Infill Density: 15%
- Pattern: Grid
- Infill/Wall Overlap: 25%
- Infill Direction: 45°

## Material Settings
- Type: Generic PLA
- Flow Ratio: 0.98
- Pressure Advance: 0.02 (disabled)
- Diameter: 1.75mm

## Future Improvements to Consider

1. Temperature Adjustments:
   - Consider reducing to:
     - First Layer: 205°C
     - Other Layers: 200°C

2. Pressure Advance:
   - Enable the setting
   - Start with 0.025 and tune from there