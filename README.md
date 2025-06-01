# 🧮 2D Kagome Materials: CIF Dataset for the $\mathrm{XY_6Z_6}$ Family

This repository provides the **Crystallographic Information Files (CIFs)** for a computational dataset of **105 two-dimensional (2D) Kagome materials** with the general chemical formula $\mathrm{XY_6Z_6}$. These structures were designed and analyzed using high-throughput density functional theory (DFT) calculations as part of the study:

> **Mechanical, Electronic, and Magnetic Properties of 2D Kagome Metals: A High-Throughput DFT Study**  
> *(C.I. Nwaogbo, A.C. Iloanya, and C.E. Ekuma., 2025)*  
> _Manuscript in submission_

---

## 🧬 Overview

The dataset stems from a high-throughput computational screening of 2D Kagome structures derived from isoelectronic substitution in the $\mathrm{XY_6Z_6}$ framework, where:

- **X-site** = Ca, Sc, Y (alkaline-earth and rare-earth elements)  
- **Y-site** = Ti, V, Cr, Nb, Ta (group 4–6 transition metals)  
- **Z-site** = C, Si, Ge, Sn, Pb, In, Sb (main group elements)

From 105 generated compounds:
- **74** satisfy Born’s mechanical stability criteria  
- **6** exhibit negative formation energies  
- **54** are ferromagnetic (FM), and **20** are antiferromagnetic (AFM)

The data includes magnetic, mechanical, and thermodynamic characterizations (published separately), while this repository hosts only the **optimized CIF files**.

---
## 📂 Repository Contents

Each `.cif` file corresponds to a relaxed 2D monolayer geometry used in DFT calculations. The filenames follow the convention: $\mathrm{XY_6Z_6.cif}$.


For example:  
- `Sc_Ti6_Sb6.cif`  
- `Y_V6_Si6.cif`

These CIFs represent fully relaxed geometries with ~20 Å vacuum along the _c_-axis to model 2D monolayer behavior.

---
## 📊 Computational Details

- Calculations performed with **VASP** using the **PBE-GGA** functional
- Plane-wave energy cutoff: **500 eV**
- K-point mesh: **3×3×1** Monkhorst–Pack grid
- Geometry relaxed until forces < 0.02 eV/Å

For full methodology, see the corresponding publication.

---
## 🔍 Citation

If you use this dataset in your research, please cite the associated manuscript (link forthcoming):

```bibtex
@article{cac2025kagome,
  title={Mechanical, Electronic, and Magnetic Properties of 2D Kagome Metals: A High-Throughput DFT Study},
  author={C.I. Nwaogbo, A.C. Iloanya, and C.E. Ekuma},
  journal={In Preparation},
  year={2025}
}
```
---

## 📬 Contact

For questions, corrections, or collaboration inquiries, please contact:

- 📧 **Chinedu Ekuma** — [cekuma1@gmail.com](mailto:cekuma1@gmail.com)  

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 🔑 Keywords

`Kagome lattice` &bull; `2D materials` &bull; `magnetism` &bull; `DFT` &bull; `CIF` &bull; `high-throughput` &bull; `spintronics` &bull; `topological materials`
