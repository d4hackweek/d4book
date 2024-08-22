# D4 Tutorial: Reproducibly Accessing Census Data in R & Python
**Authored By:**

[Tyler Fricker](https://www.ulm.edu/~tfricker/), Assistant Professor - Geography, University of Louisiana-Monroe

[Jessica Godwin](https://csde.washington.edu/staff/godwin-jessica/), Statistical Demographer - Center for Studies in Demography & Ecology, University of Washington

[June Yang](https://csde.washington.edu/staff/yang-june/), Computational Demographer - Center for Studies in Demography & Ecology, University of Washington

## Contents
 
**R tutorial contained in *Census-data-in-R.Rmd* and *Census-data-in-R.html* files.**
  * **Dependencies**
      * **Data/** contains file *Shreveport.json* necessary for the Areal Interpolation section.
      * **Figures/** contains some *.png* files necessary to knit the *.Rmd* into an *.html*.
      * **CensusAPIKey.R** is a file necessary for running or knitting the R tutorial, but is included in the *.gitignore* file. Read the R tutorial's section titled *Getting and managing your Census API Key* for more information on how to set up your own *CensusAPIKey.R* file.

***Python tutorial coming soon!***

## **Tutorial Outline**

*  Introduction
   *  Why use U.S. Census data in climate research?
   *  Census geographies and uncertainty
   *  Why access Census data with R or Python?
   *  Tutorial Outline
*  Accessing Census Bureau Data with R Packages
   *  The Census API and censusapi
   *  IPUMS, NHGIS, and ipums
   *  tidycensus and tigris
   *  Getting and managing your Census API key
*  Using tidycensus
   *  Selecting variables and tables
      *  Datasets
      *  Variable & table names
      *  Data Year
      *  Geographic scale
      *  Temporal scale
   *  Querying the Census API
      *  get_decennial()
      *  get_acs()
   *  Dealing with variable labels
*  Getting results
   *  Basic tables
   *  Multi-year results
   *  Aggregating estimates across labels
*  Census Geographic Data
   *  Plotting Geographic Data in R
   *  Working with Census Geometries
   *  Mapping Census and ACS Estimates in R
      *  Map-Making with ggplot2
      *  Map-Making with tmap
*  Areal Interpolation
