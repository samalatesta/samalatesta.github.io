---
layout: archive
title: ""
permalink: /research/
author_profile: true
---
<p align="center" style="display: flex; justify-content: center; gap: 20px; align-items: center;">

  <span style="background:white; padding:5px; height:80px; display:inline-flex; align-items:center;">
    <img src="../images/BOSTON_UNIV_CMYK.png" alt="BU SPH" style="height:100%; object-fit:contain;"/>
  </span>

  <span style="background:white; padding:5px; height:80px; display:inline-flex; align-items:center;">
    <img src="../images/bmc.png" alt="Boston Medical Center" style="height:100%; object-fit:contain;"/>
  </span>

  <span style="background:white; padding:5px; height:80px; display:inline-flex; align-items:center;">
    <img src="../images/broad.png" alt="Broad Institute" style="height:100%; object-fit:contain;"/>
  </span>

</p>
-----

## About My Work  
I am a **biostatistician and infectious disease researcher** focused on developing **statistical methods** and **modeling approaches** motivated by real-world data with the goal of producing tools and insights that inform public health and clinical decision-making. I work closely with clinicians, epidemiologists, and other scientists to ensure my methods are **clinically relevant**, while also developing **open-source software** to make these approaches broadly accessible to the research community.  

-----
## Training & Background  
I earned my PhD in Biostatistics from Boston University, where I worked with [Dr. Laura White](https://www.bu.edu/sph/profile/laura-white/) to develop statistical methods for questions in **tuberculosis (TB) epidemiology**. My doctoral research focused on integrating complex data sources and addressing methodological challenges in observational data to better understand TB dynamics in **high-risk populations**. I also collaborated with [Dr. Karen Jacobson](https://sites.bu.edu/jacobson/) at Boston Medical Center on applied TB studies in South Africa. 

-----
## Current Work  
As a **postdoctoral research fellow**, I study **infectious disease transmission** using **phylodynamics, mathematical modeling, and machine learning**. These approaches help investigate how pathogens spread and how interventions influence epidemic outcomes. I continue TB transmission collaborations with Dr. White and Dr. Jacobson. I have also expanded to work with [Dr. Ashlee Earl](https://www.broadinstitute.org/infectious-disease-and-microbiome/bacterial-genomics) at the Broad Institute on a project studying **methicillin-resistant *Staphylococcus aureus* (MRSA)** transmission in nursing homes in which we are leveraging **phylodynamic models** that **integrate genomic and epidemiological data**.  

-----
## Funding  
My postdoctoral training is supported by the **National Institute of Allergy and Infectious Diseases** (T32AI052074).  


<h2>Statistical Methods</h2>
<div style="display: flex; flex-wrap: wrap; gap: 20px;">

  <div style="flex: 1 1 300px; border: 1px solid #ddd; border-radius: 12px; padding: 15px; box-shadow: 0 2px 5px rgba(0,0,0,0.1);">
    <h3>Data-Driven TB Disease Phenotypes</h3>
    <p>Developed <strong>TB-STATIS</strong>, a model that integrates clinical information (symptoms, smear, chest X-ray) to generate TB disease phenotypes and stratify patients.</p>
    <p><strong>Software:</strong> <a href="https://github.com/samalatesta/tbSTATIS">tbSTATIS</a></p>
    <p><strong>Data Application:</strong> <a href="https://bmcinfectdis.biomedcentral.com/articles/10.1186/s12879-018-3396-y">TRUST study (a TB clinical cohort)</a> and the <a href="https://www.tballiance.org/trial/remoxtb/">REMox trial</a></p>
  </div>

  <div style="flex: 1 1 300px; border: 1px solid #ddd; border-radius: 12px; padding: 15px; box-shadow: 0 2px 5px rgba(0,0,0,0.1);">
    <h3>Inferring Associations with Respondent-Driven Sampling Data</h3>
    <p>Developed a semi-parametric randomization test that accounts for the correlated nature of respondent-driven sampling data to accurately infer associations.</p>
    <p><strong>Software:</strong> <a href="https://github.com/samalatesta/RDSAssociation">RDSAssociation</a></p>
    <p><strong>Data Application:</strong> <a href="https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0262440">TOTAL study</a></p>
    <p><a href="https://academic.oup.com/jrsssc/article-abstract/74/2/429/7909014">Publication</a></p>
  </div>

  <div style="flex: 1 1 300px; border: 1px solid #ddd; border-radius: 12px; padding: 15px; box-shadow: 0 2px 5px rgba(0,0,0,0.1);">
    <h3>Multiple Imputation for Time-to-Event Data</h3>
    <p>Explored methods for handling missing data in repeated measures for time-to-event outcomes, motivated by the need to assess time to culture conversion in TB clinical trials.</p>
    <p><strong>Software:</strong> <a href="https://github.com/samalatesta/imputeTBculture">imputeTBculture</a></p>
    <p><strong>Data Application:</strong> <a href="https://bmcinfectdis.biomedcentral.com/articles/10.1186/s12879-018-3396-y">TRUST study (a TB clinical cohort)</a></p>
    <p><a href="https://bmcmedresmethodol.biomedcentral.com/articles/10.1186/s12874-022-01782-8">Publication</a></p>
  </div>

</div>

<!-- TB Transmission -->
<h2>Modeling Infectious Disease Transmission</h2>
<div style="display: flex; flex-wrap: wrap; gap: 20px;">

  <div style="flex: 1 1 300px; border: 1px solid #ddd; border-radius: 12px; padding: 15px; box-shadow: 0 2px 5px rgba(0,0,0,0.1);">
    <h3>Role of Reinfection in Sustaining TB Transmission</h3>
    <p>Developing a population-level mathematical model to quantify the role of reinfection in sustaining TB epidemics. Results inform best intervention strategies such as active case finding, vaccination, and preventive therapy in high- and low-burden settings.</p>
  </div>

  <div style="flex: 1 1 300px; border: 1px solid #ddd; border-radius: 12px; padding: 15px; box-shadow: 0 2px 5px rgba(0,0,0,0.1);">
    <h3>TB Transmission and Substance Use</h3>
    <p>Applying <a href="https://academic.oup.com/ije/article/49/3/764/5811379">mlTransEpi</a>, a machine learning method that integrates whole genome sequencing and metadata, to explore TB transmission dynamics among people who smoke drugs in a rural community in South Africa.</p>
    <p><strong>Upcoming talk at the Union World Conference on Lung Health 2025</strong> </p>
  </div>

  <div style="flex: 1 1 300px; border: 1px solid #ddd; border-radius: 12px; padding: 15px; box-shadow: 0 2px 5px rgba(0,0,0,0.1);">
    <h3>MRSA Transmission in Nursing Homes</h3>
    <p>Studying the transmission of multidrug-resistant organisms (primarily MRSA) in <a href="https://academic.oup.com/cid/article/69/9/1566/5315468?login=false">nursing homes</a> in Orange County, California. Applying <a href="https://academic.oup.com/mbe/article/42/4/msaf083/8116767">TransPhylo2</a> to identify transmission risk factors, evaluate decolonization strategies, and explore the impact of sampling in endemic settings.</p>
  </div>
</div>

<!-- Other Applied TB -->
<h2>Other Projects</h2>
<div style="display: flex; flex-wrap: wrap; gap: 20px;">

  <div style="flex: 1 1 300px; border: 1px solid #ddd; border-radius: 12px; padding: 15px; box-shadow: 0 2px 5px rgba(0,0,0,0.1);">
    <h3>TB Prevalence Among People Who Smoke Drugs</h3> 
    <p>Estimated TB and HIV prevalence among people who smoke drugs in a rural community in South Africa using a <a href="https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0262440">respondent-driven sample</a> of 750 participants. TB prevalence was ~10% which was three times higher than community rates.</p>
    <p><a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5010346">Publication</a></p>
  </div>

</div>
