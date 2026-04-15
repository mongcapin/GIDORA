# GIDORA: Self-Organizing Multi-Task Perception Architecture

This project is a part of the AAI-590 course in the Applied Artificial Intelligence Program at the
University of San Diego (USD).

Project Status: Completed

## Installation
pip install torch torchvision numpy matplotlib

jupyter notebook GIDORA.ipynb

## Purpose
GIDORA is a multi-task deep learning perception system designed to demonstrate a partially self-organizing architecture for robotics and autonomous systems. 
The project extends modern CNN-based perception stacks by introducing learned structural organization, where elements of the perception pipeline—such as feature routing and task-specific heads—are dynamically selected rather than statically defined.

## Contributor
Matthew Ongcapin

---
## Methods Used
- **Multi-Task Learning**
  - Terrain segmentation  
  - Obstacle detection  
  - Geometric terrain estimation  

- **Shared CNN Backbone**  
  Efficient feature extraction across all tasks

- **Self-Organizing Architecture**
  - Trunk Template Instruction Set (intermediate feature grouping)
  - Terminal Template Instruction Set (task-specific heads)
  - Dynamic selection based on feature analysis

- **Data Engine (Software 2.0 Approach)**  
  Automated preprocessing, normalization, and augmentation

- **Modular Pipeline Design**
  - Data Engine  
  - Shared Backbone  
  - Feature Analyzer  
  - Trunk Selector  
  - Terminal Selector  
  - Multi-Task Outputs  


