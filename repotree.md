# 🚀 Geometry Kernel + CAE Learning Roadmap

Welcome to your self-paced learning journey for mastering **geometry kernel development (OCCT/FreeCAD)** and **CAE simulation (OOFEM/FEM)**.

---

## roadmap


[learning roadmap](./README.md)

## 📁 Repository Structure

```
geo-cae-roadmap/
├── geo-core/           # Basic geometry + FEM from scratch
├── fc-study/           # FreeCAD + OCCT exploration
├── oofem-sim/          # CAE with OOFEM
├── geo-cae-pipeline/   # Integrated CAD-to-CAE project
├── docs/               # Notes, equations, diagrams
└── books.md            # Theory and practice book list
```

---

## 📘 books.md (Textbook List)

### Geometry Kernel
- **Geometric Modeling** by Michael Mortenson
- **The NURBS Book** by Piegl & Tiller
- **Open CASCADE Technology Overview** (official docs)

### FEM and CAE
- **Fundamentals of Finite Element Analysis** by David Hutton
- **The Finite Element Method** by Zienkiewicz & Taylor
- **Introduction to Solid Mechanics** by Shames & Pitarresi
- **Programming the Finite Element Method** by Smith, Griffiths, Margetts

---

## 🧱 geo-core
- ✅ C++ implementations of 2D geometry primitives
- ✅ Mesh representation
- ✅ 1D and 2D FEM solver using Eigen
- ✅ Mesh export in VTK/OBJ format

### Suggested Tools
- C++, Eigen, ParaView

---

## 🔍 fc-study
- ✅ Build and debug FreeCAD
- ✅ Trace how OCCT is used in Part/PartDesign
- ✅ Modify or create a parametric shape
- ✅ Use OCCT standalone to load STEP, perform Booleans

### Suggested Tools
- FreeCAD source, OCCT, Qt Creator or Visual Studio

---

## 🔬 oofem-sim
- ✅ Build and run OOFEM examples
- ✅ Create custom .in input files
- ✅ Implement a new element or material model
- ✅ Convert mesh from FreeCAD/Gmsh to OOFEM

### Suggested Tools
- OOFEM, Gmsh, Python, ParaView

---

## 🔄 geo-cae-pipeline
- ✅ End-to-end project: model → mesh → simulate → visualize
- ✅ Bracket or beam simulation example
- ✅ Automated conversion scripts

### Suggested Tools
- FreeCAD scripting, Gmsh, OOFEM, ParaView

---

## 🔗 Related GitHub Projects

### Geometry / OCCT
- https://github.com/Open-Cascade-SAS/OCCT
- https://github.com/FreeCAD/FreeCAD
- https://github.com/cadquery/cadquery
- https://github.com/gkv311/occt-samples
- https://github.com/tpaviot/pythonocc-core

### FEM / CAE
- https://github.com/oofem/oofem
- https://github.com/ganfra/fem-on-cpu
- https://github.com/dealii/dealii
- https://github.com/taylorgrant/FEMTutorials

---

## 🛠️ Getting Started
1. Clone this repo and create module folders.
2. Pick a textbook and start reading alongside hands-on coding.
3. Keep notes in `docs/`.
4. Track your progress with checklists in each module.

Happy building! 🎯

