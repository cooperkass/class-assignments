---
title: "Classwork Thursday 3-9"
author: "Cooper Kass"
date: "March 9, 2017"
output: github_document
---

```{r}
install.packages("paleotree")
install.packages("paleobioDB")
library(paleotree)
library(paleobioDB)
data(graptPBDB)
data(graptOccPBDB)
data(graptPBB)
data(graptPBDB)
ls()
ls()
occSpecies <- taxonSortPBDBocc(graptOccPBDB, "species")
head(occSpecies)
plotOccData(occSpecies, groupLabel = "Species")
View(graptTaxaPBDB)
plotOccData(occSpecies, groupLabel = "Species")


```

