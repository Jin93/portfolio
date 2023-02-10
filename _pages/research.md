---
layout: page
permalink: /research/
title: Research
nav: true
sort: 2
---

# Research
I have a broad research interest in developing statistical and computational methods to address cutting-edge public health problems by integrating information from diverse large datasets. My current focus is on racial- and ethnic-based health disparities, specifically, the development of trans-ethnic models for informing the prediction and biology of diseases.

---
__Risk prediction models for human diseases__

<div class="row justify-content-sm-center">
    <div class="col-sm-5 mt-3 mt-md-0">
        {% include figure.html path="assets/img/risk_prediction_long.png" title="Example Figure: Disease Risk Prediction" class: "img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-7 mt-3 mt-md-0">Large-scale epidemiologic studies, including modern genome-wide association studies (GWAS), are now rapidly leading to the identification of novel risk factors for human diseases. To summarize these findings into more effective strategies for reducing disease burden, a critical step is to advance risk prediction tools that predict future risk of diseases for healthy individuals and precision medicine to guide treatment strategies for targeted groups of patients.</div>
</div>  
&nbsp;

- __Jin, J.$$^*$$__, Agarwala, N.$$^*$$, Kundu, P.$$^*$$, Harvey, B., Zhang, Y., Wallace, E., , Chatterjee, N. Individual and Community-level Risk for COVID-19 Mortality in the United States. *Nature Medicine*, 27(2), 264-269, 2021.
[[PDF]](https://www.nature.com/articles/s41591-020-01191-8.pdf) [[Code]](https://github.com/Jin93/COVID19Risk)
[[Online Tools]](http://covid19risktools.com/)  
- Yu, Z., __Jin, J.__, Tin, A., Kottgen, A., Yu B., Chen J., Ballantyne, C.M., Hoogeveen, R.C., Arking, D.E., Chatterjee, N., Coresh, J., Grams, M.E., Coresh J. Polygenic Risk Scores for Kidney Function to the Circulating Proteome, and Incident Kidney Diseases: the Atherosclerosis Risk in Community Study. *Journal of the American Society of Nephrology*, 2021. DOI: 10.1681/ASN.2020111599.  
[[PDF]](https://jasn.asnjournals.org/content/jnephrol/early/2021/11/02/ASN.2020111599.full.pdf?with-ds=yes)  
(This work was selected by the American Society of Nephrology (ASN) as the “Best of ASN Journals” in 2021.)
- Rabinowitz, J.A., Jin, J., Kahn, G., Kuo, S.I., Campos, A., Renteria, M., Benke, K., Wilcox, H., Ialongo, N.S., Maher, B.S. and others. Genetic Propensity for Risky Behavior and Depression and Risk of Lifetime Suicide Attempt among Urban African Americans in Adolescence and Young Adulthood. *American Journal of Medical Genetics Part B: Neuropsychiatric Genetics*, 2021. DOI: 10.1002/ajmg.b.32866.
[[PDF]](https://onlinelibrary.wiley.com/doi/10.1002/ajmg.b.32866)
- __Jin, J.__, Taub, M., Conomos, M., Mathias, R., Chatterjee, N. Ancestry-specific Polygenic Risk Scores for Telomere Length and a Phenome-wide Association Study for Their Association with Risks of Age-related Diseases. 2021+
[[Slides]](https://drive.google.com/file/d/1Vlw5RDoXcznKk4_bp4bIl52PM_wJBnYd/view?usp=sharing)
- Zhang, H., Zhan, J., __Jin, J.__, Zhang, J., Ahearn, T., Zhi, Y., O' Connell, J., Jiang, Y., Koelsch, B., 23andMe research team, Lin, X., Garcia-Closas, M., Chatterjee, N. Developing Trans-ethnic Polygenic Risk Scores Using Empirical Bayes and Super Learning Algorithm. 2021+
[[Abstract]](https://eventpilotadmin.com/doc/clients/ASHG/ASHG21/library/pdf/abstract_odP2576.pdf?display)  
&nbsp;
  
---

__High-dimensional tests for disease-associated gene pathways__

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/T2DAG_long.png" title="T2DAG" class: "img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">A major task in genetic studies is to identify genes related to human traits/diseases. Compared to marginal analyses of individual genes, detecting gene pathway, i.e., gene sets with known interactions that collectively contribute to some biological functions, can provide more biologically meaningful results. Due to the typically limited sample sizes, such analyses are usually high-dimensional, where the existing tests tend to have compromised power since they do not or only inefficiently incorporate the external pathway information on gene interactions. </div>
</div>  
I collaborated with Dr. <a href="https://taryue.github.io/">Yue Wang</a> from Arizona State Univeristy and proposed a graph-informed test which efficiently leverages the auxiliary pathway information via structural equation modeling to improve the estimation of the precision matrix.  
&nbsp;


-	__Jin, J.__, Yue, W. T2-DAG: A Powerful Test for Differentially Expressed Gene Pathways via Graph-informed Structural Equation Modeling. *Bioinformatics*, btab770, 2021.
[[PDF]](https://academic.oup.com/bioinformatics/advance-article/doi/10.1093/bioinformatics/btab770/6424893?guestAccessKey=7cc27d27-ae5c-49e7-aad0-a5111fc6ac92)
[[Code]](https://github.com/Jin93/T2DAG)

&nbsp;

---

__Mendelian randomization (MR) analysis for latent exposures__

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/MRLE_long.png" title="MRLE" class: "img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">Recent MR research has focused on improving robustness to the presence of pleiotropic associations, by which genetic instruments can affect the outcome independent of the exposure and thus leading to the violation of key assumptions. I investigated a novel setting of pleiotropic association where genetic variants might be associated with multiple observed traits through an underlying latent exposure which may have a causal effect on the outcome.</div>
</div>
&nbsp;

-	__Jin, J.__, Qi, G., Yu, Z., Chatterjee, N. Mendelian Randomization Analysis Using Multiple Biomarkers of an Underlying Common Exposure. Under Revision.
[[PDF]](https://doi.org/10.1101/2021.02.05.429979)
[[Code]](https://github.com/Jin93/MRLE)
[[Slide]](https://drive.google.com/file/d/1VJJbCpMMm7qld0f0_qB9n32d4L6Om4XN/view?usp=sharing)



&nbsp;

---

__MpMRI-based classification of Prostate cancer (PCa)__

<div class="row justify-content-sm-center">
    <div class="col-sm-5 mt-3 mt-md-0">
        {% include figure.html path="assets/img/PCA_long.png" title="PCa detection" class: "img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-7 mt-3 mt-md-0">My research during the Ph.D. program focused on voxel-wise PCa detection using mpMRI, a critical tool in PCa diagnosis and management. MpMRI examinations are currently interpreted manually which is limited due to inter-reader variability. Automatic, quantitative predictive methods are thus proposed to address these limitations. We identified critical issues of the existing methods and developed scalable, high-field MRI-based Bayesian and machine learning-based classifers that can be used as non-invasive tools to assist clinicians with PCa diagnosis and treatment.</div>
</div>
&nbsp;

-	__Jin, J.__, Zhang, L., Leng, E., Metzger, G.J., Koopmeiners, J.S. Bayesian Spatial Models for Voxel-wise Prostate Cancer Classification Using Multi-parametric MRI Data. *Statistics in Medicine*, 1-17, 2021. DOI: https://doi.org/10.1002/sim.9245.
[[PDF]](https://arxiv.org/abs/2001.07316)
[[Code]](https://github.com/Jin93/Multi-Resolution-SL)
-	__Jin, J.__, Zhang, L., Leng, E., Metzger, G.J., Koopmeiners, J.S. A Multi-resolution Super Learner Algorithm for Voxel-wise Classification of Prostate Cancer Using Multi-parametric MRI. To appear in *Journal of Applied Statistics*, 2021.
[[PDF]](https://arxiv.org/pdf/2007.00816.pdf)
[[Code]](https://github.com/Jin93/Multi-Resolution-SL)
-	Leng, E., Spilseth, Leng, E., Henriksen, J.C., Rizzardi, A.E., __Jin, J.__, Nam, J.W., Brassuer, B.M., Johnson, A.D., Reder, N.P., Koopmeiners, J.S., Schmechel, S.C., Metzger, G.J.  Signature Maps for Automatic Identification of Prostate Cancer from Colorimetric Analysis of H&E-and IHC-stained Histopathological Specimens. *Scientific Reports*, 9(1), 1-12, 2019.
[[PDF]](https://www.nature.com/articles/s41598-019-43486-y)
-	__Jin, J.__, Zhang, L., Leng, E., Metzger, G.J., Koopmeiners, J.S. Detection of Prostate Cancer with Multiparametric MRI Utilizing the Anatomic Structure of the Prostate. *Statistics in medicine*, 37(22), 3214-3229, 2018.
[[PDF]](https://onlinelibrary.wiley.com/doi/abs/10.1002/sim.7810)
[[Code]](https://github.com/Jin93/PreliminaryPoC)
-	Leng, E., Spilseth, B., Zhang, L., __Jin, J.__, Koopmeiners, J.S., Metzger, G.J. Development of A Measure for Evaluating Lesion-wise Performance of CAD Algorithms in the Context of MpMRI Detection of Prostate Cancer. *Medical Physics*, 45(5), 2076-2088, 2018.
[[PDF]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6734092/)



&nbsp;

---

__Early-phase oncology trial design__

<div class="row justify-content-sm-center">
    <div class="col-sm-5 mt-3 mt-md-0">
        {% include figure.html path="assets/img/CBHM_long.png" title="Basket Trials" class: "img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-7 mt-3 mt-md-0">As oncology research are focusing more on the genomic aberrations potentially shared by multiple cancer types, basket trials have been proposed to assess the efficacy of a new treatment simultaneously on multiple cancer types. But even with shared genetic aberration, different cancers may respond to treatments differently. I collaborated with a research team at Sanofi to develop novel Bayesian methods for detecting treatment efficacy and proof of concept (PoC) in early-phase basket trials by flexible borrowing according to sample similarity measured by the distance between posterior distributions of the treatment effects.</div>
</div>
&nbsp;

-	__Jin, J.__, Riviere, M.K., Luo, X., Dong, Y. Bayesian Methods for the Analysis of Early-phase Oncology Basket Trials with Information Borrowing across Cancer Types. *Statistics in Medicine*. 39(25), 3459-3475, 2020.
[[PDF]](https://doi.org/10.1002/sim.8675)
[[Code]](https://github.com/Jin93/CBHM)
- __Jin, J.__, Liu, Q., Zheng, W., Shun, Z., Lin, T.T., Gao, L., Dong, Y. A Bayesian Method for the Detection of Proof of Concept in Early Phase Oncology Studies with a Basket Design. *Statistics in Biosciences*. 12, 167-179, 2020.
[[PDF]](https://link.springer.com/article/10.1007/s12561-020-09267-2)
[[Code]](https://github.com/Jin93/PreliminaryPoC)


