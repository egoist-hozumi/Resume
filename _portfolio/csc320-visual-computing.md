---
title: "CSC320 Visual Computing — Project Series"
excerpt: "Four hands-on projects from the University of Toronto's Introduction to Visual Computing (Fall 2024): homographies, image morphing, inpainting, and PatchMatch."
collection: portfolio
---

**Course:** CSC320H1 — Introduction to Visual Computing
**Institution:** University of Toronto
**Term:** Fall 2024

A series of four implementation-heavy projects covering core image-processing and computational-photography techniques.

### Project 1 — Homographies
Implemented a document-scanner pipeline using homography transformations to unwarp images of planar surfaces. Derived the homography matrix from point correspondences and used **backward mapping** with bilinear resampling to produce artifact-free results.
**Tech:** Python, NumPy.

### Project 2 — Beier-Neely Image Morphing
Built a field-warping image morpher with bilinear interpolation between source and destination control lines. Optimized the inner loop through vectorized NumPy operations, improving runtime by **~75%** over the scalar baseline.
**Tech:** Python, OpenCV.

### Project 3 — Exemplar-Based Image Inpainting
Implemented **Criminisi's algorithm** to reconstruct missing regions of images via patch prioritization driven by confidence and edge-strength terms. Analyzed edge cases (textured vs. uniform regions) and documented artifacts in a technical report.
**Tech:** Python, NumPy.

### Project 4 — PatchMatch Algorithm
Implemented the randomized **PatchMatch** correspondence algorithm (the technique behind Adobe's Content-Aware Fill). Achieved near-real-time performance by eliminating explicit Python loops in favor of vectorized NumPy operations over the nearest-neighbor field.
**Tech:** Python, NumPy.
