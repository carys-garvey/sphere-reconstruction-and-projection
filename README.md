# Spherical Surface Reconstruction and Map Projection Pipeline

A computational pipeline for reconstructing approximately spherical surfaces from multi-view images and projecting them into 2D using map projections.

## Overview

This project implements a modular pipeline that takes six images of an object from different perspectives (front, back, left, right, top, bottom), reconstructs a textured spherical surface using inverse orthographic projection, and maps the result into 2D using projections such as stereographic (angle-preserving) and Lambert cylindrical (area-preserving).

The pipeline provides both a practical tool for surface visualization and a computational demonstration of differential geometry concepts such as coordinate charts, atlases, and projection-induced distortion.

---

## Features

- Multi-view spherical reconstruction
- Inverse orthographic projection
- Weighted blending of overlapping views
- Stereographic projection (conformal)
- Lambert cylindrical projection (equal-area)
- Interpolated 2D image rendering
- Modular object-oriented design

---

## Example Results

*(insert your best images here)*

- 3D reconstructed sphere
- Stereographic projection
- Lambert cylindrical projection
- Projection comparison

---

## Installation

```bash
git clone https://github.com/yourusername/spherical-surface-reconstruction.git
cd spherical-surface-reconstruction
pip install -r requirements.txt
