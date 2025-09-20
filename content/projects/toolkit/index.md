---
title: "Image Processing Toolkit"
icon: ""
date: 2023-03-15
grad: "grad-2"
draft: false
project_tags: ["C", "Image Processing"]
summary: "A toolkit for image processing built from scratch in C, without external libraries."
categories: ["personal-project"]
params:
  index: 2
weight: 2
---

<div style="text-align: center; margin-bottom: 3rem;">
  <img src="/images/fusca/featured.png" 
       alt="Image Processing Toolkit interface" 
       style="width: 75%; max-width: 800px;">
</div>

🌐 **GitHub:** [Image Processing Toolkit](https://github.com/jpviguini/image-processing-toolkit)  

---

## Overview

<p>
The <b>Image Processing Toolkit</b> is a project developed entirely in <b>C</b>, with no external libraries, to implement a wide range of fundamental image processing algorithms from scratch.  
The main motivation was to build a deeper understanding of how core techniques work under the hood by manually handling pixel-level operations, memory management, and algorithmic optimizations.
</p>

<p>
This toolkit demonstrates how low-level programming can be used to reproduce common computer vision operations efficiently, providing a solid foundation for more advanced applications.
</p>

---

## Some features

**Logarithm Operator**

<p>
A nonlinear transformation to compress the range of pixel intensities, useful for enhancing darker regions of an image.
</p>

<div style="text-align: center; margin-top: 20px;">
  <img src="/images/fusca/featured.png" alt="Logarithm operator example" style="max-width: 80%;">
  <p style="font-size: 0.9em; color: #666; margin-top: 5px;">Example of the logarithm operator applied to an input image.</p>
</div>

---

**Contrast Stretching**

<p>
A transformation that increases the dynamic range of pixel intensities, improving the visual distinction between light and dark areas.
</p>

<div style="text-align: center; margin-top: 20px;">
  <img src="/images/fusca/featured3.png" alt="Contrast stretching example" style="max-width: 80%;">
  <p style="font-size: 0.9em; color: #666; margin-top: 5px;">Contrast stretching applied to enhance image clarity.</p>
</div>

---

**Flood Fill**

<p>
Implements the classic region-filling algorithm, which is essential for segmentation and object isolation tasks.
</p>

<div style="text-align: center; margin-top: 20px;">
  <img src="/images/fusca/featured2.png" alt="Flood fill example" style="max-width: 80%;">
  <p style="font-size: 0.9em; color: #666; margin-top: 5px;">Flood fill used to segment and highlight regions of an image.</p>
</div>

---

## Key Takeaways

- Implemented **from scratch in C**, without relying on OpenCV or other libraries.  
- Strengthened knowledge of **pixel-level manipulation** and **low-level memory management**.  
- Created a modular design that can be expanded with new operators and transformations.  
