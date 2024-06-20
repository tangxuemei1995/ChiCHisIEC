# CHisIEC
This is an information extraction dataset for ancient Chinese historical documents, including NER and RE tasks.

 
## NER
./data/ner/
We processed the data in CONLL format.

## RE
./data/re/

We save the dataset in JSON format.

## Annotation Platform

The two datasets were annotated using the annotation platform https://wyd.pkudh.net/, which is a deep learning-based platform where you can annotate any corpus, developed by the Digital Humanities Research Centre of Peking University.


## Cite
If you use the dataset

please cite the paper:
```
@inproceedings{tang-etal-2024-chisiec-information,
    title = "{CH}is{IEC}: An Information Extraction Corpus for {A}ncient {C}hinese History",
    author = "Tang, Xuemei  and
      Su, Qi  and
      Wang, Jun  and
      Deng, Zekun",
    editor = "Calzolari, Nicoletta  and
      Kan, Min-Yen  and
      Hoste, Veronique  and
      Lenci, Alessandro  and
      Sakti, Sakriani  and
      Xue, Nianwen",
    booktitle = "Proceedings of the 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (LREC-COLING 2024)",
    month = may,
    year = "2024",
    address = "Torino, Italia",
    publisher = "ELRA and ICCL",
    url = "https://aclanthology.org/2024.lrec-main.283",
    pages = "3192--3202",
    abstract = "Natural Language Processing (NLP) plays a pivotal role in the realm of Digital Humanities (DH) and serves as the cornerstone for advancing the structural analysis of historical and cultural heritage texts. This is particularly true for the domains of named entity recognition (NER) and relation extraction (RE). In our commitment to expediting ancient history and culture, we present the {``}Chinese Historical Information Extraction Corpus{''}(CHisIEC). CHisIEC is a meticulously curated dataset designed to develop and evaluate NER and RE tasks, offering a resource to facilitate research in the field. Spanning a remarkable historical timeline encompassing data from 13 dynasties spanning over 1830 years, CHisIEC epitomizes the extensive temporal range and text heterogeneity inherent in Chinese historical documents. The dataset encompasses four distinct entity types and twelve relation types, resulting in a meticulously labeled dataset comprising 14,194 entities and 8,609 relations. To establish the robustness and versatility of our dataset, we have undertaken comprehensive experimentation involving models of various sizes and paradigms. Additionally, we have evaluated the capabilities of Large Language Models (LLMs) in the context of tasks related to ancient Chinese history. The dataset and code are available at \url{https://github.com/tangxuemei1995/CHisIEC}.",
}

```
