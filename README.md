# µPAD Angle Geometry Design Files (SVG)

## Overview

This repository contains scalable vector graphic (SVG) design files used to fabricate paper-based microfluidic analytical devices (µPADs) with controlled channel geometries. These designs were developed to systematically evaluate the impact of channel angle configurations on capillary-driven flow behavior and hydraulic symmetry.

The files are intended for direct use with laser cutting systems (e.g., diode laser engravers) to produce repeatable µPAD architectures for fluid transport and colorimetric analysis experiments.

---

## Purpose

These designs were created to investigate how sequential Y-split angles influence:

* Flow symmetry between branches
* Arrival time consistency across detection wells
* Velocity decay through multi-stage channel networks
* Overall reliability of fluid distribution in µPAD systems

All designs maintain controlled variables (e.g., path length and channel width) while varying only angular geometry, allowing for isolated analysis of geometric effects on flow behavior.

---

## File Contents

Each SVG file represents a distinct µPAD design with specific angle combinations.

### Key design features:

* **Inlet well:** ~6 mm diameter
* **Channel width:** ~1.5 mm
* **Detection wells:** ~3 mm diameter
* **Outlet tails:** ~1.0–1.25 mm width
* **Total path length:** ~26 mm (inlet center → detection well center)

### Angle configurations include:

* 30°–30°
* 45°–45°
* 60°–60°
* 45°–30°
* 45°–60°
* Additional combinations as labeled

Each file name corresponds to its angle configuration for clarity and reproducibility.

---

## Fabrication Instructions

### 1. Importing Files

* Open SVG files in laser control software (e.g., CutLabX, LightBurn)
* Ensure scaling is preserved (units in mm)

### 2. Recommended Laser Settings

*(Based on tested conditions in this project)*

* Power: ~80%
* Speed: ~500 mm/min
* Passes: 2–3

⚠️ These may vary depending on your laser system and material.

---

### 3. Substrate Preparation

* Material: Whatman Grade 1 chromatography paper
* Optional backing: aluminum adhesive tape (used for structural support in this project)

---

### 4. Cutting and Handling

* Align substrate consistently before cutting
* Use perimeter guides (if included) for consistent strip sizing
* After cutting, trim strips to final dimensions using guides

---

## Experimental Use

These designs are best suited for:

* Capillary flow analysis using dyed aqueous solutions
* Time-resolved wicking studies
* Evaluation of hydraulic symmetry in branched networks
* Colorimetric assay development with controlled fluid delivery

In this project, red dye samples were used for flow visualization, followed by Zn–Zincon colorimetric testing.

---

## Design Considerations

* All designs maintain **constant path length** to isolate angle effects
* Sequential Y-splits are used to examine **propagation of flow imbalance**
* Channel width was selected based on prior optimization (balance of flow speed and confinement)

---

## Limitations

* Laser fabrication introduces **thermal effects** (e.g., charring, barrier variability)
* Small deviations in alignment can affect ROI consistency in imaging
* Designs do not account for **chemical interference effects** from substrate materials

---

## Repository Structure

```
/svg-files/
    30-30_design.svg
    45-45_design.svg
    45-60_design.svg
    ...
/preview-images/ (optional)
README.md
```

---

## License

These design files are released under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

You are free to:

* Use
* Modify
* Distribute

With appropriate credit to the original author.

---

## Author

Thomas Lau
Fordham University — Environmental Science Capstone Project

---

## Related Work

These files were developed as part of a broader investigation into:

* Low-cost µPAD fabrication
* Laser-based channel patterning
* Automated colorimetric analysis using Raspberry Pi imaging systems

---

## Citation

If you use these files in academic work, please cite the associated repository:

> Lau, T. *µPAD Angle Geometry Design Files*. GitHub Repository, 2026.

---

## Notes

* Ensure consistent environmental conditions (lighting, humidity) when comparing flow behavior across designs
* For imaging workflows, maintain fixed ROI alignment relative to channel geometry

---

## Contact

For questions or collaboration inquiries, please reach out via GitHub or associated publication contact.
