# GEOG5990M_Portfolio_Assignment_Nepal
Background & Project Overview

This project investigates the relationship between deprivation and development indicators in 75 districts of Nepal. The analysis determines how indicators such as per-capita income, poverty index, access to safe water varies across districts and the patterns are visualised.

Non-spatial visualisation such as scatter plots with statistics and spatial visualisation such as chloropleths are produced by applying the cleaned and pre-processed nepal data.


Data used in this project include:

Nepal District Dataset (2007-14): Contains variables such as income, poverty, education, water access for 75 districts of nepal.
Source: GeoDa Center — Nepal dataset

Shapefile boundary data for Nepal districts: Nepal District Dataset (2007-14).
Source: GeoData Center


The notebook undertakes the following steps:

1) Data Cleaning & Preparation

2) Removal of missing values.

3) Filter dataset to interested variables: per-capita income (pcinc), poverty index (povindex), adult illiteracy (ad_illit), access to safe water (nosafh20), and population.


For Non-spatial Visualisation:

Scatter plot between per-capita income and poverty index with marker size representating population and appropriate colour scheme

Spearman's rank correlation to determine relationship and a regression model is created for poverty index and income.



For Spatial Visualisation:

A sequential and colour-blind friendly chlorpleth map of poverty across all 75 districts is created.

