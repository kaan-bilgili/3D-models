# Tolerance & Bridge Test (Ender 3 V3 SE)

This project contains a **test model** designed to evaluate 3D printing tolerances and bridging performance.  
The results below are from printing on an **Ender 3 V3 SE**.

## Files
- `l11_tolerance_bridge_test/source/tolerance_bridge_test.f3d` → Fusion 360 source file  
- `l11_tolerance_bridge_test/stl/tolerance_bridge_test.stl` → 3D printable test model  

## Print Settings
- Printer: Ender 3 V3 SE  
- Material: PLA+  
- Layer Height: 0.2 mm  
- Wall Line Count: 3  
- Infill: 20% gyroid  
- Cooling: 100% fan  
- Print Speed: 45 mm/s  

## Results
- **Tolerance cylindrical axle**: 0.4 mm works well, but **0.35 mm is optimal**  
- **Tolerance for Snug Slip Fit**: 0.3 mm  
- **Tolerance for Compression Fit**: 0.2 mm  
- **Bridges**: Clean bridging up to **27 mm** (possibly more) 

## Notes
- Use these tolerance values when designing parts for Ender 3 V3 SE.  
- Bridging performance may vary with material and cooling efficiency.  
- This test is not a functional model, only for calibration and learning.  

---
✦ Results recorded as part of my 3D printing learning process.
