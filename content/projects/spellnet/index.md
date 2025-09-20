---
title: "SpellNet: Real-Time Multilingual Sign Language Detection"
icon: ""
date: 2023-07-01
draft: false
project_tags: ["Computer Vision", "Tensorflow", "CNNs", "Feature extraction", "LSTM"]
summary: "A system for real-time detection and recognition of sign languages (LIBRAS and ASL), enabling inclusion and accessibility."
weight: 1
categories: ["research"]
params:
  index: 2
---

<div style="text-align: center; margin-bottom: 2rem;">
  <img src="/images/spellnet/featured_spellnet.png" 
        style="width: 60%; max-width: 800px;"></img>
</div>

## About the project

**SpellNet** is a research and development project that leverages artificial intelligence and computer vision to enable **real-time recognition of multiple sign languages**, with initial focus on LIBRAS (Brazilian Sign Language) and ASL (American Sign Language).  

The system uses CNNs (MobileNetV2) trained on sign language datasets to classify hand gestures and integrate them into accessible applications. Beyond recognition, the project also explores the potential of **multilingual support**, allowing users from different regions to interact seamlessly.  

Currently, we are integrating **LSTM (Long Short-Term Memory networks)** to handle dynamic gestures, expanding SpellNet’s ability from recognizing static signs to capturing more complex motion sequences in real-time.  

This initiative aims to foster **inclusion and accessibility** by breaking communication barriers for the Deaf community, while also serving as a platform for experimentation in gesture recognition, multimodal interaction, and AI-powered accessibility tools.  


## Features:
- 🖐 **Real-time sign language detection** using deep learning and computer vision.  
- 🌎 **Support for multiple sign languages** (starting with LIBRAS and ASL).  
- ⚡ **Web-based interface** for fast and easy testing.  
- 👐 **Accessibility-focused**, bridging communication between deaf and hearing individuals.  


---

## Results

- 📂 Released an open-source dataset: **5000** images per class in ASL and **3700** images per class in LIBRAS.
- ✅ Achieved **90% accuracy** on LIBRAS static gesture real-time recognition.  
- ✅ Achieved **79% accuracy** on ASL static gesture real-time recognition.  
- 🚀 Ongoing experiments with **LSTM for dynamic gestures** are showing promising improvements in real-time performance.  

---


The project is open-source, and the source code is available on [GitHub](https://github.com/gruporaia/SpellNet).  
More details about the project can be found on the [official page](https://grupo-raia.org/projetos/projeto/spellnet).  
