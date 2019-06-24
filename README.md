# pilmbc104-best-of-r

tips and tricks to start using the best of R 

This material is adapted by Lorena Pantano from the Harvard Chan School Bioinformatics Core Training team at https://github.com/hbctraining/Training-modules/tree/master/Tidyverse_ggplot2.


| Audience | Computational skills required | Duration |
:----------|:----------|:----------|
| Biologists | [Beginner/Intermediate R](https://hbctraining.github.io/Intro-to-R/) | 3-hour workshop (~3 hours of trainer-led time) |


### Description

This repository has teaching materials for a **3 hour**, hands-on workshop led at a relaxed pace. 

### Learning Objectives
* **Understanding Tidyverse syntax:** Tidyverse syntax is a bit different from base R with pipes, tibbles, and heavy opinions about row names
* **Wrangling data for use with analysis or plotting:** Explore the functions available from the dplyr package to turn your data into the format you need it 
* **Describe and utilize the ggplot2 grammar of graphics syntax:** Create elaborate custom plots by learning the functions and structure for plotting with ggplot2

> These materials are developed for a trainer-led workshop, but also amenable to self-guided learning.


### Contents

| Lessons            | Estimated Duration |
|:------------------------|:----------|
|Setting up | 15 min |
|[Tidyverse](https://pilm-bioinformatics.github.io/pilmbc104-best-of-r/tidyverse.html) | 30 min |
|[ggplot2](https://pilm-bioinformatics.github.io/pilmbc104-best-of-r/ggplot2.html) | 30 min |


### Dataset

All the files used for the above lessons are linked within, but can also be [accessed here](https://github.com/pilm-bioinformatics/pilmbc104-best-of-r/blob/master/data/gprofiler_results_Mov10oe.tsv).

### Installation Requirements

Download the most recent versions of R and RStudio for your laptop:

 - [R](http://lib.stat.cmu.edu/R/CRAN/) (Version 3.4 or higher)
 - [RStudio](https://www.rstudio.com/products/rstudio/download/#download)
 
Install the required R packages by running the following code in RStudio:

```r
# Install CRAN packages
install.packages("tidyverse")
install.packages("RColorBrewer")
```

Load the libraries to make sure the packages installed properly:

```r
library(tidyverse)
library(RColorBrewer)
```

> **NOTE:** The library used for the annotations associated with genes (here we are using `org.Hs.eg.db`) will change based on organism (e.g. if studying mouse, would need to install and load `org.Mm.eg.db`). The list of different organism packages are given [here](https://github.com/hbctraining/Training-modules/raw/master/DGE-functional-analysis/img/available_annotations.png).


*These materials have been developed by members of the teaching team at the [Harvard Chan Bioinformatics Core (HBC)](http://bioinformatics.sph.harvard.edu/). These are open access materials distributed under the terms of the [Creative Commons Attribution license](https://creativecommons.org/licenses/by/4.0/) (CC BY 4.0), which permits unrestricted use, distribution, and reproduction in any medium, provided the original author and source are credited.*

