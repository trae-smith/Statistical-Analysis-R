# Statistical Analysis Projects (R)

A collection of statistical analysis and modeling projects 
completed during my Bachelor of Mathematics (Statistics) 
at Carleton University.

## Projects

### Wine Quality Signal Decomposition — PCA & ICA
`Smith,-Trae--STAT4601-Assignment-2.Rmd`
Applied Principal Component Analysis and Independent Component 
Analysis to the UCI Wine Quality dataset (1,599 red wine samples, 
12 chemical variables). Identified that two principal components 
explain 99.4% of total variance. Applied FastICA using logcosh 
approximation to isolate independent chemical signal sources.
**Tools:** R, fastICA, ggplot2, tidyverse

### Supervised Learning — Classification & Dimensionality Reduction
`STAT4601__Supervised_Learning_FP.Rmd`
Applied KNN classification and dimensionality reduction techniques 
to structured datasets. Evaluated model performance and compared 
classification approaches.
**Tools:** R, caret, ggplot2

### Regression & Statistical Modeling
`output_of_assignment_1.Rmd`, `output_of_assignment_2.Rmd`, 
`output_of_assignment_4.Rmd`
Built and validated multiple regression models from multivariate 
data. Evaluated model performance using RMSE and R². Applied ANOVA 
and experimental design methods.
**Tools:** R, tidyverse, ggplot2

### Introductory Statistics
`assignment3_STAT1500_Trae_Smith.Rmd`,
`Final_Exam_STAT_1500_Trae_Smith_101211905.Rmd`
Probability, sampling, and descriptive statistics coursework.
**Tools:** R

## Requirements
Some files require additional libraries. Install with:
install.packages(c("tidyverse", "fastICA", "ggplot2", "caret"))
