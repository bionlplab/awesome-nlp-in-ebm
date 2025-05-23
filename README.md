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
|-------|-------|------|
| [The Use of Generative AI for Scientific Literature Searches for Systematic Reviews: ChatGPT and Microsoft Bing AI Performance Evaluation](https://doi.org/10.2196/51187) | JMIR | 2024 |
| [Matching patients to clinical trials with large language models](https://www.nature.com/articles/s41467-024-53081-z) | Nature Communications | 2024 |
| [A span-based model for extracting overlapping PICO entities from randomized controlled trial publications](https://doi.org/10.1093/jamia/ocae065) | JAMIA | 2024 |
| [LeafAI: query generator for clinical cohort discovery rivaling a human programmer](https://doi.org/10.1093/jamia/ocad149) | JAMIA | 2023 |
| [Deep learning to refine the identification of high-quality clinical research articles from the biomedical literature: Performance evaluation](https://doi.org/10.1016/j.jbi.2023.104384) | JBI | 2023 |
| [ScanMedicine: An online search system for medical innovation](https://doi.org/10.1016/j.cct.2022.107042) | Contemporary Clinical Trials | 2023 |
| [Automatically Summarizing Evidence from Clinical Trials: A Prototype Highlighting Current Challenges](https://pmc.ncbi.nlm.nih.gov/articles/PMC10361334/) | ACL | 2023 |
| [Investigation into Scaling-Up the SOAP Problem-Oriented Medical Record into a Clinical Case Study](https://doi.org/10.1109/ICHI57859.2023.00134) | IEEE ICHI | 2023 |
| [In a pilot study, automated real-time systematic review updates were feasible, accurate, and work-saving](https://doi.org/10.1016/j.jclinepi.2022.08.013) | J Clin Epidemiol | 2023 |
| [In Silico Drug Repurposing using Knowledge Graph Embeddings for Alzheimer's Disease](https://doi.org/10.1145/3569192.3569203) | ICBRA | 2022 |
| [State-of-the-Art Evidence Retriever for Precision Medicine: Algorithm Development and Validation](https://doi.org/10.2196/40743) | JMIR | 2022 |
| [Trial2Vec: Zero-Shot Clinical Trial Document Similarity Search using Self-Supervision](https://doi.org/10.18653/v1/2022.findings-emnlp.476) | EMNLP | 2022 |
| [Cohort-based Clinical Trial Retrieval](https://doi.org/10.1145/3503516.3503529) | ADCS | 2022 |
| [Improvement of intervention information detection for automated clinical literature screening during systematic review](https://doi.org/10.1016/j.jbi.2022.104185) | JBI | 2022 |
| [Preliminary Comparison of the Performance of the National Library of Medicine's Systematic Review Publication Type and the Sensitive Clinical Queries Filter for Systematic Reviews in PubMed](https://doi.org/10.5195/jmla.2022.1286) | JMLA | 2022 |
| [COVID-19 trial graph: a linked graph for COVID-19 clinical trials](https://doi.org/10.1093/jamia/ocab078) | JAMIA | 2021 |
| [Automate clinical evidence synthesis by linking trials to publications with text analytics](https://doi.org/10.1145/3459104.3459168) | ISEEIE | 2021 |
| [A probabilistic precision information retrieval model for personalized clinical trial recommendation based on heterogeneous data](https://doi.org/10.1109/icccnt51525.2021.9579891) | ICCCNT (IEEE) | 2021 |
| [Precision Medicine Search for Paediatric Oncology](https://doi.org/10.1145/3404835.3462792) | SIGIR | 2021 |
| [Evaluation of Applied Machine Learning for Health Misinformation Detection via Survey of Medical Professionals on Controversial Topics in Pediatrics](https://doi.org/10.1145/3472813.3472814) | ACM | 2021 |
| [Matching patients to clinical trials using semantically enriched document representation](https://doi.org/10.1016/j.jbi.2020.103406) | JBI | 2020 |
| [Natural Language Processing for Mimicking Clinical Trial Recruitment in Critical Care: A Semi-Automated Simulation Based on the LeoPARDS Trial](https://doi.org/10.1109/JBHI.2020.2977925) | IEEE JBHI | 2020 |
| [Clinical trial search: Using biomedical language understanding models for re-ranking](https://doi.org/10.1016/j.jbi.2020.103530) | JBI | 2020 |
| [A2A: a platform for research in biomedical literature search](https://doi.org/10.1186/s12859-020-03894-8) | BMC Bioinformatics | 2020 |
| [DQueST: dynamic questionnaire for search of clinical trials](https://doi.org/10.1093/jamia/ocz121) | JAMIA | 2019 |
| [Linking Knowledge Discovery In Clinical Notes And Massive Biomedical Literature Repositories](https://ieeexplore.ieee.org/document/RelevantDocumentNumber) | IEEE | 2019 |
| [An Experimentation Platform for Precision Medicine](https://doi.org/10.1145/3331184.3331396) | ACM | 2019 |


### 2. Acquire – Extracting Evidence
#### Entity Extraction and Normalization
| Paper | Venue | Date |
|---|---|---|
| [Improving Disease Named Entity Recognition for Clinical Trial Matching](https://doi.org/10.1109/BIBM47256.2019.8983421) | BIBM | 2019 |
| [Evaluation of an artificial intelligence clinical trial matching system in Australian lung cancer patients](https://doi.org/10.1093/jamiaopen/ooaa002) | JAMIA Open | 2020 |
| [Linking Knowledge Discovery In Clinical Notes And Massive Biomedical Literature Repositories](https://doi.org/10.1109/BIBM47256.2019.8983242) | BIBM | 2019 |
| [srBERT: automatic article classification model for systematic review using BERT](https://doi.org/10.1186/s13643-021-01763-w) | BMC Systematic Reviews | 2021 |
| [Utilizing Large Language Models for Enhanced Clinical Trial Matching: A Study on Automation in Patient Screening](https://doi.org/10.7759/cureus.60044) | Cureus | 2024 |
| [Artificial intelligence tool for optimizing eligibility screening for clinical trials in a large community cancer center](https://doi.org/10.1200/CCI.19.00079) | JCO Clinical Cancer Informatics | 2020 |
| [Controversial Trials First: Identifying Disagreement Between Clinical Guidelines and New Evidence](https://pubmed.ncbi.nlm.nih.gov/35308948/) | AMIA | 2022 |
| [Developing a fully automated evidence synthesis tool for identifying, assessing and collating the evidence](https://doi.org/10.1136/bmjebm-2018-111126) | BMJ Evidence-Based Medicine | 2021 |
| [Improving reference prioritisation with PICO recognition](https://bmcmedinformdecismak.biomedcentral.com/articles/10.1186/s12911-019-0974-4) | BMC Medical Informatics and Decision Making | 2019 |
| [An approach for transgender population information extraction and summarization from clinical trial text](https://doi.org/10.1186/s12911-019-0768-1) | BMC Medical Informatics and Decision Making | 2019 |
| [Medical Knowledge Infused Convolutional Neural Networks for Cohort Selection in Clinical Trials](https://doi.org/10.1093/jamia/ocz128) | JAMIA | 2019 |
| [Clinical trial cohort selection based on multi-level rule-based natural language processing system](https://doi.org/10.1093/jamia/ocz109) | JAMIA | 2019 |
| [Creating and evaluating chatbots as eligibility assistants for clinical trials: An active deep learning approach towards user-centered classification](https://doi.org/10.1145/3403575) | ACM Transactions on Computing for Healthcare | 2021 |
| [Natural language processing for adjudication of heart failure in a multicenter clinical trial: A secondary analysis of a randomized clinical trial](https://doi.org/10.1001/jamacardio.2023.4859) | JAMA Cardiology | 2024 |
| [In Silico Drug Repurposing using Knowledge Graph Embeddings for Alzheimer's Disease](https://doi.org/10.1145/3569192.3569203) | ACM | 2022 |
| [AutoCriteria: a generalizable clinical trial eligibility criteria extraction system powered by large language models](https://doi.org/10.1093/jamia/ocad218) | JAMIA | 2024 |
| [Automating clinical trial eligibility screening: Quantitative analysis of GPT Models versus Human Expertise](https://doi.org/10.1145/3652037.3663922) | ACM | 2024 |
| [MSˆ2: Multi-Document Summarization of Medical Studies](https://doi.org/10.18653/v1/2021.emnlp-main.594) | EMNLP | 2021 |
| [Matching Patients to Accelerate Clinical Trials (MPACT) Enabling Technology for Oncology Clinical Trial Workflow](https://doi.org/10.3233/SHTI231132) | Studies in Health Technology and Informatics | 2024 |
| [The Leaf Clinical Trials Corpus: a new resource for query generation from clinical trial eligibility criteria](https://doi.org/10.1038/s41597-022-01521-0) | Scientific Data (Nature) | 2022 |
| [LeafAI: query generator for clinical cohort discovery rivaling a human programmer](https://doi.org/10.1093/jamia/ocad149) | JAMIA | 2023 |
| [Machine Learning Assisted Citation Screening for Systematic Reviews](https://doi.org/10.3233/SHTI200171) | Studies in Health Technology and Informatics | 2020 |
| [Not so weak PICO: leveraging weak supervision for participants, interventions, and outcomes recognition for systematic review automation](https://doi.org/10.1093/jamiaopen/ooac107) | JAMIA Open | 2023 |
| [PICO to PICOS: Weak Supervision to Extend Datasets with New Labels](https://doi.org/10.3233/SHTI240775) | Studies in Health Technology and Informatics | 2024 |
| [EMR2vec: Bridging the gap between patient data and clinical trial](https://doi.org/10.1016/j.cie.2021.107236) | Computers & Industrial Engineering | 2021 |
| [The anatomy of the SARS-CoV-2 biomedical literature: Introducing the CovidX network algorithm for drug repurposing recommendation](https://doi.org/10.2196/21169) | Journal of Medical Internet Research | 2020 |
| [AlpaPICO: Extraction of PICO frames from clinical trial documents using LLMs](https://doi.org/10.1016/j.ymeth.2024.04.005) | Methods | 2024 |
| [BLINKtextsubscriptLSTM: BioLinkBERT and LSTM based approach for extraction of PICO frame from Clinical Trial Text](https://doi.org/10.1145/3632410.3632442) | ACM | 2024 |
| [Towards autonomous living meta-analyses: A framework for automation of systematic review and meta-analyses](https://doi.org/10.3233/SHTI240427) | Studies in Health Technology and Informatics | 2024 |
| [Extractive summarization of clinical trial descriptions](https://doi.org/10.1016/j.ijmedinf.2019.05.019) | International Journal of Medical Informatics | 2019 |
| [The Use of Generative AI for Scientific Literature Searches for Systematic Reviews: ChatGPT and Microsoft Bing AI Performance Evaluation](https://doi.org/10.2196/51187) | Journal of Medical Internet Research | 2024 |
| [Matching patients to clinical trials using semantically enriched document representation](https://doi.org/10.1016/j.jbi.2020.103406) | Journal of Biomedical Informatics | 2020 |
| [Automatic knowledge graph population with model-complete text comprehension for pre-clinical outcomes in the field of spinal cord injury](https://doi.org/10.1016/j.artmed.2023.102491) | Artificial Intelligence in Medicine | 2023 |
| [Towards precise PICO extraction from abstracts of randomized controlled trials using a section-specific learning approach](https://doi.org/10.1093/bioinformatics/btad542) | Bioinformatics | 2023 |
| [Exploration of biomedical knowledge for recurrent glioblastoma using natural language processing deep learning models](https://doi.org/10.1186/s12911-022-02003-4) | BMC Medical Informatics and Decision Making | 2022 |
| [Using artificial intelligence to identify drugs for repurposing to treat l-DOPA induced dyskinesia](https://doi.org/10.1016/j.neuropharm.2024.109880) | Neuropharmacology | 2024 |
| [Implementation of Machine Learning Pipelines for Clinical Practice: Development and Validation Study](https://doi.org/10.2196/37833) | Journal of Medical Internet Research | 2022 |
| [Pretraining to recognize PICO Elements from Randomized Controlled Trial Literature](https://doi.org/10.3233/SHTI190209) | Studies in Health Technology and Informatics | 2019 |
| [UMLS-based data augmentation for natural language processing of clinical research literature](https://doi.org/10.1093/jamia/ocaa309) | JAMIA | 2021 |
| [EvidenceMap: a three-level knowledge representation for medical evidence computation and comprehension](https://doi.org/10.1093/jamia/ocad036) | JAMIA | 2023 |
| [Automated Matching of Patients to Clinical Trials: A Patient-Centric Natural Language Processing Approach for Pediatric Leukemia](https://doi.org/10.1200/CCI.23.00009) | JCO Clinical Cancer Informatics | 2023 |
| [TCGA-Reports: A machine-readable pathology report resource for benchmarking text-based AI models](https://doi.org/10.1016/j.patter.2024.100933) | Patterns | 2024 |
| [Data Mining of Free-Text Responses: An Innovative Approach to Analyzing Patient Perspectives on Chronic Rhinosinusitis with Nasal Polyps in a Phase IIa Proof-of-Concept Study for Dupilumab](https://doi.org/10.2147/PPA.S320242) | Patient Preference and Adherence | 2021 |
| [Parsable Clinical Trial Eligibility Criteria Representation Using Natural Language Processing](https://pubmed.ncbi.nlm.nih.gov/37128426/) | AMIA | 2023 |
| [Precision Medicine Search for Paediatric Oncology](https://doi.org/10.1145/3404835.3462792) | ACM | 2021 |
| [Automatic categorization of self-acknowledged limitations in randomized controlled trial publications](https://doi.org/10.1016/j.jbi.2024.104628) | Journal of Biomedical Informatics | 2024 |
| [Optimizing Clinical Trial Eligibility Design Using Natural Language Processing Models and Real-World Data: Algorithm Development and Validation](https://doi.org/10.2196/50800) | Journal of Medical Internet Research | 2024 |
| [A Comparison between Human and NLP-based Annotation of Clinical Trial Eligibility Criteria Text Using The OMOP Common Data Model](https://pubmed.ncbi.nlm.nih.gov/34457154/) | AMIA | 2021 |
| [A comparative study of pre-trained language models for named entity recognition in clinical trial eligibility criteria from multiple corpora](https://doi.org/10.1186/s12911-022-01967-7) | BMC Medical Informatics and Decision Making | 2022 |
| [Automated information extraction model enhancing traditional chinese medicine rct evidence extraction (evi-bert): algorithm development and validation](https://doi.org/https://doi.org/10.3389/frai.2024.1454945) | Frontiers in Artificial Intelligence | 2024 |
| [DQueST: dynamic questionnaire for search of clinical trials](https://doi.org/10.1093/jamia/ocz121) | JAMIA | 2019 |
| [A knowledge base of clinical trial eligibility criteria](https://doi.org/10.1016/j.jbi.2021.103771) | Journal of Biomedical Informatics | 2021 |
| [Evaluation of Criteria2Query: Towards Augmented Intelligence for Cohort Identification](https://doi.org/10.3233/SHTI220082) | Studies in Health Technology and Informatics | 2022 |
| [Impact of size, location, symptomatic-nature and gender on the rupture of saccular intracranial aneurysms](https://ieeexplore.ieee.org/document/8508274) | IEEE | 2018 |
| [In a pilot study, automated real-time systematic review updates were feasible, accurate, and work-saving](https://doi.org/10.1016/j.jclinepi.2022.08.013) | Journal of Clinical Epidemiology | 2023 |
| [Enhancing evidence-based medicine with natural language argumentative analysis of clinical trials](https://doi.org/10.1016/j.artmed.2021.102098) | Artificial Intelligence in Medicine | 2021 |
| [Piloting an automated clinical trial eligibility surveillance and provider alert system based on artificial intelligence and standard data models](https://doi.org/https://doi.org/10.1186/s12874-023-01916-6) | BMC Medical Research Methodology | 2023 |
| [Data-driven method to enhance craniofacial and oral phenotype vocabularies](https://doi.org/10.1016/j.adaj.2019.05.029) | Journal of the American Dental Association | 2019 |
| [Investigation into Scaling-Up the SOAP Problem-Oriented Medical Record into a Clinical Case Study](https://doi.org/10.1109/ICHI57859.2023.00134) | IEEE | 2023 |
| [Integrating a PICO clinical questioning to the QL4POMR framework for building evidence-based clinical case reports](https://doi.org/10.1109/bigdata59044.2023.10386854) | IEEE Big Data | 2023 |
| [Generative AI for evidence-based medicine: A PICO GenAI for synthesizing clinical case reports](https://doi.org/10.1109/icc51166.2024.10622271) | IEEE ICC | 2024 |
| [Automating clinical trial matches via natural language processing of synthetic electronic health records and clinical trial eligibility criteria](https://pubmed.ncbi.nlm.nih.gov/38827083/) | AMIA | 2024 |
| [Automatic data extraction to support meta-analysis statistical analysis: a case study on breast cancer](https://doi.org/10.1186/s12911-022-01897-4) | BMC Medical Informatics and Decision Making | 2022 |
| [Validating GAN-BioBERT: A Methodology for Assessing Reporting Trends in Clinical Trials](https://doi.org/10.3389/fdgth.2022.878369) | Frontiers in Digital Health | 2022 |
| [The suitability of UMLS and SNOMED-CT for encoding outcome concepts](https://doi.org/10.1093/jamia/ocad161) | JAMIA | 2023 |
| [A Real-Time Automated Patient Screening System for Clinical Trials Eligibility in an Emergency Department: Design and Evaluation](https://doi.org/10.2196/14185) | Journal of Medical Internet Research | 2019 |
| [Developing an Inpatient Electronic Medical Record Phenotype for Hospital-Acquired Pressure Injuries: Case Study Using Natural Language Processing Models](https://doi.org/10.2196/41264) | Journal of Medical Internet Research | 2023 |
| [Knowledge graph based platform of COVID-19 drugs and symptoms](https://doi.org/10.1145/3487351.3489484) | ACM | 2021 |
| [Clinical trial search: Using biomedical language understanding models for re-ranking](https://doi.org/10.1016/j.jbi.2020.103530) | Journal of Biomedical Informatics | 2020 |
| [ScanMedicine: An online search system for medical innovation](https://doi.org/10.1016/j.cct.2022.107042) | Contemporary Clinical Trials | 2023 |
| [Artificial intelligence clinical evidence engine for automatic identification, prioritization, and extraction of relevant clinical oncology research](https://doi.org/10.1200/CCI.20.00087) | JCO Clinical Cancer Informatics | 2021 |
| [An annotated corpus of clinical trial publications supporting schema-based relational information extraction](https://doi.org/10.1186/s13326-022-00271-7) | Journal of Biomedical Semantics | 2022 |
| [Cohort Selection for Clinical Trials From Longitudinal Patient Records: Text Mining Approach](https://doi.org/10.2196/15980) | Journal of Medical Internet Research | 2019 |
| [EBM+: Advancing Evidence-Based Medicine via two level automatic identification of Populations, Interventions, Outcomes in medical literature](https://doi.org/10.1016/j.artmed.2020.101949) | Artificial Intelligence in Medicine | 2020 |
| [TransforMED: End-to-End Transformers for Evidence-Based Medicine and Argument Mining in medical literature](https://doi.org/10.1016/j.jbi.2021.103767) | Journal of Biomedical Informatics | 2021 |
| [Transformer-based named entity recognition for parsing clinical trial eligibility criteria](https://doi.org/10.1145/3459930.3469560) | ACM | 2021 |
| [Parsing Clinical Trial Eligibility Criteria for Cohort Query by a Multi-Input Multi-Output Sequence Labeling Model](https://doi.org/10.1109/BIBM58861.2023.10385876) | IEEE BIBM | 2023 |
| [Natural Language Processing for Mimicking Clinical Trial Recruitment in Critical Care: A Semi-Automated Simulation Based on the LeoPARDS Trial](https://doi.org/10.1109/JBHI.2020.2977925) | IEEE Journal of Biomedical and Health Informatics | 2020 |
| [Improvement of intervention information detection for automated clinical literature screening during systematic review](https://doi.org/10.1016/j.jbi.2022.104185) | Journal of Biomedical Informatics | 2022 |
| [Extending PICO with Observation Normalization for Evidence Computing](https://doi.org/10.3233/SHTI220076) | Studies in Health Technology and Informatics | 2022 |
| [Hybrid bag of approaches to characterize selection criteria for cohort identification](https://doi.org/10.1093/jamia/ocz079) | JAMIA | 2019 |
| [Trial2Vec: Zero-shot clinical trial document similarity search using self-supervision](https://doi.org/10.18653/v1/2022.findings-emnlp.476) | EMNLP Findings | 2022 |
| [Evaluation of an artificial intelligence-based clinical trial matching system in Chinese patients with hepatocellular carcinoma: a retrospective study](https://doi.org/10.1186/s12885-024-11959-7) | BMC Cancer | 2024 |
| [Comparing generative and extractive approaches to information extraction from abstracts describing randomized clinical trials](https://doi.org/10.1186/s13326-024-00305-2) | Journal of Biomedical Semantics | 2024 |
| [Pre-trained language models with domain knowledge for biomedical extractive summarization](https://doi.org/10.1016/j.knosys.2022.109460) | Knowledge-Based Systems | 2022 |
| [OncoCTMiner: streamlining precision oncology trial matching via molecular profile analysis](https://doi.org/10.1093/database/baad077) | Oxford Database | 2023 |
| [Text classification of cancer clinical trial eligibility criteria](https://pmc.ncbi.nlm.nih.gov/articles/PMC10785908/) | AMIA | 2024 |
| [Batch enrollment for an artificial intelligence-guided intervention to lower neurologic events in patients with undiagnosed atrial fibrillation: rationale and design of a digital clinical trial](https://doi.org/10.1016/j.ahj.2021.05.006) | American Heart Journal | 2021 |
| [Large Language Models for Healthcare Data Augmentation: An Example on Patient-Trial Matching](https://pmc.ncbi.nlm.nih.gov/articles/PMC10785941/) | AMIA | 2024 |
| [MeDict-GP: An Accurate Entity Recognition Model Combining Medical Domain Knowledge and Globalization Ideas](https://doi.org/10.1145/3594315.3594360) | ACM | 2023 |
| [A span-based model for extracting overlapping PICO entities from RCT publications](https://doi.org/10.1093/jamia/ocae065) | JAMIA | 2024 |


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
| Paper | Venue | Date |
|---|---|---|
| [Developing a fully automated evidence synthesis tool for identifying, assessing and collating the evidence](https://doi.org/10.1136/bmjebm-2018-111126) | BMJ Evidence-Based Medicine | 2021 |
| [Machine Learning Assisted Citation Screening for Systematic Reviews](https://doi.org/10.3233/SHTI200171) | Studies in Health Technology and Informatics | 2020 |
| [The Use of Generative AI for Scientific Literature Searches for Systematic Reviews: ChatGPT and Microsoft Bing AI Performance Evaluation](https://doi.org/10.2196/51187) | Journal of Medical Internet Research | 2024 |
| [State-of-the-Art Evidence Retriever for Precision Medicine: Algorithm Development and Validation](https://doi.org/10.2196/40743) | Journal of Medical Internet Research | 2022 |
| [Automatic categorization of self-acknowledged limitations in randomized controlled trial publications](https://doi.org/10.1016/j.jbi.2024.104628) | Journal of Biomedical Informatics | 2024 |
| [Deep learning to refine the identification of high-quality clinical research articles from the biomedical literature: Performance evaluation](https://doi.org/10.1016/j.jbi.2023.104384) | Journal of Biomedical Informatics | 2023 |
| [Validating GAN-BioBERT: A Methodology for Assessing Reporting Trends in Clinical Trials](https://doi.org/10.3389/fdgth.2022.878369) | Frontiers in Digital Health | 2022 |
| [Transformer-based named entity recognition for parsing clinical trial eligibility criteria](https://doi.org/10.1145/3459930.3469560) | ACM | 2021 |
| [Utilizing ChatGPT as a scientific reasoning engine to differentiate conflicting evidence and summarize challenges in controversial clinical questions](https://doi.org/10.1093/jamia/ocae100) | JAMIA | 2024 |
| [OncoCTMiner: streamlining precision oncology trial matching via molecular profile analysis](https://doi.org/10.1093/database/baad077) | Oxford Database | 2023 |
| [Towards Automated Detection of Contradictory Research Claims in Medical Literature Using Deep Learning Approach](https://doi.org/10.1109/CAMP51653.2021.9498061) | IEEE | 2021 |


#### Evidence Ranking and Screening
| Paper | Venue | Date |
|---|---|---|
| [srBERT: automatic article classification model for systematic review using BERT](https://doi.org/10.1186/s13643-021-01763-w) | Systematic Reviews (BMC) | 2021 |
| [Improving reference prioritisation with PICO recognition](https://bmcmedinformdecismak.biomedcentral.com/articles/10.1186/s12911-019-0974-4) | BMC Medical Informatics and Decision Making | 2019 |
| [AutoCriteria: a generalizable clinical trial eligibility criteria extraction system powered by large language models](https://doi.org/10.1093/jamia/ocad218) | JAMIA | 2024 |
| [The anatomy of the SARS-CoV-2 biomedical literature: Introducing the CovidX network algorithm for drug repurposing recommendation](https://doi.org/10.2196/21169) | Journal of Medical Internet Research | 2020 |
| [Towards autonomous living meta-analyses: A framework for automation of systematic review and meta-analyses](https://doi.org/10.3233/SHTI240427) | Studies in Health Technology and Informatics | 2024 |
| [Matching patients to clinical trials with large language models](https://www.nature.com/articles/s41467-024-53081-z) | Nature Communications | 2024 |
| [Using artificial intelligence to identify drugs for repurposing to treat l-DOPA induced dyskinesia](https://doi.org/10.1016/j.neuropharm.2024.109880) | Neuropharmacology | 2024 |
| [A probabilistic precision information retrieval model for personalized clinical trial recommendation based on heterogeneous data](https://doi.org/10.1109/icccnt51525.2021.9579891) | IEEE ICCCNT | 2021 |
| [Automated Matching of Patients to Clinical Trials: A Patient-Centric Natural Language Processing Approach for Pediatric Leukemia](https://doi.org/10.1200/CCI.23.00009) | JCO Clinical Cancer Informatics | 2023 |
| [Cohort-based Clinical Trial Retrieval](https://doi.org/10.1145/3503516.3503529) | ACM | 2022 |
| [Automate clinical evidence synthesis by linking trials to publications with text analytics](https://doi.org/10.1145/3459104.3459168) | ACM | 2021 |
| [Piloting an automated clinical trial eligibility surveillance and provider alert system based on artificial intelligence and standard data models](https://doi.org/https://doi.org/10.1186/s12874-023-01916-6) | BMC Medical Research Methodology | 2023 |
| [Preliminary Comparison of the Performance of the National Library of Medicine's Systematic Review Publication Type and the Sensitive Clinical Queries Filter for Systematic Reviews in PubMed](https://doi.org/10.5195/jmla.2022.1286) | Journal of the Medical Library Association | 2022 |
| [An Experimentation Platform for Precision Medicine](https://doi.org/10.1145/3331184.3331396) | ACM | 2019 |
| [Measuring the impact of screening automation on meta-analyses of diagnostic test accuracy](https://doi.org/10.1186/s13643-019-1162-x) | Systematic Reviews (BMC) | 2019 |
| [Clinical trial search: Using biomedical language understanding models for re-ranking](https://doi.org/10.1016/j.jbi.2020.103530) | Journal of Biomedical Informatics | 2020 |
| [Artificial intelligence clinical evidence engine for automatic identification, prioritization, and extraction of relevant clinical oncology research](https://doi.org/10.1200/CCI.20.00087) | JCO Clinical Cancer Informatics | 2021 |
| [OncoCTMiner: streamlining precision oncology trial matching via molecular profile analysis](https://doi.org/10.1093/database/baad077) | Oxford Database | 2023 |



#### Evidence Synthesis
| Paper | Venue | Date |
|---|---|---|
| [Developing a fully automated evidence synthesis tool for identifying, assessing and collating the evidence](https://doi.org/10.1136/bmjebm-2018-111126) | BMJ Evidence-Based Medicine | 2021 |
| [Machine Learning Assisted Citation Screening for Systematic Reviews](https://doi.org/10.3233/SHTI200171) | Studies in Health Technology and Informatics | 2020 |
| [Towards autonomous living meta-analyses: A framework for automation of systematic review and meta-analyses](https://doi.org/10.3233/SHTI240427) | Studies in Health Technology and Informatics | 2024 |
| [Automatic knowledge graph population with model-complete text comprehension for pre-clinical outcomes in the field of spinal cord injury](https://doi.org/10.1016/j.artmed.2023.102491) | Artificial Intelligence in Medicine | 2023 |
| [EvidenceMap: a three-level knowledge representation for medical evidence computation and comprehension](https://doi.org/10.1093/jamia/ocad036) | JAMIA | 2023 |
| [In a pilot study, automated real-time systematic review updates were feasible, accurate, and work-saving](https://doi.org/10.1016/j.jclinepi.2022.08.013) | Journal of Clinical Epidemiology | 2023 |
| [Generative AI for evidence-based medicine: A PICO GenAI for synthesizing clinical case reports](https://doi.org/10.1109/icc51166.2024.10622271) | IEEE ICC | 2024 |
| [Automatic data extraction to support meta-analysis statistical analysis: a case study on breast cancer](https://doi.org/10.1186/s12911-022-01897-4) | BMC Medical Informatics and Decision Making | 2022 |
| [AutoTrial: Prompting Language Models for Clinical Trial Design](https://openreview.net/forum?id=E5r96sfKO0) | EMNLP | 2023 |
| [Utilizing ChatGPT as a scientific reasoning engine to differentiate conflicting evidence and summarize challenges in controversial clinical questions](https://doi.org/10.1093/jamia/ocae100) | JAMIA | 2024 |




#### Evidence Summarization
| Paper | Venue | Date |
|---|---|---|
| [An approach for transgender population information extraction and summarization from clinical trial text](https://doi.org/10.1186/s12911-019-0768-1) | BMC Medical Informatics and Decision Making | 2019 |
| [MSˆ2: Multi-Document Summarization of Medical Studies](https://doi.org/10.18653/v1/2021.emnlp-main.594) | EMNLP | 2021 |
| [Extractive summarization of clinical trial descriptions](https://doi.org/10.1016/j.ijmedinf.2019.05.019) | International Journal of Medical Informatics | 2019 |
| [Exploring ChatGPT's potential in facilitating adaptation of clinical guidelines: A case study of Diabetic Ketoacidosis guidelines](https://doi.org/10.7759/cureus.38784) | Cureus | 2023 |
| [TriSum: Learning summarization ability from large language models with structured rationale](https://aclanthology.org/2024.naacl-long.154.pdf) | NAACL | 2024 |
| [EvidenceMap: a three-level knowledge representation for medical evidence computation and comprehension](https://doi.org/10.1093/jamia/ocad036) | JAMIA | 2023 |
| [Text summarization of medical documents using abstractive techniques](https://doi.org/10.1109/icaaic56838.2023.10140885) | IEEE ICAAIC | 2023 |
| [Integrating a PICO clinical questioning to the QL4POMR framework for building evidence-based clinical case reports](https://doi.org/10.1109/bigdata59044.2023.10386854) | IEEE Big Data | 2023 |
| [Knowledge graph based platform of COVID-19 drugs and symptoms](https://doi.org/10.1145/3487351.3489484) | ACM | 2021 |
| [Automatically Summarizing Evidence from Clinical Trials: A Prototype Highlighting Current Challenges](https://pmc.ncbi.nlm.nih.gov/articles/PMC10361334/) | ACL | 2023 |
| [A light-weight text summarization system for fast access to medical evidence](https://doi.org/10.3389/fdgth.2020.585559) | Frontiers in Digital Health | 2020 |
| [Pre-trained language models with domain knowledge for biomedical extractive summarization](https://doi.org/10.1016/j.knosys.2022.109460) | Knowledge-Based Systems | 2022 |
| [Utilizing ChatGPT as a scientific reasoning engine to differentiate conflicting evidence and summarize challenges in controversial clinical questions](https://doi.org/10.1093/jamia/ocae100) | JAMIA | 2024 |




### 4. Apply & Assess – Adoption, refinement and research
#### Clinical Trial design and identification
| Paper | Venue | Date |
|---|---|---|
| [Improving Disease Named Entity Recognition for Clinical Trial Matching](https://doi.org/10.1109/BIBM47256.2019.8983421) | IEEE BIBM | 2019 |
| [Evaluation of an artificial intelligence clinical trial matching system in Australian lung cancer patients](https://doi.org/10.1093/jamiaopen/ooaa002) | JAMIA Open | 2020 |
| [Utilizing Large Language Models for Enhanced Clinical Trial Matching: A Study on Automation in Patient Screening](https://doi.org/10.7759/cureus.60044) | Cureus | 2024 |
| [Artificial intelligence tool for optimizing eligibility screening for clinical trials in a large community cancer center](https://doi.org/10.1200/CCI.19.00079) | JCO Clinical Cancer Informatics | 2020 |
| [Improving the Efficiency of Clinical Trial Recruitment Using an Ensemble Machine Learning to Assist With Eligibility Screening](https://doi.org/10.1002/acr2.11289) | ACR Open Rheumatology | 2021 |
| [An approach for transgender population information extraction and summarization from clinical trial text](https://doi.org/10.1186/s12911-019-0768-1) | BMC Medical Informatics and Decision Making | 2019 |
| [Medical Knowledge Infused Convolutional Neural Networks for Cohort Selection in Clinical Trials](https://doi.org/10.1093/jamia/ocz128) | JAMIA | 2019 |
| [Clinical trial cohort selection based on multi-level rule-based natural language processing system](https://doi.org/10.1093/jamia/ocz109) | JAMIA | 2019 |
| [Creating and evaluating chatbots as eligibility assistants for clinical trials: An active deep learning approach towards user-centered classification](https://doi.org/10.1145/3403575) | ACM | 2021 |
| [Natural language processing for adjudication of heart failure in a multicenter clinical trial: A secondary analysis of a randomized clinical trial](https://doi.org/10.1001/jamacardio.2023.4859) | JAMA Cardiology | 2024 |
| [Automating clinical trial eligibility screening: Quantitative analysis of GPT Models versus Human Expertise](https://doi.org/10.1145/3652037.3663922) | ACM | 2024 |
| [Matching Patients to Accelerate Clinical Trials (MPACT) Enabling Technology for Oncology Clinical Trial Workflow](https://doi.org/10.3233/SHTI231132) | Studies in Health Technology and Informatics | 2024 |
| [The Leaf Clinical Trials Corpus: a new resource for query generation from clinical trial eligibility criteria](https://doi.org/10.1038/s41597-022-01521-0) | Scientific Data | 2022 |
| [LeafAI: query generator for clinical cohort discovery rivaling a human programmer](https://doi.org/10.1093/jamia/ocad149) | JAMIA | 2023 |
| [EMR2vec: Bridging the gap between patient data and clinical trial](https://doi.org/10.1016/j.cie.2021.107236) | Computers & Industrial Engineering | 2021 |
| [Matching patients to clinical trials using semantically enriched document representation](https://doi.org/10.1016/j.jbi.2020.103406) | Journal of Biomedical Informatics | 2020 |
| [Automatic knowledge graph population with model-complete text comprehension for pre-clinical outcomes in the field of spinal cord injury](https://doi.org/10.1016/j.artmed.2023.102491) | Artificial Intelligence in Medicine | 2023 |
| [Matching patients to clinical trials with large language models](https://www.nature.com/articles/s41467-024-53081-z) | Nature Communications | 2024 |
| [A probabilistic precision information retrieval model for personalized clinical trial recommendation based on heterogeneous data](https://doi.org/10.1109/icccnt51525.2021.9579891) | IEEE ICCCNT | 2021 |
| [Implementation of Machine Learning Pipelines for Clinical Practice: Development and Validation Study](https://doi.org/10.2196/37833) | Journal of Medical Internet Research | 2022 |
| [Automated Matching of Patients to Clinical Trials: A Patient-Centric Natural Language Processing Approach for Pediatric Leukemia](https://doi.org/10.1200/CCI.23.00009) | JCO Clinical Cancer Informatics | 2023 |
| [Parsable Clinical Trial Eligibility Criteria Representation Using Natural Language Processing](https://pubmed.ncbi.nlm.nih.gov/37128426/) | AMIA | 2023 |
| [Cohort-based Clinical Trial Retrieval](https://doi.org/10.1145/3503516.3503529) | ACM | 2022 |
| [Chia, a large annotated corpus of clinical trial eligibility criteria](https://doi.org/10.1038/s41597-020-00620-0) | Scientific Data | 2020 |
| [Optimizing Clinical Trial Eligibility Design Using Natural Language Processing Models and Real-World Data: Algorithm Development and Validation](https://doi.org/10.2196/50800) | Journal of Medical Internet Research | 2024 |
| [A comparative study of pre-trained language models for named entity recognition in clinical trial eligibility criteria from multiple corpora](https://doi.org/10.1186/s12911-022-01967-7) | BMC Medical Informatics and Decision Making | 2022 |
| [A knowledge base of clinical trial eligibility criteria](https://doi.org/10.1016/j.jbi.2021.103771) | Journal of Biomedical Informatics | 2021 |
| [Evaluation of Criteria2Query: Towards Augmented Intelligence for Cohort Identification](https://doi.org/10.3233/SHTI220082) | Studies in Health Technology and Informatics | 2022 |
| [Piloting an automated clinical trial eligibility surveillance and provider alert system based on artificial intelligence and standard data models](https://doi.org/https://doi.org/10.1186/s12874-023-01916-6) | BMC Medical Research Methodology | 2023 |
| [Automating clinical trial matches via natural language processing of synthetic electronic health records and clinical trial eligibility criteria](https://pubmed.ncbi.nlm.nih.gov/38827083/) | AMIA | 2024 |
| [A Real-Time Automated Patient Screening System for Clinical Trials Eligibility in an Emergency Department: Design and Evaluation](https://doi.org/10.2196/14185) | Journal of Medical Internet Research | 2019 |
| [Distilling large language models for matching patients to clinical trials](https://doi.org/10.1093/jamia/ocae073) | JAMIA | 2024 |
| [Artificial intelligence clinical evidence engine for automatic identification, prioritization, and extraction of relevant clinical oncology research](https://doi.org/10.1200/CCI.20.00087) | JCO Clinical Cancer Informatics | 2021 |
| [Cohort selection for clinical trials using deep learning models](https://doi.org/10.1093/jamia/ocz139) | JAMIA | 2019 |
| [Cohort Selection for Clinical Trials From Longitudinal Patient Records: Text Mining Approach](https://doi.org/10.2196/15980) | Journal of Medical Internet Research | 2019 |
| [Transformer-based named entity recognition for parsing clinical trial eligibility criteria](https://doi.org/10.1145/3459930.3469560) | ACM | 2021 |
| [Parsing Clinical Trial Eligibility Criteria for Cohort Query by a Multi-Input Multi-Output Sequence Labeling Model](https://doi.org/10.1109/BIBM58861.2023.10385876) | IEEE BIBM | 2023 |
| [Natural Language Processing for Mimicking Clinical Trial Recruitment in Critical Care: A Semi-Automated Simulation Based on the LeoPARDS Trial](https://doi.org/10.1109/JBHI.2020.2977925) | IEEE Journal of Biomedical and Health Informatics | 2020 |
| [Automatic Assessment of Patient Eligibility by Utilizing NLP and Rule-Based Analysis](https://doi.org/10.1109/EMBC40787.2023.10340494) | IEEE EMBC | 2023 |
| [Hybrid bag of approaches to characterize selection criteria for cohort identification](https://doi.org/10.1093/jamia/ocz079) | JAMIA | 2019 |
| [AutoTrial: Prompting Language Models for Clinical Trial Design](https://doi.org/10.18653/v1/2023.emnlp-main.766) | EMNLP | 2023 |
| [Text classification of cancer clinical trial eligibility criteria](https://pmc.ncbi.nlm.nih.gov/articles/PMC10785908/) | AMIA | 2024 |
| [Batch enrollment for an artificial intelligence-guided intervention to lower neurologic events in patients with undiagnosed atrial fibrillation: rationale and design of a digital clinical trial](https://doi.org/10.1016/j.ahj.2021.05.006) | American Heart Journal | 2021 |
| [Large Language Models for Healthcare Data Augmentation: An Example on Patient-Trial Matching](https://pmc.ncbi.nlm.nih.gov/articles/PMC10785941/) | AMIA | 2024 |
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
