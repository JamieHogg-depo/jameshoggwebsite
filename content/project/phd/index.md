---
date: "2021-04-01T00:00:00Z"
external_link: ""
header: 
  image: 
  caption: 
# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
#slides: example
summary: Details on my PhD project
tags:
- spatial modeling
- Bayesian inference
- small area estimation
- joint modelling
- clustering
title: The PhD project 
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

The page to rule all pages. Well not really, but definitely true for my stats work now! 

I am incredibly fortunate to be working with a very large collection of researchers on the second-phase of the Australian Cancer Atlas (ACA). The current version provides spatial maps of cancer incidence and excessive deaths at the small area level. My PhD work relates to cancer risk factors, which the 2019 Australian Burden of Disease Study estimated could be attributable to 44% of the health burden of cancer in Australia. We want to include spatial maps of cancer risk factors in the second-phase of the ACA.

To enable policymakers a more nuanced and targeted approach to reduce the cancer burden in Australia, I will generate small area level prevalence estimates for several cancer risk factors using the 2017-18 National Health Survey data. To achieve this (hefty, but exciting) goal, the first stage of my PhD involved the development of novel small area estimation methods --- particularly those for very sparse survey data. 

Once I’ve generated the risk factor estimates at the small area level. We hope to explore the spatial (and non-spatial) dependence of risk factors at the small area level. This is exciting and novel work for several reasons. Firstly, we must adjust for the uncertainty of the risk factor estimates which haven’t been considered for proportions yet. Either that or I haven’t found any papers that do. Secondly, we will want to apply both spatial and non-spatial models to these data as they will help to answer unique questions about the state of cancer risk in Australia. Finally, I’m excited to be able to explore multivariate spatial priors and discover ways to use these efficiently in probabilistic programming languages such as Stan. 

The final step – time permitting of course  - is to generate a single map that captures cancer risk. A single map that can give a rough overview for policymakers and simplify the dissemination of the current *state-of-health-play*, as it were. A tool such as this, if done correctly, would be super helpful and hopefully not too upsetting or concerning. Methods to generate a single map has ties to dimension reduction, clustering or health index creation. My current solution (without having tried any!) is that Bayesian structural equation models or factor models could be employed. The benefit to these is their ability to capture the estimated uncertainty and propagate it to the resulting map. By assessing or estimating whether all the cancer risk factors come from a common underlying latent spatial field, we could infer the latent risk posed by a high prevalence of cancer risk factors. 

I have about 1.5 years remaining, which is insufficient given all the interesting stats I wish to apply. Not only am I excited about exploring the stats behind the ideas I’ve very briefly discussed above, but I am enthusiastic about the potential public health impacts my PhD work may have

  

<!--{{% staticref "uploads/brag_20221116.pdf" %}}Slides{{% /staticref %}} for my BRAG talk on the topic can be found here.-->
