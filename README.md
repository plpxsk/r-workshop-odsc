## ODSC Workshop: Intro to R
[Pawel Paczuski](http://www.pavopax.com)   [AMA!] 	

Quick Start
===============================================================================
This is a hands-on introduction to R. We will go through actual code
and learn about data manipulation, graphics, and fundamentals of
statistical modeling.

**Set-up/Installation instructions are below.**

A sample directory structure is in `/templates`


Contents
===============================================================================

* Set-up
* Installing the R environment  
* **Outline/Programs**
* Resources  
* Credits  



  



Set-up
===============================================================================

1. Install R, RStudio, and the `dplyr` and `ggplot2` packages
   [see `Installing the R environment` below]

2. Download this repository ("Download Zip" link on the top right of
   this page) and *unzip* it to a convenient location on your
   computer. We will be working with its contents.

3. Open R Studio

4. Set the working directory to the `/programs` directory of the
   just-downloaded repository, as follows:

   * Session -> Set Working Directory -> Choose Directory...

   * Navigate and Open the `/programs` directory

5. Open the file `0-intro.R` [File - Open file...]. You will find it
   in `/programs`
	


Installing the R environment
===============================================================================

Below are instructions to install R, a few packages, as well as
RStudio, which we will be using during the workshop.

1. Install R

	Mac OS X  
	download and install from:  
	http://cran.r-project.org/bin/macosx/ [click `R-3.2.0.pkg` on left]

	Windows  
	download and install from:  
	http://cran.r-project.org/bin/windows/base/

	Linux, etc  
	See top of:  
	http://cran.us.r-project.org 

2. Install the **following R packages** (see instructions which
   follow):

	ggplot2

	dplyr

	a) MAC OS X and Linux:
	* Open R (not RStudio for this step)
	* In Menu, go to “Packages and Data” - > “Package Installer”
	* Search for and install the above two packages (may need to
      choose a “mirror” - click on something in the USA) as follows:
	* Type in the name of one package, click “get list”, check
      “Install Dependencies” and then “Install Selected”
	* Do the same for the other package
	
	b) Windows:
	* Open R (not RStudio for this step)
	* In Menu, go to "Packages" -> "Install package(s)..." and select
      each of the packages at top to install.
	

3. Install RStudio (a great interface for using R)

	Install for your appropriate system from the list at:
	http://www.rstudio.com/products/rstudio/download/


Outline/Programs
===============================================================================

There are four R files in `/programs`. They will function as an
"interactive notebook" for this workshop. Details follow.

* 0-intro.R

* 1-data.R

* 2-graphics.R

* 3-stats.R


### 0-intro.R
This will be a hands-on Introduction to R

* "R is a free software environment for statistical computing and graphics"
* "The best way to learn a new language is to try out the commands"

3 topics covered:  
1. data manipulation, including package `dplyr`  
2. graphics, including package `ggplot2`  
3. basic statistical models: linear and logistic regression  

Go through code in the program

**References:**

* James et al, p 42+ [see Resources section below]


### 1-data.R
Introduction to data manipulation

* using base R functions

* using intuitive, fast methods from `dplyr` 

**References:**

* James et al, p. 47

* `> vignette("introduction", "dplyr")`

* [Data wrangling handout](http://www.rstudio.com/wp-content/uploads/2015/02/data-wrangling-cheatsheet.pdf)



### 2-graphics.R

Hands-on introductions to creating graphics in R

* using base R methods

* using the very popular `ggplot2` package


**References:**

* James et al, p 45, 49

* http://docs.ggplot2.org/current/


### 3-stats.R

We use statistical analysis for:

* inference - making conclusions based on data

* prediction - what will happen when I observe new data?

...and we create models to do both of those things.

"All models are wrong - some are useful."

**Fundamentals:**

* model selection - which model is good/best?

* model diagnostics/validation - is my current model reasonable and
  does it work?

* uncertainty is always part of the final product


**References:**

* James et al, p 15 [statistical modeling]

* James et al, p 59+ [Linear regression]

* James et al, p 130+ [Logistic regression]






	




Resources
===============================================================================

Data Wrangling handout  
http://www.rstudio.com/wp-content/uploads/2015/02/data-wrangling-cheatsheet.pdf

Quick-R  
http://www.statmethods.net

An Introduction to Statistical Learning with Applications in R, by James et al:  
http://www-bcf.usc.edu/~gareth/ISL/




Credits 
===============================================================================
Matthew Eaton for help with some workshop content    
Hadley Wickham: dplyr, ggplot2, etc etc   
ISLR book authors  


