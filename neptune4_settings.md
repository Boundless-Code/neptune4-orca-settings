# Neptune 4 Configuration and Settings

## Current Hardware Status
- Firmware: v1.1.3.2
- Screen Firmware: v1.2.14
- Bed Leveling: Completed (±0.05mm variance)
- Z-offset: Calibrated via paper method
- WebUI: 10.42.70.42

## Calibration Status
### E-steps Calibration
- Base E-steps: 400 steps/mm (factory default)
- Verification Method: 100mm extrusion test
- Temperature: 200°C for testing
- Process:
  1. Mark filament at 120mm
  2. Extrude 100mm
  3. Measure remaining distance
  4. Calculate new value if needed

### Flow Rate Calibration
- Current Flow Rate: 0.965 (-3% modifier)
- Calibration Method: Single-wall cube test
- Wall Thickness Target: Match nozzle size
- Process:
  1. Print 20mm calibration cube, no top
  2. Vase mode (single wall)
  3. Measure all four walls
  4. Average measurements
  5. Adjust flow rate = (Expected/Measured) * Current

## Recent Mechanical Fixes
- Tightened extruder wheels that were loose
- Tightened loose belt
- Performed new auto-level after mechanical adjustments

## Print Settings
- Flow Rate: 0.965 (-3% modifier)
- First Layer Speed: 15mm/s
- Part Cooling: 
  - First Layer: 0%
  - Other Layers: 50% max
- Temperature: 
  - First Layer: 215°C
  - Main Layers: 205°C
- First Layer Height: 0.3mm

## Previous Issues
- Small feature quality needed improvement
- Layer inconsistency in cube test prints
- First layer adhesion problems
- Initial diagnosis focused on cooling and tension
- Root cause identified as mechanical: loose wheels and belt

## Current Status
- Mechanical issues addressed
- New auto-level completed
- First layer settings adjusted
- Test cube printing to verify improvements

## Next Steps
1. Test first layer adhesion with new settings
2. Monitor mechanical components for any loosening
3. Document results of fixes

## Maintenance Notes
- Regular check of wheel tightness recommended
- Belt tension should be monitored
- Auto-level after any mechanical adjustments
- Verify E-steps after any extruder maintenance
- Check flow calibration when changing filaments