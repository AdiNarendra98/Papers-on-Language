# DistilBERT, a distilled version of BERT: smaller, faster, cheaper and lighter

 
### [Original Paper](https://arxiv.org/pdf/1910.01108v4.pdf)

- <ins>***Authors,Venue & Year***</ins>: **Victor Sanh, Lysandre Debut, Julien Chaumond, Thomas Wolf, NeurIPS, 2019**

## Summary

- This paper by Sanh et al. from Huggingface in the Energy Efficient Machine Learning and Cognitive Computing - NeurIPS 2019 introduced a language representation model, DistilBERT which is a general-purpose pre-trained version of BERT. DistilBERT is **40% smaller, 60% faster, cheaper to pre-train, and retains 97% of the language understanding capabilities**. DistilBERT can be fine-tuned with good performances on a wide range of tasks much like its larger counterparts.

- While most prior work investigated the use of distillation for building task-specific models, they leverage **knowledge distillation during the pre-training phase** and show that DistilBERT is a compelling option for edge applications.

- To leverage the inductive biases learned by larger models during pretraining, they **introduce a triple loss combining language modeling, distillation and cosine-distance losses**.



