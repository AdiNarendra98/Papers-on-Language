# BERT-Pre-training of Deep Bidirectional Transformers for Language Understanding
 
### [Original Paper](https://arxiv.org/pdf/1810.04805v2.pdf)

- <ins>Authors,Venue & Year</ins>: Jacob Devlin, Ming-Wei Chang, Kenton Lee, Kristina Toutanova, NAACL, 2019

## Summary

- This paper by Devlin et al. from Google in ACL 2019 proposed BERT (Bidirectional Encoder Representations from Transformers), a **Transformer-based language representation model which proposed pre-training bidirectional representations from unlabeled text by jointly conditioning on both left and right context in all layers**. BERT is pre-trained using two unsupervised tasks: (i) **masked language modeling (MLM)** and, (ii) **next sentence prediction (NSP)**.
   - MLM is often referred to as a Cloze task in the literature (Taylor, 1953). In this case, **the final hidden vectors corresponding to the mask tokens are fed into an output softmax over the vocabulary**, as in a standard LM.
   - NSP is needed because many important downstream tasks such as Question Answering (QA) and Natural Language Inference (NLI) are based on understanding the relationship between two sentences, which is not directly captured by language modeling. In order to train a model that understands sentence relationships, they **pre-train for a binarized next sentence prediction task that can be trivially generated from any monolingual corpus**.
   
- Fine-tuning for the task at hand involves **using an additional output layer**, to create state-of-the-art models for a wide range of tasks, such as question answering and language inference, without substantial task-specific architecture modifications.

- BERT comes in two flavors: 
   - (i) **BERT Base**: 12 layers (transformer blocks), 12 attention heads, and 110 million parameters
   - (ii) **BERT Large**: 24 layers (transformer blocks), 16 attention heads, and 340 million parameters
   
- BERT consumes a max of 512 input tokens. At its output, word embeddings for BERT (what is called BERT-base) have 768 dimensions.

- BERT obtains new state-of-the-art results on eleven natural language processing tasks, including pushing the **GLUE score to 80.5%** (7.7% point absolute improvement), **MultiNLI accuracy to 86.7%** (4.6% absolute improvement), **SQuAD v1.1 question answering Test F1 to 93.2** (1.5 point absolute improvement) and **SQuAD v2.0 Test F1 to 83.1** (5.1 point absolute improvement).

- BERT demonstrated that unsupervised pretraining is an integral part of many language understanding systems and enables even low-resource tasks to benefit from them.
