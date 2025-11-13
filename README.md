# AHEAD • AI for Health 

### **Evaluation of Applications & Datasets**
The AHEAD Project brings together global expertise to set the standards for trustworthy AI that protects quality healthcare for all.

This repository contains the source code for the AHEAD Resources GitHub page. You can explore the site here: [**AHEAD resources**](https://biodataanalysisgroup.github.io/ahead-resources).

## Setting out the standards for trustworthy AI
While the use of Artificial Intelligence (AI) is on the rise, there remains a lack of consensus on standardised approaches for its responsible implementation…

The AHEAD project is working to create a transdisciplinary, diverse and global community that draws on the expertise of professionals in different fields to address the ongoing effort of tackling challenges and setting important standards in an ever-changing landscape.

## Enhancing trasndisciplinary collaboration
AHEAD will encourage responsible AI innovation through constant collaboration and knowledge exchanges, to continuously meet the demands of the fast-changing AI landscape and ensure that this technology is used to enhance quality healthcare for all.

## Requirements

- Install `R`: https://cloud.r-project.org/.
- Install `RStudio`: https://posit.co/download/rstudio-desktop/.
- Install `Quarto`: https://quarto.org/docs/get-started/.
- Inside RStudio install the following libraries: 
```r
install.packages(c("data.table", "rjson", "reactable"))
```

## Deploy the site locally
In the `RStudio` terminal run:
```r
quarto render
quarto preview
```

## Commit and push your changes to GitHub

1. Commit and push your changes. Please see here: https://docs.github.com/en/get-started/using-github/github-flow.
2. Publish to gh-pages branch:
```r
quarto publish gh-pages
```
