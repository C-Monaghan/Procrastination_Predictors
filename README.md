<h1 align = "center"> Procrastination, Depressive Symptomatology, and Loneliness in Later Life </h1>
<h4 align = "center"> Cormac Monaghan<sup>1,4 </sup>, Dr. Ione Avila-Palencia<sup>2 </sup>, Dr. S. Duke Han<sup>3 </sup>, & Dr. Joanna McHugh Power<sup> 4</sup> </h4>

<sup>1</sup> Hamilton Institute, Maynooth University  
<sup>2</sup> Centre for Public Health, Queens University  
<sup>3</sup> Department of Psychology, University of Southern California  
<sup>4</sup> Department of Psychology, Maynooth University  

#### [Paper Link](https://www.tandfonline.com/doi/full/10.1080/13607863.2024.2345781)

---

> [!Important]
> The Health and Retirement Study (HRS) provides a special file called a cross-wave tracker file to help analyze data across different HRS surveys (called waves). This file is used for the included script, [Aggregation.R](https://github.com/C-Monaghan/Procrastination_Predictors/blob/main/02__Models/01__Processing/01__Aggregation.R). However, the file is quite large (185 MB) and exceeds typical file size limits.
>
> To run the script, download the cross-wave tracker file from the [HRS website](https://hrsdata.isr.umich.edu/data-products/cross-wave-tracker-file) and save it in the following directory with the filename **./01__Data/01__Raw_Data/Tracker.sav**.

## Overview
Procrastination is a behaviour performed by various age groups. However, over the years, research has predominantly focused on student and younger adult populations, with **little attention given to procrastination behaviours among older adults**. This complex behaviour is influenced by a multitude of factors. Through previous studies on younger populations, researchers have identified numerous factors closely associated with procrastination. However, to gain a more comprehensive and holistic understanding of procrastination, research also needs to take into consideration procrastination in later life and examine whether these factors also apply to older adults.

As such, the objectives of this study were twofold:

- Investigate the potential association between age and procrastination.
- Investigate the mediating roles of depressive symptomology and loneliness on procrastination tendencies among older adults.

## Repository Structure
The repository is organized as follows:

- **00__Documentation:** Contains code books and information about the HRS data.
- **01__Data:** Contains both the raw and processed datafiles.
- **02__Models:** Contains all the project code.
  - **01__Processing:** Code to process the raw data.
  - **02__DAG:** Code to create a visualisation of the variable relationships for age and procrastination.
  - **03__SEM:** Code for creating the SEM model.
  - **04__Exploratory:** Code for descriptives and supplementary analysis

## Getting started
To get started with using this repository, follow these steps:

Clone the repository to your local machine using the following command:

```bash
git clone https://github.com/C-Monaghan/Procrastination_Predictors.git
```

Open the R project

```bash
start Procrastination_SEM.Rproj
```

## Contact

If you have any questions or need further assistance, please contact the corresponding author at [cormacmonaghan@protonmail.com](mailto:cormacmonaghan@protonmail.com)
