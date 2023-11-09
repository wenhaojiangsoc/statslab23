# Introduction to Statistics, Graduate Level
Lab materials for SOC-GA 2332 Intro to Stats (Fall 2023, NYU Sociology) \
Office Hours: Tuesday 11-12:20PM [here if meet on Zoom](https://nyu.zoom.us/my/wenhaojiang)
 

### Prerequisite
+ Please download & install R: https://cloud.r-project.org/
+ Please download & install Rstudio: https://rstudio.com/products/rstudio/download/. If you have installed R and Rstudio before, please update it to the latest version.
+ Please sign up for Overleaf (for LaTeX): https://www.overleaf.com/. Using your `nyu` email address will give you free access to professional account. We will use Overleaf for the final replication project.
+ For Mac users, please download and install [MacTeX](https://tug.org/mactex/). For Windows users, please download and install [MiKTeX](https://miktex.org/download). We will need a TeX installation to knit R Markdown codes into PDFs to complete assignments.
+ We can trouble shoot in Lab, but you can also email me if you have questions or run into issues: wj2068@nyu.edu

### Lab 1 Basic of R and Rstudio, R Markdown, LaTeX (9/8/2023)
+ Lab 1 covers the introduction R and to Rstudio, LaTeX, data structures in R, basic data cleaning, and a guidance to assignment 1.
+ Preview lab notes: [Lab 1](https://htmlpreview.github.io/?https://github.com/wenhaojiangsoc/statslab/blob/main/lab1/lab1.html)
+ Download the lab or assignment folder from the link: https://download-directory.github.io/. You will need to **copy and paste the link of the folder after you click the target folder**. For example, lab 1 link is: https://github.com/wenhaojiangsoc/statslab/tree/main/lab1

### Problem Set 1 (Due 9/29/2023)
+ Please knit `ps1_problems.Rmd` in the `ps1` folder to convert the problem set to either a PDF or html file. Please submit a PDF file if you can, and only submit a html file if PDF is not possible. Please pay attention to the instructions of the assignment.

### Lab 2 Visualization and Sampling Simulation (9/15/2023)
+ Lab 2 covers basic visualizations in R using the standard package `ggplot2`. We will use the package to simulate the sampling process and visualize some properties for the sampling distribution. A guidance to assignment 1 will be included.
+ Preview lab notes: [Lab 2](https://htmlpreview.github.io/?https://github.com/wenhaojiangsoc/statslab/blob/main/lab2/lab2.html)
+ **Solutions to the in-class exercise is uploaded to the Lab 2 folder.** You can also check the file [here](https://htmlpreview.github.io/?https://github.com/wenhaojiangsoc/statslab/blob/main/lab2/solution.html).

### Lab 3 Hypothesis Testing, Two Sample Means, and Overleaf (9/22/2023)
+ Lab 3 covers the R implementation of hypothesis testing, the comparison of two sample means, and an introduction to Overleaf.
+ Preview lab notes: [Lab 3](https://htmlpreview.github.io/?https://github.com/wenhaojiangsoc/statslab/blob/main/lab3/lab3.html)
+ An Overleaf template for your final project and for your future use as a baseline can be found [here](https://www.overleaf.com/8539929553qtggbbwwpbvq). **Please do not edit it**; instead, select it and copy it to **your own archive** for your future use.

### Lab 4 Bivariate OLS Regression, Download Data from IPUMS (9/29/2023)
+ Lab 4 covers the R implementation of basic bivariate OLS regression and an introduction to IPUMS and data extraction.
+ Preview lab notes: [Lab 4](https://htmlpreview.github.io/?https://github.com/wenhaojiangsoc/statslab/blob/main/lab4/lab4.html)
+ When you fail to knit your Rmarkdown file because of the `kableExtra` package, please run the following codes in your RStudio **Console**:
    + `install.packages("devtools")`
    + `devtools::install_github("kupietz/kableExtra")` \
Then knit the file again.

### Problem Set 2 (Due 10/23/2023)
+ Please knit `ps2_problems.Rmd` in the `ps2` folder to convert the problem set to either a PDF or html file.
+ Please feel free to raise questions in lab or in my office hours.

### Lab 5 Simulation of OLS Regression with Interaction Terms (10/06/2023)
+ Lab 5 covers simulations of OLS regression, with one and multiple predictors, using R. We will also cover interaction terms and how to interpret them. 
+ Preview lab notes: [Lab 5](https://htmlpreview.github.io/?https://github.com/wenhaojiangsoc/statslab/blob/main/lab5/lab5.html)

### Lab 6 OLS Anatomy, Confounding, Interactions with Dummies (10/13/2023)
+ Lab 6 covers the exogeneity assumption in OLS, its relation with confounding, and interactions with dummy variables.
+ Preview lab notes: [Lab 6](https://htmlpreview.github.io/?https://github.com/wenhaojiangsoc/statslab/blob/main/lab6/lab6.html)

### Lab 7 Types of Multivariate Relationships, Hetero/Homoskedasticity, F-test for Nested Models (10/20/2023)
+ Lab 7 covers the four types of multivariate relationships, the violation of homoskedasticity, robust standard error, F-test for nested models, and standardizing regression coefficients
+ Preview lab notes: [Lab 7](https://htmlpreview.github.io/?https://github.com/wenhaojiangsoc/statslab/blob/main/lab7/lab7.html)

### Lab 8 Replication Project, Causal Inference Framework, and Logistic Regressions (11/03/2023)
+ Lab 8 covers tips of the replication project, the causal inference framework, and the R implementation of logistic regressions.
+ Preview lab notes: [Lab 8](https://htmlpreview.github.io/?https://github.com/wenhaojiangsoc/statslab/blob/main/lab8/lab8.html)

### Lab 9 Kitagawa-Oaxaca-Blinder Decomposition, Ordered Logit Model, Multinomial Logit Model, Conditional Logit Model (11/10/2023)
+ Lab 9 covers the Kitagawa-Oaxaca-Blinder Decomposition that is used in Mandel and Semyonov (2016), and Ordered, Multinomial, and Conditional Logit Models
+ Preview lab notes: [Lab 8](https://htmlpreview.github.io/?https://github.com/wenhaojiangsoc/statslab/blob/main/lab9/lab9.html)
