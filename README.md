# Numerical Simulation of Electrical Conductivity in Liquid Foams

This repository hosts the research materials for my M.Sc. research project **“Numerical Simulation of Electrical Conductivity in Liquid Foams”** at Technische Universität Dresden. The work investigates how the geometry of liquid foams (structured vs. unstructured) influences their effective electrical conductivity, using tomography-based 3D geometries and finite element simulations. :contentReference[oaicite:0]{index=0}

## Overview

Liquid foams are gas–liquid dispersions with a complex network of thin films and Plateau borders. In this project, I:

- Reconstructed **3D foam geometries** (structured and unstructured) from X-ray tomography data.
- Prepared and cleaned the meshes using tools such as **MATLAB, 3D Slicer, MeshLab, MeshMixer, and SolidWorks**.
- Simulated **steady-state DC conduction** in ANSYS Maxwell 3D to compute the **effective and relative electrical conductivity**.
- Compared the numerical results with classical models (Lemlich, Maxwell, Feitosa) across different liquid fractions to analyze the role of foam structure and anisotropy. :contentReference[oaicite:1]{index=1}

## Contents

- `Smita_Salunkhe_ResearchProject_Report.pdf` – Full project report (methods, theory, results, and discussion). :contentReference[oaicite:2]{index=2}


At the moment, this repository mainly serves as an archive of the written work and a place to add code and data in the future.

## Methods in one paragraph

The foam geometries were obtained from tomography of structured and random alginate foams, segmented to binary masks, reconstructed to 3D meshes, and cleaned via Poisson surface reconstruction and remeshing. These geometries were then embedded between copper electrodes in a surrounding air box and solved with a DC conduction FEM formulation, assuming an insulating gas phase and a homogeneous conducting liquid phase. The effective conductivity was derived from the simulated current and normalized by the liquid conductivity to get relative conductivity, which was compared against analytical models over different domain sizes and directions. :contentReference[oaicite:3]{index=3}

## Citation

If you use or refer to this work, please cite:

> Smita Ashokrao Salunkhe, *Numerical Simulation of Electrical Conductivity in Liquid Foams*, M.Sc. Research Project, TU Dresden, 2025. :contentReference[oaicite:4]{index=4}
