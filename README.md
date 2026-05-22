
# 193-group-project: vegetation

## General information

- This repository contains data and code to explore patterns in native grassland vegetation abundance at North Campus Open Space. 

- The research question we are trying to answer is: How have key species changed through time in grassland habitats?

To work with the code in this repository, you will need the following packages:

```
library(tidyverse)
library(here)
library(janitor)
library(snakecase)
library(scales)
library(readxl)
library(naniar)
library(patchwork)
```

## Data and file information

```
.
├── README.md
├── code                                          
│   ├── draft-visualizations.pdf                  # visualizations to answer research question
│   ├── draft-visualizations.qmd
│   ├── in-class-code.pdf                         # class code for data management
│   └── in-class-code.qmd
├── data
│   ├── veg.csv                                   # vegetation survey data
│   └── vp_veg_metadata.csv                       # transect information
└── 193-group-project.Rproj
```

## Rendered output

The rendered document for sample visualizations is [here](https://github.com/alyssahagele29/193-group-project/blob/main/code/in-class-code.pdf).

The rendered document for the timeline check-in is [here](https://github.com/alyssahagele29/193-group-project/blob/main/code/timeline-check-in.pdf).


