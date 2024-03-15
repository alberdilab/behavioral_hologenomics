# Behavioral Hologenomics

I'm a PhD candidate at the University of Copenhagen, Center for Evolutionary Hologenomics. My PhD is atm entitled "The bugs and behaviours of animals – Hologenomics as a tool for studying the role of the gut microbiota in mammalian behaviour". The main aim of PhD thesis is to investigate how/if the gut microbiome influences animal behaviour using a hologenomic approach. I have two research studies in my PhD to assess this and they are called:
1. Fox study (alias: behavioural fox study, fox project)
2. Mice study (alias: BeHo study, BeHo project, behavioural hologenomics mice study)

Here I share the computational work (codes and results) of the BeHo project. The text below origins from this document:
https://docs.google.com/document/d/1Ra6K9tJBcnQmh23X5Pv3lZoZJmxm84B3S1uOH_diuWY/edit?usp=sharing

## Index

## Analysis procedures

The raw code used for data analysis is in the **Rmd** files stored in the root directory of this repository, while the bookdown-rendered webbook is available at:

[alberdilab.github.io/lizard_sample_types](https://alberdilab.github.io/lizard_sample_types)

While the webbook provides a user-friendly overview of the procedures, analyses can be directly reproduced using the Rmd documents. Note that the code chunks that require heavy computation have been tuned off using 'eval=FALSE'. To re-render the webbook, you can use the following code:

```r
library(bookdown)
library(htmlwidgets)
library(webshot)

render_book(input = ".", output_format = "bookdown::gitbook", output_dir = "docs")
```