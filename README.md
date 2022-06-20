# Summer School in Metabolic Modeling - 2022 edition

## Description
The course will introduce state-of-the-art metabolic modeling covering the full process from model reconstruction 
to phenotype predictions and analysis. 
The course will focus on metabolic model reconstruction, phenotype simulation, integration with omics data, 
and strain optimization, including both unicellular microbes and more complex organisms, such as plants and humans. 
Applications include metabolic engineering, and both plant and health sciences.

The following topics will be covered:
- Genome annotation and reconstruction of metabolic models using merlin. 
Check out merlin for more details.

- Flux analysis, phenotype simulation, and strain optimization using OptFlux, COBRApy, and MEWpy. 
Check out OptFlux, COBRApy, and MEWpy for more details.

- Analysis and integration of omics data into genome-scale metabolic models, using Troppo. 
Check out Troppo for more details.

- Novel modeling paradigms including protein allocation constraints, transcription/translation, and regulatory interactions, using MEWpy. 
Check out MEWpy for more details.


## Repository
This repository contains the course materials and the notebooks.


## Course Materials
The following course materials are available:

### Python Tutorial
In the folder `python_tutorial` you can find the scripts for each module of this tutorial. 
Please start by reading the `python_related_requirements.pdf`file and follow the steps to install all the requirements needed for this tutorial. 
After that, you can watch the videos that are on the Moodle platform and use these scripts to follow along. 

*Note that you have both `.html` and `.ipynb` files. If you managed to install jupyter notebook on your computer, 
we recommend using the `.ipynb` to run the scripts on your machine. Otherwise, just use the `.html` version.

### Flux analysis
In the folder `flux_analysis`, you can find the material for all exercises of the hands-on sessions on flux analysis and constraint-based modeling.
Each jupyter notebook contains the answers to all questions of a given exercise. These notebooks start by loading a GEM model from the `data` directory.
Jupyter notebooks for exercises 2 to 4 will be used in this hands-on session.
Please check the presentation for the hands-on sessions on flux analysis and constraint-based modeling to know more about the exercises.

### Phenotype prediction
In the folder `phenotype_prediction`, you can find the material for all exercises of the hands-on sessions on phenotype_prediction.
Each jupyter notebook contains the answers to all questions of a given exercise. These notebooks start by loading a GEM model from the `data` directory.
Jupyter notebooks for exercises 5 to 7 will be used in this hands-on session.
Please check the presentation for the hands-on sessions on phenotype_prediction to know more about the exercises.

### Strain optimization
In the folder `mewpy_tutorial`, you can find the material for all exercises of the hands-on sessions on Computational Strain Optimization.
Each jupyter notebook contains the answers to all questions of a given exercise.
Jupyter notebooks for exercises 8 to 11 will be used in this hands-on session.
Please check the presentations for the hands-on sessions on Computational Strain Optimization and Alternative Modelling Approaches to know more about the exercises.
