# NSMC-Sentiment-Fine-Tuning
This repository is dedicated to the sentiment analysis of Korean movie reviews from the Naver Sentiment Movie Corpus (NSMC) <br/>
Using two state-of-the-art language models: meta-llama/Llama-2-7b-chat-hf and KT-AI/midm-bitext-S-7B-inst-v1 <br/>
## Repository Contents
**Fine-Tuned Models**: <br/>
The repository features two fine-tuned models, each tailored to accurately predict the sentiment of Korean text as either 'positive' or 'negative' <br/>
**Datasets**: <br/>
Included are the subsets of the NSMC dataset that were used: 9,000 samples for training and 1,000 for validation, enabling users to replicate or extend the fine-tuning process <br/>
**Training Scripts**: <br/>
Scripts that were used to fine-tune and validate the models, alongside the hyperparameters and configurations, offer insights into the fine-tuning process <br/>
**Performance Metrics**: <br/>
Detailed evaluation metrics are provided to assess the models' accuracy and performance improvements post fine-tuning <br/>
**Utilities**: <br/>
Utility scripts to handle environment setup, including dependency management and memory optimization, are available <br/>
**Documentation**: <br/>
Comprehensive guides and instructions explain the methodology, setup, and execution steps for utilizing the fine-tuned models <br/>

## Fine-Tuned LLaMA-2-7B Adapter for NSMC
Repository URL: https://huggingface.co/growingpenguin/hw-llama-2-7B-nsmc/tree/main <br/>
This part of the repository hosts the fine-tuned adapter of the meta-llama/Llama-2-7b-chat-hf model, specifically optimized for understanding and analyzing the sentiment of Korean movie reviews <br/>
By leveraging the LoRA (Low-Rank Adaptation) technique, we've adapted this model to provide nuanced sentiment predictions, distinguishing between positive and negative reviews with high accuracy <br/>
## Fine-Tuned midm-7B Adapter for NSMC
Repository URL: https://huggingface.co/growingpenguin/hw-midm-7B-nsmc/tree/main <br/>
This section of the repository presents the fine-tuned KT-AI/midm-bitext-S-7B-inst-v1 model adapter, which has been meticulously fine-tuned to comprehend and evaluate sentiments in Korean movie reviews <br/>
It serves as a specialized tool for NSMC sentiment classification, designed to enhance the performance of sentiment prediction in a nuanced and culturally contextual manner <br/>
