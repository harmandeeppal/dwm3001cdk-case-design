# Wearable Sensor Pod — CAD & 3D Print Enclosures

**AUT COMP971 Dissertation — Wearable Sensor System**  
Physical Enclosure Design Iterations (Versions 1 to 4)

---

## Final Selected Design: Version 4

> [!IMPORTANT]
> **Production Choice**: **Version 4** is the final validated, print-ready physical design selected for the wearable sensor nodes.
>
> - **Folder**: [version_4/](file:///c:/Users/harma/OneDrive%20-%20AUT%20University/AUT%20-%20COMP971%20Dissertation%20%2860%20points%29/case_design/version_4)
> - **Base Enclosure**: [case_base_v4.stl](file:///c:/Users/harma/OneDrive%20-%20AUT%20University/AUT%20-%20COMP971%20Dissertation%20%2860%20points%29/case_design/version_4/case_base_v4.stl)
> - **Top Cover / Lid**: [case_top_v4.stl](file:///c:/Users/harma/OneDrive%20-%20AUT%20University/AUT%20-%20COMP971%20Dissertation%20%2860%20points%29/case_design/version_4/case_top_v4.stl)

---

## 1. Repository Structure & Symmetry

The `case_design` folder is organized with strict symmetry across all versions.

- **Folder Names**: Symmetrically numbered (`version_1`, `version_2`, `version_3`, `version_4`).
- **File Names**: Every version contains exactly two symmetric STL files:
  - `case_base_v<N>.stl` (the lower chassis holding the electronics, battery, and strap slots)
  - `case_top_v<N>.stl` (the upper protective lid)

```text
case_design/
├── README.md                  # This file
│
├── version_1/                 # Initial rectangular prototype
│   ├── case_base_v1.stl       # Lower base housing
│   └── case_top_v1.stl        # Upper lid
│
├── version_2/                 # First redesign with integrated strap wings & snap-fit
│   ├── case_base_v2.stl       # Lower base with 22 mm strap slots
│   └── case_top_v2.stl        # Snap-on top cap
│
├── version_3/                 # Ergonomic revision with refined clearances
│   ├── case_base_v3.stl       # Lower base housing
│   └── case_top_v3.stl        # Snap-on top cap
│
└── version_4/                 # ★ FINAL SELECTED VERSION ★
    ├── case_base_v4.stl       # Final print-ready base (50.00 × 62.00 × 27.29 mm)
    └── case_top_v4.stl        # Final print-ready top lid (50.00 × 62.00 × 13.00 mm)
```

---

## 2. Hardware Enclosure Requirements

The enclosure is engineered to hold the physical hardware stack for real-time motion capture and spatial tracking:

1. **Qorvo DWM3001CDK** (50.0 × 40.0 × 5.0 mm): UWB transceiver and BLE controller board.
2. **Adafruit ICM-20948** (25.7 × 17.7 × 4.6 mm): 9-DOF IMU sensor module.
3. **800mAh Lion Battery (14500)**: Rechargeable battery seated on the side.
4. **Strap Mounting**: 22 mm integrated watch-band wings on the base for limb strapping (wrists, ankles, head, torso).

---

## 3. Design Evolution Across Versions

| Version | Folder | Base File | Top File | Notes & Progression |
| :--- | :--- | :--- | :--- | :--- |
| **V1** | [version_1/](file:///c:/Users/harma/OneDrive%20-%20AUT%20University/AUT%20-%20COMP971%20Dissertation%20%2860%20points%29/case_design/version_1) | [case_base_v1.stl](file:///c:/Users/harma/OneDrive%20-%20AUT%20University/AUT%20-%20COMP971%20Dissertation%20%2860%20points%29/case_design/version_1/case_base_v1.stl) | [case_top_v1.stl](file:///c:/Users/harma/OneDrive%20-%20AUT%20University/AUT%20-%20COMP971%20Dissertation%20%2860%20points%29/case_design/version_1/case_top_v1.stl) | Initial rectangular concept, flat bottom, separated base and lid. |
| **V2** | [version_2/](file:///c:/Users/harma/OneDrive%20-%20AUT%20University/AUT%20-%20COMP971%20Dissertation%20%2860%20points%29/case_design/version_2) | [case_base_v2.stl](file:///c:/Users/harma/OneDrive%20-%20AUT%20University/AUT%20-%20COMP971%20Dissertation%20%2860%20points%29/case_design/version_2/case_base_v2.stl) | [case_top_v2.stl](file:///c:/Users/harma/OneDrive%20-%20AUT%20University/AUT%20-%20COMP971%20Dissertation%20%2860%20points%29/case_design/version_2/case_top_v2.stl) | Redesigned with organic curved edges, 22 mm strap lugs, and snap-fit joints. |
| **V3** | [version_3/](file:///c:/Users/harma/OneDrive%20-%20AUT%20University/AUT%20-%20COMP971%20Dissertation%20%2860%20points%29/case_design/version_3) | [case_base_v3.stl](file:///c:/Users/harma/OneDrive%20-%20AUT%20University/AUT%20-%20COMP971%20Dissertation%20%2860%20points%29/case_design/version_3/case_base_v3.stl) | [case_top_v3.stl](file:///c:/Users/harma/OneDrive%20-%20AUT%20University/AUT%20-%20COMP971%20Dissertation%20%2860%20points%29/case_design/version_3/case_top_v3.stl) | Refined curvature, adjusted battery clearances, and reinforced perimeter walls. |
| **V4** | [version_4/](file:///c:/Users/harma/OneDrive%20-%20AUT%20University/AUT%20-%20COMP971%20Dissertation%20%2860%20points%29/case_design/version_4) | [case_base_v4.stl](file:///c:/Users/harma/OneDrive%20-%20AUT%20University/AUT%20-%20COMP971%20Dissertation%20%2860%20points%29/case_design/version_4/case_base_v4.stl) | [case_top_v4.stl](file:///c:/Users/harma/OneDrive%20-%20AUT%20University/AUT%20-%20COMP971%20Dissertation%20%2860%20points%29/case_design/version_4/case_top_v4.stl) | **★ Final Selected Design ★**: Slimmed total height to 28.3 mm, optimized snap retention, robust strap slots, clean USB cutout. |

---

## 4. Version 4 Physical Specifications

- **Base Dimensions**: 50.00 mm (Width) × 62.00 mm (Length) × 27.29 mm (Height)
- **Top Dimensions**: 50.00 mm (Width) × 62.00 mm (Length) × 13.00 mm (Height)
- **Assembled Height**: ~28.3 mm
- **Strap Slot Width**: 22.0 mm (standard watch band or Velcro strap)
- **Fasteners Required**: Yes
