---
title: "AD Related Drugs"
categories:
  - Alzheimer's Disease
tags:
  - dementia
  - treatment pathways
  - drug-drug interactions
toc: true
---
 
## Paper Reading

### Treatment Pathways
   — defined here as the ordered sequence of medications that a patient is prescribed.
   {: .small}

> <font color='red'>Paper:</font> Hripcsak, George, et al. "[Characterizing treatment pathways at scale using the OHDSI network](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4941483/pdf/pnas.201510502.pdf)." Proceedings of the National Academy of Sciences 113.27 (2016): 7329-7336.
{: .small}

* Our aim was to reveal patterns and variation in treatment among data sources and diseases.
* The pathways revealed that the world is moving toward more consistent therapy over time across diseases and across locations, but significant heterogeneity remains among sources, pointing to challenges in generalizing clinical trial results. Diabetes favored a single first-line medication, metformin, to a much greater extent than hypertension or depression. About 10% of diabetes and depression patients and almost 25% of hypertension patients followed a treatment pathway that was unique within the cohort.
* Aside from factors such as sample size and underlying population (academic medical center versus general population), electronic health records data and administrative claims data revealed similar results. 
{: .small}

> <font color='red'>Paper:</font> Chen, Ruijun, et al. "[Treatment Patterns for Chronic Comorbid Conditions in Patients With Cancer Using a Large-Scale Observational Data Network](https://ascopubs.org/doi/pdf/10.1200/CCI.19.00107)." JCO Clinical Cancer Informatics (2020).
{: .small}

* To characterize real-world treatment patterns for the chronic, comorbid conditions of depression, hypertension, and type 2
diabetes mellitus in patients with cancer.
* We identified wide variations in the treatment of common comorbidities in patients with cancer.
* Implementation details
    * Study Population -- For each of chronic condition, entry into the subcohort was determined by the date of first treatment (as defined below) for the chronic disease, with at least 365 days of prior observation before first treatment and at least 365 days of follow-up time post-treatment. We required a diagnosis of cancer and of the chronic disease on or before the first treatment, as well as persistent treatment after initiation of the first treatment, defined as at least one exposure to treatment of the chronic disease during the 121-day to 240-day and the 241-day to 365-day periods postindex.
    * Treatment Pattern Analysis -- Please refer to the paper.
        * For each patient in the qualifying subcohorts, we identified the sequence of treatments to which they were exposed during the 12 months after first exposure. 
        * Treatments were analyzed at the RxNorm—the standard vocabulary for medications—ingredient level, which represents the primary active ingredient in the drug. The sequence was determined by ordering the dates of first exposure to each qualifying ingredient for the disease.
{: .small}



### Drug Repurposing for AD

> <font color='red'>Paper:</font> Fang, Jiansong, et al. "[Network-based Translation of GWAS Findings to Pathobiology and Drug Repurposing for Alzheimer's Disease](https://www.medrxiv.org/content/10.1101/2020.01.15.20017160v1.full.pdf)." medRxiv (2020).
{: .small}

* In summary, they present an integrated, network-based methodology to rapidly translate GWAS findings and multi-omics data to genotype-informed therapeutic discovery in AD.
* 现在假设，通过整合GWAS的发现和与人类相互作用网络模型相结合的多组学特征，系统地识别可能的致病基因，也将揭示AD中基于基因型的治疗发现的疾病特异性靶点。这种方法需要基因组、转录组、蛋白质组和人类蛋白质-蛋白质相互作用体的独特整合。specifically, they integrates GWAS findings, multi-omics data from brain samples of AD patients and preclinical AD models, drug-target networks, and the human protein-protein interactome, along with large-scale patient database validation and <cite>in vitro</cite> mechanistic observations in human microglia cells.  
* Data
    * Collection of GWAS SNPs from large-scale studies
    * Construction of human protein-protein interactome
    * Collection of functional genomics data
    * Collection of biological and functional data
        * Disease-associated genes from Open targets
        * Experimentally validated genes for Alzheimer’s disease
        * Brain specific expression
        * Gene Expression
* Through this approach, we identified 103 AD risk genes (ARGs) validated by various levels of pathobiological evidence in AD.
* Via network-based prediction and population-based validation, we then showed that pioglitazone (吡格列酮) usage is significantly associated with decreased risk of AD in a retrospective case-control validation.
吡格列酮是一种用于治疗2型糖尿病的过氧化物酶体增殖激活受体激动剂，而倾向评分匹配队列研究证实，与也用于治疗2型糖尿病的胰岛素促分泌药glipizide(格列吡嗪)相比，吡格列酮可降低AD风险。
{: .small}

### Drug-drug Interactions

> <font color='red'>Paper:</font> Bogetti-Salazar, Michele, et al. "[Severe potential drug-drug interactions in older adults with dementia and associated factors](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4763155/pdf/cln-71-01-017.pdf)." Clinics 71.1 (2016): 17-21.
{: .small}

* The main severe potential drug-drug interactions (DDIs) were caused by the combinations [citalopram](https://www.drugs.com/citalopram.html)/[antiplatelet](https://www.drugs.com/drug-class/antiplatelet-agents.html) (11.6%), [clopidogrel](https://www.drugs.com/mtm/clopidogrel.html)/[omeprazole](https://www.drugs.com/omeprazole.html) (6.1%), and clopidogrel/ aspirin (5.5%). 
* Antidepressants, antiplatelets, anti-psychotics and omeprazole were the drugs most commonly involved in severe potential drug-drug interactions. 
* Despite their frequent use, anti-dementia drugs were not involved in these interactions. 
* The number and type of medications taken, dementia severity and depression in patients in addition to caregiver burden should be considered to avoid possible drug interactions in this population.
* <font color='green'>Top ten severe potential DDIs (severe and contraindicated).</font>
{: .small}


