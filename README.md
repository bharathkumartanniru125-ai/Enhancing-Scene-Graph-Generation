# Enhancing Scene Graph Generation with Stacked Motif Networks and Deep Learning Innovations

## Project Overview
This project improves Scene Graph Generation (SGG) by enhancing the original Stacked Motif Networks (MOTIFNET) architecture with modern deep learning techniques.

The goal is to help computers understand not only objects inside images but also relationships between those objects.

Example:
Person → riding → bicycle

This enables better visual understanding for applications such as:
- Autonomous Vehicles
- Robotics
- Visual Intelligence
- Image Understanding
- Computer Vision Systems

---

## Problem Statement

Traditional Scene Graph Generation methods struggle with:

- Capturing global context
- Understanding object relationships
- Computational efficiency
- Generalization across datasets

This project enhances MOTIFNET to improve scene understanding and relational reasoning.

---

## Objectives

- Reproduce original MOTIFNET architecture
- Improve contextual understanding using Attention
- Enhance relational learning using Graph Neural Networks
- Improve efficiency using Knowledge Distillation

---

## Technologies Used

- Python
- PyTorch
- Torchvision
- Torch Geometric
- NumPy
- Matplotlib

---

## Algorithms & Models

### Multi-Head Self Attention
- Captures relationships between image regions
- Improves contextual awareness

### Graph Neural Networks (GCN)
- Learns relationships between connected objects

### Convolutional Neural Networks (CNN)
- Extracts visual features

### Faster R-CNN
- Detects and classifies objects

### Knowledge Distillation
- Compresses larger models into efficient student models

---

## Dataset

Visual Genome Dataset

Used for:
- Object Detection
- Relationship Extraction
- Scene Graph Construction

---

## Project Workflow

Input Image
↓
CNN Feature Extraction
↓
Object Detection (Faster R-CNN)
↓
Multi-Head Attention
↓
Graph Neural Network
↓
Scene Graph Generation
↓
Knowledge Distillation

---

## Results

Achievements:
- Improved contextual understanding
- Better relational reasoning
- Higher recall performance
- Improved computational efficiency

Visual outputs include:
- Attention Output
- Attention Heatmaps
- Object Detection
- Scene Relationship Analysis

---

## Repository Structure

```
Scene-Graph-Generation/
│
├── README.md
├── Code.pdf
├── Finalprojectreport.docx
├── Enhancing Scene Graph Generation with Stacked Motif Networks.pptx
└── outputs/
```

---

## Future Improvements

- Dynamic Scene Understanding (Video)
- Transformer Architectures
- Larger Datasets
- Improved Knowledge Distillation

---

## Authors

Bharath Kumar Tanniru  
University of Massachusetts Dartmouth

Co-Author:
Abhinava Tirumala Sai Ganesh Kunapareddy

Advisor:
Donghui Yan, PhD

---

## License

Academic / Educational Use
