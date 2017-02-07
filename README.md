# digital-methods-R
Swirl courses for supporting teaching at the Department of Digital Humanities, King's College London.
We start with a basic introduction to R.

To obtain a suitable Rstudio environment, you might try our
[docker image](https://github.com/kingsBSD/rstudio-kcl-ddh) or
[VirtualBox appliance](https://github.com/kingsBSD/DDH-OneTrueBox). These include a number of extra R packages
to support further teaching in the digital humanities.

Assuming you have Swirl installed, to download and run the courses from R or Rstudio:

```
library(swirl)
install_course_url('https://github.com/kingsBSD/digital-methods-R/releases/download/r_intro/digital_methods.zip')
swirl()
```

## Class 1
* Variables and assignment
* Functions
* Vectors
* Matrices

## Class 2
* Dataframes
* Slicing
* Subsets
* Sorting
* Lists
* Factors
* Conditionals
* Loops
* The "apply" function
* Defining functions
