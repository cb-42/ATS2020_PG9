
ATS2020\_PG9
============

This is a guide for acquiring the course materials for ATS 2020 PG9: A HANDS-ON INTRODUCTION TO STUDYING THE LUNG MICROBIOME

Pre-course preparation
======================

Prior to starting the section entitled Hands-On: A Crash Course in Microbiome Analysis: Part 1 several pieces of software need to be acquired.

I. R
----

First you'll need to acquire R itself. This can be done directly from [CRAN](https://cran.r-project.org/).

II. RStudio
-----------

Secondly, install the free desktop version of [RStudio](https://rstudio.com/products/rstudio/download/#download).

III. Course Package
-------------------

Finally, the course package needs to be installed. To do this, open RStudio then copy, paste the following R code into the console, and then enter the code to execute it.

First, install the devtools package if needed, then load it:

    if (!require(devtools)) install.packages("devtools")
    library(devtools)

Next, install and load the course package.

    install_github("https://github.com/cb-42/NAME_TBD")  
    library(NAME_TBD)

This package includes all of the data and code necessary to follow along during the hands-on session.
