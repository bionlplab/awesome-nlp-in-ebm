# Awesome - Natural Language Processing in Support of Evidence-based Medicine

A curated list of Natural Language Processing (NLP) research papers in the field of Evidence-Based Medicine (EBM).  

This list is based on the scoping review “Natural Language Processing in Support of Evidence-Based Medicine: A Scoping Review” (ACL 2025 submission), which surveyed 129 peer-reviewed publications from 2019–2024.

The growth of medical literature demands automated tools to support clinicians in searching, appraising, synthesizing, and applying evidence in clinical practice. NLP is at the core of this transformation.

## Table of Contents

- [Ask – Search and Question Formulation](#1-ask--search-and-question-formulation)

- [Acquire – Extracting Evidence](#2-acquire--extracting-evidence)
  - [Entity Extraction and Normalization](#entity-extraction-and-normalization)
  - [Relation Extraction](#relation-extraction)

- [Appraise, Synthesize, and Summarization](#3-appraise-synthesize-and-summarization)
  - [Quality Assessment](#quality-assessment)
  - [Evidence Ranking and Screening](#evidence-ranking-and-screening)
  - [Evidence Synthesis](#evidence-synthesis)
  - [Evidence Summarization](#evidence-summarization)

- [Apply & Assess – Adoption, refinement and research](#4-apply--assess--adoption-refinement-and-research)
  - [Specialty-Specific adoption](#specialty-specific-adoption)
  - [Clinical Trial design and identification](#clinical-trial-design-and-identification)
  - [Drug Repurposing](#drug-repurposing)
  - [Question Answering](#question-answering)

- [EBM Benchmark Datasets](#ebm-benchmark-datasets)

## NLP techniques for EBM

### 1. Ask – Search and Question Formulation

Here is the Markdown table ordered by year (from latest to earliest):

| Paper | Venue | Date |
|:------|:------|:-----|
| [The Use of Generative AI for Scientific Literature Searches for Systematic Reviews: ChatGPT and Microsoft Bing AI Performance Evaluation](https://doi.org/10.2196/51187) | JMIR | 2024 |
| [Matching patients to clinical trials with large language models](https://doi.org/10.1038/s41467-024-53081-z) | Nature Communications | 2024 |
| [A span-based model for extracting overlapping PICO entities from randomized controlled trial publications](https://doi.org/10.1093/jamia/ocae065) | JAMIA | 2024 |

| [LeafAI: query generator for clinical cohort discovery rivaling a human programmer](https://doi.org/10.1093/jamia/ocad149) | JAMIA | 2023 |
| [Deep learning to refine the identification of high-quality clinical research articles from the biomedical literature: Performance evaluation](https://doi.org/10.1016/j.jbi.2023.104384) | JBI | 2023 |
| [ScanMedicine: An online search system for medical innovation](https://doi.org/10.1016/j.cct.2022.107042) | Contemporary Clinical Trials | 2023 |
| [Automatically Summarizing Evidence from Clinical Trials: A Prototype Highlighting Current Challenges](https://doi.org/10.18653/v1/2023.eacl-demo.27) | ACL | 2023 |
| [Investigation into Scaling-Up the SOAP Problem-Oriented Medical Record into a Clinical Case Study](https://doi.org/10.1109/ICHI57859.2023.00134) | ICHI | 2023 |
| [In a pilot study, automated real-time systematic review updates were feasible, accurate, and work-saving](https://doi.org/10.1016/j.jclinepi.2022.08.013) | J Clin Epidemiol | 2023 |
| [In Silico Drug Repurposing using Knowledge Graph Embeddings for Alzheimer's Disease](https://doi.org/10.1145/3569192.3569203) | ICBRA | 2022 |
| [State-of-the-Art Evidence Retriever for Precision Medicine: Algorithm Development and Validation](https://doi.org/10.2196/40743) | JMIR | 2022 |
| [Trial2Vec: Zero-Shot Clinical Trial Document Similarity Search using Self-Supervision](https://doi.org/10.18653/v1/2022.findings-emnlp.476) | EMNLP | 2022 |
| [Cohort-based Clinical Trial Retrieval](https://doi.org/10.1145/3503516.3503529) | ADCS | 2022 |
| [Improvement of intervention information detection for automated clinical literature screening during systematic review](https://doi.org/10.1016/j.jbi.2022.104185) | JBI | 2022 |
| [Preliminary Comparison of the Performance of the National Library of Medicine's Systematic Review Publication Type and the Sensitive Clinical Queries Filter for Systematic Reviews in PubMed](https://doi.org/10.5195/jmla.2022.1286) | JMLA | 2022 |
| [COVID-19 trial graph: a linked graph for COVID-19 clinical trials](https://doi.org/10.1093/jamia/ocab078) | JAMIA | 2021 |
| [Automate clinical evidence synthesis by linking trials to publications with text analytics](https://doi.org/10.1145/3459104.3459168) | ISEEIE | 2021 |
| [A probabilistic precision information retrieval model for personalized clinical trial recommendation based on heterogeneous data](https://doi.org/10.1109/icccnt51525.2021.9579891) | ICCCNT | 2021 |
| [Precision Medicine Search for Paediatric Oncology](https://doi.org/10.1145/3404835.3462792) | SIGIR | 2021 |
| [Evaluation of Applied Machine Learning for Health Misinformation Detection via Survey of Medical Professionals on Controversial Topics in Pediatrics](https://doi.org/10.1145/3472813.3472814) | ICMHI | 2021 |
| [Matching patients to clinical trials using semantically enriched document representation](https://doi.org/10.1016/j.jbi.2020.103406) | JBI | 2020 |
| [Natural Language Processing for Mimicking Clinical Trial Recruitment in Critical Care: A Semi-Automated Simulation Based on the LeoPARDS Trial](https://doi.org/10.1109/JBHI.2020.2977925) | IEEE JBHI | 2020 |
| [Clinical trial search: Using biomedical language understanding models for re-ranking](https://doi.org/10.1016/j.jbi.2020.103530) | JBI | 2020 |
| [A2A: a platform for research in biomedical literature search](https://doi.org/10.1186/s12859-020-03894-8) | BMC Bioinformatics | 2020 |
| [DQueST: dynamic questionnaire for search of clinical trials](https://doi.org/10.1093/jamia/ocz121) | JAMIA | 2019 |
| [Linking Knowledge Discovery In Clinical Notes And Massive Biomedical Literature Repositories](https://doi.org/10.1109/BIBM47256.2019.8983242) | BIBM | 2019 |
| [An Experimentation Platform for Precision Medicine](https://doi.org/10.1145/3331184.3331396) | SIGIR | 2019 |


### 2. Acquire – Extracting Evidence
#### Entity Extraction and Normalization
| Paper | Venue | Date |
|:------|:------|:-----|
| [Automatic categorization of self-acknowledged limitations in randomized controlled trial publications](https://doi.org/10.1016/j.jbi.2024.104628) | Journal of Biomedical Informatics | 2024 |
| [Utilizing Large Language Models for Enhanced Clinical Trial Matching: A Study on Automation in Patient Screening](https://doi.org/10.7759/cureus.60044) | Cureus | 2024 |
| [AutoCriteria: a generalizable clinical trial eligibility criteria extraction system powered by large language models](https://doi.org/10.1093/jamia/ocad218) | JAMIA | 2024 |
| [Automating Clinical Trial Eligibility Screening: Quantitative Analysis of GPT Models versus Human Expertise](https://doi.org/10.1145/3652037.3663922) | PETRA | 2024 |
| [Matching Patients to Accelerate Clinical Trials (MPACT): Enabling Technology for Oncology Clinical Trial Workflow](https://doi.org/10.3233/SHTI231132) | Studies in Health Technology and Informatics | 2024 |
| [The Use of Generative AI for Scientific Literature Searches for Systematic Reviews: ChatGPT and Microsoft Bing AI Performance Evaluation](https://doi.org/10.2196/51187) | Journal of Medical Internet Research | 2024 |
| [AlpaPICO: Extraction of PICO frames from clinical trial documents using LLMs](https://doi.org/10.1016/j.ymeth.2024.04.005) | Methods | 2024 |
| [BLINKtextsubscriptLSTM: BioLinkBERT and LSTM based approach for extraction of PICO frame from Clinical Trial Text](https://doi.org/10.1145/3632410.3632442) | CODS-COMAD | 2024 |
| [PICO to PICOS: Weak Supervision to Extend Datasets with New Labels](https://doi.org/10.3233/SHTI240775) | Studies in Health Technology and Informatics | 2024 |
| [TCGA-Reports: A machine-readable pathology report resource for benchmarking text-based AI models](https://doi.org/10.1016/j.patter.2024.100933) | Patterns | 2024 |
| [Optimizing Clinical Trial Eligibility Design Using Natural Language Processing Models and Real-World Data: Algorithm Development and Validation](https://doi.org/10.2196/50800) | Journal of Medical Internet Research | 2024 |
| [Generative AI for evidence-based medicine: A PICO GenAI for Synthesizing Clinical Case Reports](https://doi.org/10.1109/icc51166.2024.10622271) | IEEE ICC | 2024 |
| [Not so weak PICO:leveraging weak supervision for participants, interventions, and outcomes recognition for systematic review automatio](https://doi.org/10.1093/jamiaopen/ooac107) | JAMIA Open | 2023 |
| [LeafAI: query generator for clinical cohort discovery rivaling a human programmer](https://doi.org/10.1093/jamia/ocad149) | JAMIA | 2023 |
| [Automatic knowledge graph population with model-complete text comprehension for pre-clinical outcomes in the field of spinal cord injury](https://doi.org/10.1016/j.artmed.2023.102491) | Artificial Intelligence in Medicine | 2023 |
| [Towards precise PICO extraction from abstracts of randomized controlled trials using a section-specific learning approach](https://doi.org/10.1093/bioinformatics/btad542) | Bioinformatics | 2023 |
| [EvidenceMap:a three-level knowledge representation for medical evidence computation and comprehension](https://doi.org/10.1093/jamia/ocad036) | JAMIA | 2023 |
| [Automated Matching of Patients to Clinical Trials: A Patient-Centric Natural Language Processing Approach for Pediatric Leukemia](https://doi.org/10.1200/CCI.23.00009) | JCO Clinical Cancer Informatics | 2023 |
| [In a pilot study, automated real-time systematic review updates were feasible, accurate, and work-saving](https://doi.org/10.1016/j.jclinepi.2022.08.013) | Journal of Clinical Epidemiology | 2023 |
| [Parsable Clinical Trial Eligibility Criteria Representation Using Natural Language Processing](https://pubmed.ncbi.nlm.nih.gov/37128426/) | AMIA | 2023 |
| [Piloting an automated clinical trial eligibility surveillance and provider alert system based on artificial intelligence and standard data models](https://doi.org/10.1186/s12874-023-01916-6) | BMC Medical Research Methodology | 2023 |
| [Controversial Trials First: Identifying Disagreement Between Clinical Guidelines and New Evidence](https://pubmed.ncbi.nlm.nih.gov/35308948/) | AMIA | 2022 |
| [In Silico Drug Repurposing using Knowledge Graph Embeddings](https://doi.org/10.1145/3569192.3569203) | ICBRA | 2022 |
| [The Leaf Clinical Trials Corpus: a new resource for query generation from clinical trial eligibility criteria](https://doi.org/10.1038/s41597-022-01521-0) | Scientific Data (Nature) | 2022 |
| [Exploration of biomedical knowledge for recurrent glioblastoma using natural language processing deep learning models](https://doi.org/10.1186/s12911-022-02003-4) | BMC Medical Informatics and Decision Making | 2022 |
| [Implementation of Machine Learning Pipelines for Clinical Practice: Development and Validation Study](https://doi.org/10.2196/37833) | Journal of Medical Internet Research | 2022 |
| [A comparative study of pre-trained language models for named entity recognition in clinical trial eligibility criteria from multiple corpora](https://doi.org/10.1186/s12911-022-01967-7) | BMC Medical Informatics and Decision Making | 2022 |
| [Evaluation of Criteria2Query: Towards Augmented Intelligence for Cohort Identification](https://doi.org/10.3233/SHTI220082) | Studies in Health Technology and Informatics | 2022 |
| [Improvement of intervention information detection for automated clinical literature screening during systematic review](https://doi.org/10.1016/j.jbi.2022.104185) | Journal of Biomedical Informatics | 2022 |
| [srBERT: automatic article classification model for systematic review using BERT](https://doi.org/10.1186/s13643-021-01763-w) | BMC Systematic Reviews | 2021 |
| [Creating and evaluating chatbots as eligibility assistants for clinical trials](https://doi.org/10.1145/3403575) | ACM Transactions on Computing for Healthcare | 2021 |
| [Developing a fully automated evidence synthesis tool for identifying, assessing and collating the evidence](https://doi.org/10.1136/bmjebm-2018-111126) | BMJ Evidence-Based Medicine | 2021 |
| [MSˆ2: Multi-Document Summarization of Medical Studies](https://doi.org/10.18653/v1/2021.emnlp-main.594) | EMNLP | 2021 |
| [UMLS-based data augmentation for natural language processing of clinical research literature](https://doi.org/10.1093/jamia/ocaa309) | JAMIA | 2021 |
| [Precision Medicine Search for Paediatric Oncology](https://doi.org/10.1145/3404835.3462792) | SIGIR | 2021 |
| [Data Mining of Free-Text Responses: An Innovative Approach to Analyzing Patient Perspectives on Treatment for Chronic Rhinosinusitis with Nasal Polyps in a Phase IIa Proof-of-Concept Study for Dupilumab](https://doi.org/10.2147/PPA.S320242) | Patient Preference and Adherence | 2021 |
| [A knowledge base of clinical trial eligibility criteria](https://doi.org/10.1016/j.jbi.2021.103771) | Journal of Biomedical Informatics | 2021 |
| [Evaluation of an artificial intelligence clinical trial matching system in Australian lung cancer patients](https://doi.org/10.1093/jamiaopen/ooaa002) | JAMIA Open | 2020 |
| [Artificial intelligence tool for optimizing eligibility screening for clinical trials in a large community cancer center](https://doi.org/10.1200/CCI.19.00079) | JCO Clinical Cancer Informatics | 2020 |
| [Machine Learning Assisted Citation Screening for Systematic Reviews](https://doi.org/10.3233/SHTI200171) | Studies in Health Technology and Informatics | 2020 |
| [The anatomy of the SARS-CoV-2 biomedical literature](https://doi.org/10.2196/21169) | Journal of Medical Internet Research | 2020 |
| [Matching patients to clinical trials using semantically enriched document representation](https://doi.org/10.1016/j.jbi.2020.103406) | Journal of Biomedical Informatics | 2020 |
| [Clinical trial search: Using biomedical language understanding models for re-ranking](https://doi.org/10.1016/j.jbi.2020.103530) | Journal of Biomedical Informatics | 2020 |
| [Natural Language Processing for Mimicking Clinical Trial Recruitment in Critical Care](https://doi.org/10.1109/JBHI.2020.2977925) | IEEE Journal of Biomedical and Health Informatics | 2020 |
| [Improving Disease Named Entity Recognition for Clinical Trial Matching](https://doi.org/10.1109/BIBM47256.2019.8983421) | BIBM | 2019 |
| [Linking Knowledge Discovery In Clinical Notes And Massive Biomedical Literature Repositories](https://doi.org/10.1109/BIBM47256.2019.8983242) | BIBM | 2019 |
| [Improving reference prioritisation with PICO recognition](https://doi.org/10.1186/s12911-019-0992-8) | BMC Medical Informatics and Decision Making | 2019 |
| [An approach for transgender population information extraction and summarization from clinical trial text](https://doi.org/10.1186/s12911-019-0768-1) | BMC Medical Informatics and Decision Making | 2019 |
| [Medical Knowledge Infused Convolutional Neural Networks for Cohort Selection in Clinical Trials](https://doi.org/10.1093/jamia/ocz128) | JAMIA | 2019 |
| [Clinical trial cohort selection based on multi-level rule-based natural language processing system](https://doi.org/10.1093/jamia/ocz109) | JAMIA | 2019 |
| [Extractive summarization of clinical trial descriptions](https://doi.org/10.1016/j.ijmedinf.2019.05.019) | International Journal of Medical Informatics | 2019 |
| [Pretraining to recognize PICO Elements from Randomized Controlled Trial Literature](https://doi.org/10.3233/SHTI190209) | Studies in Health Technology and Informatics | 2019 |
| [DQueST: dynamic questionnaire for search of clinical trials](https://doi.org/10.1093/jamia/ocz121) | JAMIA | 2019 |
| [Data-driven method to enhance craniofacial and oral phenotype vocabularies](https://doi.org/10.1016/j.adaj.2019.05.029) | Journal of the American Dental Association | 2019 |
| [Impact of size, location, symptomatic-nature and gender on the rupture of saccular intracranial aneurysms](https://doi.org/10.1109/ASONAM.2018.8508274) | ASONAM | 2018 |


#### Relation Extraction

| Paper | Venue | Date |
|:------|:------|:-----|
| [AutoTrial: Prompting Language Models for Clinical Trial Design](https://doi.org/10.18653/v1/2023.emnlp-main.766) | EMNLP | 2023 |
| [LeafAI: query generator for clinical cohort discovery rivaling a human programmer](https://doi.org/10.1093/jamia/ocad149) | JAMIA | 2023 |
| [Controversial Trials First: Identifying Disagreement Between Clinical Guidelines and New Evidence](https://pubmed.ncbi.nlm.nih.gov/35308948/) | AMIA | 2022 |
| [The Leaf Clinical Trials Corpus: a new resource for query generation from clinical trial eligibility criteria](https://doi.org/10.1038/s41597-022-01521-0) | Scientific Data | 2022 |
| [Evaluation of Criteria2Query: Towards Augmented Intelligence for Cohort Identification](https://doi.org/10.3233/SHTI220082) | MedInfo | 2022 |
| [Knowledge graph based platform of COVID-19 drugs and symptoms](https://doi.org/10.1145/3487351.3489484) | ASONAM | 2021 |
| [Enhancing evidence-based medicine with natural language argumentative analysis of clinical trials](https://doi.org/10.1016/j.artmed.2021.102098) | Artificial Intelligence in Medicine | 2021 |
| [A knowledge base of clinical trial eligibility criteria](https://doi.org/10.1016/j.jbi.2021.103771) | Journal of Biomedical Informatics | 2021 |
| [MS²: Multi-Document Summarization of Medical Studies](https://doi.org/10.18653/v1/2021.emnlp-main.594) | EMNLP | 2021 |
| [srBERT: automatic article classification model for systematic review using BERT](https://doi.org/10.1186/s13643-021-01763-w) | Systematic Reviews | 2021 |
| [Linking Knowledge Discovery In Clinical Notes And Massive Biomedical Literature Repositories](https://doi.org/10.1109/BIBM47256.2019.8983242) | BIBM | 2019 |
| [An approach for transgender population information extraction and summarization from clinical trial text](https://doi.org/10.1186/s12911-019-0768-1) | BMC Medical Informatics and Decision Making | 2019 |



### 3. Appraise, Synthesize, and Summarization
#### Quality Assessment
| Paper | Venue | Date |
|:------|:------|:-----|
| [Machine Learning Assisted Citation Screening for Systematic Reviews](https://doi.org/10.3233/SHTI200171) | Studies in Health Technology and Informatics | 2020 |
(https://doi.org/10.2196/51187) | Journal of Medical Internet Research | 2024 |
| [Automatic categorization of self-acknowledged limitations in randomized controlled trial publications](https://doi.org/10.1016/j.jbi.2024.104628) | Journal of Biomedical Informatics | 2024 |
| [Utilizing ChatGPT as a scientific reasoning engine to differentiate conflicting evidence and summarize challenges in controversial clinical questions](https://doi.org/10.1093/jamia/ocae100) | JAMIA | 2024 |
| [Deep learning to refine the identification of high-quality clinical research articles from the biomedical literature: Performance evaluation](https://doi.org/10.1016/j.jbi.2023.104384) | Journal of Biomedical Informatics | 2023 |
| [OncoCTMiner: streamlining precision oncology trial matching via molecular profile analysis](https://doi.org/10.1093/database/baad077) | Oxford Database | 2023 |
| [The Use of Generative AI for Scientific Literature Searches for Systematic Reviews: ChatGPT and Microsoft Bing AI Performance Evaluation]
| [State-of-the-Art Evidence Retriever for Precision Medicine: Algorithm Development and Validation](https://doi.org/10.2196/40743) | Journal of Medical Internet Research | 2022 |
| [Validating GAN-BioBERT: A Methodology for Assessing Reporting Trends in Clinical Trials](https://doi.org/10.3389/fdgth.2022.878369) | Frontiers in Digital Health | 2022 |
| [Transformer-based named entity recognition for parsing clinical trial eligibility criteria](https://doi.org/10.1145/3459930.3469560) | BCB | 2021 |
| [Developing a fully automated evidence synthesis tool for identifying, assessing and collating the evidence](https://doi.org/10.1136/bmjebm-2018-111126) | BMJ Evidence-Based Medicine | 2021 |
| [Towards Automated Detection of Contradictory Research Claims in Medical Literature Using Deep Learning Approach](https://doi.org/10.1109/CAMP51653.2021.9498061) | CAMP | 2021 |


#### Evidence Ranking and Screening
| Paper | Venue | Date |
|:------|:------|:-----|
| [AutoCriteria: a generalizable clinical trial eligibility criteria extraction system powered by large language models](https://doi.org/10.1093/jamia/ocad218) | JAMIA | 2024 |
| [Towards autonomous living meta-analyses: A framework for automation of systematic review and meta-analyses](https://doi.org/10.3233/SHTI240427) | Studies in Health Technology and Informatics | 2024 |
| [Matching patients to clinical trials with large language models](https://www.nature.com/articles/s41467-024-53081-z) | Nature Communications | 2024 |
| [Using artificial intelligence to identify drugs for repurposing to treat l-DOPA induced dyskinesia](https://doi.org/10.1016/j.neuropharm.2024.109880) | Neuropharmacology | 2024 |
| [OncoCTMiner: streamlining precision oncology trial matching via molecular profile analysis](https://doi.org/10.1093/database/baad077) | Oxford Database | 2023 |
| [Piloting an automated clinical trial eligibility surveillance and provider alert system based on artificial intelligence and standard data models](https://doi.org/https://doi.org/10.1186/s12874-023-01916-6) | BMC Medical Research Methodology | 2023 |
| [Preliminary Comparison of the Performance of the National Library of Medicine's Systematic Review Publication Type and the Sensitive Clinical Queries Filter for Systematic Reviews in PubMed](https://doi.org/10.5195/jmla.2022.1286) | J Med Libr Assoc | 2022 |
| [Cohort-based Clinical Trial Retrieval](https://doi.org/10.1145/3503516.3503529) | ADCS | 2022 |
| [srBERT: automatic article classification model for systematic review using BERT](https://doi.org/10.1186/s13643-021-01763-w) | Syst Rev | 2021 |
| [Automate clinical evidence synthesis by linking trials to publications with text analytics](https://doi.org/10.1145/3459104.3459168) | ISEEIE | 2021 |
| [A probabilistic precision information retrieval model for personalized clinical trial recommendation based on heterogeneous data](https://doi.org/10.1109/icccnt51525.2021.9579891) | ICCCNT | 2021 |
| [Artificial intelligence clinical evidence engine for automatic identification, prioritization, and extraction of relevant clinical oncology research](https://doi.org/10.1200/CCI.20.00087) | JCO Clinical Cancer Informatics | 2021 |
| [The anatomy of the SARS-CoV-2 biomedical literature: Introducing the CovidX network algorithm for drug repurposing recommendation](https://doi.org/10.2196/21169) | Journal of Medical Internet Research | 2020 |
| [Clinical trial search: Using biomedical language understanding models for re-ranking](https://doi.org/10.1016/j.jbi.2020.103530) | Journal of Biomedical Informatics | 2020 |
| [Improving reference prioritisation with PICO recognition](https://doi.org/10.1186/s12911-019-0992-8) | BMC Medical Informatics and Decision Making | 2019 |
| [An Experimentation Platform for Precision Medicine](https://doi.org/10.1145/3331184.3331396) | SIGIR | 2019 |
| [Measuring the impact of screening automation on meta-analyses of diagnostic test accuracy](https://doi.org/10.1186/s13643-019-1162-x) | Syst Rev | 2019 |


#### Evidence Synthesis
| Paper | Venue | Date |
|:------|:------|:-----|
| [Utilizing ChatGPT as a scientific reasoning engine to differentiate conflicting evidence and summarize challenges in controversial clinical questions](https://doi.org/10.1093/jamia/ocae100) | JAMIA | 2024 |
| [Generative AI for evidence-based medicine: A PICO GenAI for synthesizing clinical case reports](https://doi.org/10.1109/icc51166.2024.10622271) | ICC | 2024 |
| [Towards autonomous living meta-analyses: A framework for automation of systematic review and meta-analyses](https://doi.org/10.3233/SHTI240427) | Studies in Health Technology and Informatics | 2024 |
| [In a pilot study, automated real-time systematic review updates were feasible, accurate, and work-saving](https://doi.org/10.1016/j.jclinepi.2022.08.013) | Journal of Clinical Epidemiology | 2023 |
| [Automatic knowledge graph population with model-complete text comprehension for pre-clinical outcomes in the field of spinal cord injury](https://doi.org/10.1016/j.artmed.2023.102491) | Artificial Intelligence in Medicine | 2023 |
| [EvidenceMap: a three-level knowledge representation for medical evidence computation and comprehension](https://doi.org/10.1093/jamia/ocad036) | JAMIA | 2023 |
| [AutoTrial: Prompting Language Models for Clinical Trial Design](https://doi.org/10.18653/v1/2023.emnlp-main.766) | EMNLP | 2023 |
| [Automatic data extraction to support meta-analysis statistical analysis: a case study on breast cancer](https://doi.org/10.1186/s12911-022-01897-4) | BMC Medical Informatics and Decision Making | 2022 |
| [Developing a fully automated evidence synthesis tool for identifying, assessing and collating the evidence](https://doi.org/10.1136/bmjebm-2018-111126) | BMJ Evidence-Based Medicine | 2021 |
| [Machine Learning Assisted Citation Screening for Systematic Reviews](https://doi.org/10.3233/SHTI200171) | Studies in Health Technology and Informatics | 2020 |


#### Evidence Summarization
| Paper | Venue | Date |
|:------|:------|:-----|
| [TriSum: Learning summarization ability from large language models with structured rationale](https://doi.org/10.18653/v1/2024.naacl-long.154) | NAACL | 2024 |
| [Utilizing ChatGPT as a scientific reasoning engine to differentiate conflicting evidence and summarize challenges in controversial clinical questions](https://doi.org/10.1093/jamia/ocae100) | JAMIA | 2024 |
| [Automatically Summarizing Evidence from Clinical Trials: A Prototype Highlighting Current Challenges](https://doi.org/10.18653/v1/2023.eacl-demo.27) | ACL | 2023 |
| [Exploring ChatGPT's potential in facilitating adaptation of clinical guidelines: A case study of Diabetic Ketoacidosis guidelines](https://doi.org/10.7759/cureus.38784) | Cureus | 2023 |
| [EvidenceMap: a three-level knowledge representation for medical evidence computation and comprehension](https://doi.org/10.1093/jamia/ocad036) | JAMIA | 2023 |
| [Text summarization of medical documents using abstractive techniques](https://doi.org/10.1109/icaaic56838.2023.10140885) | ICAAIC | 2023 |
| [Integrating a PICO clinical questioning to the QL4POMR framework for building evidence-based clinical case reports](https://doi.org/10.1109/bigdata59044.2023.10386854) | IEEE Big Data | 2023 |
| [Pre-trained language models with domain knowledge for biomedical extractive summarization](https://doi.org/10.1016/j.knosys.2022.109460) | Knowledge-Based Systems | 2022 |
| [MSˆ2: Multi-Document Summarization of Medical Studies](https://doi.org/10.18653/v1/2021.emnlp-main.594) | EMNLP | 2021 |
| [Knowledge graph based platform of COVID-19 drugs and symptoms](https://doi.org/10.1145/3487351.3489484) | ASONAM | 2021 |
| [A light-weight text summarization system for fast access to medical evidence](https://doi.org/10.3389/fdgth.2020.585559) | Frontiers in Digital Health | 2020 |
| [An approach for transgender population information extraction and summarization from clinical trial text](https://doi.org/10.1186/s12911-019-0768-1) | BMC Medical Informatics and Decision Making | 2019 |
| [Extractive summarization of clinical trial descriptions](https://doi.org/10.1016/j.ijmedinf.2019.05.019) | International Journal of Medical Informatics | 2019 |



### 4. Apply & Assess – Adoption, refinement and research
#### Clinical Trial design and identification
| Paper | Venue | Date |
|:------|:------|:-----|
| [Utilizing Large Language Models for Enhanced Clinical Trial Matching: A Study on Automation in Patient Screening](https://doi.org/10.7759/cureus.60044) | Cureus | 2024 |
| [Natural language processing for adjudication of heart failure in a multicenter clinical trial: A secondary analysis of a randomized clinical trial](https://doi.org/10.1001/jamacardio.2023.4859) | JAMA Cardiology | 2024 |
| [Automating clinical trial eligibility screening: Quantitative analysis of GPT Models versus Human Expertise](https://doi.org/10.1145/3652037.3663922) | PETRA | 2024 |
| [Matching Patients to Accelerate Clinical Trials (MPACT) Enabling Technology for Oncology Clinical Trial Workflow](https://doi.org/10.3233/SHTI231132) | Studies in Health Technology and Informatics | 2024 |
| [Optimizing Clinical Trial Eligibility Design Using Natural Language Processing Models and Real-World Data: Algorithm Development and Validation](https://doi.org/10.2196/50800) | Journal of Medical Internet Research | 2024 |
| [Automating clinical trial matches via natural language processing of synthetic electronic health records and clinical trial eligibility criteria](https://pubmed.ncbi.nlm.nih.gov/38827083/) | AMIA | 2024 |
| [Distilling large language models for matching patients to clinical trials](https://doi.org/10.1093/jamia/ocae073) | JAMIA | 2024 |
| [Matching patients to clinical trials with large language models](https://doi.org/10.1038/s41467-024-53081-z) | Nature Communications | 2024 |
| [Text classification of cancer clinical trial eligibility criteria](https://pmc.ncbi.nlm.nih.gov/articles/PMC10785908/) | AMIA | 2024 |
| [Large Language Models for Healthcare Data Augmentation: An Example on Patient-Trial Matching](https://pmc.ncbi.nlm.nih.gov/articles/PMC10785941/) | AMIA | 2024 |
| [LeafAI: query generator for clinical cohort discovery rivaling a human programmer](https://doi.org/10.1093/jamia/ocad149) | JAMIA | 2023 |
| [Automatic knowledge graph population with model-complete text comprehension for pre-clinical outcomes in the field of spinal cord injury](https://doi.org/10.1016/j.artmed.2023.102491) | Artificial Intelligence in Medicine | 2023 |
| [Automated Matching of Patients to Clinical Trials: A Patient-Centric Natural Language Processing Approach for Pediatric Leukemia](https://doi.org/10.1200/CCI.23.00009) | JCO Clinical Cancer Informatics | 2023 |
| [Parsable Clinical Trial Eligibility Criteria Representation Using Natural Language Processing](https://pubmed.ncbi.nlm.nih.gov/37128426/) | AMIA | 2023 |
| [Piloting an automated clinical trial eligibility surveillance and provider alert system based on artificial intelligence and standard data models](https://doi.org/https://doi.org/10.1186/s12874-023-01916-6) | BMC Medical Research Methodology | 2023 |
| [Parsing Clinical Trial Eligibility Criteria for Cohort Query by a Multi-Input Multi-Output Sequence Labeling Model](https://doi.org/10.1109/BIBM58861.2023.10385876) | BIBM | 2023 |
| [Automatic Assessment of Patient Eligibility by Utilizing NLP and Rule-Based Analysis](https://doi.org/10.1109/EMBC40787.2023.10340494) | EMBC | 2023 |
| [AutoTrial: Prompting Language Models for Clinical Trial Design](https://doi.org/10.18653/v1/2023.emnlp-main.766) | EMNLP | 2023 |
| [Implementation of Machine Learning Pipelines for Clinical Practice: Development and Validation Study](https://doi.org/10.2196/37833) | Journal of Medical Internet Research | 2022 |
| [The Leaf Clinical Trials Corpus: a new resource for query generation from clinical trial eligibility criteria](https://doi.org/10.1038/s41597-022-01521-0) | Scientific Data | 2022 |
| [Cohort-based Clinical Trial Retrieval](https://doi.org/10.1145/3503516.3503529) | ADCS | 2022 |
| [A comparative study of pre-trained language models for named entity recognition in clinical trial eligibility criteria from multiple corpora](https://doi.org/10.1186/s12911-022-01967-7) | BMC Medical Informatics and Decision Making | 2022 |
| [Evaluation of Criteria2Query: Towards Augmented Intelligence for Cohort Identification](https://doi.org/10.3233/SHTI220082) | Studies in Health Technology and Informatics | 2022 |
| [Improving the Efficiency of Clinical Trial Recruitment Using an Ensemble Machine Learning to Assist With Eligibility Screening](https://doi.org/10.1002/acr2.11289) | ACR Open Rheumatology | 2021 |
| [Creating and evaluating chatbots as eligibility assistants for clinical trials: An active deep learning approach towards user-centered classification](https://doi.org/10.1145/3403575) | ACM Transactions on Computing for Healthcare | 2021 |
| [EMR2vec: Bridging the gap between patient data and clinical trial](https://doi.org/10.1016/j.cie.2021.107236) | Computers & Industrial Engineering | 2021 |
| [A probabilistic precision information retrieval model for personalized clinical trial recommendation based on heterogeneous data](https://doi.org/10.1109/icccnt51525.2021.9579891) | ICCCNT | 2021 |
| [A knowledge base of clinical trial eligibility criteria](https://doi.org/10.1016/j.jbi.2021.103771) | Journal of Biomedical Informatics | 2021 |
| [Transformer-based named entity recognition for parsing clinical trial eligibility criteria](https://doi.org/10.1145/3459930.3469560) | BCB | 2021 |
| [Batch enrollment for an artificial intelligence-guided intervention to lower neurologic events in patients with undiagnosed atrial fibrillation: rationale and design of a digital clinical trial](https://doi.org/10.1016/j.ahj.2021.05.006) | American Heart Journal | 2021 |
| [Evaluation of an artificial intelligence clinical trial matching system in Australian lung cancer patients](https://doi.org/10.1093/jamiaopen/ooaa002) | JAMIA Open | 2020 |
| [Artificial intelligence tool for optimizing eligibility screening for clinical trials in a large community cancer center](https://doi.org/10.1200/CCI.19.00079) | JCO Clinical Cancer Informatics | 2020 |
| [Matching patients to clinical trials using semantically enriched document representation](https://doi.org/10.1016/j.jbi.2020.103406) | Journal of Biomedical Informatics | 2020 |
| [Chia, a large annotated corpus of clinical trial eligibility criteria](https://doi.org/10.1038/s41597-020-00620-0) | Scientific Data | 2020 |
| [Natural Language Processing for Mimicking Clinical Trial Recruitment in Critical Care: A Semi-Automated Simulation Based on the LeoPARDS Trial](https://doi.org/10.1109/JBHI.2020.2977925) | IEEE Journal of Biomedical and Health Informatics | 2020 |
| [Improving Disease Named Entity Recognition for Clinical Trial Matching](https://doi.org/10.1109/BIBM47256.2019.8983421) | BIBM | 2019 |
| [An approach for transgender population information extraction and summarization from clinical trial text](https://doi.org/10.1186/s12911-019-0768-1) | BMC Medical Informatics and Decision Making | 2019 |
| [Medical Knowledge Infused Convolutional Neural Networks for Cohort Selection in Clinical Trials](https://doi.org/10.1093/jamia/ocz128) | JAMIA | 2019 |
| [Clinical trial cohort selection based on multi-level rule-based natural language processing system](https://doi.org/10.1093/jamia/ocz109) | JAMIA | 2019 |
| [Cohort selection for clinical trials using deep learning models](https://doi.org/10.1093/jamia/ocz139) | JAMIA | 2019 |
| [Cohort Selection for Clinical Trials From Longitudinal Patient Records: Text Mining Approach](https://doi.org/10.2196/15980) | Journal of Medical Internet Research | 2019 |
| [Hybrid bag of approaches to characterize selection criteria for cohort identification](https://doi.org/10.1093/jamia/ocz079) | JAMIA | 2019 |
| [A Real-Time Automated Patient Screening System for Clinical Trials Eligibility in an Emergency Department: Design and Evaluation](https://doi.org/10.2196/14185) | Journal of Medical Internet Research | 2019 |


#### Question Answering
| Paper | Venue | Date |
|:-----|:-----|:-----|
| [Assessment of a Large Language Model's Responses to Questions and Cases About Glaucoma and Retina Management](https://doi.org/10.1001/jamaophthalmol.2023.6917) | JAMA Ophthalmology | 2024 |
| [TriSum: Learning summarization ability from large language models with structured rationale](https://doi.org/10.18653/v1/2024.naacl-long.154) | NAACL | 2024 |
| [Generative AI for evidence-based medicine: A PICO GenAI for synthesizing clinical case reports](https://doi.org/10.1109/icc51166.2024.10622271) | IEEE ICC | 2024 |
| [Performance of ChatGPT in Answering Clinical Questions on the Practical Guideline of Blepharoptosis](https://doi.org/10.1007/s00266-024-04005-1) | Aesthetic Plastic Surgery | 2024 |
| [Retrieval Augmented Generation enabled generative pre-trained transformer 4 (GPT-4) Performance for Clinical Trial Screening](https://doi.org/10.1056/AIoa2400181) | NEJM AI | 2024 |
| [Development and evaluation of a large language model of ophthalmology in Chinese](https://doi.org/10.1136/bjo-2023-324526) | British Journal of Ophthalmology | 2024 |

| [Aesthetic surgery advice and counseling from artificial intelligence: A rhinoplasty consultation with ChatGPT](https://doi.org/10.1007/s00266-023-03338-7) | Aesthetic Plastic Surgery | 2023 |
| [Exploring ChatGPT's potential in facilitating adaptation of clinical guidelines: A case study of Diabetic Ketoacidosis guidelines](https://doi.org/10.7759/cureus.38784) | Cureus | 2023 |
| [MediGPT: Exploring Potentials of Conventional and Large Language Models on Medical Data](https://doi.org/10.1109/ACCESS.2024.3428918) | IEEE Access | 2023 |
| [Exploration of biomedical knowledge for recurrent glioblastoma using natural language processing deep learning models](https://doi.org/10.1186/s12911-022-02003-4) | BMC Medical Informatics and Decision Making | 2022 |
| [Creating and evaluating chatbots as eligibility assistants for clinical trials: An active deep learning approach towards user-centered classification](https://doi.org/10.1145/3403575) | ACM Transactions on Computing for Healthcare | 2021 |
| [Knowledge graph based platform of COVID-19 drugs and symptoms](https://doi.org/10.1145/3487351.3489484) | ASONAM | 2021 |
| [MedTruth: A Semi-supervised Approach to Discovering Knowledge Condition Information from Multi-Source Medical Data](https://doi.org/10.1145/3357384.3357934) | CIKM | 2019 |

# Acknowledgement
This project was sponsored by the National Library of Medicine grant R01LM009886, R01LM014344, and R01LM014573.
