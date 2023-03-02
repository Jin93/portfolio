---
layout: page
permalink: /software/
title: Software
nav: true
sort: 5
---

#### R Packages
[MEBayesSL](https://github.com/Jin93/MEBayesSL){:target="_blank"}
MEBayesSL is an R-based command line tool for implementing ME-Bayes SL, a powerful method for developing ancestry-specific polygenic risk score (PRS) that integrates information from GWAS summary statistics and external LD reference data from multiple populations (ancestry groups). ME-Bayes SL infers SNP effect sizes via a Bayesian model with an induced prior correlation structure across populations followed by an ensemble learning step with the Super Learner. 
[Paper available upon request: Jin.Jin@Pennmedicine.upenn.edu]

[MRLE](https://github.com/Jin93/MRLE){:target="_blank"}
Mendelian randomization analysis for latent exposures leveraging information from multiple biomarkers. [[Paper](https://www.biorxiv.org/content/10.1101/2021.02.05.429979v3.abstract)]

[T2DAG](https://github.com/Jin93/T2DAG){:target="_blank"}
A DAG-informed high-dimensional two-sample test for disease-associated gene pathways. [[Paper](https://academic.oup.com/bioinformatics/article/38/4/1005/6424893)]
&nbsp;

--- 
#### COVID-19 Risk Tools
[Mortality Risk Calculator](https://covid19risktools.com:8443/riskcalculator){:target="_blank"}

<div class="row justify-content-sm-center">
    <div class="col-sm-5 mt-3 mt-md-0">
        {% include figure.html path="assets/img/risktool.png" title="Example output of the risk tool" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-7 mt-3 mt-md-0">The tool provides an assessment of individualized risks for mortality from COVID-19 using the best publicly available information on risks associated with various pre-existing conditions and socio-demographic factors. We further tailored it to produce absolute risk estimates in future time frames by incorporating information on pandemic dynamics at the community level with projections available from an ensemble of pandemic forecasting models. [[Paper](https://www.nature.com/articles/s41591-020-01191-8)]</div>
</div>
&nbsp;


[Risk Interactive Maps](https://jhucovid19.policymap.com/newmaps#/){:target="_blank"}

<div class="row justify-content-sm-center">
    <div class="col-sm-5 mt-3 mt-md-0">
        {% include figure.html path="assets/img/policymap.png" title="State-level projections of COVID-19 Mortality Risk" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-7 mt-3 mt-md-0">Developed through a collaborative effort with Eliza Wallace from <a href="https://www.policymap.com/">PolicyMap</a>, the interactive maps show sizes of high-risk populations in the U.S., nationwide and by cities, countries, and states.
</div>
</div>
&nbsp;
