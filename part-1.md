## Part 1: Introduction to Workshop and R & Data Analysis in R 

### Introductory Activity

[Introduction Padlet](https://padlet.com/jschilling_ccs/air_R_intro)


### R Setup
- Install [R](https://www.r-project.org/)
- Install [RStudio](https://www.rstudio.com/)
- Install packages (here, explore, tidyverse, scales)
 ```
  install.packages(c("here", "explore", 
                     "tidyverse", "scales"))
 ```
- Download [workshop materials folder with R Markdown and data files](https://github.com/jennschilling/data-analysis-viz-in-R-materials)

### Workshop Materials
- code
  - data-analysis-viz-in-r-code.Rmd
- data
  - IPEDS_inst_adm.csv
  - IPEDS_inst_char.csv
  - IPEDS_inst_compl.csv
  - IPDES_inst_enrl.csv
- output
- plots
- .here
- README.txt

### Data
The data for this workshop is sources from the Integrated Postsecondary Education Data System from the National Center for Education Statistics ([IPEDS](https://nces.ed.gov/ipeds/use-the-data)).

Data comes from the following surveys:
- Institutional Characteristics
- Admissions and Test Scores
- Fall Enrollment
- Completions

I pulled data from 2017-2020 and selected 16 institutions based on the University of Arizona's peers defined by the Arizona Board of Regents. Then I reformatted the data to be tidy. 

### Code

[Data Exploration Code](https://jennschilling.me/data-analysis-viz-in-R/workshop-code.html#Data_Exploration)

### Data Exploration Resources

- [explore package](https://github.com/rolkra/explore)
