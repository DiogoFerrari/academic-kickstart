---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Semi-parametric Bayesian Methods for Comparative Politics"
summary: ""
authors: []
tags: [Methodology, NPB]
categories: []
date: 2019-07-11T23:18:51-03:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
 <div align="justify">

<img src="/img/simpsons-paradox.png" align="left" width="300" style="padding-right: 10px;"> My work in Political Methodology has focused on machine learning approaches, non- and semi-parametric Bayesian statistics, and computational methods for density estimation and latent variable modeling in political science. 

In a large-n quantitative comparative analysis, researchers cannot possibly measure all factors that can affect the political behavior. Very likely, some factors that condition the effect of observed covariates are omitted or remain latent. It can lead to latent occurrence Simpson’s Paradox, which is a long-standing problem in statistical analysis in general and in the social sciences in particular. Simpson’s paradox refers to the possibility that an effect found when data are aggregated is completely different or even reversed when data are separated and analyzed in groups. If such groups are latent, classical empirical approaches (GLM, mixed models, etc.) are not able to detect and deal with them, meaning that Simpson’s Paradox goes unnoticed by the researcher. In comparative analysis there is another level of complication: different countries can have different latent factors conditioning different observed covariates.  My research in political methodology focuses on machine and statistical learning tools – particularly model-based clustering methods, stochastic processes, and semi-parametric and non-parametric Bayesian estimation – for investigating ways to deal with those problems.

I have worked with Dirichlet Regression models and proposed a hierarchical approach with semi-parametric Bayesian models (SPB) to deal with latent heterogeneity in the effect of treatment variables in experimental studies and/or latent heterogeneity in conditional associations in observational studies.

<img src="/img/densities-polarization.png" align="right" width="300" style="padding-left: 10px;">I have used SPB models to study the latent structure of public support for welfare policies in OECD countries. I show that there is a hidden polarization among the observed socioeconomic groups in some countries but not others. My research indicates that one side effect of welfare policies in highly unequal societies with fragmented party systems is the existence of latent polarization in welfare policy preferences among individuals with similar observed socioeconomic characteristics. Countries that does not display such a latent polarization (the USA, Japan, Australia, New Zealand) usually have comparative smaller welfare states. Here are some related work: 


- (2019) <a href="/publication/ferrari-2019-modeling/" style="color:blue2"> Modeling Context-Dependent Latent Effect Heterogeneity</a> <i>Political Analysis</i>
- Identification Analysis and Multimodality of Posterior Distribution in Bayesian Models.
