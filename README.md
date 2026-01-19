# Spatial Multiplex Analysis – Course Notes

## Spatial biology

Recent advances in spatial proteomics now make it possible to measure dozens to hundreds of proteins directly in intact tissue sections. These technologies generate highly multiplexed images that capture both protein expression and spatial relationships between cells. While biologically powerful, such datasets are complex and their analysis is far from trivial.

A major challenge of spatial multiplex imaging is not data acquisition, but data analysis. Highly multiplexed images must be transformed into structured, interpretable datasets through multiple processing steps, each involving methodological choices that can strongly impact biological conclusions.

The purpose of this course is to introduce the main concepts and workflows used in spatial multiplex analysis, with a strong emphasis on accessibility and interpretability. Whenever possible, the course relies on graphical user interfaces (GUIs) to make analyses more intuitive and reproducible. QuPath serves as the main platform for image-based analysis, while Python-based tools are introduced only when additional downstream analyses are required.


## Course overview

This course introduces the main concepts and practical steps required to analyze spatial multiplex imaging data.

It covers:
- Image analysis using QuPath:
  - tissue detection through pixel classification
  - cell segmentation using deep learning approaches such as StarDist, Cellpose, or InstanSeg
  - quality control and data filtering
  - object classification using thresholding and machine learning methods (e.g. random forests)
  - extraction and export of per-cell measurements

- Downstream analysis in Python:
  - data normalization
  - high-dimensional cell clustering
  - spatial neighborhood and microenvironment analysis
  - interpretation of spatial patterns and methodological limitations

The focus is on understanding workflows and concepts, rather than on providing black-box pipelines.


## Prerequisites

Basic familiarity with microscopy concepts is assumed.
No advanced programming skills are required, and Python is introduced progressively when needed.

For readers who wish to learn or refresh concepts, the following resources may be helpful:
- GloBIAS training resources: https://neubias.github.io/training-resources/all-modules/
- QuPath documentation: https://qupath.readthedocs.io/en/stable/docs/intro/about.html

## Course structure

The course is organized into chapters located in the `docs/` folder:

## Course structure

The course is organized into chapters located in the `docs/` folder:

- [Chapter 1 – QuPath basics and project setup](docs/01_qupath_basics.md)  

- [Chapter 2 – Instance segmentation](docs/02_instance_segmentation.md)  

- [Chapter 3 – Quality control and object classification](docs/03_qc_and_classification.md)  

- [Chapter 4 – Exporting spatial data to Python](docs/04_export_to_python.md)  

- [Chapter 5 – Clustering and spatial neighborhood analysis](docs/05_spatial_analysis.md)  


## License
