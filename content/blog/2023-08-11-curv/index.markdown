---
title: CURV - connecting, uplifting, and recognizing voices 
author: Jo Hardin
date: '2023-08-11'
slug: curv
featured: true
categories: []
tags: []
summary: 'CURV is a database which seeks to celebrate scholars who are traditionally under represented in statistics and data science. The scholars represent the diversity of undergraduate students; they are individuals who are working to make statistics more accessible; and their works leads to making the world a better place.'
---




In most of my courses, I've introduced a weekly activity of "Statistician of the Day."  The scholars who I present are those traditionally underrepresented in statistics and data science.  Many of them are people of color, but they also represent individuals who are pushing boundaries to make statistics and data science more accessible and inclusive, often because they themselves have navigated a world which was not accessible or not inclusive.

The database is called <a href = "https://hardin47.github.io/CURV/" target = "_blank">CURV - connecting, uplifting, and recognizing voices</a>.  You can see the source code and/or contribute to the database by exploring the <a href = "https://github.com/hardin47/CURV/" target = "_blank">CURV GitHub repo</a>.

# Representation Matters

When I think about the statisticians I encountered during my education, these four on my <a href = "https://www.etsy.com/shop/NausicaaDistribution" target = "_blank">coaster set</a> come to mind.

<img src="coasters.jpg" alt="A set of four coasters including Gosset, Pearson, Bayes, and Fisher" width="639" />


My coasters aside, a Google search on "famous statisticians" produces a few women on the list, but the demographics of the individuals presented are remarkably homogeneous.

<img src="google.png" alt="In a Google search for famous statisticians, the individuals listed include Tukey, Nightingale, Fisher, Cox, Pearson, Box, Bayes, Deming, and Gosset." width="562" />


## David Blackwell 

Arguably, the most famous/influential/brilliant African American statistician is <a href = "https://en.wikipedia.org/wiki/David_Blackwell" target = "_blank">David Blackwell</a>.  Statisticians may know Blackwell from the <a href = "https://en.wikipedia.org/wiki/Rao%E2%80%93Blackwell_theorem" target = "_blank">Rao-Blackwell theorem</a> which says that after conditioning on a sufficient statistic, the new estimator will have smaller (or equal to) mean squared error than the original estimator.  

Blackwell was the 1st African American elected to the National Academies of Science and the 1st African American tenured at UC Berkeley.  He was the 7th African American to receive a PhD in mathematics.  In 2012, President Obama posthumously awarded Blackwell the National Medal of Science.

The majority of Blackwell's career in statistics was spent at UC Berkeley (1954-1988).  However, his start at UC Berkeley was postponed due to racism in the Department of Mathematics.  Hear Blackwell describe the situation in his own words in the following video:

:::{.column-page}
<iframe src="https://www.youtube.com/watch?v=Mqpf9tw44Xw" title="Interview with David Blackwell" width="1000" height="500" data-external="1"></iframe>
:::

<p>   </p>

Interview with David Blackwell can be found at<a href="https://www.youtube.com/watch?v=Mqpf9tw44Xw" target="_blank">https://www.youtube.com/watch?v=Mqpf9tw44Xw/</a>.


### Why does representation matter?

When individuals don't feel a part of the community, their identity gets mixed up with their ability.  The following xkcd commit encapsulates what can happen when individuals of the non-dominant demographic group engage with the content of the course / curriculum / minor / major.

<div class="figure">
<img src="xkcd.png" alt="In the first panel, a stick figure makes a mathematical mistake, and the other stick figure says &quot;you are bad at math&quot;.  In the second panel, a stick figure with long hair (presumably a female stick figure) makes the same mistake, and the other stick figure says &quot;girls are bad at math.&quot;" width="205" />
<p class="caption"><span id="fig:unnamed-chunk-4"></span>Figure 1: image credit -- https://xkcd.com/385/</p>
</div>



