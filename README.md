# Introduction

This repo houses an extremely important folders and files to feed my pesonal blog created using [the Distill® for R Markdown template in RStudio,Inc.](https://rstudio.github.io/distill/website.html)  and being hosted on [Github Page](https:mgisa.github.io/myblog)

# Steps and creation worflow

Here below is the advanced workflow for creating a new Distill site inside a R project in Rstudio currently known as __Posit__:

* From Rstudio (Posit) IDE _Click File > New Project > New Directory_

* Scroll down and select Distill Website, and check the box to “Configure for GitHub Pages”

Then use your R console to run this code:

```{r}
use_git()
use_github() # you have to have a PAT (GitHub Tokens) setup
```
For More detailed plz visit [Book](https://rstudio4edu.github.io/rstudio4edu-book/) especiallyt in Chapter IV
