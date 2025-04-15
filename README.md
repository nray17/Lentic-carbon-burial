# Lentic-carbon-burial
This code was used to estimate rates of carbon burial and total carbon burial in lentic ecosystems on earth.

**#Setup**
The code uses R and is loaded here as an R Markdown file, so it should be run using RStudio. Each package needed is listed throughout the code and should be installed separately.

Data files needed for this code can be accessed via FigShare here: https://figshare.com/s/d928d5b76950c5e4cd0e (currently this is a private link). You will need to save these files in the same folder as the code is saved in on your computer, and be sure to set your working directory to that folder. The code is a single script that incldues basic data exploration, random forest modelling, applying random forest models to datasets of lentic system location, area, and other predictor variables, and the pond and small lake < 0.1 km2 distribution code.

Hardware used: this code was developed on a Dell desktop computer with 16 GB RAM and a 13th Gen Intel Core i7 that is equipped with Windows 11 Enterprise. The "predict" functions for estimating carbon burial in a given system were split across sub-sections of the lake dataset used as the computer would sometimes get hung up attempting to predict on the whole dataset at once.

Software versions: code was written in R version 4.4.1 in RStudio version 2024.04.2+764

**#Contact info**
If you have any questions, please email the lead author of the paper (me): nickray -at- udel.edu