>Research indicates that many young people may be deterred from pursuing STEM fields due to prominent stereotypes regarding who best fits and belongs in such fields.^[Nguyen and Riegle-Crumb.  *Who is a scientist? The relationship between counter-stereotypical beliefs about scientists and the STEM major intentions of Black and Latinx male and female students*. **International Journal of STEM Education**, volume 8, Article number: 28 (2021), https://doi.org/10.1186/s40594-021-00288-x]


#### What are some reasons that representation impacts participation in engaging in STEM?

* stereotypes about innate abilities
* stereotypes about images in the field


# Who is in CURV?

* Scholars who represent the diversity of students
* Scholars working to make statistics more accessible
* Scholars using statistics to do good in the world


## Liz Hare

Liz Hare is not a statistician.  Indeed, she is a geneticist, working primarily in dog / animal genetics.  However, as someone who is very active in the <a href = "https://mircommunity.com/about/" target + "_blank">Minorities in R (MiR) Community</a>,  she works regularly with statisticians.

Liz Hare is visually impaired and has focused <a href = "https://www.urban.org/sites/default/files/2022-12/Do%20No%20Harm%20Guide%20Centering%20Accessibility%20in%20Data%20Visualization.pdf#page=31&zoom=100,0,0" target = "_blank">her work</a> on communicating the value and ease with which statisticians and data scientists can add alt text to their reports.  In the alt text, she asks us to consider and report:

1. What kind of graph or chart is it?
2. What variables are on the axes?
3. What are the ranges of the variables?
4. What does the appearance tell you about the relationships between the variables?

:::{.column-page}
<iframe src="ibo_tweets.mov" title="Screen reading of a TidyTuesday analysis of Ibo tweets." width="1000" height="500" data-external="1"></iframe>
:::

After presenting Liz Hare and her work to my students, I am able to teach them how to include alt text in their own work, a process which is extremely straightforward if students are using R markdown or Quarto documents.  

In R, including alt text is done by providing information for the relevant R chunk.  After introducing students to Liz Hare's work, it takes very little overhead to communicate to them the ways that a graphic can be made more accessible by adding alt text to each figure.


<div class="figure">
<img src="r_code.png" alt="To include alt text in Rmarkdown or Quarto files, the alt text information is given in the arguments of the R chunk." width="751" />
<p class="caption"><span id="fig:unnamed-chunk-5"></span>Figure 2: R code for Ibo tweets in TidyTuesday analysis.</p>
</div>


<div class="figure">
<img src="captions.png" alt="The figure contains information on how to communicate information about a graphic through alt text, report captions, and individual figure captions." width="760" />
<p class="caption"><span id="fig:unnamed-chunk-6"></span>Figure 3: Different ways to annotate a figure include alt text, figure captions for the full file, and figure captions for the ggplot.</p>
</div>

## Rafael Irizarry

Rafael Irizarry is a well known biostatistician, having done his PhD at Berkeley, worked for many years at Johns Hopkins University, and currently running a lab at Harvard as Professor of Biostatistics and at the Dana-Farber Cancer Institute as Professor of Biostatistics and Computational Biology.  He has dozens of online courses through the <a href = "https://www.edx.org/bio/rafael-irizarry" target = "_blank">edX platform</a> and over a hundred publications via <a href = "https://scholar.google.com/citations?user=nFW-2Q8AAAAJ&hl=en" target = "_blank">Google scholar</a>.

Relevant to the <a href = "https://hardin47.github.io/CURV/" target = "_blank">CURV database</a> however is the work that Rafael Irizarry has done in Puerto Rico.  Having graduated from the University of Puerto Rico, Rafael Irizarry had a vested interest in the community that was ravaged in 2017 when Hurricane Maria, a category 5 hurricane, ravaged the island. With collaborators, Professor Irizarry performed a representative stratified sample to measure neighborhoods based on how easily accessible they were in the aftermath of the hurricane.

The original news reports months after the hurricane was that the official death report from Hurricane Maria was 64 people.  Professor Irizarry and colleagues estimated that the number of excess deaths was 4645, with a 95% confidence interval of 793 to 8498.

Their work provides a myriad of topics to unpack in a statistics classroom.  Some of the discussions I have had with my students include: who is doing the work to understand climate change at a global level; how is stratified sampling different from simple random samples and why can't we always take simple random samples; and why is the CI so large?

<img src="maria.png" alt="New England Journal of Medicine paper from July 2018 titled &quot;Mortality in Puerto Rico after Hurricane Maria&quot; with Irizarry and co-authors" width="396" />


<img src="maria_abstract.png" alt="Abstract of the New England Journal of Medicine paper.  In particular, they provide a point estimate for the mortality number to be 4645 excess deaths, with a CI of 793 to 8498." width="502" />


# CURV in the classroom

While you surely have creative ideas on how to use CURV in the classroom, I have mostly used it as a "statistician of the day" project.  Once a week (or at every class period), I briefly introduce the scholar and present the different ways they have contributed to the field.  My students have been extremely positive about the engagement reporting the following about being introduced to the scholars in the CURV database.

* inspiring
* a great way to better understand the career paths of data science
* a venue for having important conversations with peers
* highlighted diversity in the field of statistics
* made the classroom environment feel more inclusive


# Contributing to CURV

Please contribute!!!  Share information about the scholars you know who are aligned with the CURV goals.  If you just have a name or idea, feel free to submit an issue on the <a href = "https://github.com/hardin47/CURV/" target = "_blank">CURV GitHub repo</a>  If you have a lot of information about a particular individual, I welcome pull requests.  Thank you for helping the resource become a community efrort.

# CURV aligned

I developed the CURV database because I didn't know of a different resource that I could use for my "Statistician of the Day" classroom exercise.  I wanted the information provided to be relevant to my students, connecting either through identity or through class content.  That said, I've borrowed heavily from existing resources, and I appreciate the myriad existing efforts which engage students in many different ways.  There are many good resources highlighting statisticians, data scientists, and mathematicians who are traditionally underrepresented.
I've listed just a few here, I encourage you and your students to check them out!

* <a href = "https://www.mathad.com/" target = "_blank">Mathematicians of the African Diaspora</a> is dedicated to promoting and highlighting the contributions of members of the African diaspora to mathematics, especially contributions to current mathematical research.
* <a href = "http://www.datascijedi.org/" target = "_blank">Justice, Equity, Diversity, and Inclusion Outreach Group</a>, a community of statisticians and data scientists, is committed to communication, programming, and professional development to advance and support a society that values all people. 
* <a href = "https://d4bl.org/" target = "_blank">Data for Black Lives</a> movement of activists, organizers, and scientists committed to the mission of using data to create concrete and measurable change in the lives of Black people.
* <a href = "https://weallcount.com/2021/04/16/learning-from-indigenous-ways-of-knowing/" target = "_blank">We All Count</a> Extensive guidelines for data inclusivity.
* <a href = "https://www.gaytascience.com/" target = "_blank">Gayta Science</a> Data stories / data viz / data analysis / data science on gender fluidity.
* <a href = "https://blogs.ams.org/inclusionexclusion/2020/11/16/building-gender-and-sexuality-allyship-in-the-mathematics-community/" target = "_blank">Inclusivity Resource</a> Building Gender and Sexuality Allyship in the Mathematics Community.
* <a href = "https://mathematicallygiftedandblack.com/" target = "_blank">Mathematically Gifted and Black</a> celebrates mathematicians from the African diaspora across the mathematical sciences.
* <a href = "https://www.lathisms.org/" target = "_blank">Lathisms</a> A vibrant, inclusive, and diverse Mathematical community where the Latinx and Hispanic culture is valued, cultivated, and celebrated.


