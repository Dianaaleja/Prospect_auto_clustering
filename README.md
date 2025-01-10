![image](https://github.com/user-attachments/assets/43097e2e-29cb-4562-87a6-e6541f390625)


## Prospect_auto_clustering
A classification model designed to determine the category or type of a vehicle.

## Problem Overview
“Prospect Auto,” a network of car repair shops, requested the development of a model capable of distinguishing between three vehicle types based on their silhouettes. This required creating a classification model to predict the vehicle category. The main question to address is: what steps are necessary to successfully complete this project?

## Project Workflow
Library and Data Setup
Import the necessary libraries, upload the dataset, and load it for analysis.

## Exploratory Data Analysis (EDA)
Perform a detailed analysis of the dataset, both numerically and visually, to uncover patterns and insights.

## Data Preprocessing
Normalize and standardize the dataset to ensure consistency and prepare it for modeling. Split the dataset into training and testing subsets for model evaluation.

## Dimensionality Reduction
Investigate whether dimensionality reduction techniques, such as Principal Component Analysis (PCA), can reduce the 18 original features to fewer dimensions while preserving the data’s variance.

## Approaching the Classification Problem
Address the classification task using two approaches: supervised classification and unsupervised clustering. Calculate relevant metrics to evaluate and compare the performance of each method.

## Data Overview
The dataset for this project consists of numerical features derived from the geometric silhouettes of vehicles captured from various angles.

## The features in the dataset represent three types of vehicles:

Bus: A double-decker bus.
Van: A Chevrolet van.
Car: Either a Saab 9000 or an Opel Manta.
This specific selection of vehicles was made with the expectation that the bus and van would be relatively easy to differentiate, but distinguishing between the two car models might pose a greater challenge.

The dataset, which can be downloaded from the provided link, contains the following columns:

The class column identifies the vehicle type with one of three possible values: bus, van, or car.
The remaining columns are numerical features describing the vehicle's silhouette. These features represent abstract measurements, and while their specific meanings might not be immediately clear, they provide valuable information about the geometry of each vehicle's silhouette.

## List of Features

Here are the numerical columns included in the dataset:

* Compactness
* Circularity
* Distance Circularity
* Radius Ratio
* PR Axis Aspect Ratio
* Max Length Aspect Ratio
* Scatter Ratio
* Elongatedness
* PR Axis Rectangularity
* Max Length Rectangularity
* Scaled Variance (two columns: .1 and unmarked)
* Scaled Radius of Gyration (two columns: .1 and unmarked)
* Skewness About (three columns: .1, .2, and unmarked)
* Hollows Ratio
* This dataset forms the foundation for analyzing and modeling vehicle classification based on silhouette characteristics.

## Files Attached

-[Colab Notebook](https://colab.research.google.com/drive/1cX_UFFYLrmV87AEKBtnWU9e0t_Hqs62E?usp=sharing)
