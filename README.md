# Global modeling vs local modeling for XGBoost

## Title: Global or local modeling for XGBoost in geospatial studies upon simulated data and German COVID-19 infection forecasting

## Abstract
Methods from artificial intelligence (AI) and, in particular, machine learning and deep learning, have advanced rapidly in recent years and have been applied to multiple fields including geospatial analysis. Due to the spatial heterogeneity and the fact that conventional methods can not mine large data, geospatial studies typically model homogeneous regions locally within the entire study area. However, AI models can process large amounts of data, and, theoretically, the more diverse the train data, the more robust a well-trained model will be. In this paper, we study a typical machine learning method XGBoost, with the question: Is it better to build a single global or multiple local models for XGBoost in geospatial studies? To compare the global and local modeling, XGBoost is first studied on simulated data and then also studied to forecast daily infection cases of COVID-19 in Germany. The results indicate that if the data under different relationships between independent and dependent variables are balanced and the corresponding value ranges are similar, i.e., low spatial variation, global modeling of XGBoost is better for most cases; otherwise, local modeling of XGBoost is more stable and better, especially for the secondary data. Besides, local modeling has the potential of using parallel computing because each sub-model is trained independently, but the spatial partition of local modeling requires extra attention and can affect results.

## Statement
The experiments of the German Covid-19 forecasting belong to the DAKI-FWS (01MK21009A) project supported by the Federal Ministry for Economic Affairs and Climate Action (BMWK), Germany; therefore, the code and data of this part are not available to the public.

## Code description
The file "Simulation_global_local.ipynb" is the program of the simulation experiments of global- and local modeling for XGBoost, including simulated data generation, data resampling according to specific distribution density, global- and local modeling of XGBoost, and other experiments on data distributions, sample sizes, value ranges, and data transformation.



## Cite
Please consider citing our paper if this helps in your work:

Ximeng Cheng & Jackie Ma (2025). Global or local modeling for XGBoost in geospatial studies upon simulated data and German COVID-19 infection forecasting. Scientific Reports, 15(1), 8858. [DOI](https://doi.org/10.1038/s41598-025-92995-6)
