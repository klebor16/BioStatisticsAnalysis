---
title: "Palmer Penguins Initial Analysis"
author: "Kati Lebor"
format: html
editor: visual
execute:
  keep-md: true
---



# *Palmer Penguins*

```{#Load the tidyverse}
library(tidyverse)

#Read the penguins_samp1 data file from github
penguins <- read_csv("https://raw.githubusercontent.com/mcduryea/Intro-to-Bioinformatics/main/data/penguins_samp1.csv")

#See the first six rows of the data we've read in to our notebook
penguins %>% head()



```