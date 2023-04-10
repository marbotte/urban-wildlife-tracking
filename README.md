# urban-wildlife-tracking

## Object and objectives

With this repository, we aim to describe the processes of data management and analysis from the project "Rastreo de la fauna urbana en la Área Metropolitana del Valle de Aburrá, Antioquia, Colombia" (Urban fauna tracking in the Metropolitan Area of Valle de Aburrá, Antioquia, Colombia).
This work was conducted by the Instituto Alexander von Humboldt (public Colombian research institute) in an agreement with "Área Metropolitana del Valle de Aburrá" (AMVA).

## Contents

The repository includes :

1. folder "data_management": documents y codes for the data management steps of the project:
    + subfolder "general": data stream description
    + subfolder "movebank": setup and use of the movebank platform
    + subfolder "oracle_amva": storing the data in the AMVA Oracle database
    + subfolder "local": local filters and data treatment of the data from movebank
2. folder "data_analysis": documents and codes for data analysis
    + subfolder "documentation": analysis flow and bibliography description. An analysis of the literature was conducted in order to assess the potential movement ecology methodology that may be useful in our project
    + subfolder "analysis": codes and description of the analysis in R

## Rmarkdown
Most of the codes shown are in rmarkdown document which may be applied and rendered locally in R using:

```
rmarkdown::render("filename.Rmd")
```


