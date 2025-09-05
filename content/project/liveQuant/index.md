---
title: liveQuant
date: 2024-10-26
links:
  - type: site
    url: https://github.com/rachel-kt/liveQuant
tags:
  # - Hugo
  # - HugoBlox
  # - Markdown
---

A software package for analyzing live-cell microscopy data of transcription. Includes tools for pre-processing, segmentation, motion correction, spot and cluster detection, parameter tuning, and high-confidence transcription site tracking with GUI support. Outputs include trajectories and nascent RNA quantification.

This repository contains a comprehensive software package designed for the analysis of live-cell microscopy data focused on the transcription process. The pipeline enables users to systematically process time-lapse 3D imaging datasets acquired during transcriptional activity using fluorescence microscopy techniques (e.g., MS2 systems).
![image info](./cartoon%20cell.png)

Key features of the software include:

Pre-processing of Raw Imaging Data: Supports conversion from large-scale imaging formats (e.g., Imaris .ims) into manageable 3D TIFF stacks, along with motion correction and cropping of single nuclei for downstream analysis.

Segmentation and Motion Correction: Incorporates automated and manual tools for accurate segmentation of nuclei and correction of cellular movement across time.

![image info](./figure-2_preprocess.png)
Spot and Cluster Detection: Provides parameter optimization modules (e.g., thresholds, alpha, beta, gamma, cluster radius) for robust detection of transcription-related fluorescence spots and their clustering into transcription sites.

![image info](./Figure-4_parameters.svg)

Interactive GUI Tools: User-friendly graphical interfaces to assist in setting thresholds, verifying segmentation, drawing transcription site outlines, and correcting tracks.

![image info](./Figure-5_ref%20spot.svg)

High-Confidence Transcription Site Tracking: Employs computational blurring techniques to distinguish transcription sites from freely diffusing single molecules, enhancing tracking reliability.
![image info](./Figure-6_comp_blur.svg)

Final Quantification and Output: Produces detailed outputs including transcription site trajectories, spot and cluster coordinates, nascent RNA quantification, and visualization tools for validation.

The package is modular, allowing users to run individual steps or the entire pipeline depending on their experimental design. It is intended for researchers studying gene expression dynamics at single-cell and single-molecule resolution.

![image info](./figure-0.png)

Thanks to these open source libraries!
![image info](./FIGURE-1.svg)

<!--more-->
