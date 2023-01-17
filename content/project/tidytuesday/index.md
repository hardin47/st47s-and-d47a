---
title: "TidyTuesday adventures"
subtitle: "a collection of TidyTuesday plots and models"
excerpt: "a collection of TidyTuesday plots and models"
weight: 2
author: "Jo Hardin"
draft: false
# layout options: single or single-sidebar
layout: single-sidebar
links:
- icon: link
  icon_pack: fas
  name: https://hardin47.github.io/TidyTuesday/
  url: https://hardin47.github.io/TidyTuesday/
- icon: github
  icon_pack: fab
  name: my source code -  https://github.com/hardin47/TidyTuesday/tree/gh-pages
  url: https://github.com/hardin47/TidyTuesday/tree/gh-pages
- icon: github
  icon_pack: fab
  name: official TidyTuesday repo - https://github.com/rfordatascience/tidytuesday
  url: https://github.com/rfordatascience/tidytuesday
- icon: twitter
  icon_pack: fab
  name: search "#TidyTuesday" on mastodon for really fantastic ideas!
  url: https://fosstodon.org/tags/tidytuesday
---

<figure>
<img style = "padding: 10px;float: right;" alt = 'hrdag' width='500' src='postoffices.png' />
</figure>

<br/>

<br/>

<br/>

I try my best to put in a few Tuesday hours working on a TidyTuesday dataset when I can.
If you are in Claremont, I hope you will join us; reach out to me for information on time and place.


* Official GitHub Repo for TidyTuesday: <a href = "https://github.com/rfordatascience/tidytuesday" target = "_blank">https://github.com/rfordatascience/tidytuesday</a>
* The week’s data is posted each Tuesday on GitHub: <a href = "https://github.com/rfordatascience/tidytuesday/tree/master/data/2022" target = "_blank">https://github.com/rfordatascience/tidytuesday/tree/master/data/2022</a>
* My TidyTuesday adventures
  * GitHub repo:  <a href = "https://github.com/hardin47/TidyTuesday/tree/gh-pages" target = "_blank">https://github.com/hardin47/TidyTuesday/tree/gh-pages</a>
  * posts:  <a href = "https://hardin47.github.io/TidyTuesday/" target = "_blank">https://hardin47.github.io/TidyTuesday/</a>
  
## Novice

* Log in to <a href = "https://rstudio.cloud/" target = "_blank">https://rstudio.cloud/</a> (if you are a Pomona student, use your abc0123@mymail email address to connect on the cloud with slightly higher bandwith / support).  
* If you go to Pomona College, log in to Pomona's RStudio server at <a href = "https://rstudio.pomona.edu/" target = "_blank">https://rstudio.pomona.edu/</a>
* Or download R and RStudio (both free) onto your own computer.  R is available at <a href="http://www.r-project.org/" target="_blank">http://www.r-project.org/</a>. Additionally, install RStudio in order to use RMarkdown, <a href="http://rstudio.org/" target="_blank">http://rstudio.org/</a>.  

To load the data in, create an R chunk and copy in the lines of code which are just below the phrase: `# Or read in the data manually` on the `tidytuesday` GitHub site for the particular day of interest.  It will look something like this:

````r
```{r}
dataset_1 <- readr::read_csv('https://raw.githubusercontent.com/rfordatascience/tidytuesday/master/data/2022/some_date/dataset_1.csv')

dataset_2 <- readr::read_csv('https://raw.githubusercontent.com/rfordatascience/tidytuesday/master/data/2022/some_date/dataset_2.csv')
```
````


## Beginner

* Getting started with R:  <a href = "https://education.rstudio.com/learn/" target = "_blank">https://education.rstudio.com/learn/</a> and <a href = "https://rstudio.cloud/learn/primers" target = "_blank">https://rstudio.cloud/learn/primers</a>

* The **introverse** package is truly meant for beginners to the **tidyverse**.  <a href = "https://sjspielman.github.io/introverse/index.html" target = "_blank">https://sjspielman.github.io/introverse/index.html</a> 

* A fantastic <a href = "https://www.cedricscherer.com/2019/08/05/a-ggplot2-tutorial-for-beautiful-plotting-in-r/" target = "_blank">**ggplot2** tutorial</a>

## Intermediate

* Go through the R for Data Science book (highly recommended!): <a href = "https://r4ds.had.co.nz/" target = "_blank">https://r4ds.had.co.nz/</a>

* All of the fantastic <a href = "https://www.rstudio.com/resources/cheatsheets/" target = "_blank">cheatsheets</a>

## Experienced

* More Advanced R for data science: <a href = "https://adv-r.hadley.nz/" target = "_blank">https://adv-r.hadley.nz/</a>

* Great idea to get started with GitHub: <a href = "https://happygitwithr.com/" target = "_blank">https://happygitwithr.com/</a>

* <a href = "https://www.tmwr.org/" target = "_blank">Tidy Modeling with R</a> by Max Kuhn and Juli Silge.

* <a href = "https://www.tidytextmining.com/" target = "_blank">Text Mining with R</a> by Julia Silge and David Robinson.
