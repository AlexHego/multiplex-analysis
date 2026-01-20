# Spatial multiplex image analysis

## Spatial biology

Recent advances in spatial proteomics now make it possible to measure dozens to hundreds of proteins directly in intact tissue sections. These technologies generate highly multiplexed images that capture both protein expression and spatial relationships between cells. While biologically powerful, such datasets are complex and their analysis is far from trivial.

A major challenge of spatial multiplex imaging is not data acquisition, but data analysis. Highly multiplexed images must be transformed into structured, interpretable datasets through multiple processing steps, each involving methodological choices that can strongly impact biological conclusions.

The purpose of this course is to introduce the main concepts and workflows used in spatial multiplex analysis, with a strong emphasis on accessibility and interpretability. Whenever possible, the course relies on graphical user interfaces (GUIs) to make analyses more intuitive and reproducible.

In addition to QuPath, graphical tools such as CytoMAP are used as intermediate steps to illustrate clustering and neighborhood analysis concepts before introducing Python-based implementations.

## Goals

This repository provides learning resources for anyone interested in multiplex image analysis, with a particular focus on students and scientists working with microscopy data in the life sciences. It starts with QuPath, which is used to transform multiplex images into single-cell data through tissue detection, cell segmentation, object classification, and feature extraction. CytoMAP is then introduced as a graphical tool to make clustering and spatial neighborhood concepts explicit and accessible. Finally, Python-based workflows are presented as a flexible and extensible option for advanced spatial analysis.

## Contents

This repository is organized into chapters located in the `courses/` folder:

- [Chapter 1 – QuPath basics](courses/01_qupath_basics.md)  
- [Chapter 2 – Tissue detection and cell segmentation](courses/02_segmentation.md)  
- [Chapter 3 – Object classification and phenotyping](courses/03_object_classification.md)  
- [Chapter 4 – Quality control and data filtering](courses/04_quality_control.md)  
- [Chapter 5 – First spatial analysis in QuPath](courses/05_spatial_qupath.md)  
- [Chapter 6 – Graphical spatial analysis with CytoMAP](courses/06_cytomap_spatial_analysis.md)  
- [Chapter 7 – Transition CytoMAP to Python](courses/07_cytomap_to_python.md)  
- [Chapter 8 – Advanced spatial analysis in Python](courses/08_python_spatial_analysis.md)  

## Prerequisites

Basic familiarity with microscopy concepts is assumed. Additional background resources and references are provided within the relevant chapters when appropriate. 

No advanced programming skills are required, and Python is introduced progressively when needed.

## License
