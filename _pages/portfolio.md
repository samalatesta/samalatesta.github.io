---
layout: archive
title: "Research & Software"
permalink: /research/
author_profile: true
---

<p>My research focuses on understanding how infectious diseases spread and developing statistical methods to analyze complex data. I study <strong>tuberculosis (TB)</strong> and <strong>methicillin-resistant <i>Staphylococcus aureus</i> (MRSA)</strong> transmission, combining epidemiologic and genomic data to uncover patterns of spread.</p>

<p>Much of my <strong>statistical methods</strong> work is done in collaboration with my thesis advisor, <strong>Laura White</strong>. Applied <strong>TB</strong> projects are conducted with <strong>Karen Jacobson's group</strong> at Boston Medical Center, and <strong>MRSA</strong> research is done with <strong>Ashlee Earl's group</strong> at the Broad Institute. Alongside these applied projects, I create statistical tools and open-source software to enable more accurate modeling, inference, and data sharing for infectious disease research. Below are selected projects and tools from these research areas.</p>

<!-- Statistical Methods -->
<h2>Statistical Methods</h2>
<div style="display: flex; flex-wrap: wrap; gap: 20px;">

  <div style="flex: 1 1 300px; border: 1px solid #ddd; border-radius: 12px; padding: 15px; box-shadow: 0 2px 5px rgba(0,0,0,0.1);">
    <h3>Data-Driven TB Disease Phenotypes</h3>
    <p>Developed <strong>TB-STATIS</strong>, a model that integrates clinical information (symptoms, smear, chest X-ray) to generate TB disease phenotypes and stratify patients.</p>
    <p><strong>Software:</strong> <a href="https://github.com/samalatesta/tbSTATIS">tbSTATIS</a></p>
  </div>

  <div style="flex: 1 1 300px; border: 1px solid #ddd; border-radius: 12px; padding: 15px; box-shadow: 0 2px 5px rgba(0,0,0,0.1);">
    <h3>Inferring Associations with Respondent-Driven Sampling Data</h3>
    <p>Developed a semi-parametric randomization test that accounts for the correlated nature of respondent-driven sampling data to accurately infer associations.</p>
    <p><strong>Software:</strong> <a href="https://github.com/samalatesta/RDSAssociation">RDSAssociation</a></p>
    <p><a href="https://academic.oup.com/jrsssc/article-abstract/74/2/429/7909014">Publication</a></p>
  </div>

  <div style="flex: 1 1 300px; border: 1px solid #ddd; border-radius: 12px; padding: 15px; box-shadow: 0 2px 5px rgba(0,0,0,0.1);">
    <h3>Multiple Imputation for Time-to-Event Data</h3>
    <p>Explored methods for handling missing data in repeated measures for time-to-event outcomes, motivated by the need to assess time to culture conversion in TB clinical trials.</p>
    <p><strong>Software:</strong> <a href="https://github.com/samalatesta/imputeTBculture">imputeTBculture</a></p>
    <p><a href="https://bmcmedresmethodol.biomedcentral.com/articles/10.1186/s12874-022-01782-8">Publication</a></p>
  </div>

</div>

<!-- TB Transmission -->
<h2>TB Transmission</h2>
<div style="display: flex; flex-wrap: wrap; gap: 20px;">

  <div style="flex: 1 1 300px; border: 1px solid #ddd; border-radius: 12px; padding: 15px; box-shadow: 0 2px 5px rgba(0,0,0,0.1);">
    <h3>Role of Reinfection in Sustaining TB Transmission</h3>
    <p>Developing a population-level mathematical model to quantify the role of reinfection in sustaining TB epidemics. Results inform strategies such as active case finding, vaccination, and preventive therapy in high- and low-burden settings.</p>
  </div>

  <div style="flex: 1 1 300px; border: 1px solid #ddd; border-radius: 12px; padding: 15px; box-shadow: 0 2px 5px rgba(0,0,0,0.1);">
    <h3>TB Transmission and Substance Use</h3>
    <p>Applying a machine learning method that integrates whole genome sequencing and metadata to explore TB transmission dynamics among people who smoke drugs in a rural community in South Africa.</p>
  </div>

</div>

<!-- MRSA -->
<h2>MRSA Transmission</h2>
<div style="display: flex; flex-wrap: wrap; gap: 20px;">

  <div style="flex: 1 1 300px; border: 1px solid #ddd; border-radius: 12px; padding: 15px; box-shadow: 0 2px 5px rgba(0,0,0,0.1);">
    <h3>MRSA Transmission in Nursing Homes</h3>
    <p>Studying the transmission of multidrug-resistant organisms (primarily MRSA) in nursing homes. Applying <strong>TransPhylo</strong> to identify transmission risk factors, evaluate decolonization strategies, and explore the impact of sampling in endemic settings.</p>
  </div>

</div>

<!-- Other Applied TB -->
<h2>Other Applied TB Projects</h2>
<div style="display: flex; flex-wrap: wrap; gap: 20px;">

  <div style="flex: 1 1 300px; border: 1px solid #ddd; border-radius: 12px; padding: 15px; box-shadow: 0 2px 5px rgba(0,0,0,0.1);">
    <h3>TB Prevalence Among People Who Smoke Drugs</h3>
    <p>Recruited 750 people who smoke drugs using respondent-driven sampling in a rural South African community. Estimated TB prevalence (~10%) was three times higher than community rates.</p>
    <p><a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5010346">Publication</a></p>
  </div>

</div>
