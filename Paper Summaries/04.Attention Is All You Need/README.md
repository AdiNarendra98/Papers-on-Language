# Attention Is All You Need

 
### [Original Paper](https://arxiv.org/pdf/1706.03762v5.pdf)

- <ins>***Authors,Venue & Year***</ins>: **Ashish Vaswani, Noam Shazeer, Niki Parmar, Jakob Uszkoreit et. , NeurIPS, 2017**

## Summary

- This work introduces Transformer, a novel sequence transduction model based entirely on attention mechanism.


- The authors are motivated to use self-attention because of three major criteria:  

   - One is that the total computational complexity per layer.
   - Another is the amount of computation that can be parallelized, as measured by the minimum number of sequential operations required.
   - The third is the path length between long-range dependencies in the network.

- The Transformer uses two different types of attention functions:

   - **Scaled Dot-Product Attention**, computes the attention function on a set of queries simultaneously, packed together into a matrix.

   - **Multi-head Attention**, allows the model to jointly attend to information from different representation subspaces at different positions.



-  It replaces the recurrent layers most commonly used in encoder-decoder architectures with multi-headed self-attention.. Transformer can be trained significantly faster than architectures based on recurrent or convolutional layers for translation tasks.

- On both WMT 2014 English-to-German and WMT 2014 English-to-French translation tasks, the model achieves a new state of the art.  In the former task the model outperforms all previously reported ensembles.



