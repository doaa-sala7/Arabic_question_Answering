
# Arabic Question Answering System

## Overview:
This project aims to develop an Arabic question-answering (QA) system utilizing various approaches, including machine learning models, transformer models and fine-tuned Large Language Models (LLMs). The system enables users to pose questions in Arabic and receive accurate answers extracted from Arabic text.

## Components:
* Machine Learning Model: Utilizes traditional machine learning algorithms for Arabic QA, and unsupervised learning techniques.

* Transformer Model: Utilizes a pre-trained model from hugging face, the model is AraElectra base fine-tuned on ARCD.

* Fine-tuned Large Language Model (LLM): Utilizes the QLORA to fine-tune pre-trained LLMs (AceGPT 7b model), adapting them to Arabic QA tasks by leveraging domain-specific datasets.

## Installation:
This project is designed to be compatible with Google Colab, a cloud-based Jupyter notebook environment. Follow these steps to set up the project in Google Colab:

1. Open Google Colab: Visit [colab](colab.research.google.com) and sign in with your Google account.

2. Clone the repository:

Run the following cell in a new Colab notebook to clone the repository:
```
!git clone <https://github.com/doaa-sala7/Arabic_question_Answering>
```


## Acknowledgments:
The Hugging Face community for providing pre-trained transformer models and frameworks for fine-tuning.
Authors of the QLORA framework for enabling fine-tuning of LLMs on custom datasets.

