# ExNormalizeMets

Authors: Alysha M De Livera, Gavriel Olshansly <br />
License: GPL (>=2) <br />
Contact: <br />
* Excel: olshansky.g@unimelb.edu.au
* R: alyshad@unimelb.edu.au

<br />

## Software for Normalising and Analysing metabolomics data


### About the package:

Metabolomics data are inevitably subject to a component of unwanted variation, due to factors such as batch effects, matrix effects, and confounding biological variation. The NormalizeMets R package contains a collection of functions to aid in the statistical analysis of metabolomic data. It can be used to assess, select and implement statistical methods for normalizing metabolomics data. The interactive excel interface provides an opportunity to use these functions through a user-friendly interface in excel.

#### Requirements
It is required to install the R software (version 3.4.3 or higher) and Microsoft Excel (2016 or later).

#### Input data format

The input data format consists of three parts: (i) "featuredata" which is the metabolomics data matrix containing all metabolite peak intensities (or concentrations). Unique sample names must be provided as row names and unique metabolite names as column names, (ii) "metabolitedata" contains metabolite-specific information in a separate dataframe. These information can include, but is not limited to, designation of metabolites as internal/external standards, or positive/negative controls. Metabolite names need to be provided as row names, and (iii) "sampledata" is a dataframe that contains sample-specific information. These information can include sample type, order of analysis, factors of interest and other sample-specific data relevant to the analysis. Unique sample names need to be provided as row names.

#### Installation and Usage

A detailed installation manual and user guide can be viewd [here]({{project.usrl}}/docs/ExNormalizeMets_manual.1.pdf).




