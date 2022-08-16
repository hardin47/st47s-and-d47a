---
title: "Data Sources"
weight: 6
slug: data
excerpt: ""
date: ""
draft: false
featured: true
show_post_date: false
---


# Data Sources

<figure>
<img src="tidydata_2_featured.jpg" align="right">
<figcaption>Art by @allison_horst</figcaption>
</figure>

## Data for Equity & Inclusion

* <a href = "https://www.slavevoyages.org/" target = "_blank"><bf>SlaveVoyages</bf></a>: "The SlaveVoyages website is a collaborative digital initiative that compiles and makes publicly accessible records of the largest slave trades in history. Search these records to learn about the broad origins and forced relocations of more than 12 million African people who were sent across the Atlantic in slave ships, and hundreds of thousands more who were trafficked within the Americas."  
* <a href = "https://github.com/bryandmartin/gibboda" target = "_blank"><bf>gibboda</bf></a>: Gender Isn’t Binary But Other Data Are!  
* <a href="http://hatespeechdata.com/" target = "_blank"><bf>hate speak corpora</bf></a>: particularly interesting for training NLP models 

## R packages for connecting to APIs:

* [**coinmarketcapr**](https://github.com/amrrs/coinmarketcapr): Connecting to Coin Market Cap to get Cryptocurrencies Market Cap Prices .
* [**rtweet**](https://github.com/ropensci/rtweet): R client for accessing Twitter (stream and REST) API.
* [**epidata**](https://github.com/hrbrmstr/epidata): R package to link to the [API](http://www.epi.org/).  The Economic Policy Institute provides researchers, media, and the public with easily accessible, up-to-date, and comprehensive historical data on the American labor force. It is compiled from Economic Policy Institute analysis of government data sources. Use it to research wages, inequality, and other economic indicators over time and among demographic groups. Data is usually updated monthly.
* [**acs**](https://github.com/cran/acs): R package to link to the [API](https://www.census.gov/data/developers/data-sets.html).  Provides a general toolkit for downloading, managing, analyzing, and presenting data from the U.S. Census, including SF1 (Decennial short-form), SF3 (Decennial long-form), and the American Community Survey (ACS). 
* [**tidyhydat**](https://github.com/ropensci/tidyhydat):  Canadian hydrometric data — Historical data is contained within HYDAT, the Canadian national Water Data Archive, which is published quarterly by the Government of Canada’s Department of Environment and Climate Change. Data in this archive range from 1850 to 2017. tidyhydat also provides functions to access real-time data over the web. This package would be of interest to anyone who has need for Canadian hydrometric data in R.
* [**ipumsr**](https://cran.r-project.org/web/packages/ipumsr/vignettes/ipums.html): An easy way to import census, survey and geographic data provided by ‘IPUMS’ into R plus tools to help use the associated metadata to make analysis easier. ‘IPUMS’ data describing 1.4 billion individuals drawn from over 750 censuses and surveys is available free of charge from their [website](https://ipums.org).
* [**essurvey**](https://cran.r-project.org/web/packages/essurvey/vignettes/intro_ess.html): Download data from the European Social Survey directly from their [website](http://www.europeansocialsurvey.org/). There are two families of functions that allow you to download and interactively check all countries and rounds available.
* [**data360r**](https://cran.r-project.org/web/packages/data360r/index.html):  Makes it easy to engage with the Application Program Interface (API) of the [TCdata360](https://tcdata360.worldbank.org/) and [Govdata360](https://govdata360.worldbank.org/) platforms. These APIs provide access to over 5000 trade, competitiveness, and governance indicator data, metadata, and related information from sources both inside and outside the World Bank Group. Package functions include easier download of data sets, metadata, and related information, as well as searching based on user-inputted query.
* [**lahman**](https://cran.r-project.org/web/packages/Lahman/index.html): Provides the tables from the ‘Sean Lahman Baseball Database’ as a set of R data.frames. It uses the data on pitching, hitting and fielding performance and other tables from 1871 through 2015, as recorded in the 2016 version of the database.
* [**wbstats**](https://github.com/saghirb/Women-in-Parliament-Hex-Sticker): Women in Parliament dataset and link to worldbank 


## R packages containing multiple datasets:

* [**gibboda**](https://github.com/bryandmartin/gibboda): Gender Isn’t Binary But Other Data Are!
* [**openintro**](https://github.com/OpenIntroStat/openintro) an R package for data and supplemental functions for OpenIntro resources 
* [**tidyverse**](https://www.tidyverse.org/) is a suite of R packages that contain some fantastic datasets 
* **fivethirtyeight**: an [R package](https://cran.r-project.org/web/packages/fivethirtyeight/vignettes/fivethirtyeight.html) that pulls in data that 538 has already [publicly posted](https://github.com/fivethirtyeight/data)
* [**mosaicData**](https://github.com/ProjectMOSAIC/mosaicData)
* The R package **dslabs** has some great datasets, described in this [Simply Statistics blog](https://simplystatistics.org/2019/07/19/more-datasets-for-teaching-data-science-the-expanded-dslabs-package/)

## Dynamic Data Sets / Databases:

* The amazing [TidyTuesday](https://github.com/rfordatascience/tidytuesday) datasets.  For example, data on [Juneteenth](https://github.com/rfordatascience/tidytuesday/tree/master/data/2020/2020-06-16) or [Wealth Inequality](https://github.com/rfordatascience/tidytuesday/tree/master/data/2021/2021-02-09)
* [College Scorecard](https://collegescorecard.ed.gov/).  A tremendous amount of information about all universities (though some of it collected only from students on financial aid).
* [National Park Service Visitor Use Statistics](https://irma.nps.gov/Stats/)
* [Financial and Economic data](https://www.quandl.com/)
* [Behavioral Risk Factor Surveillance System](http://www.cdc.gov/brfss/)
* [General Social Survey](https://gss.norc.org/get-the-data)
* [National Health and Nutrition Examination Survey from the CDC](https://wwwn.cdc.gov/nchs/nhanes/Default.aspx)  also available in two different R pakcages: [**nhanesA**](https://cran.r-project.org/web/packages/nhanesA/vignettes/Introducing_nhanesA.html) and  [**NHANES**](https://github.com/ProjectMOSAIC/NHANES)
* [Medicare dataset](https://www.cms.gov/Research-Statistics-Data-and-Systems/Statistics-Trends-and-Reports/Medicare-Provider-Charge-Data/Inpatient) (discussed on whitehouse.gov)
* [State Health Facts](http://www.statehealthfacts.org/)
* [gapminder.org](https://www.gapminder.org/) – a fascinating website with amazing graphics (social and economic data broken down by country). Click on the spreadsheet links to download the data.
* [Wolfram/Alpha](http://www.wolframalpha.com/)  is billed as a computational search engine. Put in "nachos" you get a detailed nutritional analysis, put in "GDP of Albania"and you get several forms of GDP, a historical graph and other economic variables, put in your favorite college and get lots of info (including number of degrees in mathematics in 2009, location on a map and link to a satellite view of campus). While the case by case data display is not so convenient for building datasets there are pretty good links to the sources that Wolfram is pulling data from. For example, the Wolfram/Alpha page of info on a college or university has a data source link at the bottom to the National Center For Educational Statistics website where you can download your own custom data files from the IPSEDS (Integrated Post Secondary Education Data System) – want to know the average faculty salary by rank for all the schools in your comparison group? or the nacho search gives a link to the USDA’s National Nutrient database and a few clicks later I’ve got a spreadsheet with data on 50+ nutrients in 7400+ foods (and that’s the abbreviated data!)
* [The Census Bureau](http://www.census.gov/)
* [Baby names](http://www.ssa.gov/oact/babynames/) (popularity by year and state), compiled by the Social Security Administration
 

## New & Continuously Revised Static Data Sets / Databases:


* <a href = "https://osf.io/gpxwa/" target = "_blank"><bf>Boston College COVID-19 Sleep and Well-Being Dataset</bf></a>
* <a href = "https://www.norcalbiostat.com/data/" target = "_blank">Collection of datasets</a> compiled by <a href = "https://www.norcalbiostat.com/" target = "_blank">Robin Donatello</a> at CSU Chico.
* <a href = "https://dataverse.harvard.edu/" target = "_blank">Harvard Dataverse</a>
* <a href="http://hatespeechdata.com/" target = "_blank">hate speak corpora</a>, particularly interesting for training NLP models 
* The R package **dslabs** has some great datasets, <a href="https://flowingdata.com/2018/04/09/datasets-for-teaching-data-science/" target = "_blank">described in this Simply Statistics blog</a>
* <a href="https://www.cdc.gov/nchs/" target = "_blank">CDC health datasets</a> which are freely available and formatted.  To be analyzed correctly, these survey data require proper weighting, clustering and stratification adjustments.  There are many such datasets available, including NHAMCS (OPD and ED), NAMCS, BRFSS, NSFG, NHIS, NIS-Child, NIS-Teen, NHANES, NVSS. A quick google of any of these acronyms will take you directly to each webpage.
* <a href = "https://www.kaggle.com/" target = "_blank">kaggle.com</a> is a repository for data used in analysis competitions.
* <a href = "https://archive.ics.uci.edu/ml/index.php" target = "_blank">UC Irvine’s Machine Learning Repository</a>  (huge and fantastic database!).
* The GitHub site and other info for many of 538’s analyses.  
<a href = "https://fivethirtyeight.com/" target = "_blank">FiveThirtyEight.com</a> has been very forward thinking in making the data and code used in many of their articles accessible on <a href = "https://github.com/fivethirtyeight/data" target = "_blank">GitHub</a>. With consultation from Andrew Flowers and Andrei Scheinkman of FiveThirtyEight, we go one step further in our package by pre-processing the data so that it more accessible statistics and data science novices and providing ample documentation in the help files.  
See a usage example and R package called <a href = "https://github.com/rudeboybert/fivethirtyeight#installation--usage" target = "_blank">**fivethirtyeight**</a>. For a more detailed outline of all data sets and a discussion on our motivation and data guidelines, see the package vignette.  
And this: <a href = "https://www.storybench.org/how-to-explore-a-dataset-from-the-fivethirtyeight-package-in-r/?utm_content=buffer3af3e&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer" target = "_blank">How to explore data from 538</a>
* <a href = "http://tinyletter.com/data-is-plural/archive" target = "_blank">Data is Plural</a> set of fun and interesting new datasets and the <a href = "https://docs.google.com/spreadsheets/d/1wZhPLMCHKJvwOkP4juclhjFgqIY8fQFMemwKL2c64vk/edit#gid=0" target = "_blank">spreadsheet with all relevant info</a> 
* The StudentLife Study. In 2013, four dozen Dartmouth College students agreed to let a custom smartphone app surveil them for the StudentLife Study. During the 10 weeks of the spring academic term, the app collected data on the students’ physical activity, GPS coordinates, eating schedule, sleep habits, phone usage, and more. The study combined all that information with a slew of other data, including the students’ class deadlines, academic performance, and their responses to surveys about stress, depression, personality, and sleep quality. The study’s public (and anonymized) <a href = "http://studentlife.cs.dartmouth.edu/" target = "_blank">dataset</a> clocks in at 53 gigabytes.
* Shonda Kuiper's (Grinnell College) <a href = "https://stat2labs.sites.grinnell.edu/DataResources.html" target = "_blank">many data resources</a>
* <a href = "http://www.realclimate.org/index.php/data-sources/" target = "_blank">realclimate.org</a> keeps an up to date catalogue of many different types of climate data
* An <a href = "https://github.com/rundel/Dennys_LaQuinta_Chance" target = "_blank">analysis of Denny’s vs LaQuinta</a> restaurants
* <a href = "https://github.com/swang87/atus" target = "_blank">American Time Use survey</a> 
* <a href="https://github.com/hadley/fec-dplyr" target = "_blank">FEC contributions data</a> (as part of Hadley Wickham’s dplyr package)
* <a href="http://webscope.sandbox.yahoo.com/" target = "_blank">Yahoo big data datasets</a>
* SF OKCupid Users Everett Wetchler wrote a python script back in the day to rip the public profiles of San Francisco OkCupid users.  He pulled one <a href="https://github.com/evee746/okcupid" target = "_blank">snapshot</a> (June 26, 2012) of all OkCupid users who lived within 25 miles of San Francisco along with other caveats. It might be of interest to students given the recent press that data-driven approaches to online dating have been getting, specifically the Wired article <a href="http://www.wired.com/wiredscience/2014/01/how-to-hack-okcupid/" target = "_blank">"How a Math Genius Hacked OkCupid to Find True Love"</a> and Amy Webb’s Ted Talk <a href="http://www.ted.com/talks/amy_webb_how_i_hacked_online_dating" target = "_blank">"How I hacked online dating"</a>.
* This <a href = "http://www.lerner.ccf.org/qhs/datasets/" target = "_blank">growing dataset repository</a> presents raw data from real medical studies and offers (a) a vignette summarizing the study, research question and study design; (b) a data dictionary with clear documentation of variables and codes; (c) a complete citation for the associated study publication; and (d) a variety of data formats compatible with the majority of statistical packages. 
* <a href = "https://www.causeweb.org/tshs/category/dataset/" target = "_blank">Clinical Trials datasets</a> from Teaching Statistics in the Health Sciences 
* <a href = "http://jse.amstat.org/" target = "_blank">Journal of Statistics and Data Science Education</a> (check the archive) – datasets contributed by statistics teachers. Raw data are given in a .dat file with explanations of the variables in an accompanying .doc file. 
* <a href = "http://dasl.datadesk.com/" target = "_blank">DASL (Data and Story Library)</a> – a collection of datasets and related documentation which may be searched by data subjects or by statistical techniques
* <a href = "https://github.com/caesar0301/awesome-public-datasets/blob/master/README.rst" target = "_blank">Awesome public datasets</a> 
* <a href = "https://docs.google.com/document/d/1w7KhqotVi5eoKE3I_AZHbsxdr-NmcWsLTIiZrpxWx4w/pub" target = "_blank">Bessie Chu‘s compilation of datasets</a> 
* <a href = "https://www.dataquest.io/blog/free-datasets-for-projects/" target = "_blank"> 21 Places to Find Free Datasets for Data Science Projects</a>
* Lots of fun data from <a href = "https://www.openintro.org/data" target = "_blank">OpenIntro</a>


## Journals / Journal articles that provide corresponding data:

* The GitHub site and other info for many of 538’s analyses.  
<a href = "https://fivethirtyeight.com/" target = "_blank">FiveThirtyEight.com</a> has been very forward thinking in making the data and code used in many of their articles accessible on <a href = "https://github.com/fivethirtyeight/data" target = "_blank">GitHub</a>. With consultation from Andrew Flowers and Andrei Scheinkman of FiveThirtyEight, we go one step further in our package by pre-processing the data so that it more accessible statistics and data science novices and providing ample documentation in the help files.  
See a usage example and R package called <a href = "https://github.com/rudeboybert/fivethirtyeight#installation--usage" target = "_blank">**fivethirtyeight**</a>. For a more detailed outline of all data sets and a discussion on our motivation and data guidelines, see the package vignette.  
And this: <a href = "https://www.storybench.org/how-to-explore-a-dataset-from-the-fivethirtyeight-package-in-r/?utm_content=buffer3af3e&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer" target = "_blank">How to explore data from 538</a>

* Nature – Many articles have a "Data availability" section.  See <a href = "https://www.nature.com/articles/s41586-018-0352-3" target = "_blank">Hurricane-induced selection on the morphology of an island lizard</a> which includes a <a href = "https://datadryad.org/stash/dataset/doi:10.5061/dryad.2t41r64" target = "_blank">link to the data</a>. 
* <a href = "http://jse.amstat.org/" target = "_blank">Journal of Statistics and Data Science Education</a> (check the archive) or <a href = "https://www.tandfonline.com/toc/ujse/current" target = "_blank">more recent papers</a>

## Static Data Sets / Databases:

* <a href="http://www.statsci.org/data/" target = "_blank">DASL in Australia</a>
* <a href="http://lib.stat.cmu.edu/datasets/" target = "_blank">Statlib Dataset Archive</a> – one of the original sources for archived data
* <a href="http://www.itl.nist.gov/div898/education/datasets.htm" target = "_blank">National Institute of Standards and Technology</a> (NIST) education data sets
* <a href="http://www.dartmouth.edu/~chance/teaching_aids/data.html" target = "_blank">CHANCE Project Datasets</a> – data from recent media coverage of current events. Only a few datasets here, but many excellent references to teaching applications of statistics in the news can be found at the main CHANCE page
* A <a href = "http://www.statsci.org/datasets.html" target = "_blank">data repository from statsci.org</a> – a statistics and bioinformatics group in Australia 


## Visualizing Data:

* <a href="http://www.informationisbeautiful.net/" target = "_blank">Information is Beautiful</a> 
* From Mark Ward at Purdue: <a href = "http://llc.stat.purdue.edu/2014/29000/visualsites.html" target="_blank">Websites for Visualizing Data</a>
* Nathan Yau’s amazing visualizations: <a href = "http://flowingdata.com/" target = "_blank">FlowingData</a>, most of which include corresponding datasets.
* Kerry Lock Morgan has posted a compilation<a href = "http://www.personal.psu.edu/klm47/visualization.htm" target = "_blank"> data visualizations</a>
* Caitlin Hudon's GitHub site of <a href="https://github.com/caitlinhudon/data_viz_resources/blob/main/README.md" target="_blank">Data Viz Resources</a>
* No data here, but I have to link to these <a href = "https://www.darkhorseanalytics.com/portfolio-data-looks-better-naked" target = "_blank">amazing gifs</a> which get cleaner as they go, byt Darkhorse Analytics.


