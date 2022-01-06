# PET-images-analysis with AFNI
Analysis of Functional NeuroImages (AFNI) is an open-source environment for processing and displaying functional MRI data—a technique for mapping human brain activity.
AFNI is an agglomeration of programs that can be used interactively or flexibly assembled for batch processing using shell script. The term AFNI refers both to the entire suite and to a particular interactive program often used for visualization. AFNI is actively developed by the NIMH Scientific and Statistical Computing Core and its capabilities are continually expanding.
![AFNI_screenshot](https://user-images.githubusercontent.com/97203740/148383144-0bcf8d50-6a37-4b64-989b-56f31f74a85a.png)

Visualization:: 
one of AFNI's initial offerings improved the approach to transforming scans of individual brains onto a shared standardized space. Since each person's individual brain is unique in size and shape, comparing across a number of brains requires warping (rotating, scaling, etc.) individual brains into a standard shape. Unfortunately, functional MRI data at the time of AFNI's development was too low resolution for effective transformations. Instead, researchers use the higher resolution anatomical brain scans, often acquired at the beginning of an imaging session.
![Graph_afni](https://user-images.githubusercontent.com/97203740/148383547-128636c3-e9fc-4530-83a9-afaccd41a488.png)

Image Pre-processing:
Here "afni_proc.py" is a pre-made script that will run fMRI data from a single subject through a series of pre-processing steps, starting with the raw data. The default settings will perform to pre-processing steps and finish with a basic regression analysis.
![3D-digital-template-atlas-in-AFNI-and-SUMA-interface-Areal-delineations-of-different](https://user-images.githubusercontent.com/97203740/148383975-5102119e-f7fc-4f7b-8171-fab8841baeae.png)



