# Neptune 4 Configuration and Settings

## Current Hardware Status
- Firmware: v1.1.3.2
- Screen Firmware: v1.2.14
- Bed Leveling: Completed (±0.05mm variance)
- Z-offset: Calibrated via paper method
- WebUI: 10.42.70.42
- E-steps: Verified at factory default (400 steps/mm)
- PID Values: Kp=21.442 Ki=1.014 Kd=113.377

## Recent Mechanical Fixes
- Tightened extruder wheels that were loose
- Tightened loose belt
- Performed new auto-level after mechanical adjustments
- Completed PID tune at 205°C

## Print Settings
- Flow Rate: 0.965 (-3% modifier)
- First Layer Speed: 15mm/s
- Part Cooling: 
  - First Layer: 0%
  - Other Layers: 50% max
- Temperature: 
  - First Layer: 210°C
  - Main Layers: 210°C
- First Layer Height: 0.3mm
- Pressure Advance: Enabled (0.02)

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
- PID tuning completed
- Pressure Advance enabled
- Test cube printing to verify improvements

## Next Steps
1. Test print with PA enabled
2. Monitor mechanical components for any loosening
3. Document results of PA implementation

## Maintenance Notes
- Regular check of wheel tightness recommended
- Belt tension should be monitored
- Auto-level after any mechanical adjustments