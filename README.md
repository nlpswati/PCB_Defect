# PCB Defect Detection Using Image Processing

## Objective
Detect and classify defects in Printed Circuit Boards (PCBs) using advanced image processing techniques to ensure manufacturing quality and reliability.

## Methodology

### 1. Image Pre-Processing
- Applied **grayscale conversion**, **median filtering**, and **Gaussian filtering** to clean images and reduce noise.
- Generated **image histograms** to identify intensity distributions corresponding to **background, wiring, and soldering regions**.

### 2. Image Segmentation
- Used **multi-level thresholding** to segment PCBs into three regions: **Background**, **Wiring**, and **Soldering**.
- Facilitated accurate separation of PCB components for defect detection.

### 3. Defect Classification
- Classified defects as **positive (present)** or **negative (absent)**.
- Visualized results with **red for negative defects** and **blue for positive defects** for clear identification.

## Outcome
- Enabled **automated inspection** of PCB images with high accuracy.
- Reduced manual inspection effort and improved defect detection reliability.
