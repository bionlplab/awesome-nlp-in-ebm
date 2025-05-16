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

`Parse the references, generate a table with three columns: Paper, Venue, Date. Add the links to the paper title. Order the table by years from the latest.`

| Paper | Venue | Date |
|-------|-------|------|
| [The Use of Generative AI for Scientific Literature Searches for Systematic Reviews: ChatGPT and Microsoft Bing AI Performance Evaluation](https://doi.org/10.2196/51187) | JMIR | 2024 |
| [Matching patients to clinical trials with large language models](#) | - | 2024 |
| [A span-based model for extracting overlapping PICO entities from randomized controlled trial publications](https://doi.org/10.1093/jamia/ocae065) | JAMIA | 2024 |
| [LeafAI: query generator for clinical cohort discovery rivaling a human programmer](https://doi.org/10.1093/jamia/ocad149) | JAMIA | 2023 |
| [Deep learning to refine the identification of high-quality clinical research articles from the biomedical literature: Performance evaluation](https://doi.org/10.1016/j.jbi.2023.104384) | JBI | 2023 |
| [ScanMedicine: An online search system for medical innovation](https://doi.org/10.1016/j.cct.2022.107042) | Contemporary Clinical Trials | 2023 |
| Automatically Summarizing Evidence from Clinical Trials: A Prototype Highlighting Current Challenges | - | 2023 |
| [Investigation into Scaling-Up the SOAP Problem-Oriented Medical Record into a Clinical Case Study](https://doi.org/10.1109/ICHI57859.2023.00134) | IEEE ICHI | 2023 |
| [In a pilot study, automated real-time systematic review updates were feasible, accurate, and work-saving](https://doi.org/10.1016/j.jclinepi.2022.08.013) | J Clin Epidemiol | 2023 |
| [In Silico Drug Repurposing using Knowledge Graph Embeddings for Alzheimer's Disease](https://doi.org/10.1145/3569192.3569203) | ACM | 2022 |
| [State-of-the-Art Evidence Retriever for Precision Medicine: Algorithm Development and Validation](https://doi.org/10.2196/40743) | JMIR | 2022 |
| [Trial2Vec: Zero-Shot Clinical Trial Document Similarity Search using Self-Supervision](https://doi.org/10.18653/v1/2022.findings-emnlp.476) | Findings of EMNLP | 2022 |
| [Cohort-based Clinical Trial Retrieval](https://doi.org/10.1145/3503516.3503529) | ACM | 2022 |
| [Improvement of intervention information detection for automated clinical literature screening during systematic review](https://doi.org/10.1016/j.jbi.2022.104185) | JBI | 2022 |
| [Preliminary Comparison of the Performance of the National Library of Medicine's Systematic Review Publication Type and the Sensitive Clinical Queries Filter for Systematic Reviews in PubMed](https://doi.org/10.5195/jmla.2022.1286) | JMLA | 2022 |
| [COVID-19 trial graph: a linked graph for COVID-19 clinical trials](https://doi.org/10.1093/jamia/ocab078) | JAMIA | 2021 |
| [Automate clinical evidence synthesis by linking trials to publications with text analytics](https://doi.org/10.1145/3459104.3459168) | ACM | 2021 |
| [A probabilistic precision information retrieval model for personalized clinical trial recommendation based on heterogeneous data](https://doi.org/10.1109/icccnt51525.2021.9579891) | ICCCNT (IEEE) | 2021 |
| [Precision Medicine Search for Paediatric Oncology](https://doi.org/10.1145/3404835.3462792) | ACM | 2021 |
| [Evaluation of Applied Machine Learning for Health Misinformation Detection via Survey of Medical Professionals on Controversial Topics in Pediatrics](https://doi.org/10.1145/3472813.3472814) | ACM | 2021 |
| [Matching patients to clinical trials using semantically enriched document representation](https://doi.org/10.1016/j.jbi.2020.103406) | JBI | 2020 |
| [Natural Language Processing for Mimicking Clinical Trial Recruitment in Critical Care: A Semi-Automated Simulation Based on the LeoPARDS Trial](https://doi.org/10.1109/JBHI.2020.2977925) | IEEE JBHI | 2020 |
| [Clinical trial search: Using biomedical language understanding models for re-ranking](https://doi.org/10.1016/j.jbi.2020.103530) | JBI | 2020 |
| [A2A: a platform for research in biomedical literature search](https://doi.org/10.1186/s12859-020-03894-8) | BMC Bioinformatics | 2020 |
| [DQueST: dynamic questionnaire for search of clinical trials](https://doi.org/10.1093/jamia/ocz121) | JAMIA | 2019 |
| [Linking Knowledge Discovery In Clinical Notes And Massive Biomedical Literature Repositories](https://ieeexplore.ieee.org/document/RelevantDocumentNumber) | IEEE | 2019 |
| [An Experimentation Platform for Precision Medicine](https://doi.org/10.1145/3331184.3331396) | ACM | 2019 |

- Linking Knowledge Discovery In Clinical Notes And Massive Biomedical Literature Repositories (2019), Mohammad S. Alodadi et al.  (https://ieeexplore.ieee.org/document/RelevantDocumentNumber)
- In Silico Drug Repurposing using Knowledge Graph Embeddings for Alzheimer's Disease (2022), Daluwatumulle, Geesa et al.  (https://doi.org/10.1145/3569192.3569203)
- {LeafAI}: query generator for clinical cohort discovery rivaling a human programmer (2023), Dobbins, Nicholas J. et al.  (https://doi.org/10.1093/jamia/ocad149)
- {COVID-19} trial graph: a linked graph for COVID-19 clinical trials (2021), Du, Jingcheng et al.  (https://doi.org/10.1093/jamia/ocab078)
- The Use of Generative AI for Scientific Literature Searches for Systematic Reviews: ChatGPT and Microsoft Bing AI Performance Evaluation (2024), Gwon, YN et al.  (https://doi.org/10.2196/51187)
- Matching patients to clinical trials using semantically enriched document representation (2020), Hassanzadeh, Hamed et al.  (https://doi.org/10.1016/j.jbi.2020.103406)
- State-of-the-Art Evidence Retriever for Precision Medicine: Algorithm Development and Validation (2022), Qiao Jin et al.  (https://doi.org/10.2196/40743)
- Matching patients to clinical trials with large language models (2024), Jin, Qiao et al.
- A probabilistic precision information retrieval model for personalized clinical trial recommendation based on heterogeneous data (2021), Kamath, Sowmya et al.  (https://doi.org/10.1109/icccnt51525.2021.9579891)
- Precision Medicine Search for Paediatric Oncology (2021), Koopman, Bevan et al.  (https://doi.org/10.1145/3404835.3462792)
- Cohort-based Clinical Trial Retrieval (2022), Koopman, Bevan et al.  (https://doi.org/10.1145/3503516.3503529)
- Automate clinical evidence synthesis by linking trials to publications with text analytics (2021), Li, Chao et al.  (https://doi.org/10.1145/3459104.3459168)
- DQueST: dynamic questionnaire for search of clinical trials (2019), Cong Liu et al.  (https://doi.org/10.1093/jamia/ocz121)
- Deep learning to refine the identification of high-quality clinical research articles from the biomedical literature: Performance evaluation (2023), Lokker, Cynthia et al.  (https://doi.org/10.1016/j.jbi.2023.104384)
- In a pilot study, automated real-time systematic review updates were feasible, accurate, and work-saving (2023), Marshall, Iain J et al.  (https://doi.org/10.1016/j.jclinepi.2022.08.013)
- Investigation into Scaling-Up the SOAP Problem-Oriented Medical Record into a Clinical Case Study (2023), Sabah Mohammed et al.  (https://doi.org/10.1109/ICHI57859.2023.00134)
- Preliminary Comparison of the Performance of the National Library of Medicine's Systematic Review Publication Type and the Sensitive Clinical Queries Filter for Systematic Reviews in PubMed (2022), Tamara Navarro-Ruan et al.  (https://doi.org/10.5195/jmla.2022.1286)
- An Experimentation Platform for Precision Medicine (2019), Nguyen, Vincent et al.  (https://doi.org/10.1145/3331184.3331396)
- Automatically Summarizing Evidence from Clinical Trials: A Prototype Highlighting Current Challenges (2023), Sanjana Ramprasad et al.
- {A2A}: a platform for research in biomedical literature search (2020), Rybinski, Maciej et al.  (https://doi.org/10.1186/s12859-020-03894-8)
- Clinical trial search: Using biomedical language understanding models for re-ranking (2020), Rybinski, Maciej et al.  (https://doi.org/10.1016/j.jbi.2020.103530)
- ScanMedicine: An online search system for medical innovation (2023), Jawad Sadek et al.  (https://doi.org/10.1016/j.cct.2022.107042)
- Evaluation of Applied Machine Learning for Health Misinformation Detection via Survey of Medical Professionals on Controversial Topics in Pediatrics (2021), Hamman Samuel et al.  (https://doi.org/10.1145/3472813.3472814)
- Natural Language Processing for Mimicking Clinical Trial Recruitment in Critical Care: A Semi-Automated Simulation Based on the LeoPARDS Trial (2020), Hegler C. Tissot et al.  (https://doi.org/10.1109/JBHI.2020.2977925)
- Improvement of intervention information detection for automated clinical literature screening during systematic review (2022), Tsubota, Tadashi et al.  (https://doi.org/10.1016/j.jbi.2022.104185)
- {Trial2Vec}: Zero-Shot Clinical Trial Document Similarity Search using Self-Supervision (2022), Wang, Zifeng et al.  (https://doi.org/10.18653/v1/2022.findings-emnlp.476)
- A span-based model for extracting overlapping {PICO} entities from randomized controlled trial publications (2024), Zhang, Gongbo et al.  (https://doi.org/10.1093/jamia/ocae065)


### 2. Acquire – Extracting Evidence
#### Entity Extraction and Normalization
- Improving Disease Named Entity Recognition for Clinical Trial Matching (2019), Al Hafiz Khan, Md Abdullah et al.  (https://doi.org/10.1109/BIBM47256.2019.8983421)
- Evaluation of an artificial intelligence clinical trial matching system in Australian lung cancer patients (2020), Alexander, Marliese et al.  (https://doi.org/10.1093/jamiaopen/ooaa002)
- Linking Knowledge Discovery In Clinical Notes And Massive Biomedical Literature Repositories (2019), Mohammad S. Alodadi et al.  (https://ieeexplore.ieee.org/document/RelevantDocumentNumber)
- {srBERT}: automatic article classification model for systematic review using BERT (2021), Aum, Sungmin et al.  (https://doi.org/10.1186/s13643-021-01763-w)
- Utilizing Large Language Models for Enhanced Clinical Trial Matching: A Study on Automation in Patient Screening (2024), Jacob Beattie et al.  (https://doi.org/10.7759/cureus.60044)
- Artificial intelligence tool for optimizing eligibility screening for clinical trials in a large community cancer center (2020), Beck, J Thaddeus et al.  (https://doi.org/10.1200/CCI.19.00079)
- Controversial Trials First: Identifying Disagreement Between Clinical Guidelines and New Evidence (2022), Florian Borchert et al.
- Developing a fully automated evidence synthesis tool for identifying, assessing and collating the evidence (2021), Brassey, Jon et al.  (https://doi.org/10.1136/bmjebm-2018-111126)
- Improving reference prioritisation with PICO recognition (2019), Austin J. Brockmeier et al.  (https://bmcmedinformdecismak.biomedcentral.com/articles/10.1186/s12911-019-0974-4)
- An approach for transgender population information extraction and summarization from clinical trial text (2019), Chen, Boyu et al.  (https://doi.org/10.1186/s12911-019-0768-1)
- Medical Knowledge Infused Convolutional Neural Networks for Cohort Selection in Clinical Trials (2019), Chen, Chi-Jen et al.  (https://doi.org/10.1093/jamia/ocz128)
- Clinical trial cohort selection based on multi-level rule-based natural language processing system (2019), Chen, Long et al.  (https://doi.org/10.1093/jamia/ocz109)
- Creating and evaluating chatbots as eligibility assistants for clinical trials: An active deep learning approach towards user-centered classification (2021), Chuan, Ching-Hua et al.  (https://doi.org/10.1145/3403575)
- Natural language processing for adjudication of heart failure in a multicenter clinical trial: A secondary analysis of a randomized clinical trial (2024), Cunningham, Jonathan W et al.  (https://doi.org/10.1001/jamacardio.2023.4859)
- In Silico Drug Repurposing using Knowledge Graph Embeddings for Alzheimer's Disease (2022), Daluwatumulle, Geesa et al.  (https://doi.org/10.1145/3569192.3569203)
- AutoCriteria: a generalizable clinical trial eligibility criteria extraction system powered by large language models (2024), Surabhi Datta et al.  (https://doi.org/10.1093/jamia/ocad218)
- Automating clinical trial eligibility screening: Quantitative analysis of {GPT} Models versus Human Expertise (2024), Devi, Arti et al.  (https://doi.org/10.1145/3652037.3663922)
- {MSˆ2}: Multi-Document Summarization of Medical Studies (2021), DeYoung, Jay et al.  (https://doi.org/10.18653/v1/2021.emnlp-main.594)
- Matching Patients to Accelerate Clinical Trials ({MPACT}) Enabling Technology for Oncology Clinical Trial Workflow (2024), Do, Nhan V et al.  (https://doi.org/10.3233/SHTI231132)
- The Leaf Clinical Trials Corpus: a new resource for query generation from clinical trial eligibility criteria (2022), Dobbins, Nicholas J et al.  (https://doi.org/10.1038/s41597-022-01521-0)
- {LeafAI}: query generator for clinical cohort discovery rivaling a human programmer (2023), Dobbins, Nicholas J. et al.  (https://doi.org/10.1093/jamia/ocad149)
- Machine Learning Assisted Citation Screening for Systematic Reviews (2020), Anjani Dhrangadhariya et al.  (https://doi.org/10.3233/SHTI200171)
- Not so weak PICO: leveraging weak supervision for participants, interventions, and outcomes recognition for systematic review automation (2023), Anjani Dhrangadhariya et al.  (https://doi.org/10.1093/jamiaopen/ooac107)
- PICO to PICOS: Weak Supervision to Extend Datasets with New Labels (2024), Anjani Dhrangadhariya et al.  (https://doi.org/10.3233/SHTI240775)
- EMR2vec: Bridging the gap between patient data and clinical trial (2021), Houssein Dhayne et al.  (https://doi.org/10.1016/j.cie.2021.107236)

- The anatomy of the {SARS}-{CoV}-2 biomedical literature: Introducing the {CovidX} network algorithm for drug repurposing recommendation (2020), Gates, Lyndsey Elaine et al.  (https://doi.org/10.2196/21169)
- {AlpaPICO}: Extraction of {PICO} frames from clinical trial documents using {LLMs} (2024), Ghosh, Madhusudan et al.  (https://doi.org/10.1016/j.ymeth.2024.04.005)
- {BLINKtextsubscriptLSTM}: {BioLinkBERT} and {LSTM} based approach for extraction of {PICO} frame from Clinical Trial Text (2024), Ghosh, Madhusudan et al.  (https://doi.org/10.1145/3632410.3632442)
- Towards autonomous living meta-analyses: A framework for automation of systematic review and meta-analyses (2024), Górska, Anna et al.  (https://doi.org/10.3233/SHTI240427)
- Extractive summarization of clinical trial descriptions (2019), Gulden, Christian et al.  (https://doi.org/10.1016/j.ijmedinf.2019.05.019)
- The Use of Generative AI for Scientific Literature Searches for Systematic Reviews: ChatGPT and Microsoft Bing AI Performance Evaluation (2024), Gwon, YN et al.  (https://doi.org/10.2196/51187)
- Matching patients to clinical trials using semantically enriched document representation (2020), Hassanzadeh, Hamed et al.  (https://doi.org/10.1016/j.jbi.2020.103406)
- Automatic knowledge graph population with model-complete text comprehension for pre-clinical outcomes in the field of spinal cord injury (2023), Hendrik Ter Horst et al.  (https://doi.org/10.1016/j.artmed.2023.102491)
- Towards precise {PICO} extraction from abstracts of randomized controlled trials using a section-specific learning approach (2023), Hu, Yan et al.  (https://doi.org/10.1093/bioinformatics/btad542)
- Exploration of biomedical knowledge for recurrent glioblastoma using natural language processing deep learning models (2022), Jang, Bum-Sup et al.  (https://doi.org/10.1186/s12911-022-02003-4)
- Using artificial intelligence to identify drugs for repurposing to treat l-{DOPA} induced dyskinesia (2024), Johnston, Tom H et al.  (https://doi.org/10.1016/j.neuropharm.2024.109880)
- Implementation of Machine Learning Pipelines for Clinical Practice: Development and Validation Study (2022), Kanbar, Lara J et al.  (https://doi.org/10.2196/37833)
- Pretraining to recognize {PICO} Elements from Randomized Controlled Trial Literature (2019), Kang, Tian et al.  (https://doi.org/10.3233/SHTI190209)
- UMLS-based data augmentation for natural language processing of clinical research literature (2021), Tian Kang et al.  (https://doi.org/10.1093/jamia/ocaa309)
- {EvidenceMap}: a three-level knowledge representation for medical evidence computation and comprehension (2023), Kang, Tian et al.  (https://doi.org/10.1093/jamia/ocad036)
- Automated Matching of Patients to Clinical Trials: A Patient-Centric Natural Language Processing Approach for Pediatric Leukemia (2023), Samuel Kaskovich et al.  (https://doi.org/10.1200/CCI.23.00009)
- TCGA-Reports: A machine-readable pathology report resource for benchmarking text-based AI models (2024), Jenna Kefeli et al.  (https://doi.org/10.1016/j.patter.2024.100933)
- Data Mining of Free-Text Responses: An Innovative Approach to Analyzing Patient Perspectives on Chronic Rhinosinusitis with Nasal Polyps in a Phase IIa Proof-of-Concept Study for Dupilumab (2021), Khan, AH et al.  (https://doi.org/10.2147/PPA.S320242)
- Parsable Clinical Trial Eligibility Criteria Representation Using Natural Language Processing (2023), Kim, Jeongeun et al.
- Parsable Clinical Trial Eligibility Criteria Representation Using Natural Language Processing (2023), Kim, Jeongeun et al.
- Precision Medicine Search for Paediatric Oncology (2021), Koopman, Bevan et al.  (https://doi.org/10.1145/3404835.3462792)
- Automatic categorization of self-acknowledged limitations in randomized controlled trial publications (2024), Lan, Mengfei et al.  (https://doi.org/10.1016/j.jbi.2024.104628)
- Optimizing Clinical Trial Eligibility Design Using Natural Language Processing Models and Real-World Data: Algorithm Development and Validation (2024), Lee, Kyeryoung et al.  (https://doi.org/10.2196/50800)
- A Comparison between Human and NLP-based Annotation of Clinical Trial Eligibility Criteria Text Using The OMOP Common Data Model (2021), Li, Xinhang et al.
- A comparative study of pre-trained language models for named entity recognition in clinical trial eligibility criteria from multiple corpora (2022), Li, Jianfu et al.  (https://doi.org/10.1186/s12911-022-01967-7)
- Automated information extraction model enhancing traditional chinese medicine rct evidence extraction (evi-bert): algorithm development and validation (2024), Li, Yizhen et al.  (https://doi.org/https://doi.org/10.3389/frai.2024.1454945)
- DQueST: dynamic questionnaire for search of clinical trials (2019), Cong Liu et al.  (https://doi.org/10.1093/jamia/ocz121)
- A knowledge base of clinical trial eligibility criteria (2021), Hao Liu et al.  (https://doi.org/10.1016/j.jbi.2021.103771)
- Evaluation of {Criteria2Query}: Towards Augmented Intelligence for Cohort Identification (2022), Liu, Cong et al.  (https://doi.org/10.3233/SHTI220082)
- Impact of size, location, symptomatic-nature and gender on the rupture of saccular intracranial aneurysms (2020), Malik, Khalid Mahmood et al.
- In a pilot study, automated real-time systematic review updates were feasible, accurate, and work-saving (2023), Marshall, Iain J et al.  (https://doi.org/10.1016/j.jclinepi.2022.08.013)
- Enhancing evidence-based medicine with natural language argumentative analysis of clinical trials (2021), Mayer, Tobias et al.  (https://doi.org/10.1016/j.artmed.2021.102098)
- Piloting an automated clinical trial eligibility surveillance and provider alert system based on artificial intelligence and standard data models (2023), St'e et al.  (https://doi.org/https://doi.org/10.1186/s12874-023-01916-6)
- Data-driven method to enhance craniofacial and oral phenotype vocabularies (2019), Rashmi Mishra et al.  (https://doi.org/10.1016/j.adaj.2019.05.029)
- Investigation into Scaling-Up the SOAP Problem-Oriented Medical Record into a Clinical Case Study (2023), Sabah Mohammed et al.  (https://doi.org/10.1109/ICHI57859.2023.00134)
- Integrating a {PICO} clinical questioning to the {QL4POMR} framework for building evidence-based clinical case reports (2023), Mohammed, Sabah et al.  (https://doi.org/10.1109/bigdata59044.2023.10386854)
- Generative {AI} for evidence-based medicine: A {PICO} {GenAI} for synthesizing clinical case reports (2024), Mohammed, Sabah et al.  (https://doi.org/10.1109/icc51166.2024.10622271)
- Automating clinical trial matches via natural language processing of synthetic electronic health records and clinical trial eligibility criteria (2024), Murcia, Victor M et al.
- Automatic data extraction to support meta-analysis statistical analysis: a case study on breast cancer (2022), Mutinda, Faith Wavinya et al.  (https://doi.org/10.1186/s12911-022-01897-4)
- Validating GAN-BioBERT: A Methodology for Assessing Reporting Trends in Clinical Trials (2022), Joshua J. Myszewski et al.  (https://doi.org/10.3389/fdgth.2022.878369)
- The suitability of {UMLS} and {SNOMED}-{CT} for encoding outcome concepts (2023), Newbury, Abigail et al.  (https://doi.org/10.1093/jamia/ocad161)
- A Real-Time Automated Patient Screening System for Clinical Trials Eligibility in an Emergency Department: Design and Evaluation (2019), Ni, Yizhao et al.  (https://doi.org/10.2196/14185)
- Developing an Inpatient Electronic Medical Record Phenotype for Hospital-Acquired Pressure Injuries: Case Study Using Natural Language Processing Models (2023), Elvira Nurmambetova et al.  (https://doi.org/10.2196/41264)
- Knowledge graph based platform of {COVID}-19 drugs and symptoms (2021), Pan, Zhenhe et al.  (https://doi.org/10.1145/3487351.3489484)
- Clinical trial search: Using biomedical language understanding models for re-ranking (2020), Rybinski, Maciej et al.  (https://doi.org/10.1016/j.jbi.2020.103530)
- ScanMedicine: An online search system for medical innovation (2023), Jawad Sadek et al.  (https://doi.org/10.1016/j.cct.2022.107042)
- Artificial intelligence clinical evidence engine for automatic identification, prioritization, and extraction of relevant clinical oncology research (2021), Saiz, Fernando Suarez et al.  (https://doi.org/10.1200/CCI.20.00087)
- An annotated corpus of clinical trial publications supporting schema-based relational information extraction (2022), Sanchez-Graillet, Olivia et al.  (https://doi.org/10.1186/s13326-022-00271-7)
- Cohort Selection for Clinical Trials From Longitudinal Patient Records: Text Mining Approach (2019), Spasic, Irena et al.  (https://doi.org/10.2196/15980)
- EBM+: Advancing Evidence-Based Medicine via two level automatic identification of Populations, Interventions, Outcomes in medical literature (2020), Stylianou, Nikolaos et al.  (https://doi.org/10.1016/j.artmed.2020.101949)
- {TransforMED}: End-to-End Transformers for Evidence-Based Medicine and Argument Mining in medical literature (2021), Stylianou, Nikolaos et al.  (https://doi.org/10.1016/j.jbi.2021.103767)
- Transformer-based named entity recognition for parsing clinical trial eligibility criteria (2021), Tian, Shubo et al.  (https://doi.org/10.1145/3459930.3469560)
- Parsing Clinical Trial Eligibility Criteria for Cohort Query by a Multi-Input Multi-Output Sequence Labeling Model (2023), Tian, Shubo et al.  (https://doi.org/10.1109/BIBM58861.2023.10385876)
- Natural Language Processing for Mimicking Clinical Trial Recruitment in Critical Care: A Semi-Automated Simulation Based on the LeoPARDS Trial (2020), Hegler C. Tissot et al.  (https://doi.org/10.1109/JBHI.2020.2977925)
- Improvement of intervention information detection for automated clinical literature screening during systematic review (2022), Tsubota, Tadashi et al.  (https://doi.org/10.1016/j.jbi.2022.104185)
- Extending PICO with Observation Normalization for Evidence Computing (2022), Turfaha, Ali et al.  (https://doi.org/10.3233/SHTI220076)
- Hybrid bag of approaches to characterize selection criteria for cohort identification (2019), Vydiswaran, V G Vinod et al.  (https://doi.org/10.1093/jamia/ocz079)
- {Trial2Vec}: Zero-shot clinical trial document similarity search using self-supervision (2022), Wang, Zifeng et al.  (https://doi.org/10.18653/v1/2022.findings-emnlp.476)
- Evaluation of an artificial intelligence-based clinical trial matching system in Chinese patients with hepatocellular carcinoma: a retrospective study (2024), Wang, Kunyuan et al.  (https://doi.org/10.1186/s12885-024-11959-7)
- Comparing generative and extractive approaches to information extraction from abstracts describing randomized clinical trials (2024), Witte, Christian et al.  (https://doi.org/10.1186/s13326-024-00305-2)
- Pre-trained language models with domain knowledge for biomedical extractive summarization (2022), Xie, Qianqian et al.  (https://doi.org/10.1016/j.knosys.2022.109460)
- {OncoCTMiner}: streamlining precision oncology trial matching via molecular profile analysis (2023), Xu, Quan et al.  (https://doi.org/10.1093/database/baad077)
- Text classification of cancer clinical trial eligibility criteria (2023), Yang, Yumeng et al.
- Batch enrollment for an artificial intelligence-guided intervention to lower neurologic events in patients with undiagnosed atrial fibrillation: rationale and design of a digital clinical trial (2021), Yao, Xiaoxi et al.  (https://doi.org/10.1016/j.ahj.2021.05.006)
- Large Language Models for Healthcare Data Augmentation: An Example on Patient-Trial Matching (2024), Jiayi Yuan et al.
- MeDict-GP: An Accurate Entity Recognition Model Combining Medical Domain Knowledge and Globalization Ideas (2023), Zhang, Yixuan et al.  (https://doi.org/10.1145/3594315.3594360)
- A span-based model for extracting overlapping {PICO} entities from {RCT} publications (2024), Zhang, Gongbo et al.  (https://doi.org/10.1093/jamia/ocae065)






#### Relation Extraction

| Paper | Venue | Date |
|:------|:------|:-----|
| [AutoTrial: Prompting Language Models for Clinical Trial Design](https://doi.org/10.18653/v1/2023.emnlp-main.766) | EMNLP | 2023 |
| [LeafAI: query generator for clinical cohort discovery rivaling a human programmer](https://doi.org/10.1093/jamia/ocad149) | JAMIA | 2023 |
| [Controversial Trials First: Identifying Disagreement Between Clinical Guidelines and New Evidence](https://pubmed.ncbi.nlm.nih.gov/35308948/) | AMIA Annu Symp Proc | 2022 |
| [The Leaf Clinical Trials Corpus: a new resource for query generation from clinical trial eligibility criteria](https://doi.org/10.1038/s41597-022-01521-0) | Scientific Data | 2022 |
| [Evaluation of Criteria2Query: Towards Augmented Intelligence for Cohort Identification](https://doi.org/10.3233/SHTI220082) | MedInfo | 2022 |
| [Knowledge graph based platform of COVID-19 drugs and symptoms](https://doi.org/10.1145/3487351.3489484) | ACM | 2021 |
| [Enhancing evidence-based medicine with natural language argumentative analysis of clinical trials](https://doi.org/10.1016/j.artmed.2021.102098) | Artificial Intelligence in Medicine | 2021 |
| [A knowledge base of clinical trial eligibility criteria](https://doi.org/10.1016/j.jbi.2021.103771) | Journal of Biomedical Informatics | 2021 |
| [MS²: Multi-Document Summarization of Medical Studies](https://doi.org/10.18653/v1/2021.emnlp-main.594) | EMNLP | 2021 |
| [srBERT: automatic article classification model for systematic review using BERT](https://doi.org/10.1186/s13643-021-01763-w) | Systematic Reviews | 2021 |
| [Linking Knowledge Discovery In Clinical Notes And Massive Biomedical Literature Repositories](https://doi.org/10.1109/BIBM47256.2019.8983242) | BIBM | 2019 |
| [An approach for transgender population information extraction and summarization from clinical trial text](https://doi.org/10.1186/s12911-019-0768-1) | BMC Medical Informatics and Decision Making | 2019 |



### 3. Appraise, Synthesize, and Summarization
#### Quality Assessment
- Developing a fully automated evidence synthesis tool for identifying, assessing and collating the evidence (2021), Brassey, Jon et al.  (https://doi.org/10.1136/bmjebm-2018-111126)
- Machine Learning Assisted Citation Screening for Systematic Reviews (2020), Anjani Dhrangadhariya et al.  (https://doi.org/10.3233/SHTI200171)
- The Use of Generative AI for Scientific Literature Searches for Systematic Reviews: ChatGPT and Microsoft Bing AI Performance Evaluation (2024), Gwon, YN et al.  (https://doi.org/10.2196/51187)
- State-of-the-Art Evidence Retriever for Precision Medicine: Algorithm Development and Validation (2022), Qiao Jin et al.  (https://doi.org/10.2196/40743)
- Automatic categorization of self-acknowledged limitations in randomized controlled trial publications (2024), Lan, Mengfei et al.  (https://doi.org/10.1016/j.jbi.2024.104628)
- Deep learning to refine the identification of high-quality clinical research articles from the biomedical literature: Performance evaluation (2023), Lokker, Cynthia et al.  (https://doi.org/10.1016/j.jbi.2023.104384)
- Validating GAN-BioBERT: A Methodology for Assessing Reporting Trends in Clinical Trials (2022), Joshua J. Myszewski et al.  (https://doi.org/10.3389/fdgth.2022.878369)
- Transformer-based named entity recognition for parsing clinical trial eligibility criteria (2021), Tian, Shubo et al.  (https://doi.org/10.1145/3459930.3469560)
- Utilizing ChatGPT as a scientific reasoning engine to differentiate conflicting evidence and summarize challenges in controversial clinical questions (2024), Xie, Shiyao et al.  (https://doi.org/10.1093/jamia/ocae100)
- {OncoCTMiner}: streamlining precision oncology trial matching via molecular profile analysis (2023), Xu, Quan et al.  (https://doi.org/10.1093/database/baad077)
- 2021 Fifth International Conference on Information Retrieval and Knowledge Management (CAMP) (2021), Yazi, Fatin Syafiqah et al.  (https://doi.org/10.1109/CAMP51653.2021.9498061)

#### Evidence Ranking and Screening
- {srBERT}: automatic article classification model for systematic review using BERT (2021), Aum, Sungmin et al.  (https://doi.org/10.1186/s13643-021-01763-w)
- Improving reference prioritisation with PICO recognition (2019), Austin J. Brockmeier et al.  (https://bmcmedinformdecismak.biomedcentral.com/articles/10.1186/s12911-019-0974-4)
- AutoCriteria: a generalizable clinical trial eligibility criteria extraction system powered by large language models (2024), Surabhi Datta et al.  (https://doi.org/10.1093/jamia/ocad218)
- The anatomy of the {SARS}-{CoV}-2 biomedical literature: Introducing the {CovidX} network algorithm for drug repurposing recommendation (2020), Gates, Lyndsey Elaine et al.  (https://doi.org/10.2196/21169)
- Towards autonomous living meta-analyses: A framework for automation of systematic review and meta-analyses (2024), Górska, Anna et al.  (https://doi.org/10.3233/SHTI240427)
- Matching patients to clinical trials with large language models (2024), Jin, Qiao et al.
- Using artificial intelligence to identify drugs for repurposing to treat l-{DOPA} induced dyskinesia (2024), Johnston, Tom H et al.  (https://doi.org/10.1016/j.neuropharm.2024.109880)
- A probabilistic precision information retrieval model for personalized clinical trial recommendation based on heterogeneous data (2021), Kamath, Sowmya et al.  (https://doi.org/10.1109/icccnt51525.2021.9579891)
- Automated Matching of Patients to Clinical Trials: A Patient-Centric Natural Language Processing Approach for Pediatric Leukemia (2023), Samuel Kaskovich et al.  (https://doi.org/10.1200/CCI.23.00009)
- Cohort-based Clinical Trial Retrieval (2022), Koopman, Bevan et al.  (https://doi.org/10.1145/3503516.3503529)
- Automate clinical evidence synthesis by linking trials to publications with text analytics (2021), Li, Chao et al.  (https://doi.org/10.1145/3459104.3459168)
- Piloting an automated clinical trial eligibility surveillance and provider alert system based on artificial intelligence and standard data models (2023), St'e et al.  (https://doi.org/https://doi.org/10.1186/s12874-023-01916-6)
- Preliminary Comparison of the Performance of the National Library of Medicine's Systematic Review Publication Type and the Sensitive Clinical Queries Filter for Systematic Reviews in PubMed (2022), Tamara Navarro-Ruan et al.  (https://doi.org/10.5195/jmla.2022.1286)
- An Experimentation Platform for Precision Medicine (2019), Nguyen, Vincent et al.  (https://doi.org/10.1145/3331184.3331396)
- Measuring the impact of screening automation on meta-analyses of diagnostic test accuracy (2019), Norman, Christopher R et al.  (https://doi.org/10.1186/s13643-019-1162-x)
- Clinical trial search: Using biomedical language understanding models for re-ranking (2020), Rybinski, Maciej et al.  (https://doi.org/10.1016/j.jbi.2020.103530)
- Artificial intelligence clinical evidence engine for automatic identification, prioritization, and extraction of relevant clinical oncology research (2021), Saiz, Fernando Suarez et al.  (https://doi.org/10.1200/CCI.20.00087)
- {OncoCTMiner}: streamlining precision oncology trial matching via molecular profile analysis (2023), Xu, Quan et al.  (https://doi.org/10.1093/database/baad077)


#### Evidence Synthesis
- Developing a fully automated evidence synthesis tool for identifying, assessing and collating the evidence (2021), Brassey, Jon et al.  (https://doi.org/10.1136/bmjebm-2018-111126)
- Machine Learning Assisted Citation Screening for Systematic Reviews (2020), Anjani Dhrangadhariya et al.  (https://doi.org/10.3233/SHTI200171)
- Towards autonomous living meta-analyses: A framework for automation of systematic review and meta-analyses (2024), Górska, Anna et al.  (https://doi.org/10.3233/SHTI240427)
- Automatic knowledge graph population with model-complete text comprehension for pre-clinical outcomes in the field of spinal cord injury (2023), Hendrik Ter Horst et al.  (https://doi.org/10.1016/j.artmed.2023.102491)
- {EvidenceMap}: a three-level knowledge representation for medical evidence computation and comprehension (2023), Kang, Tian et al.  (https://doi.org/10.1093/jamia/ocad036)
- In a pilot study, automated real-time systematic review updates were feasible, accurate, and work-saving (2023), Marshall, Iain J et al.  (https://doi.org/10.1016/j.jclinepi.2022.08.013)
- Generative {AI} for evidence-based medicine: A {PICO} {GenAI} for synthesizing clinical case reports (2024), Mohammed, Sabah et al.  (https://doi.org/10.1109/icc51166.2024.10622271)
- Automatic data extraction to support meta-analysis statistical analysis: a case study on breast cancer (2022), Mutinda, Faith Wavinya et al.  (https://doi.org/10.1186/s12911-022-01897-4)
- {AutoTrial}: Prompting Language Models for Clinical Trial Design (2023), Wang, Zifeng et al.
- Utilizing ChatGPT as a scientific reasoning engine to differentiate conflicting evidence and summarize challenges in controversial clinical questions (2024), Xie, Shiyao et al.  (https://doi.org/10.1093/jamia/ocae100)



#### Evidence Summarization
- An approach for transgender population information extraction and summarization from clinical trial text (2019), Chen, Boyu et al.  (https://doi.org/10.1186/s12911-019-0768-1)
- {MSˆ2}: Multi-Document Summarization of Medical Studies (2021), DeYoung, Jay et al.  (https://doi.org/10.18653/v1/2021.emnlp-main.594)
- Extractive summarization of clinical trial descriptions (2019), Gulden, Christian et al.  (https://doi.org/10.1016/j.ijmedinf.2019.05.019)
- Exploring {ChatGPT}'s potential in facilitating adaptation of clinical guidelines: A case study of Diabetic Ketoacidosis guidelines (2023), Hamed, Ehab et al.  (https://doi.org/10.7759/cureus.38784)
- {TriSum}: Learning summarization ability from large language models with structured rationale (2024), Jiang, Pengcheng et al.
- {EvidenceMap}: a three-level knowledge representation for medical evidence computation and comprehension (2023), Kang, Tian et al.  (https://doi.org/10.1093/jamia/ocad036)
- Text summarization of medical documents using abstractive techniques (2023), Lalitha, Evani et al.  (https://doi.org/10.1109/icaaic56838.2023.10140885)
- Integrating a {PICO} clinical questioning to the {QL4POMR} framework for building evidence-based clinical case reports (2023), Mohammed, Sabah et al.  (https://doi.org/10.1109/bigdata59044.2023.10386854)
- Knowledge graph based platform of {COVID}-19 drugs and symptoms (2021), Pan, Zhenhe et al.  (https://doi.org/10.1145/3487351.3489484)
- Automatically Summarizing Evidence from Clinical Trials: A Prototype Highlighting Current Challenges (2023), Sanjana Ramprasad et al.
- A light-weight text summarization system for fast access to medical evidence (2020), Sarker, Abeed et al.  (https://doi.org/10.3389/fdgth.2020.585559)
- Pre-trained language models with domain knowledge for biomedical extractive summarization (2022), Xie, Qianqian et al.  (https://doi.org/10.1016/j.knosys.2022.109460)
- Utilizing ChatGPT as a scientific reasoning engine to differentiate conflicting evidence and summarize challenges in controversial clinical questions (2024), Xie, Shiyao et al.  (https://doi.org/10.1093/jamia/ocae100)



### 4. Apply & Assess – Adoption, refinement and research
#### Clinical Trial design and identification
- Improving Disease Named Entity Recognition for Clinical Trial Matching (2019), Al Hafiz Khan, Md Abdullah et al.  (https://doi.org/10.1109/BIBM47256.2019.8983421)
- Evaluation of an artificial intelligence clinical trial matching system in Australian lung cancer patients (2020), Alexander, Marliese et al.  (https://doi.org/10.1093/jamiaopen/ooaa002)
- Utilizing Large Language Models for Enhanced Clinical Trial Matching: A Study on Automation in Patient Screening (2024), Jacob Beattie et al.  (https://doi.org/10.7759/cureus.60044)
- Artificial intelligence tool for optimizing eligibility screening for clinical trials in a large community cancer center (2020), Beck, J Thaddeus et al.  (https://doi.org/10.1200/CCI.19.00079)
- Improving the Efficiency of Clinical Trial Recruitment Using an Ensemble Machine Learning to Assist With Eligibility Screening (2021), Cai, Tianrun et al.  (https://doi.org/10.1002/acr2.11289)
- An approach for transgender population information extraction and summarization from clinical trial text (2019), Chen, Boyu et al.  (https://doi.org/10.1186/s12911-019-0768-1)
- Medical Knowledge Infused Convolutional Neural Networks for Cohort Selection in Clinical Trials (2019), Chen, Chi-Jen et al.  (https://doi.org/10.1093/jamia/ocz128)
- Clinical trial cohort selection based on multi-level rule-based natural language processing system (2019), Chen, Long et al.  (https://doi.org/10.1093/jamia/ocz109)
- Creating and evaluating chatbots as eligibility assistants for clinical trials: An active deep learning approach towards user-centered classification (2021), Chuan, Ching-Hua et al.  (https://doi.org/10.1145/3403575)
- Natural language processing for adjudication of heart failure in a multicenter clinical trial: A secondary analysis of a randomized clinical trial (2024), Cunningham, Jonathan W et al.  (https://doi.org/10.1001/jamacardio.2023.4859)
- Automating clinical trial eligibility screening: Quantitative analysis of {GPT} Models versus Human Expertise (2024), Devi, Arti et al.  (https://doi.org/10.1145/3652037.3663922)
- Matching Patients to Accelerate Clinical Trials ({MPACT}) Enabling Technology for Oncology Clinical Trial Workflow (2024), Do, Nhan V et al.  (https://doi.org/10.3233/SHTI231132)
- The Leaf Clinical Trials Corpus: a new resource for query generation from clinical trial eligibility criteria (2022), Dobbins, Nicholas J et al.  (https://doi.org/10.1038/s41597-022-01521-0)
- {LeafAI}: query generator for clinical cohort discovery rivaling a human programmer (2023), Dobbins, Nicholas J. et al.  (https://doi.org/10.1093/jamia/ocad149)
- EMR2vec: Bridging the gap between patient data and clinical trial (2021), Houssein Dhayne et al.  (https://doi.org/10.1016/j.cie.2021.107236)

- Matching patients to clinical trials using semantically enriched document representation (2020), Hassanzadeh, Hamed et al.  (https://doi.org/10.1016/j.jbi.2020.103406)
- Automatic knowledge graph population with model-complete text comprehension for pre-clinical outcomes in the field of spinal cord injury (2023), Hendrik Ter Horst et al.  (https://doi.org/10.1016/j.artmed.2023.102491)
- Matching patients to clinical trials with large language models (2024), Jin, Qiao et al.
- A probabilistic precision information retrieval model for personalized clinical trial recommendation based on heterogeneous data (2021), Kamath, Sowmya et al.  (https://doi.org/10.1109/icccnt51525.2021.9579891)
- Implementation of Machine Learning Pipelines for Clinical Practice: Development and Validation Study (2022), Kanbar, Lara J et al.  (https://doi.org/10.2196/37833)
- Automated Matching of Patients to Clinical Trials: A Patient-Centric Natural Language Processing Approach for Pediatric Leukemia (2023), Samuel Kaskovich et al.  (https://doi.org/10.1200/CCI.23.00009)
- Parsable Clinical Trial Eligibility Criteria Representation Using Natural Language Processing (2023), Kim, Jeongeun et al.
- Parsable Clinical Trial Eligibility Criteria Representation Using Natural Language Processing (2023), Kim, Jeongeun et al.
- Cohort-based Clinical Trial Retrieval (2022), Koopman, Bevan et al.  (https://doi.org/10.1145/3503516.3503529)
- Chia, a large annotated corpus of clinical trial eligibility criteria (2020), Kury, Fabrício et al.  (https://doi.org/10.1038/s41597-020-00620-0)
- Optimizing Clinical Trial Eligibility Design Using Natural Language Processing Models and Real-World Data: Algorithm Development and Validation (2024), Lee, Kyeryoung et al.  (https://doi.org/10.2196/50800)
- A comparative study of pre-trained language models for named entity recognition in clinical trial eligibility criteria from multiple corpora (2022), Li, Jianfu et al.  (https://doi.org/10.1186/s12911-022-01967-7)
- A knowledge base of clinical trial eligibility criteria (2021), Hao Liu et al.  (https://doi.org/10.1016/j.jbi.2021.103771)
- Evaluation of {Criteria2Query}: Towards Augmented Intelligence for Cohort Identification (2022), Liu, Cong et al.  (https://doi.org/10.3233/SHTI220082)
- Piloting an automated clinical trial eligibility surveillance and provider alert system based on artificial intelligence and standard data models (2023), St'e et al.  (https://doi.org/https://doi.org/10.1186/s12874-023-01916-6)
- Automating clinical trial matches via natural language processing of synthetic electronic health records and clinical trial eligibility criteria (2024), Murcia, Victor M et al.
- A Real-Time Automated Patient Screening System for Clinical Trials Eligibility in an Emergency Department: Design and Evaluation (2019), Ni, Yizhao et al.  (https://doi.org/10.2196/14185)
- Distilling large language models for matching patients to clinical trials (2024), Nievas, Mauro et al.  (https://doi.org/10.1093/jamia/ocae073)
- Artificial intelligence clinical evidence engine for automatic identification, prioritization, and extraction of relevant clinical oncology research (2021), Saiz, Fernando Suarez et al.  (https://doi.org/10.1200/CCI.20.00087)
- Cohort selection for clinical trials using deep learning models (2019), Segura-Bedmar, Isabel et al.  (https://doi.org/10.1093/jamia/ocz139)
- Cohort Selection for Clinical Trials From Longitudinal Patient Records: Text Mining Approach (2019), Spasic, Irena et al.  (https://doi.org/10.2196/15980)
- Transformer-based named entity recognition for parsing clinical trial eligibility criteria (2021), Tian, Shubo et al.  (https://doi.org/10.1145/3459930.3469560)
- Parsing Clinical Trial Eligibility Criteria for Cohort Query by a Multi-Input Multi-Output Sequence Labeling Model (2023), Tian, Shubo et al.  (https://doi.org/10.1109/BIBM58861.2023.10385876)
- Natural Language Processing for Mimicking Clinical Trial Recruitment in Critical Care: A Semi-Automated Simulation Based on the LeoPARDS Trial (2020), Hegler C. Tissot et al.  (https://doi.org/10.1109/JBHI.2020.2977925)
- Automatic Assessment of Patient Eligibility by Utilizing NLP and Rule-Based Analysis (2023), Pyae Phyo Tun et al.  (https://doi.org/10.1109/EMBC40787.2023.10340494)
- Hybrid bag of approaches to characterize selection criteria for cohort identification (2019), Vydiswaran, V G Vinod et al.  (https://doi.org/10.1093/jamia/ocz079)
- {AutoTrial}: Prompting Language Models for Clinical Trial Design (2023), Wang, Zifeng et al.
- Text classification of cancer clinical trial eligibility criteria (2023), Yang, Yumeng et al.
- Batch enrollment for an artificial intelligence-guided intervention to lower neurologic events in patients with undiagnosed atrial fibrillation: rationale and design of a digital clinical trial (2021), Yao, Xiaoxi et al.  (https://doi.org/10.1016/j.ahj.2021.05.006)
- Large Language Models for Healthcare Data Augmentation: An Example on Patient-Trial Matching (2024), Jiayi Yuan et al.

#### Question Answering

|Paper|Venue|Date|
|:-----|:-----|:-----|
|[Assessment of a Large Language Model's Responses to Questions and Cases About Glaucoma and Retina Management](https://doi.org/10.1001/jamaophthalmol.2023.6917)|JAMA Ophthalmology|2024|
|[TriSum: Learning summarization ability from large language models with structured rationale](https://doi.org/10.18653/v1/2024.naacl-long.154)|NAACL|2024|
|[Generative AI for evidence-based medicine: A PICO GenAI for synthesizing clinical case reports](https://doi.org/10.1109/icc51166.2024.10622271)|IEEE ICC|2024|
|[Performance of ChatGPT in Answering Clinical Questions on the Practical Guideline of Blepharoptosis](https://doi.org/10.1007/s00266-024-04005-1)|Aesthetic Plastic Surgery|2024|
|[Retrieval Augmented Generation enabled generative pre-trained transformer 4 (GPT-4) Performance for Clinical Trial Screening](https://doi.org/10.1056/AIoa2400181)|NEJM AI|2024|
|[Development and evaluation of a large language model of ophthalmology in Chinese](https://doi.org/10.1136/bjo-2023-324526)|British Journal of Ophthalmology|2024|
|[Exploring ChatGPT's potential in facilitating adaptation of clinical guidelines: A case study of Diabetic Ketoacidosis guidelines](https://doi.org/10.7759/cureus.38784)|Cureus|2023|
|[MediGPT: Exploring Potentials of Conventional and Large Language Models on Medical Data](https://ieeexplore.ieee.org/document/10599190/)|IEEE Access|2023|
|[Aesthetic surgery advice and counseling from artificial intelligence: A rhinoplasty consultation with ChatGPT](https://doi.org/10.1007/s00266-023-03338-7)|Aesthetic Plastic Surgery|2023|
|[Exploration of biomedical knowledge for recurrent glioblastoma using natural language processing deep learning models](https://doi.org/10.1186/s12911-022-02003-4)|BMC Medical Informatics and Decision Making|2022|
|[Creating and evaluating chatbots as eligibility assistants for clinical trials: An active deep learning approach towards user-centered classification](https://doi.org/10.1145/3403575)|ACM Transactions on Computing for Healthcare|2021|
|[Knowledge graph based platform of COVID-19 drugs and symptoms](https://doi.org/10.1145/3487351.3489484)|ASONAM|2021|
|[MedTruth: A Semi-supervised Approach to Discovering Knowledge Condition Information from Multi-Source Medical Data](https://doi.org/10.1145/3357384.3357934)|CIKM|2019|

# Acknowledgement
This project was sponsored by the National Library of Medicine grant R01LM009886, R01LM014344, and R01LM014573.
