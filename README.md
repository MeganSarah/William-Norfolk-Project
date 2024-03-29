# Analysis of citizen science water quality monitoring in Key Largo, Florida. 

This is the MADA fall 2019 Class Project Repository for William Norfolk.

## How to Locate All Raw Data, Processing, and/or Analysis Scripts

All code, figures, and text are reproducible from various subfolders within the project directory.

## **Raw Data**

Raw Data can be found in the ```data``` folder under the subfolder ```raw_data``` and is viewable as an xlsx file both before date/time modification and afterwards.

### Processed (clean) Data

Processed Data can be found in the folder ```data``` under the subfolder ```processed_data``` and is an R object generated by the processing Rmd. file. 

### Individual Program Data

Individual program data is a subfolder within the ```code``` folder and contains the template excel sheet ```individual_program_data_template_example```. This template is a pre-designed shell for the entry of data collected through the MarineLab citizen science water quality program. Data entered into this template can directly analyzed with the ```citizen_science_processing_script``` (located in ```code``` folder and ```processing_code``` subfolder) to produce quick visualizations of program data. Detailed insructions for data entry and script running are located in the ReadMe file within the ```code``` folder.

## **Processing Code**

### Water Quality Processing Script

The script ```WQprocessing.Rmd``` contains the code to produce the processed data object and can be found in the ```code``` folder under the subfolder ```processing code``` and is accessible as both an Rmd. file and docx file. Instructions for running the processing code can be found in the ReadMe file in the folder ```code```.

### Citizen Science Processing Script

The script ```citizen_science_processing_script``` is a template script designed to be integrated into the MarineLab citizen science data collection program.This script produces quick visualizations of collected data that has been entered into the ```individual_program_data_template_example``` excel sheet. Detailed instructions to load new data and run this script can be found in the ReadMe file in the ```code``` folder. 

## **Analysis Code**

Analysis code can be found in the folder ```code``` under the subfolder ```analysis code```. 

### Exploratory Analysis

Exploratory analysis is broken into two divisions Exploratory_Data_Analysis_Location and Exploratory_Data_Analysis_Season to generate exploratory plots of different variables of interest. Instructions for running the exploratory analysis code can be found in the ReadMe file in the folder ```code```. All figures of interest generated in both exploratory scripts are saved as png files under the folder``` results```.

### Bivariate Analysis

Bivariate analysis investigates the association between all water quality parameters of interest and produces and produces an in depth analysis of seasonal water quality trends/patterns. Instructions for running the bivariate analysis code can be found in the ReadMe file in the folder ```code```. All figures of interest generated in this script are saved as png files under the folder ```results```.

### Hurricane Irma Analysis

Hurricane Irma analysis investigates the effects of the September 10, 2017 landfall of the storm in the Florida Keys with respect to water quality conditions.Instructions for running the Hurricane Irma analysis code can be found in the ReadMe file in the folder ```code```. All figures of interest generated in this script are saved as png files under the folder ```results```. 

### Citizen Science Efficacy Analysis

Citizen science efficacy analysis compares the results of citizen science-collected data to data collected by the Florida Key National Marine Sanctuary. Instructions for running the Citizen Science Efficacy analysis code can be found in the ReadMe file in the folder ```code```. All figures of interest generated in this script are saved as png files under the folder ```results```.

### Unsupervised Learning Analysis

Unsupervised learning analysis uses agglomerative hierarchical cluster analysis to visualize patterns of data clustering based on location and season. Instructions for running the Unsupervised Learning analysis code can be found in the ReadMe file in the folder ```code```. All figures of interest generated in this script are saved as png files under the folder ```results```.





