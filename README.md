# Stoma3D-YOLOv8

**3D Stomatal Detection and Quantification Using YOLOv8 and qDPC Microscopy**

This repository hosts the full pipeline for **automated 3D stomatal trait analysis**, developed as part of the MSc thesis project:  
**"AI quantification for optimising plant water use and global food security"**  
by **Shen Liu**, University of Nottingham, 2025.

---

## 🔍 Overview

**StomaQuant-AI** integrates high-resolution **qDPC microscopy**, **UV-resin surface replication**, and **deep learning models (YOLOv8 + U-Net)** to detect and quantify **plant stomatal features** in 3D.

The project addresses limitations in conventional stomatal phenotyping by providing a **non-invasive, scalable, and AI-driven solution** for measuring key traits used in **Water-Use Efficiency (WUE)** estimation.

---

## 🧠 Key Features

- 📷 **UV-resin surface printing**: high-fidelity, non-destructive leaf sampling
- 🔬 **qDPC Imaging**: label-free 3D reconstruction of stomatal structures
- 🤖 **YOLOv8-based detection**: real-time identification of stomata
- 🎯 **U-Net fallback**: semantic segmentation for morphological precision
- 📐 **Quantitative trait extraction**:
  - Aperture width & area
  - Stomatal density & orientation
  - Guard cell volume (pseudo-3D)
- 📊 **Gs Max estimation** for WUE modeling
- 🌱 Dual species validation: *Watercress* and *Arabidopsis thaliana*
- ⚡ Optional module: blue-light stimulation for dynamic stomatal behavior

---

## 📁 Directory Structure

