# NER-system-Of-Chhattisgarhi-Dialect
This project focuses on developing a Named Entity Recognition (NER) system for the Chhattisgarhi dialect and its regional variations.
NER is a crucial task in Natural Language Processing (NLP) that automatically identifies entities such as persons, locations, organizations, dates, and more from text.

Since Chhattisgarhi and its dialects are underrepresented in NLP research, this project aims to build a resource and system to support future computational linguistics work for these languages.


#Project Overview

Objective:
To collect, preprocess, and annotate Chhattisgarhi dialectal data for training NER models using transformer-based architectures such as mBERT, IndicBERT, MuRIL, and XLM-RoBERTa.

Data Sources:
The dataset is compiled from multiple authentic online resources, including:

📰 Chhattisgarhi news portals & online articles

📚 CIIL (Central Institute of Indian Languages)

🎥 YouTube channels featuring Chhattisgarhi dialects

#Dialects Covered:

1.Standard Chhattisgarhi
2.Sarguijha

3.Baiagni

4.Halbi

5.Gondi

6.Sadri


📂 Dataset

Data is collected in raw form from multiple sources.

Preprocessing includes:

1.Tokenization

2.Cleaning (removal of noise, special symbols, etc.)

3.Normalization (handling script/orthographic variations)

4.Annotation is performed for NER labels (Person, Location, Organization, Miscellaneous, etc.). Following Indian Language Named Entities Tagset and Annotation
Guidelines
Prepared

The dataset follows a CSV/JSON format suitable for HuggingFace Transformers.

⚙️ Methodology

Data Collection & Cleaning

NER Annotation (BIO tagging scheme)

Model Training with transformer-based multilingual models:

bert-base-multilingual-cased (HindiBERT)

