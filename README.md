# Hong Kong health care workers study

## 1. Study overview

Prior to widespread H1N1 vaccination, healthcare workers (HCWs) faced elevated infection risks, potentially endangering both themselves and vulnerable patients. Following the 2009 H1N1 pandemic, we conducted a serological study to estimate the true infection rate among HCWs, as many cases were missed by clinical reporting.

Between February and March 2010, we recruited unvaccinated HCWs from six public hospitals. We aimed to enroll at least 500 participants to provide reliable prevalence estimates. Serum samples were analyzed using a viral microneutralization (VN) assay (threshold ≥1:40 for seropositivity), chosen for its higher sensitivity compared to hemagglutination inhibition (HAI). Some samples were also tested via HAI for comparison.

## 2. Raw data

The latest version of the HCWs antibody study is available to download here:

-   [HCWs2010data](data/hcws2010.csv).

This version of the dataset covers the basic characteristics of HCWs, vaccine history, pH1N1 infection history, and serology results.

We provide our data under the [Open Data Commons Public Domain Dedication and License](%22http://www.opendatacommons.org/odc-public-domain-dedication-and-licence/%22), which is a version of open access for data. Under this licence we reserve no rights: there are no restrictions on use of our data, and no requirement to cite our work or this website. However we would anticipate that for academic purposes the standard practice of referencing sources would apply. We would like to hear from researchers who are using our data and we would be keen to work together on analyses.

## 3. Main findings

The primary findings from our main study have been published in [Zhou et al. (2011, JHI)](http://www.ncbi.nlm.nih.gov/pubmed/21501896). Our main findings were that age-specific antibody prevalence in HCWs did not significantly differ from the general population, suggesting no elevated occupational risk during the first pandemic wave.

Results described in Zhou et al. (2011) are reproduced in the following scripts which can be run in [R](http://www.r-project.org):

-   [Table 1](HCW_scripts/Table_1.r).

-   [Table 2](HCW_scripts/Table_2.r).

-   [Table 3](HCW_scripts/Table_3.r).

-   [Other results described in the manuscript text](HCW_scripts/Text_results.r).

## 4. Future work

We have further analyses underway using the data from our study. More details will follow later.

## Authors and investigators

The principal investigator of this study is [Ben Cowling](https://sph.hku.hk/en/Biography/Cowling-Benjamin-John) . The data were uploaded by [Ben Cowling](https://sph.hku.hk/en/Biography/Cowling-Benjamin-John) , and the scripts were written by Joey Zhou, Vicky Fang and [Ben Cowling](https://sph.hku.hk/en/Biography/Cowling-Benjamin-John).

## A comment on reproducible research

We fully support the [increasing calls](http://dx.doi.org/10.1097/EDE.0b013e318196784a) from the academic community for [epidemiologic analyses to be reproducible](http://dx.doi.org/10.1093/aje/kwj093) , and [raw data from randomized controlled trials to be published](http://dx.doi.org/10.1186/1745-6215-10-17), as a part of the wider scientific endeavour to replicate results. Another example of this recommendation is in the [Good Practice Guide for Quantitative Veterinary Epidemiology](http://www.qve-goodpracticeguide.org.uk/guide#TOC-2.4-Inputs). Here we have published the raw *anonymised* data from our household transmission study. We have also published scripts which allow the analyses in our published papers to be reproduced.

Thousands of local people have given their time, and their families', as part of their participation in our studies, all in the expectation that our research studies will add to medical and scientific knowledge. Participants should also expect that we will make the best possible use of the information that we have collected about them. It would be difficult to argue that facilitating best use of the data by the research community need not involve releasing raw data.

Publication of anonymised raw data has been approved by our local IRB and funding sources, and participants were advised that anonymised data would be published during the informed consent process. We anticipate that release of the raw data will:

-   Promote reproducibility of our results.

-   Allow other investigators to conduct their own analyses on our data.

-   Allow other investigators to compare our data with theirs, for example to explore similarities and differences between research findings.

-   Allow other investigators to prepare and plan for their own studies.

## Publications

1.  Zhou Y, Ng DMW, Seto WH, Ip DKM, Kwok HKH, Ma ESK, Ng S, Lau LLH, Wu JT, Peiris JSM, Cowling BJ. Seroprevalence of antibody to pandemic influenza A (H1N1) 2009 among healthcare workers after the first wave in Hong Kong. *Journal of Hospital Infection*, 2011 **78 (4)**:308-311. [[link]](http://www.journalofhospitalinfection.com/article/S0195-6701(11)00113-7/abstract) [[PubMed]](http://www.ncbi.nlm.nih.gov/pubmed/21501896).

## Acknowledgements

This project was funded by the Area of Excellence Scheme of the Hong Kong University Grants Committee (grant no. AoE/M-12/06) and the Research Fund for the Control of Infetious Disease, Food and Health Bureau, Government of the Hong Kong SAR (grant no. PHE-20).

[![Creative Commons License](https://i.creativecommons.org/l/by/3.0/80x15.png)](http://creativecommons.org/licenses/by/3.0/) This work is licensed under a [Creative Commons Attribution 3.0 Unported License](http://creativecommons.org/licenses/by/3.0/). It was written by [Ben Cowling](http://www.hku.hk/cmd/staff/bio/cowling.htm) (email).
