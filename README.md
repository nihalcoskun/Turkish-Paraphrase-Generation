# Gemma-2b Turkish Paraphrase Generation

This project focuses on developing a high-performing language model specialized in generating paraphrases in Turkish. 
Our goal is to enhance natural language understanding and generation capabilities for Turkish text.

## Project Objective

The primary objective of this project is to create a robust Turkish paraphrase generation model. We utilized advanced NLP techniques to finetune the Gemma-2b model using the Unsloth SFT library. 
The training was conducted over approximately 14,500 steps, ensuring the model learns a deep understanding of language nuances and paraphrasing techniques.

## Dataset

Turkish Paraphrase Generation Combined Dataset: https://huggingface.co/datasets/ncoskun/paraphraseTrain
This dataset is meticulously compiled to aid NLP tasks that require paraphrase understanding and generation in Turkish. It includes a total of 863,782 paraphrase pairs, 
organized in Alpaca format for optimal model training. It comprises seven distinct datasets, each adding unique value to the diversity and richness of Turkish paraphrases available.

## Model Training and Evaluation

Our model was rigorously trained and tested, achieving impressive results in paraphrase generation. The evaluation scores are as follows:

ROUGE-1: 0.570991 (Standard Deviation: 0.284570)

ROUGE-2: 0.393279 (Standard Deviation: 0.325551)

ROUGE-L: 0.565127 (Standard Deviation: 0.286318)

BLEU Score: 0.22280 (Standard Deviation: 0.359949)

BERT Score: 0.80374 (Standard Deviation: 0.207895)

These scores reflect the model's ability to effectively capture and reproduce the semantic and syntactic essence of the source texts.

## Access the Model

For those interested in utilizing or further developing this model, access is available through the following link:
https://huggingface.co/Marmara-NLP/gemma-2b-CSE4078S24_Grp4-r16-batch16-4bit-tr-paraphrase


## Conclusion
This project represents a significant step forward in the field of NLP for Turkish language processing, specifically in paraphrase generation. 
We invite the community to utilize our model, contribute to its improvement, and help advance the state of Turkish NLP.

