# Schmidt-Boehm-Tuten-Roorda_2019

This repo contains the raw data and analyses presented in:

[Brian P. Schmidt](https://bps10.github.io), Alexandra E. Boehm, William S. Tuten, Austin Roorda. _Spatial summation of individual cones in human color vision'_ 

All analyses were conducted in the [R programming language](https://www.r-project.org/). Html versions of the analysis scripts are linked below. The files ending in `.Rmd` are the source code R notebook files. Scripts should be run in the order they are numbered.

1. [01_Process-Data.nb.html](https://bps10.github.io/static/01_Process-Data.nb.html) takes the raw data in [all_trial_data.csv](all_trial_data.csv) and does some light filtering and sanity checking. The output of this script is [filtered_data.csv](filtered_data.csv).

2. [02_Analyze-Data.nb.html](https://bps10.github.io/static/02_Analyze-Data.nb.html) contains the analyzes that are described in the manuscript.

## Install

1. Download and install [Rstudio](https://www.rstudio.com/products/rstudio/download/).

2. Install dependencies: [tidyverse](https://www.tidyverse.org), [ggthemes](https://cran.r-project.org/web/packages/ggthemes/index.html), [gridExtra](https://cran.r-project.org/web/packages/gridExtra/index.html), [corrplot](https://cran.r-project.org/web/packages/corrplot/index.html) and [car](https://cran.r-project.org/web/packages/car/index.html). From the R console:

```r
install.packages(c("tidyverse", "ggthemes", "gridExtra", "corrplot", "car"))
```
3. Clone this repo:

```
git clone https://github.com/bps10/Schmidt-Boehm-Tuten-Roorda_2019
```
