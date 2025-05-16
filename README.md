# Awesome - Natural Language Processing in Support of Evidence-based Medicine

A curated list of Natural Language Processing (NLP) research papers in the field of Evidence-Based Medicine (EBM).  

This list is based on the scoping review **“Natural Language Processing in Support of Evidence-Based Medicine: A Scoping Review”** (ACL 2025 submission), which surveyed **129 peer-reviewed publications** from 2019–2024.

The growth of medical literature demands automated tools to support clinicians in searching, appraising, synthesizing, and applying evidence in clinical practice. NLP is at the core of this transformation.

## Table of Contents

- [Ask – Search and Question Formulation](#1-ask--search-and-question-formulation)
  - [Keyword-based search](#keyword-based-search)
  - [Query generation](#query-generation)
  - [Clinical question answering](#clinical-question-answering)

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

# Acknowledgement
This project was sponsored by the National Library of Medicine grant R01LM009886, R01LM014344, and R01LM014573.

## NLP techniques for EBM

### 1. Ask – Search and Question Formulation
  - **{A2A}: a platform for research in biomedical literature search** (2020), Rybinski, Maciej et al. 
  - **Chia, a large annotated corpus of clinical trial eligibility criteria** (2020), Kury, Fabrício et al. 
  - **A span-based model for extracting overlapping {PICO} entities from {RCT} publications** (2024), Zhang, Gongbo et al. 
  - **Automate clinical evidence synthesis by linking trials to publications with text analytics** (2021), Li, Chao et al. 
  - **A probabilistic precision information retrieval model for personalized clinical trial recommendation based on heterogeneous data** (2021), Kamath, Sowmya et al. 
  - **Deep learning to refine the identification of high-quality clinical research articles from the biomedical literature: Performance evaluation** (2023), Lokker, Cynthia et al.
  - **Improvement of intervention information detection for automated clinical literature screening during systematic review** (2022), Tsubota, Tadashi et al.  
  - **In a pilot study, automated real-time systematic review updates were feasible, accurate, and work-saving** (2023), Marshall, Iain J et al. 
  - **{COVID}-19 trial graph: a linked graph for {COVID}-19 clinical trials** (2021), Du, Jingcheng et al. 
  - **{Trial2Vec}: Zero-shot clinical trial document similarity search using self-supervision** (2022), Wang, Zifeng et al. 

### 2. Acquire – Extracting Evidence

#### Entity Extraction and Normalization
  - **Text classification of cancer clinical trial eligibility criteria** (2023), Yang, Yumeng et al.
  - **Hybrid bag of approaches to characterize selection criteria for cohort identification** (2019), Vydiswaran, V G Vinod et al. 
  - **Evaluation of an artificial intelligence clinical trial matching system in Australian lung cancer patients** (2020), Alexander, Marliese et al. 
  - **Chia, a large annotated corpus of clinical trial eligibility criteria** (2020), Kury, Fabrício et al. 
  - **Evaluation of an artificial intelligence-based clinical trial matching system in Chinese patients with hepatocellular carcinoma: a retrospective study** (2024), Wang, Kunyuan et al. 
  - **Extractive summarization of clinical trial descriptions** (2019), Gulden, Christian et al. 
  - **{AlpaPICO}: Extraction of {PICO} frames from clinical trial documents using {LLMs}** (2024), Ghosh, Madhusudan et al. 
  - **Comparing generative and extractive approaches to information extraction from abstracts describing randomized clinical trials** (2024), Witte, Christian et al. 
  - **A span-based model for extracting overlapping {PICO} entities from {RCT} publications** (2024), Zhang, Gongbo et al. 
  - **Generative {AI} for evidence-based medicine: A {PICO} {GenAI} for synthesizing clinical case reports** (2024), Mohammed, Sabah et al. 
  - **Automating clinical trial matches via natural language processing of synthetic electronic health records and clinical trial eligibility criteria** (2024), Murcia, Victor M et al. 
  - **The suitability of {UMLS} and {SNOMED}-{CT} for encoding outcome concepts** (2023), Newbury, Abigail et al. 
  - **Pre-trained language models with domain knowledge for biomedical extractive summarization** (2022), Xie, Qianqian et al. 
  - **Exploration of biomedical knowledge for recurrent glioblastoma using natural language processing deep learning models** (2022), Jang, Bum-Sup et al. 
  - **{TransforMED}: End-to-End Transformers for Evidence-Based Medicine and Argument Mining in medical literature** (2021), Stylianou, Nikolaos et al. 
  - **Transformer-based named entity recognition for parsing clinical trial eligibility criteria** (2021), Tian, Shubo et al. 
  - **Evaluation of {Criteria2Query}: Towards Augmented Intelligence for cohort identification** (2022), Liu, Cong et al. 
  - **Improvement of intervention information detection for automated clinical literature screening during systematic review** (2022), Tsubota, Tadashi et al. 
  - **An approach for transgender population information extraction and summarization from clinical trial text** (2019), Chen, Boyu et al.
  - **Artificial intelligence tool for optimizing eligibility screening for clinical trials in a large community cancer center** (2020), Beck, J Thaddeus et al. 
  - **{srBERT}: automatic article classification model for systematic review using {BERT}** (2021), Aum, Sungmin et al. 
  - **In a pilot study, automated real-time systematic review updates were feasible, accurate, and work-saving** (2023), Marshall, Iain J et al. 
  - **Matching Patients to Accelerate Clinical Trials ({MPACT}): Enabling technology for oncology clinical trial workflow** (2024), Do, Nhan V et al. 
  - **Pretraining to recognize {PICO} elements from randomized controlled trial literature** (2019), Kang, Tian et al. 
  - **{BLINKtextsubscriptLSTM}: {BioLinkBERT} and {LSTM} based approach for extraction of {PICO} frame from Clinical Trial Text** (2024), Ghosh, Madhusudan et al. 
  - **Natural language processing for adjudication of heart failure in a multicenter clinical trial: A secondary analysis of a randomized clinical trial** (2024), Cunningham, Jonathan W et al.
  - **{EvidenceMap}: a three-level knowledge representation for medical evidence computation and comprehension** (2023), Kang, Tian et al. 
  - **{MSˆ2}: Multi-Document Summarization of Medical Studies** (2021), DeYoung, Jay et al. 
  - **{OncoCTMiner}: streamlining precision oncology trial matching via molecular profile analysis** (2023), Xu, Quan et al. 
  - **An annotated corpus of clinical trial publications supporting schema-based relational information extraction** (2022), Sanchez-Graillet, Olivia et al. 
  - **The anatomy of the {SARS}-{CoV}-2 biomedical literature: Introducing the {CovidX} network algorithm for drug repurposing recommendation** (2020), Gates, Lyndsey Elaine et al.
  - **Automatic data extraction to support meta-analysis statistical analysis: a case study on breast cancer** (2022), Mutinda, Faith Wavinya et al.  
  - **Developing a fully automated evidence synthesis tool for identifying, assessing and collating the evidence** (2021), Brassey, Jon et al. 
  - **Automating clinical trial eligibility screening: Quantitative analysis of {GPT} models versus human expertise** (2024), Devi, Arti et al. 
  - **Developing a fully automated evidence synthesis tool for identifying, assessing and collating the evidence** (2021), Brassey, Jon et al. 
  - **Automatic categorization of self-acknowledged limitations in randomized controlled trial publications** (2024), Lan, Mengfei et al. 
  - **Integrating a {PICO} clinical questioning to the {QL4POMR} framework for building evidence-based clinical case reports** (2023), Mohammed, Sabah et al. 
  - **The Leaf Clinical Trials Corpus: a new resource for query generation from clinical trial eligibility criteria** (2022), Dobbins, Nicholas J et al. 
  - **{Trial2Vec}: Zero-shot clinical trial document similarity search using self-supervision** (2022), Wang, Zifeng et al. 
  - **Artificial intelligence clinical evidence engine for automatic identification, prioritization, and extraction of relevant clinical oncology research** (2021), Saiz, Fernando Suarez et al. 
  - **Using artificial intelligence to identify drugs for repurposing to treat l-{DOPA}-induced dyskinesia** (2024), Johnston, Tom H et al. 
  - **Towards autonomous living meta-analyses: A framework for automation of systematic review and meta-analyses** (2024), Górska, Anna et al. 
  - **In Silico Drug Repurposing using Knowledge Graph Embeddings for Alzheimer's Disease** (2022), Daluwatumulle, Geesa et al. 
  - **In Silico Drug Repurposing using Knowledge Graph Embeddings for Alzheimer's Disease** (2022), Daluwatumulle, Geesa et al. 

#### Relation Extraction
  - **{AutoTrial}: Prompting Language Models for Clinical Trial Design** (2023), Wang, Zifeng et al. 
  - **Evaluation of {Criteria2Query}: Towards Augmented Intelligence for cohort identification** (2022), Liu, Cong et al. 
  - **An approach for transgender population information extraction and summarization from clinical trial text** (2019), Chen, Boyu et al.
  - **{srBERT}: automatic article classification model for systematic review using {BERT}** (2021), Aum, Sungmin et al. 
  - **{MSˆ2}: Multi-Document Summarization of Medical Studies** (2021), DeYoung, Jay et al. 
  - **The Leaf Clinical Trials Corpus: a new resource for query generation from clinical trial eligibility criteria** (2022), Dobbins, Nicholas J et al. 
  - **In Silico Drug Repurposing using Knowledge Graph Embeddings for Alzheimer's Disease** (2022), Daluwatumulle, Geesa et al. 

### 3. Appraise, Synthesize, and Summarization
#### Quality Assessment
  - **Transformer-based named entity recognition for parsing clinical trial eligibility criteria** (2021), Tian, Shubo et al. 
  - **Deep learning to refine the identification of high-quality clinical research articles from the biomedical literature: Performance evaluation** (2023), Lokker, Cynthia et al. 
  - **{OncoCTMiner}: streamlining precision oncology trial matching via molecular profile analysis** (2023), Xu, Quan et al. 
  - **Developing a fully automated evidence synthesis tool for identifying, assessing and collating the evidence** (2021), Brassey, Jon et al. 
  - **Automatic categorization of self-acknowledged limitations in randomized controlled trial publications** (2024), Lan, Mengfei et al. 

#### Evidence Ranking and Screening
  - **Automate clinical evidence synthesis by linking trials to publications with text analytics** (2021), Li, Chao et al. 
  - **A probabilistic precision information retrieval model for personalized clinical trial recommendation based on heterogeneous data** (2021), Kamath, Sowmya et al. 
  - **{srBERT}: automatic article classification model for systematic review using {BERT}** (2021), Aum, Sungmin et al. 
  - **Measuring the impact of screening automation on meta-analyses of diagnostic test accuracy** (2019), Norman, Christopher R et al. 
  - **{OncoCTMiner}: streamlining precision oncology trial matching via molecular profile analysis** (2023), Xu, Quan et al. 
  - **The anatomy of the {SARS}-{CoV}-2 biomedical literature: Introducing the {CovidX} network algorithm for drug repurposing recommendation** (2020), Gates, Lyndsey Elaine et al. 
  - **Clinical trial search: Using biomedical language understanding models for re-ranking** (2020), Rybinski, Maciej et al. 
  - **Artificial intelligence clinical evidence engine for automatic identification, prioritization, and extraction of relevant clinical oncology research** (2021), Saiz, Fernando Suarez et al. 
  - **Using artificial intelligence to identify drugs for repurposing to treat l-{DOPA}-induced dyskinesia** (2024), Johnston, Tom H et al. 
  - **Towards autonomous living meta-analyses: A framework for automation of systematic review and meta-analyses** (2024), Górska, Anna et al. 

#### Evidence Synthesis
  - **{AutoTrial}: Prompting Language Models for Clinical Trial Design** (2023), Wang, Zifeng et al. 
  - **Generative {AI} for evidence-based medicine: A {PICO} {GenAI} for synthesizing clinical case reports** (2024), Mohammed, Sabah et al. 
  - **In a pilot study, automated real-time systematic review updates were feasible, accurate, and work-saving** (2023), Marshall, Iain J et al. 
  - **{EvidenceMap}: a three-level knowledge representation for medical evidence computation and comprehension** (2023), Kang, Tian et al. 
  - **Automatic data extraction to support meta-analysis statistical analysis: a case study on breast cancer** (2022), Mutinda, Faith Wavinya et al. 
  - **Developing a fully automated evidence synthesis tool for identifying, assessing and collating the evidence** (2021), Brassey, Jon et al. 
  - **Towards autonomous living meta-analyses: A framework for automation of systematic review and meta-analyses** (2024), Górska, Anna et al. 

#### Evidence Summarization
  - **{TriSum}: Learning summarization ability from large language models with structured rationale** (2024), Jiang, Pengcheng et al. 
  - **Extractive summarization of clinical trial descriptions** (2019), Gulden, Christian et al. 
  - **Pre-trained language models with domain knowledge for biomedical extractive summarization** (2022), Xie, Qianqian et al. 
  - **An approach for transgender population information extraction and summarization from clinical trial text** (2019), Chen, Boyu et al.
  - **{EvidenceMap}: a three-level knowledge representation for medical evidence computation and comprehension** (2023), Kang, Tian et al. 
  - **Exploring {ChatGPT}'s potential in facilitating adaptation of clinical guidelines: A case study of Diabetic Ketoacidosis guidelines** (2023), Hamed, Ehab et al. 
  - **{MSˆ2}: Multi-Document Summarization of Medical Studies** (2021), DeYoung, Jay et al. 
  - **A light-weight text summarization system for fast access to medical evidence** (2020), Sarker, Abeed et al. 
  - **Integrating a {PICO} clinical questioning to the {QL4POMR} framework for building evidence-based clinical case reports** (2023), Mohammed, Sabah et al. 
  - **Text summarization of medical documents using abstractive techniques** (2023), Lalitha, Evani et al. 

### 4. Apply & Assess – Adoption, refinement and research

#### Clinical Trial design and identification
  - **{AutoTrial}: Prompting Language Models for Clinical Trial Design** (2023), Wang, Zifeng et al. 
  - **Text classification of cancer clinical trial eligibility criteria** (2023), Yang, Yumeng et al.
  - **Hybrid bag of approaches to characterize selection criteria for cohort identification** (2019), Vydiswaran, V G Vinod et al. 
  - **Evaluation of an artificial intelligence clinical trial matching system in Australian lung cancer patients** (2020), Alexander, Marliese et al. 
  - **Automating clinical trial matches via natural language processing of synthetic electronic health records and clinical trial eligibility criteria** (2024), Murcia, Victor M et al. 
  - **A probabilistic precision information retrieval model for personalized clinical trial recommendation based on heterogeneous data** (2021), Kamath, Sowmya et al. 
  - **Transformer-based named entity recognition for parsing clinical trial eligibility criteria** (2021), Tian, Shubo et al. 
  - **Evaluation of {Criteria2Query}: Towards Augmented Intelligence for cohort identification** (2022), Liu, Cong et al. 
  - **An approach for transgender population information extraction and summarization from clinical trial text** (2019), Chen, Boyu et al.
  - **Artificial intelligence tool for optimizing eligibility screening for clinical trials in a large community cancer center** (2020), Beck, J Thaddeus et al. 
  - **Matching Patients to Accelerate Clinical Trials ({MPACT}): Enabling technology for oncology clinical trial workflow** (2024), Do, Nhan V et al. 
  - **Automating clinical trial eligibility screening: Quantitative analysis of {GPT} models versus human expertise** (2024), Devi, Arti et al. 
  - **The Leaf Clinical Trials Corpus: a new resource for query generation from clinical trial eligibility criteria** (2022), Dobbins, Nicholas J et al. 
  - **Artificial intelligence clinical evidence engine for automatic identification, prioritization, and extraction of relevant clinical oncology research** (2021), Saiz, Fernando Suarez et al. 
  - **In Silico Drug Repurposing using Knowledge Graph Embeddings for Alzheimer's Disease** (2022), Daluwatumulle, Geesa et al. 

#### Question Answering
  - **{TriSum}: Learning summarization ability from large language models with structured rationale** (2024), Jiang, Pengcheng et al. 
  - **Generative {AI} for evidence-based medicine: A {PICO} {GenAI} for synthesizing clinical case reports** (2024), Mohammed, Sabah et al. 
  - **Aesthetic surgery advice and counseling from artificial intelligence: A rhinoplasty consultation with {ChatGPT}** (2023), Xie, Yi et al. 
  - **Exploration of biomedical knowledge for recurrent glioblastoma using natural language processing deep learning models** (2022), Jang, Bum-Sup et al. 
  - **Retrieval Augmented Generation enabled generative pre-trained transformer 4 ({GPT}-4) performance for clinical trial screening** (2024), Unlu, Ozan et al. 
  - **Performance of {ChatGPT} in answering clinical questions on the practical guideline of blepharoptosis** (2024), Shiraishi, Makoto et al. 
  - **Natural language processing for adjudication of heart failure in a multicenter clinical trial: A secondary analysis of a randomized clinical trial** (2024), Cunningham, Jonathan W et al.
  - **Exploring {ChatGPT}'s potential in facilitating adaptation of clinical guidelines: A case study of Diabetic Ketoacidosis guidelines** (2023), Hamed, Ehab et al. 
  - **Development and evaluation of a large language model of ophthalmology in Chinese** (2024), Zheng, Ce et al. 
  - **Knowledge graph based platform of {COVID}-19 drugs and symptoms** (2021), Pan, Zhenhe et al. 
---

### EBM Benchmark Datasets
  - **Trialstreamer: A living, automatically updated database of clinical trial reports** (2020), Marshall, Iain J et al. 
  - **{MSˆ2}: Multi-Document Summarization of Medical Studies** (2021), DeYoung, Jay et al. 
  - **The Leaf Clinical Trials Corpus: a new resource for query generation from clinical trial eligibility criteria** (2022), Dobbins, Nicholas J et al. 

## 📄 Citation

If you find this useful, please cite our scoping review:

```bibtex

,@ARTICLE{Li2022-kv,
  title = "A comparative study of pre-trained language models for named entity recognition in clinical trial eligibility criteria from multiple corpora",
  author = "Li, Jianfu and Wei, Qiang and Ghiasvand, Omid and Chen, Miao and Lobanov, Victor and Weng, Chunhua and Xu, Hua",
  journal = "BMC Med. Inform. Decis. Mak.",
  publisher = "Springer Science and Business Media LLC",
  volume =  22,
  number = "Suppl 3",
  pages =  235,
  month =  "6~" # sep,
  year =  2022,
  doi = "10.1186/s12911-022-01967-7",
  pmc = "PMC9450226",
  pmid =  36068551,
  issn = "1472-6947"
}
,@ARTICLE{Segura-Bedmar2019-kj,
  title = "Cohort selection for clinical trials using deep learning models",
  author = "Segura-Bedmar, Isabel and Raez, Pablo",
  journal = "J. Am. Med. Inform. Assoc.",
  publisher = "Oxford University Press (OUP)",
  volume =  26,
  number =  11,
  pages = "1181--1188",
  month =  "1~" # nov,
  year =  2019,
  doi = "10.1093/jamia/ocz139",
  pmc = "PMC6798560",
  pmid =  31532478,
  issn = "1067-5027,1527-974X"
}
,@ARTICLE{Jin2024-cf,
  title = "Matching patients to clinical trials with large language models",
  author = "Jin, Qiao and Wang, Zifeng and Floudas, Charalampos S and Chen, Fangyuan and Gong, Changlin and Bracken-Clarke, Dara and Xue, Elisabetta and Yang, Yifan and Sun, Jimeng and Lu, Zhiyong",
  journal = "ArXiv",
  month =  "27~" # apr,
  year =  2024,
  pmc = "PMC10418514",
  pmid =  37576126,
  issn = "2331-8422"
}
,@ARTICLE{Hu2023-zc,
  title = "Towards precise {PICO} extraction from abstracts of randomized controlled trials using a section-specific learning approach",
  author = "Hu, Yan and Keloth, Vipina K and Raja, Kalpana and Chen, Yong and Xu, Hua",
  journal = "Bioinformatics",
  publisher = "Oxford Academic",
  volume =  39,
  number =  9,
  pages = "btad542",
  month =  "5~" # sep,
  year =  2023,
  doi = "10.1093/bioinformatics/btad542",
  pmc = "PMC10500081",
  pmid =  37669123,
  issn = "1367-4803,1367-4811"
}
,@ARTICLE{Chuan2021-np,
  title = "Creating and evaluating chatbots as eligibility assistants for clinical trials: An active deep learning approach towards user-centered classification",
  author = "Chuan, Ching-Hua and Morgan, Susan",
  journal = "ACM Trans. Comput. Healthc.",
  publisher = "Association for Computing Machinery (ACM)",
  volume =  2,
  number =  1,
  pages = "1--19",
  month =  "31~" # jan,
  year =  2021,
  doi = "10.1145/3403575",
  issn = "2691-1957,2637-8051"
}
@article{picodef,
  title={Appearance of Population, Intervention, Comparison, and Outcome as research question in the title of articles of three different anesthesia journals: A pilot study},
  author={Eldawlatly, Abdelazeem and Alshehri, Hussain and Alqahtani, Abdullah and Ahmad, Abdulaziz and Al-Dammas, Fatma and Marzouk, Amir},
  journal={Saudi Journal of Anaesthesia},
  volume={12},
  number={2},
  pages={283--286},
  year={2018},
  publisher={Wolters Kluwer -- Medknow Publications},
  doi={10.4103/sja.SJA_767_17}
}
@article{EBM-NLP,
  title={A Corpus with Multi-Level Annotations of Patients, Interventions and Outcomes to Support Language Processing for Medical Literature},
  author={Benjamin Nye and Junyi Jessy Li and Roma Patel and Yinfeng Yang and Jain Marshall and Ani Nenkova and Byron C. Wallace},
  journal={Proceedings of the Conference on Computational Linguistics and Clinical Psychology: From Linguistic Signal to Clinical Reality},
  year={2018},
  pages={197--207},
  month={July},
  note={Author manuscript; available in PMC 2018 Oct 8. Published in final edited form as: Proc Conf Assoc Comput Linguist Meet.},
  pmcid={PMC6174533},
  nihmsid={NIHMS988059},
  pmid={30305770},
 }
@article{CT-EBM-SP,
  title={A clinical trials corpus annotated with UMLS entities to enhance the access to evidence-based medicine},
  author={Leonardo Campillos-Llanos and Ana Valverde-Mateos and Adri{\'a}n Capllonch-Carri{\'o}n and Antonio Moreno-Sandoval},
  journal={BMC Medical Informatics and Decision Making},
  volume={21},
  number={69},
  year={2021},
  doi={10.1186/s12911-021-01395-z},
  pmcid={PMC7898014},
  pmid={33618727},
  note={This article has been corrected. See BMC Med Inform Decis Mak. 2021 Apr 7;21:118.},
  url={https://doi.org/10.1186/s12911-021-01395-z}
}
@misc{NICTA-PIBOSO,
  author = {Su Nam Kim and David Martinez and Lawrence Cavedon and Lars Yencken},
  title = {NICTA-PIBOSO dataset},
  year = {2024},
  howpublished = {\url{https://doi.org/10.57702/ne4r48m1}},
  doi = {10.57702/ne4r48m1},
  note = {Dataset consists of 1,000 medical abstracts manually annotated with semantic tags based on the PICO criteria to support the automatic classification of sentences.},
  url = {https://doi.org/10.57702/ne4r48m1}
}
@inproceedings{Limsi-Cochrane,
    title = "A distantly supervised dataset for automated data extraction from diagnostic studies",
    author = "Norman, Christopher  and
      Leeflang, Mariska  and
      Spijker, Ren{\'e}  and
      Kanoulas, Evangelos  and
      N{\'e}v{\'e}ol, Aur{\'e}lie",
    editor = "Demner-Fushman, Dina  and
      Cohen, Kevin Bretonnel  and
      Ananiadou, Sophia  and
      Tsujii, Junichi",
    booktitle = "Proceedings of the 18th BioNLP Workshop and Shared Task",
    month = aug,
    year = "2019",
    address = "Florence, Italy",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/W19-5012",
    doi = "10.18653/v1/W19-5012",
    pages = "105--114",
    abstract = "Systematic reviews are important in evidence based medicine, but are expensive to produce. Automating or semi-automating the data extraction of index test, target condition, and reference standard from articles has the potential to decrease the cost of conducting systematic reviews of diagnostic test accuracy, but relevant training data is not available. We create a distantly supervised dataset of approximately 90,000 sentences, and let two experts manually annotate a small subset of around 1,000 sentences for evaluation. We evaluate the performance of BioBERT and logistic regression for ranking the sentences, and compare the performance for distant and direct supervision. Our results suggest that distant supervision can work as well as, or better than direct supervision on this problem, and that distantly trained models can perform as well as, or better than human annotators.",
}

@inproceedings{PICO-corpus,
    title = "{PICO} Corpus: A Publicly Available Corpus to Support Automatic Data Extraction from Biomedical Literature",
    author = "Mutinda, Faith  and
      Liew, Kongmeng  and
      Yada, Shuntaro  and
      Wakamiya, Shoko  and
      Aramaki, Eiji",
    editor = "Ghosal, Tirthankar  and
      Blanco-Cuaresma, Sergi  and
      Accomazzi, Alberto  and
      Patton, Robert M.  and
      Grezes, Felix  and
      Allen, Thomas",
    booktitle = "Proceedings of the first Workshop on Information Extraction from Scientific Publications",
    month = nov,
    year = "2022",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2022.wiesp-1.4",
    doi = "10.18653/v1/2022.wiesp-1.4",
    pages = "26--31",
    abstract = "We present a publicly available corpus with detailed annotations describing the core elements of clinical trials: Participants, Intervention, Control, and Outcomes. The corpus consists of 1011 abstracts of breast cancer randomized controlled trials extracted from the PubMed database. The corpus improves previous corpora by providing detailed annotations for outcomes to identify numeric texts that report the number of participants that experience specific outcomes. The corpus will be helpful for the development of systems for automatic extraction of data from randomized controlled trial literature to support evidence-based medicine. Additionally, we demonstrate the feasibility of the corpus by using two strong baselines for named entity recognition task. Most of the entities achieve F1 scores greater than 0.80 demonstrating the quality of the dataset.",
}
@article{MediGPT,
  title={MediGPT: Exploring Potentials of Conventional and Large Language Models on Medical Data},
  author={Mohammad Abu Tareq Rony and Mohammad Shariful Islam and Tipu Sultan and Samah Alshathri and Walid El-Shafai},
  journal={IEEE Access},
  volume={12},
  year={2023},
  publisher={IEEE},
  doi={10.1109/ACCESS.2024.3428918},
  url={https://ieeexplore.ieee.org/document/10599190/}
}

@inproceedings{EliIE,
    title = "We Understand Elliptical Sentences, and Language Models should Too: A New Dataset for Studying Ellipsis and its Interaction with Thematic Fit",
    author = "Testa, Davide  and
      Chersoni, Emmanuele  and
      Lenci, Alessandro",
    editor = "Rogers, Anna  and
      Boyd-Graber, Jordan  and
      Okazaki, Naoaki",
    booktitle = "Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)",
    month = jul,
    year = "2023",
    address = "Toronto, Canada",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2023.acl-long.188",
    doi = "10.18653/v1/2023.acl-long.188",
    pages = "3340--3353",
    abstract = "Ellipsis is a linguistic phenomenon characterized by the omission of one or more sentence elements. Solving such a linguistic construction is not a trivial issue in natural language processing since it involves the retrieval of non-overtly expressed verbal material, which might in turn require the model to integrate human-like syntactic and semantic knowledge. In this paper, we explored the issue of how the prototypicality of event participants affects the ability of Language Models (LMs) to handle elliptical sentences and to identify the omitted arguments at different degrees of thematic fit, ranging from highly typical participants to semantically anomalous ones. With this purpose in mind, we built ELLie, the first dataset composed entirely of utterances containing different types of elliptical constructions, and structurally suited for evaluating the effect of argument thematic fit in solving ellipsis and reconstructing the missing element. Our tests demonstrated that the probability scores assigned by the models are higher for typical events than for atypical and impossible ones in different elliptical contexts, confirming the influence of prototypicality of the event participants in interpreting such linguistic structures. Finally, we conducted a retrieval task of the elided verb in the sentence in which the low performance of LMs highlighted a considerable difficulty in reconstructing the correct event.",
}
@inproceedings{SIGIR,
  title={A test collection for matching patients to clinical trials},
  author={Bevan Koopman and Guido Zuccon},
  booktitle={Proceedings of the 39th International ACM SIGIR Conference on Research and Development in Information Retrieval},
  year={2016},
  pages={669--672},
  address={Pisa, Italy},
  organization={SIGIR 2016},
  url={https://doi.org/10.1145/2911451.2914672}
}
@article{NCBI,
  title={NCBI disease corpus: A resource for disease name recognition and concept normalization},
  author={Rezarta Islamaj Do{\u{g}}an and Robert Leaman and Zhiyong Lu},
  journal={Journal of Biomedical Informatics},
  volume={47},
  pages={1-10},
  year={2014},
  month={February},
  publisher={Elsevier},
  doi={10.1016/j.jbi.2013.12.006},
  url={https://doi.org/10.1016/j.jbi.2013.12.006}
}
@inproceedings{GGPONC,
    title = "{GGPONC}: A Corpus of {G}erman Medical Text with Rich Metadata Based on Clinical Practice Guidelines",
    author = "Borchert, Florian  and
      Lohr, Christina  and
      Modersohn, Luise  and
      Langer, Thomas  and
      Follmann, Markus  and
      Sachs, Jan Philipp  and
      Hahn, Udo  and
      Schapranow, Matthieu-P.",
    editor = "Holderness, Eben  and
      Jimeno Yepes, Antonio  and
      Lavelli, Alberto  and
      Minard, Anne-Lyse  and
      Pustejovsky, James  and
      Rinaldi, Fabio",
    booktitle = "Proceedings of the 11th International Workshop on Health Text Mining and Information Analysis",
    month = nov,
    year = "2020",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2020.louhi-1.5",
    doi = "10.18653/v1/2020.louhi-1.5",
    pages = "38--48",
    abstract = "The lack of publicly accessible text corpora is a major obstacle for progress in natural language processing. For medical applications, unfortunately, all language communities other than English are low-resourced. In this work, we present GGPONC (German Guideline Program in Oncology NLP Corpus), a freely dis tributable German language corpus based on clinical practice guidelines for oncology. This corpus is one of the largest ever built from German medical documents. Unlike clinical documents, clinical guidelines do not contain any patient-related information and can therefore be used without data protection restrictions. Moreover, GGPONC is the first corpus for the German language covering diverse conditions in a large medical subfield and provides a variety of metadata, such as literature references and evidence levels. By applying and evaluating existing medical information extraction pipelines for German text, we are able to draw comparisons for the use of medical language to other corpora, medical and non-medical ones.",
}
@article{5A,
  title={Evidence-Based Medicine: History, Review, Criticisms, and Pitfalls},
  author={Iqbal Ratnani and Sahar Fatima and Muhammad Mohsin Abid and Zehra Surani and Salim Surani},
  journal={Cureus},
  volume={15},
  number={2},
  pages={e35266},
  year={2023},
  month={February},
  doi={10.7759/cureus.35266},
  url={https://doi.org/10.7759/cureus.35266},
  pmid={36968905},
  pmcid={PMC10035760}
}
@inproceedings{Alodadi2019,
  author    = {Mohammad S. Alodadi and Vandana P. Janeja},
  title     = {Linking Knowledge Discovery In Clinical Notes And Massive Biomedical Literature Repositories},
  booktitle = {2019 IEEE International Conference on Big Data},
  year      = {2019},
  publisher = {IEEE},
  doi       = {10.1109/BIBM47256.2019.8983242},
  url       = {https://ieeexplore.ieee.org/document/RelevantDocumentNumber}
}
@inproceedings{239,
  author    = {Sabah Mohammed and Jinan Fiaidhi},
  title     = {Investigation into Scaling-Up the SOAP Problem-Oriented Medical Record into a Clinical Case Study},
  booktitle = {2023 IEEE 11th International Conference},
  year      = {2023},
  doi       = {10.1109/ICHI57859.2023.00134},
  publisher = {IEEE}
}
@article{40,
  author    = {Rashmi Mishra and Andrea Burke and Bonnie Gitman and Payal Verma and Mark Engelstad and Ilias Alevizos and William A. Gahl and Michael T. Collins and Janice S. Lee and Murat Sincan},
  title     = {Data-driven method to enhance craniofacial and oral phenotype vocabularies},
  journal   = {The Journal of the American Dental Association},
  volume    = {150},
  number    = {11},
  pages     = {933-939.e2},
  year      = {2019},
  doi       = {10.1016/j.adaj.2019.05.029},
  url       = {https://doi.org/10.1016/j.adaj.2019.05.029}
}
@article{54,
  author    = {Anjani Dhrangadhariya and Henning Müller},
  title     = {Not so weak PICO: leveraging weak supervision for participants, interventions, and outcomes recognition for systematic review automation},
  journal   = {JAMIA Open},
  volume    = {6},
  number    = {1},
  year      = {2023},
  doi       = {10.1093/jamiaopen/ooac107},
  url       = {https://doi.org/10.1093/jamiaopen/ooac107},
  publisher = {Oxford University Press},
  month     = {April}
}
@article{2,
  author    = {Tian Kang and Adler Perotte and Youlan Tang and Casey Ta and Chunhua Weng},
  title     = {UMLS-based data augmentation for natural language processing of clinical research literature},
  journal   = {Journal of the American Medical Informatics Association},
  volume    = {28},
  number    = {4},
  pages     = {812--823},
  year      = {2021},
  doi       = {10.1093/jamia/ocaa309},
  url       = {https://doi.org/10.1093/jamia/ocaa309},
  month     = {April},
  publisher = {Oxford University Press}
}
@inproceedings{154,
author = {Malik, Khalid Mahmood and Krishnamurthy, Madan and Marcinek, Pawel and Malik, Ghaus M},
title = {Impact of size, location, symptomatic-nature and gender on the rupture of saccular intracranial aneurysms},
year = {2020},
isbn = {9781538660515},
publisher = {IEEE Press},
booktitle = {Proceedings of the 2018 IEEE/ACM International Conference on Advances in Social Networks Analysis and Mining},
pages = {995–1001},
numpages = {7},
keywords = {symptotic, statistical analysis, size, saccular, rupture, natural language processing, logistic regression, location, intracranial anuerysm, gender},
location = {Barcelona, Spain},
series = {ASONAM '18}
}
@inproceedings{182,
  author    = {Hamman Samuel and Osmar Zaiane and Francois Bolduc},
  title     = {Evaluation of Applied Machine Learning for Health Misinformation Detection via Survey of Medical Professionals on Controversial Topics in Pediatrics},
  booktitle = {Proceedings of the 5th International Conference on Medical and Health Informatics},
  year      = {2021},
  pages     = {1--6},
  doi       = {10.1145/3472813.3472814},
  publisher = {ACM}
}
@article{300,
  author    = {Houssein Dhayne and Rima Kilany and Rafiqul Haque and Yehia Taher},
  title     = {EMR2vec: Bridging the gap between patient data and clinical trial},
  journal   = {Computers \& Industrial Engineering},
  volume    = {156},
  pages     = {107236},
  year      = {2021},
  month     = {June},
  doi       = {10.1016/j.cie.2021.107236},
  url       = {https://doi.org/10.1016/j.cie.2021.107236}
}
@article{421,
  title     = {Developing an Inpatient Electronic Medical Record Phenotype for Hospital-Acquired Pressure Injuries: Case Study Using Natural Language Processing Models},
  author    = {Elvira Nurmambetova and Jie Pan and Zilong Zhang and Seungwon Lee and Danielle A Southern and Elliot A Martin and Guosong Wu and Chester Ho and Cathy A Eastwood},
  journal   = {JMIR AI},
  volume    = {2},
  number    = {2023},
  pages     = {e41264},
  year      = {2023},
  doi       = {10.2196/41264},
  url       = {https://doi.org/10.2196/41264}
}
@inproceedings{626,
author = {Deng, Yang and Li, Yaliang and Shen, Ying and Du, Nan and Fan, Wei and Yang, Min and Lei, Kai},
title = {MedTruth: A Semi-supervised Approach to Discovering Knowledge Condition Information from Multi-Source Medical Data},
year = {2019},
isbn = {9781450369763},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3357384.3357934},
doi = {10.1145/3357384.3357934},
booktitle = {Proceedings of the 28th ACM International Conference on Information and Knowledge Management},
pages = {719–728},
numpages = {10},
keywords = {knowledge discovery, multi-source data, truth discovery},
location = {Beijing, China},
series = {CIKM '19}
}
@inproceedings{693,
author = {Koopman, Bevan and Zuccon, Guido},
title = {Cohort-based Clinical Trial Retrieval},
year = {2022},
isbn = {9781450395991},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3503516.3503529},
doi = {10.1145/3503516.3503529},
booktitle = {Proceedings of the 25th Australasian Document Computing Symposium},
articleno = {3},
numpages = {9},
keywords = {query cohorts, clinical trials, clinical information retrieval},
location = {Virtual Event, Australia},
series = {ADCS '21}
}
@inproceedings{750,
author = {Nguyen, Vincent and Karimi, Sarvnaz and Jin, Brian},
title = {An Experimentation Platform for Precision Medicine},
year = {2019},
isbn = {9781450361729},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3331184.3331396},
doi = {10.1145/3331184.3331396},
booktitle = {Proceedings of the 42nd International ACM SIGIR Conference on Research and Development in Information Retrieval},
pages = {1357–1360},
numpages = {4},
keywords = {literature search, health informatics, domain-specific search},
location = {Paris, France},
series = {SIGIR'19}
}
@article{492,
  title     = {TCGA-Reports: A machine-readable pathology report resource for benchmarking text-based AI models},
  author    = {Jenna Kefeli and Nicholas Tatonetti},
  journal   = {Patterns},
  volume    = {5},
  number    = {3},
  pages     = {100933},
  year      = {2024},
  doi       = {10.1016/j.patter.2024.100933},
  url       = {https://doi.org/10.1016/j.patter.2024.100933},
  publisher = {Elsevier},
  note      = {Published online February 21, 2024}
}
@inproceedings{371,
  title={Large Language Models for Healthcare Data Augmentation: An Example on Patient-Trial Matching},
  author={Jiayi Yuan and Ruixiang Tang and Xiaoqian Jiang and Xia Hu},
  booktitle={AMIA Annual Symposium Proceedings},
  volume={2024},
  pages={1324--1333},
  year={2024},
  pmcid={PMC10785941},
  pmid={38222339},
  organization={AMIA}
}
@article{381,
  title={ScanMedicine: An online search system for medical innovation},
  author={Jawad Sadek and Alex Inskip and James Woltmann and Georgina Wilkins and Christopher Marshall and Maria Pokora and Amey Vedpathak and Anastasija Jadrevska and Dawn Craig and Michael Trenell},
  journal={Contemporary Clinical Trials},
  volume={125},
  pages={107042},
  year={2023},
  month={Feb},
  doi={10.1016/j.cct.2022.107042},
  publisher={Elsevier}
}

@inproceedings{692,
author = {Koopman, Bevan and Wright, Tracey and Omer, Natacha and McCabe, Veronica and Zuccon, Guido},
title = {Precision Medicine Search for Paediatric Oncology},
year = {2021},
isbn = {9781450380379},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3404835.3462792},
doi = {10.1145/3404835.3462792},
abstract = {We present a search engine aimed to help clinicians find targeted treatments for children with cancer. Childhood cancer is a leading cause of death and clinicians increasingly seek treatments that are tailored to an individual patient, particularly their tumour genetics. Finding treatments that are specific to paediatrics and match individual genetics is a real challenge amongst the vast and growing body of medical literature and clinical trials. We aim to help clinicians through a search system tailored to this problem.The system retrieves PubMed articles and clinical trials. Entity extraction is done to highlight genes, drugs and cancers --- three key information types clinicians care about. Query suggestion helps clinicians formulate otherwise difficult queries and results are presented as a knowledge graph to help result interpretability. The proposed system aims to both significantly reduce the effort of searching for targeted treatments and potentially find life saving treatments that may have otherwise been missed. Demo details at http://health-search.csiro.au/oscar/},
booktitle = {Proceedings of the 44th International ACM SIGIR Conference on Research and Development in Information Retrieval},
pages = {2536–2540},
numpages = {5},
location = {Virtual Event, Canada},
series = {SIGIR '21}
}
@article{468,
  title={Data Mining of Free-Text Responses: An Innovative Approach to Analyzing Patient Perspectives on Chronic Rhinosinusitis with Nasal Polyps in a Phase IIa Proof-of-Concept Study for Dupilumab},
  author={Khan, AH and Abbe, A and Falissard, B and Carita, P and Bachert, C and Mullol, J and Reaney, M and Chao, J and Mannent, LP and Amin, N and Mahajan, P and Pirozzi, G and Eckert, L},
  journal={Dove Medical Press}, 
  volume={2021},
  number={15},
  pages={2577--2586},
  year={2021},
  doi={10.2147/PPA.S320242},
  publisher={Taylor & Francis Group}
}
@inproceedings{860,
author = {Zhang, Yixuan and Liu, Junzhen and Lu, Wei},
title = {MeDict-GP: An Accurate Entity Recognition Model Combining Medical Domain Knowledge and Globalization Ideas},
year = {2023},
isbn = {9781450399029},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3594315.3594360},
doi = {10.1145/3594315.3594360},
booktitle = {Proceedings of the 2023 9th International Conference on Computing and Artificial Intelligence},
pages = {477–483},
numpages = {7},
keywords = {Nested Relationships, Medical Named Entity Recognition, Medical Domain Knowledge, Globalization Framework},
location = {Tianjin, China},
series = {ICCAI '23}
}
@article{396,
  title={Matching patients to clinical trials using semantically enriched document representation},
  author={Hassanzadeh, Hamed and Karimi, Sarvnaz and Nguyen, Anthony},
  journal={Journal of Biomedical Informatics},
  volume={105},
  pages={103406},
  year={2020},
  publisher={Elsevier},
  doi={10.1016/j.jbi.2020.103406}
}
@inproceedings{393,
  title={A Comparison between Human and NLP-based Annotation of Clinical Trial Eligibility Criteria Text Using The OMOP Common Data Model},
  author={Li, Xinhang and Liu, Hao and Kury, Fabrício and Yuan, Chi and Butler, Alex and Sun, Yingcheng and Ostropolets, Anna and Xu, Hua and Weng, Chunhua},
  booktitle={AMIA Joint Summits on Translational Science Proceedings},
  pages={394--403},
  year={2021},
  organization={AMIA},
  pmid={34457154},
  pmcid={PMC8378608}
}
@inproceedings{257,
  title={Parsable Clinical Trial Eligibility Criteria Representation Using Natural Language Processing},
  author={Kim, Jeongeun and Izower, Mitchell and Quintana, Yuri},
  booktitle={AMIA Annual Symposium Proceedings},
  pages={616--624},
  year={2023},
  organization={American Medical Informatics Association},
  pmcid={PMC10148319},
  pmid={37128426}
}
@inproceedings{414,
  title={Parsable Clinical Trial Eligibility Criteria Representation Using Natural Language Processing},
  author={Kim, Jeongeun and Izower, Mitchell and Quintana, Yuri},
  booktitle={AMIA Annual Symposium Proceedings},
  pages={616--624},
  year={2023},
  organization={American Medical Informatics Association},
  pmcid={PMC10148319},
  pmid={37128426}
}
@article{458,
  title={Improving the Efficiency of Clinical Trial Recruitment Using an Ensemble Machine Learning to Assist With Eligibility Screening},
  author={Cai, Tianrun and Cai, Fiona and Dahal, Kumar P. and Cremone, Gabrielle and Lam, Ethan and Golnik, Charlotte and Seyok, Thany and Hong, Chuan and Liao, Katherine P.},
  journal={ACR Open Rheumatology},
  volume={3},
  pages={593-600},
  year={2021},
  publisher={Wiley},
  doi={10.1002/acr2.11289}
}
@inproceedings{278,
  author = {Pyae Phyo Tun and Jiawen Luo and Jiecheng Xie and Sandi Wibowo and Chen Hao},
  title = {Automatic Assessment of Patient Eligibility by Utilizing NLP and Rule-Based Analysis},
  booktitle = {2023 45th Annual International Conference of the IEEE Engineering in Medicine \& Biology Society (EMBC)},
  year = {2023},
  pages = {10340494},
  doi = {10.1109/EMBC40787.2023.10340494},
  publisher = {IEEE},
  address = {Sydney, Australia},
  month = jul,
  pubmedid = {38082656}
}
@article{316,
  title={Clinical trial cohort selection based on multi-level rule-based natural language processing system},
  author={Chen, Long and Gu, Yu and Ji, Xin and Lou, Chao and Sun, Zhiyong and Li, Haodan and Gao, Yuan and Huang, Yang},
  journal={Journal of the American Medical Informatics Association},
  volume={26},
  number={11},
  pages={1218--1226},
  year={2019},
  month={Nov},
  publisher={Oxford University Press},
  doi={10.1093/jamia/ocz109}
}
@inproceedings{310,
  title={Extending PICO with Observation Normalization for Evidence Computing},
  author={Turfaha, Ali and Liu, Hao and Stewart, Latoya A and Kang, Tian and Weng, Chunhua},
  booktitle={MEDINFO 2021: One World, One Health -- Global Partnership for Digital Innovation},
  pages={268--272},
  year={2022},
  organization={International Medical Informatics Association and IOS Press},
  doi={10.3233/SHTI220076},
  address={New York, New York, USA},
  publisher={IOS Press}
}
@article{268,
  title={Enhancing evidence-based medicine with natural language argumentative analysis of clinical trials},
  author={Mayer, Tobias and Marro, Santiago and Cabrio, Elena and Villata, Serena},
  journal={Artificial Intelligence in Medicine},
  volume={118},
  pages={102098},
  year={2021},
  publisher={Elsevier},
  doi={10.1016/j.artmed.2021.102098},
  address={Universit{\'e} C{\^o}te d'Azur, CNRS, Inria I3S, France},
}

@article{369,
  author    = {Yilu Fang and Jae Hyun Kim and Betina Ross Idnay and Rebeca Aragon Garcia and 
               Carmen E. Castillo and Yingcheng Sun and Hao Liu and Cong Liu and Chi Yuan and Chunhua Weng},
  title     = {Participatory Design of a Clinical Trial Eligibility Criteria Simplification Method},
  journal   = {Studies in Health Technology and Informatics},
  volume    = {281},
  pages     = {984--988},
  year      = {2021},
  doi       = {10.3233/SHTI210325},
  category  = {Research Article}
}

@article{389,
  author = {Hegler C. Tissot and Anoop D. Shah and David Brealey and Steve Harris and Ruth Agbakoba and Amos Folarin},
  title = {Natural Language Processing for Mimicking Clinical Trial Recruitment in Critical Care: A Semi-Automated Simulation Based on the LeoPARDS Trial},
  journal = {IEEE Journal of Biomedical and Health Informatics},
  volume = {24},
  number = {10},
  pages = {2950--2959},
  year = {2020},
  doi = {10.1109/JBHI.2020.2977925},
  ISSN = {2168-2194},
  month = {October},
  publisher = {IEEE}
}
@article{311,
  title={A knowledge base of clinical trial eligibility criteria},
  author={Hao Liu and Yuan Chi and Alex Butler and Yingcheng Sun and Chunhua Weng},
  journal={Journal of Biomedical Informatics},
  volume={117},
  pages={103771},
  year={2021},
  publisher={Elsevier},
  doi={10.1016/j.jbi.2021.103771}
}
@INPROCEEDINGS{332,
  author={Tian, Shubo and Yin, Pengfei and Zhang, Hansi and Erdengasileng, Arslan and Bian, Jiang and He, Zhe},
  booktitle={2023 IEEE International Conference on Bioinformatics and Biomedicine (BIBM)}, 
  title={Parsing Clinical Trial Eligibility Criteria for Cohort Query by a Multi-Input Multi-Output Sequence Labeling Model}, 
  year={2023},
  volume={},
  number={},
  pages={4426-4430},
  keywords={Training;Electric potential;Databases;Computational modeling;Biological system modeling;Clinical trials;Natural language processing;Clinical trial;Eligibility criteria;Natural language processing},
  doi={10.1109/BIBM58861.2023.10385876}}
@article{274,
  title={Applying Natural Language Processing to ClinicalTrials.gov: mRNA cancer vaccine case study},
  author={Bianca Vora and Denison Kuruvilla and Chloe Kim and Michael Wu and Colby S. Shemesh and Gillie A. Roth},
  journal={Clinical and Translational Science},
  volume={16},
  pages={2417-2420},
  year={2023},
  publisher={Wiley},
  doi={10.1111/cts.13648}
}
@article{514,
  title={A Real-Time Automated Patient Screening System for Clinical Trials Eligibility in an Emergency Department: Design and Evaluation},
  author={Ni, Yizhao and Bermudez, Monica and Kennebeck, Stephanie and Liddy-Hicks, Stacey and Dexheimer, Judith},
  journal={JMIR Medical Informatics},
  volume={7},
  number={3},
  pages={e14185},
  year={2019},
  doi={10.2196/14185},
  PMID={31342909},
  PMCID={PMC6685132}
}
@article{324,
  title={EBM+: Advancing Evidence-Based Medicine via two level automatic identification of Populations, Interventions, Outcomes in medical literature},
  author={Stylianou, Nikolaos and Razis, Gerasimos and Goulis, Dimitrios G. and Vlahavas, Ioannis},
  journal={Artificial Intelligence in Medicine},
  volume={108},
  pages={101949},
  year={2020},
  month={Aug},
  publisher={Elsevier},
  doi={10.1016/j.artmed.2020.101949}
}
@INPROCEEDINGS{240,
  author={Yazi, Fatin Syafiqah and Vong, Wan-Tze and Raman, Valliappan and Then, Patrick Hang Hui and Lunia, Mukulraj J},
  booktitle={2021 Fifth International Conference on Information Retrieval and Knowledge Management (CAMP)}, 
  title={Towards Automated Detection of Contradictory Research Claims in Medical Literature Using Deep Learning Approach}, 
  year={2021},
  volume={},
  number={},
  pages={116-121},
  keywords={Deep learning;Systematics;Bit error rate;Buildings;Information retrieval;Knowledge management;contradiction detection;medical literature;natural language processing;deep learning},
  doi={10.1109/CAMP51653.2021.9498061}}
@article{269,
  title={Medical text classification based on the discriminative pre-training model and prompt-tuning},
  author={Wang, Yu and Wang, Yuan and Yang, Fei and others},
  journal={Digital Health},
  year={2023},
  publisher={SAGE Publications},
  doi={10.1177/20552076231193213}
}
@article{341,
  title={Distilling large language models for matching patients to clinical trials},
  author={Nievas, Mauro and Basu, Aditya and Wang, Yanshan and Singh, Hrituraj},
  journal={Journal of the American Medical Informatics Association},
  volume={31},
  number={9},
  pages={1953--1963},
  year={2024},
  publisher={Oxford University Press},
  doi={10.1093/jamia/ocae073}
}
@article{289,
  title={Implementation of Machine Learning Pipelines for Clinical Practice: Development and Validation Study},
  author={Kanbar, Lara J and Wissel, Benjamin and Ni, Yizhao and Pajor, Nathan and Glauser, Tracy and Pestian, John and Dexheimer, Judith W},
  journal={JMIR Medical Informatics},
  volume={10},
  number={12},
  pages={e37833},
  year={2022},
  doi={10.2196/37833},
  PMID={36525289},
  PMCID={PMC9804095}
}
@article{438,
  title={Batch enrollment for an artificial intelligence-guided intervention to lower neurologic events in patients with undiagnosed atrial fibrillation: rationale and design of a digital clinical trial},
  author={Yao, Xiaoxi and Attia, Zachi I. and Behnken, Emma M. and Walvatne, Kelli and Giblon, Rachel E. and Liu, Sijia and Siontis, Konstantinos C. and Gersh, Bernard J. and Graff-Radford, Jonathan and Rabinstein, Alejandro A. and Friedman, Paul A. and Noseworthy, Peter A.},
  journal={American Heart Journal},
  volume={239},
  pages={73--79},
  year={2021},
  month={Sep},
  publisher={Elsevier},
  doi={10.1016/j.ahj.2021.05.006}
}
@article{487,
  title={Medical Knowledge Infused Convolutional Neural Networks for Cohort Selection in Clinical Trials},
  author={Chen, Chi-Jen and Warikoo, Neha and Chang, Yun Chun and Chen},
  journal={Journal of the american medical informatics association},
  volume={26},
  number={11},
  pages={1227--1236},
  year={2019},
  month={nov},
  publisher={oxford university press},
  doi={10.1093/jamia/ocz128}
}
@article{46, 
title={Automated information extraction model enhancing traditional chinese medicine rct evidence extraction (evi-bert): algorithm development and validation}, 
author={Li, Yizhen and Luan, Zhongzhi and Liu, Yixing and Liu, Heyuan and Qi, Jiaxing and Han, Dongran}, 
journal={frontiers artificial intelligence}, 
volume={7}, 
number={1454945}, 
pages={not listed}, 
year={2024}, 
month={aug}, 
publisher={frontiers media inc}, 
doi={https://doi.org/10.3389/frai.2024.1454945}}
@article{425,
  author = {Zeng, Kun and Pan, Zhiwei and Xu, Yibin and Qu, Yingying},
  title = {An Ensemble Learning Strategy for Eligibility Criteria Text Classification for Clinical Trial Recruitment: Algorithm Development and Validation},
  journal = {JMIR Medical Informatics},
  volume = {8},
  number = {7},
  pages = {e17832},
  year = {2020},
  doi = {10.2196/17832},
  PMID = {32609092},
  PMCID = {PMC7367522}
}
@article{345,
  author = {Samuel Kaskovich and Kirk D. Wyatt and Tomasz Oliwa and Luca Graglia and Brian Furner and Jooho Lee and Anoop Mayampurath and Samuel L. Volchenboum},
  title = {Automated Matching of Patients to Clinical Trials: A Patient-Centric Natural Language Processing Approach for Pediatric Leukemia},
  journal = {JCO Clinical Cancer Informatics},
  volume = {7},
  doi = {10.1200/CCI.23.00009},
  year = {2023},
  url = {https://doi.org/10.1200/CCI.23.00009},
  publisher = {American Society of Clinical Oncology},
}
@article{453,
  title={PICO to PICOS: Weak Supervision to Extend Datasets with New Labels},
  author={Anjani Dhrangadhariya and Gaetano Manzo and Henning Müller},
  journal={Digital Health and Informatics Innovations for Sustainable Health Care Systems},
  volume={316},
  year={2024},
  publisher={IOS Press},
  doi={10.3233/SHTI240775}
}

@article{451,
  title={DQueST: dynamic questionnaire for search of clinical trials},
  author={Cong Liu and Chi Yuan and Alex M Butler and Richard D Carvajal and Ziran Ryan Li and Casey N Ta and Chunhua Weng},
  journal={Journal of the American Medical Informatics Association},
  volume={26},
  number={11},
  pages={1333--1343},
  year={2019},
  doi={10.1093/jamia/ocz121},
  publisher={Oxford University Press}
}
@article{377,
  title={Utilizing Large Language Models for Enhanced Clinical Trial Matching: A Study on Automation in Patient Screening},
  author={Jacob Beattie and Sarah Neufeld and Daniel Yang and Christian Chukwuma and Ahmed Gul and Neil Desai and Steve Jiang and Michael Dohopolski},
  journal={Cureus},
  volume={16},
  number={5},
  pages={e60044},
  year={2024},
  doi={10.7759/cureus.60044},
  publisher={Cureus Inc.}
}
@article{402,
  title={Automatic knowledge graph population with model-complete text comprehension for pre-clinical outcomes in the field of spinal cord injury},
  author={Hendrik Ter Horst and Nicole Brazda and Jessica Schira-Heinen and Julia Krebbers and Hans-Werner Müller and Philipp Cimiano},
  journal={Artificial Intelligence in Medicine},
  volume={137},
  pages={102491},
  year={2023},
  month={March},
  publisher={Elsevier},
  doi={10.1016/j.artmed.2023.102491}
}
@article{463,
  title={Cohort Selection for Clinical Trials From Longitudinal Patient Records: Text Mining Approach},
  author={Spasic, Irena and Krzeminski, David and Corcoran, Paul and Balinsky, Alexander},
  journal={JMIR Medical Informatics},
  volume={7},
  number={4},
  pages={e15980},
  year={2019},
  doi={10.2196/15980},
  PMID={31674914},
  PMCID={PMC6913747}
}

@article{399,
  title={Machine Learning Assisted Citation Screening for Systematic Reviews},
  author={Anjani Dhrangadhariya and Roger Hilfiker and Roger Schaer and Henning Müller},
  journal={Digital Personalized Health and Medicine},
  year={2020},
  doi={10.3233/SHTI200171},
}
@article{430,
  title={Optimizing Clinical Trial Eligibility Design Using Natural Language Processing Models and Real-World Data: Algorithm Development and Validation},
  author={Lee, Kyeryoung and Liu, Zongzhi and Mai, Yun and Jun, Tomi and Ma, Meng and Wang, Tongyu and Ai, Lei and Calay, Ediz and Oh, William and Stolovitzky, Gustavo and Schadt, Eric and Wang, Xiaoyan},
  journal={JMIR AI},
  volume={3},
  pages={e50800},
  year={2024},
  doi={10.2196/50800},
  PMID={39073872},
  PMCID={11319878}
}

@article{neveol2011semi,
  title={Semi-automatic semantic annotation of PubMed queries: a study on quality, efficiency, satisfaction},
  author={N{\'e}v{\'e}ol, Aur{\'e}lie and Do{\u{g}}an, Rezarta Islamaj and Lu, Zhiyong},
  journal={Journal of biomedical informatics},
  volume={44},
  number={2},
  pages={310--318},
  year={2011},
  publisher={Elsevier}
}

@article{lee2020biobert,
  title={BioBERT: a pre-trained biomedical language representation model for biomedical text mining},
  author={Lee, Jinhyuk and Yoon, Wonjin and Kim, Sungdong and Kim, Donghyeon and Kim, Sunkyu and So, Chan Ho and Kang, Jaewoo},
  journal={Bioinformatics},
  volume={36},
  number={4},
  pages={1234--1240},
  year={2020},
  publisher={Oxford University Press}
}
@article{55,
  title={Preliminary Comparison of the Performance of the National Library of Medicine's Systematic Review Publication Type and the Sensitive Clinical Queries Filter for Systematic Reviews in PubMed},
  author={Tamara Navarro-Ruan and R. Brian Haynes},
  journal={Journal of the Medical Library Association},
  volume={110},
  number={1},
  year={2022},
  pages={},
  doi={10.5195/jmla.2022.1286},
  url={https://doi.org/10.5195/jmla.2022.1286},
  publisher={University Library System, University of Pittsburgh}
}
@article{380,
  title={AutoCriteria: a generalizable clinical trial eligibility criteria extraction system powered by large language models},
  author={Surabhi Datta and Kyeryoung Lee and Hunki Paek and Frank J. Manion and Nneka Ofoegbu and Jingcheng Du and Ying Li and Liang-Chin Huang and Jingqi Wang and Bin Lin and Hua Xu and Xiaoyan Wang},
  journal={Journal of the American Medical Informatics Association},
  volume={31},
  number={2},
  pages={375--385},
  year={2024},
  month={February},
  doi={10.1093/jamia/ocad218},
  url={https://doi.org/10.1093/jamia/ocad218},
  publisher={Oxford University Press},
  note={Published: 11 November 2023}
}
@article{5,
  title={State-of-the-Art Evidence Retriever for Precision Medicine: Algorithm Development and Validation},
  author={Qiao Jin and Chuanqi Tan and Mosha Chen and Ming Yan and Ningyu Zhang, Songfang Huang, Xiaozhong Liu},
  journal={JMIR Medical Informatics},
  volume={10},
  number={12},
  pages={e40743},
  year={2022},
  doi={10.2196/40743},
  pmid={36409468},
  pmcid={9801267}
}
@article{13,
  author = {Austin J. Brockmeier and Meizhi Ju and Piotr Przybyła and Sophia Ananiadou},
  title = {Improving reference prioritisation with PICO recognition},
  journal = {BMC Medical Informatics and Decision Making},
  volume = {19},
  pages = {256},
  year = {2019},
  doi = {https://doi.org/10.1186/s12911-019-0992-8},
  publisher = {Springer Nature},
  url = {https://bmcmedinformdecismak.biomedcentral.com/articles/10.1186/s12911-019-0974-4}
}
@article{388,
  author = {Joshua J. Myszewski and Emily Klossowski and Patrick Meyer and Kristin Bevil and Lisa Klesius and Kristopher M. Schroeder},
  title = {Validating GAN-BioBERT: A Methodology for Assessing Reporting Trends in Clinical Trials},
  journal = {Frontiers in Digital Health},
  volume = {4},
  year = {2022},
  month = {May},
  doi = {10.3389/fdgth.2022.878369},
  url = {https://doi.org/10.3389/fdgth.2022.878369}
}
@article{69,
  author = {Gwon, YN and Kim, JH and Chung, HS and Jung, EJ and Chun, J and Lee, S and Shim, SR},
  title = {The Use of Generative AI for Scientific Literature Searches for Systematic Reviews: ChatGPT and Microsoft Bing AI Performance Evaluation},
  journal = {JMIR Medical Informatics},
  volume = {12},
  pages = {e51187},
  year = {2024},
  doi = {10.2196/51187},
  pmid = {38771247},
  pmcid = {11107769}
}
@article{352,
  author = {Dobbins, Nicholas J. and Han, Bin and Zhou, Weipeng and Lan, Kristine F. and Kim, H. Nina and Harrington, Robert and Uzuner, Özlem and Yetisgen, Meliha},
  title = {{LeafAI}: query generator for clinical cohort discovery rivaling a human programmer},
  journal = {Journal of the American Medical Informatics Association},
  volume = {30},
  number = {12},
  pages = {1954--1964},
  year = {2023},
  month = {December},
  doi = {10.1093/jamia/ocad149},
  url = {https://doi.org/10.1093/jamia/ocad149}
}
@inproceedings{292,
  author = {Florian Borchert and Laura Meister and Thomas Langer and Markus Follmann and Bert Arnrich and Matthieu-P Schapranow},
  title = {Controversial Trials First: Identifying Disagreement Between Clinical Guidelines and New Evidence},
  booktitle = {AMIA Annual Symposium Proceedings},
  year = {2022},
  month = {February},
  pages = {237--246},
  pmcid = {PMC8861732},
  pmid = {35308948}
}
@article{15,
  author = {Andy S. Huang and Kyle Hirabayashi and Laura Barna and Deep Parikh and Louis R. Pasquale},
  title = {Assessment of a Large Language Model's Responses to Questions and Cases About Glaucoma and Retina Management},
  journal = {JAMA Ophthalmology},
  year = {2024},
  volume = {142},
  number = {4},
  pages = {371--375},
  doi = {10.1001/jamaophthalmol.2023.6917},
  month = {February}
}
@article{375,
  author = {St{\'e}phane M. Meystre and Paul M. Heider and Andrew Cates and Grace Bastian and Tara Pittman and Stephanie Gentilin and Teresa J. Kelechi},
  title = {Piloting an automated clinical trial eligibility surveillance and provider alert system based on artificial intelligence and standard data models},
  journal = {BMC Medical Research Methodology},
  volume = {23},
  year = {2023},
  number = {88},
  doi = {https://doi.org/10.1186/s12874-023-01916-6},
  publisher = {BMC},
  date = {April 11, 2023}
}
@inproceedings{Ramprasad2023AutomaticallySummarizing,
  author = {Sanjana Ramprasad and Iain J. Marshall and Denis Jered McInerney and Byron C. Wallace},
  title = {Automatically Summarizing Evidence from Clinical Trials: A Prototype Highlighting Current Challenges},
  booktitle = {Proceedings of the Conference of the Association for Computational Linguistics Meeting},
  year = {2023},
  month = {May},
  pages = {236--247},
  pmcid = {PMC10361334},
  nihmsid = {NIHMS1912129},
  pmid = {37483390}
}
@article{493,
  title={Utilizing ChatGPT as a scientific reasoning engine to differentiate conflicting evidence and summarize challenges in controversial clinical questions},
  author={Xie, Shiyao and Zhao, Wenjing and Deng, Guanghui and He, Guohua and He, Na and Lu, Zhenhua and Hu, Weihua and Zhao, Mingming and Du, Jian},
  journal={Journal of the American Medical Informatics Association},
  volume={31},
  number={7},
  pages={1551--1560},
  year={2024},
  month={July},
  doi={10.1093/jamia/ocae100},
  publisher={Oxford University Press},
  note={Published online: 17 May 2024}
}
@INPROCEEDINGS{540,
  author={Al Hafiz Khan, Md Abdullah and Shamsuzzaman, Md and Hasan, Sadid A. and Sorower, Mohammad S and Liu, Joey and Datla, Vivek and Milosevic, Mladen and Mankovich, Gabe and van Ommering, Rob and Dimitrova, Nevenka},
  booktitle={2019 IEEE International Conference on Bioinformatics and Biomedicine (BIBM)}, 
  title={Improving Disease Named Entity Recognition for Clinical Trial Matching}, 
  year={2019},
  volume={},
  number={},
  pages={2541-2548},
  keywords={Disease Named Entity Recognition;Clinical Trial;Deep Learning;Contextual Embedding;Domain Knowledge Embedding},
  doi={10.1109/BIBM47256.2019.8983421}}
@article{evidence,
  title = {The Levels of Evidence and Their Role in Evidence-Based Medicine},
  author = {Patricia B. Burns and Rod J. Rohrich and Kevin C. Chung},
  journal = {Plastic and Reconstructive Surgery},
    volume = {128},
  number = {1},
  pages = {305--310},
  year = {2011},
  doi = {10.1097/PRS.0b013e318219c171},
  pmid = {21701348},
  pmcid = {PMC3124652},
  publisher = {Lippincott Williams & Wilkins},
  note = {Author manuscript; available in PMC: 2012 Jul 1.},
}
@article{Blunt2022PyramidSchema,
  author = {Chris J. Blunt},
  title = {The Pyramid Schema: The Origins and Impact of Evidence Pyramids},
  journal = {Preprint},
  year = {2022},
  month = {December},
  doi = {10.13140/RG.2.2.16118.88643},
  url = {https://www.researchgate.net/publication/366120029},
}
@article{Guan2019,
  title={Natural language processing and recurrent network models for identifying genomic mutation-associated cancer treatment change from patient progress notes},
  author={Meijian Guan and Samuel Cho and Robin Petro and Wei Zhang and Boris Pasche and Umit Topaloglu},
  journal={JAMIA Open},
  volume={2},
  number={1},
  pages={139--149},
  year={2019},
  doi={10.1093/jamiaopen/ooy061},
  pmid={30944913},
  pmcid={PMC6435007},
  publisher={Oxford University Press}
}
@article{Khurana2023,
  title={Natural language processing: state of the art, current trends and challenges},
  author={Khurana, Deepak and Koli, Ankush and Khatter, Kapil and Singh, Yogesh},
  journal={Multimedia Tools and Applications},
  volume={82},
  pages={3713--3744},
  year={2023},
  doi={10.1007/s11042-022-13428-4},
  publisher={Springer}
}
@article{Kalyan2022,
  title={AMMU: A survey of transformer-based biomedical pretrained language models},
  author={Katikapalli Subramanyam Kalyan and Ajit Rajasekharan and Sivanesan Sangeetha},
  journal={Journal of Biomedical Informatics},
  volume={126},
  pages={103982},
  year={2022},
  publisher={Elsevier},
  doi={10.1016/j.jbi.2021.103982}
}
@article{Thirunavukarasu2023,
  title={Large language models in medicine},
  author={Thirunavukarasu, Arun James and Ting, Darren Shu Jeng and Elangovan, Kabilan. and others},
  journal={Nature Medicine},
  volume={29},
  pages={1930--1940},
  year={2023},
  publisher={Nature Publishing Group},
  doi={10.1038/s41591-023-02448-8}
}
@article{Rohanian2024,
  title={Exploring the effectiveness of instruction tuning in biomedical language processing},
  author={Rohanian, Omid and Nouriborji, Mohammadmahdi and Kouchaki, Samaneh and Nooralahzadeh, Farhad and Clifton, Lei and Clifton, David A.},
  journal={Artificial Intelligence in Medicine},
  volume={158},
  pages={103007},
  year={2024},
  publisher={Elsevier},
  doi={10.1016/j.artmed.2024.103007}
}
@article{sackett1996evidence,
  title={Evidence based medicine: what it is and what it isn't},
  author={David L. Sackett and William M. C. Rosenberg and J. A. Muir Gray and R. Brian Haynes and W. Scott Richardson},
  journal={BMJ},
  volume={312},
  number={7023},
  pages={71--72},
  year={1996},
  publisher={British Medical Journal Publishing Group},
  doi={10.1136/bmj.312.7023.71},
  pmid={8555924},
  pmcid={PMC2349778}
}
@article{LSTM,
author = {Hochreiter, Sepp and Schmidhuber, J\"{u}rgen},
title = {Long Short-Term Memory},
year = {1997},
issue_date = {November 15, 1997},
publisher = {MIT Press},
address = {Cambridge, MA, USA},
volume = {9},
number = {8},
issn = {0899-7667},
url = {https://doi.org/10.1162/neco.1997.9.8.1735},
doi = {10.1162/neco.1997.9.8.1735},
journal = {Neural Comput.},
month = nov,
pages = {1735–1780},
numpages = {46}
}
@article{CNNdaily,
  title={Get To The Point: Summarization with Pointer-Generator Networks},
  author={Abigail See and Peter J. Liu and Christopher D. Manning},
  journal={arXiv preprint arXiv:1704.04368},
  year={2017},
  doi={10.48550/arXiv.1704.04368},
  url={https://doi.org/10.48550/arXiv.1704.04368},
  archivePrefix={arXiv},
  eprint={1704.04368},
  primaryClass={cs.CL}
}
@article{Arora2019,
  title={Bayesian Networks for Risk Prediction Using Real-World Data: A Tool for Precision Medicine},
  author={Arora, Paul and Boyne, Devon and Slater, Justin J. and Gupta, Alind and Brenner, Darren R. and Druzdzel, Marek J.},
  journal={Value in Health},
  volume={22},
  number={4},
  pages={439--445},
  year={2019},
  publisher={Elsevier},
  doi={10.1016/j.jval.2019.01.006}
}
@article{Zhang2024,
  author       = {Gongbo Zhang and Qiao Jin and Yiliang Zhou and Song Wang and Betina Idnay and Yiming Luo and Elizabeth Park and Jordan G. Nestor and Matthew E. Spotnitz and Ali Soroush and Thomas R. Campion Jr and Zhiyong Lu and Chunhua Weng and Yifan Peng},
  title        = {Closing the gap between open source and commercial large language models for medical evidence summarization},
  journal      = {NPJ Digital Medicine},
  volume       = {7},
  number       = {1},
  pages        = {239},
  year         = {2024},
  month        = {Sep},
  doi          = {10.1038/s41746-024-01239-w},
  pmid         = {39251804},
  pmcid        = {PMC11383939}
}


```

---
