# Small Language Model — Google DeepMind Challenge Lab

This repository contains the code and resources for building, training, and evaluating a **small language model**, following the **Google DeepMind Challenge Lab** curriculum. The project demonstrates how transformer-based language models can be trained from scratch on small datasets and includes notebooks, tokenizers, basic training loops, and evaluation scripts.

## Overview

Modern large language models (LLMs) like those developed by DeepMind or Google are highly powerful but computationally expensive. This project explores training and deploying a **small language model (SLM)** with fewer parameters, making it suitable for experimentation on local hardware or cloud-based lab environments.

The primary focus of this project is to help learners understand foundational concepts in language modeling and machine learning development pipeline, including:

- Tokenization and data preprocessing:
  - Implementation of basic tokenization strategies  
  - Conversion of raw text into token sequences  
  - Vocabulary construction and handling of padding and unknown tokens 
- Model architecture (e.g., transformer encoder / decoder)  
- Training loops and optimization techniques  
- Probabilistic Language Modeling Objective:
  - Next-token prediction as the primary learning task  
  - Teacher forcing during training  
  - Analysis of loss trends and overfitting on small datasets  
- Evaluation of text generation quality:
  - Sampling-based text generation from trained models  
  - Qualitative evaluation of coherence and fluency  
  - Discussion of limitations of small models
    
## Educational Value

By working through this repository, we gain:
- A concrete understanding of how LLM concepts scale down to smaller models  
- Insight into trade-offs between model size, data, and performance  
- A strong foundation for progressing to larger architectures or research projects  

