## Part 1: Introduction to Workshop and R & Data Analysis in R 

### Introductory Activity

[Introduction Padlet](https://padlet.com/jschilling_ccs/air_R_intro)


### R Setup
- [R](https://www.r-project.org/)
- [RStudio](https://www.rstudio.com/)
- Packages Installed (here, explore, tidyverse, scales)
```
 install.packages(c("here", "explore", 
                    "tidyverse", "scales"))
```
- [Workshop folder with R Markdown and data files](https://github.com/jennschilling/data-analysis-viz-in-R/tree/main/air-workshop-materials)

### Workshop Materials
- code
  - data-analysis-viz-in-r-code.Rmd
- data
  - IPEDS_inst_adm.csv
  - IPEDS_inst_char.csv
  - IPEDS_inst_compl.csv
  - IPDES_inst_enrl.csv
- plots
- .here
- README.txt

### Data
The data for this workshop is sources from the Integrated Postsecondary Education Data System from the National Center for Education Statistics (or [IPEDS](https://nces.ed.gov/ipeds/use-the-data)).

Data comes from the following surveys:
- Institutional Characteristics
- Admissions and Test Scores
- Fall Enrollment
- Completions

I pulled data from 2017-2020 and selected 16 institutions based on the University of Arizona's peers defined by the Arizona Board of Regents. Then I reformatted the data to be tidy. 

