# Different Inductive Biases Can Lead to Similar Performance via Distinct Algorithms

[![Paper](https://img.shields.io/badge/Paper-007ACC?style=for-the-badge&labelColor=007ACC)](https://arxiv.org/abs/2502.12352)
[![Drive Folder](https://img.shields.io/badge/Drive_Folder-007ACC?style=for-the-badge&labelColor=007ACC)](https://drive.google.com/drive/folders/1rCwxa3mjwZ9m24sl7gttgiJ-dzUZoNt1?usp=sharing)
[![Presentation](https://img.shields.io/badge/Presentation-007ACC?style=for-the-badge&labelColor=007ACC)](https://github.com/batu-el/understanding-inductive-biases-of-gnns/blob/main/presentation.pdf)
[![Course Page](https://img.shields.io/badge/Course_Page-007ACC?style=for-the-badge&labelColor=007ACC)](https://www.cl.cam.ac.uk/teaching/2324/L65/)

## Abstract
We introduce Attention Graphs, a new tool for mechanistic interpretability of Graph Neural Networks (GNNs) and Graph Transformers based on the mathematical equivalence between message passing in GNNs and the self-attention mechanism in Transformers. Attention Graphs aggregate attention matrices across Transformer layers and heads to describe how information flows among input nodes. Through experiments on homophilous and heterophilous node classification tasks, we analyze Attention Graphs from a network science perspective and find that: (1) When Graph Transformers are allowed to learn the optimal graph structure using all-to-all attention among input nodes, the Attention Graphs learned by the model do not tend to correlate with the input/original graph structure; and (2) For heterophilous graphs, different Graph Transformer variants can achieve similar performance while utilising distinct information flow patterns.

## Models
![Alt text](assets/models.png)

## Information Flow Patterns
![Alt text](assets/heatmaps.png)

## Citation
```bibtex
@article{differentinductivebias2024,
    title={Different Inductive Biases Can Lead to Similar Performance via Distinct Algorithms},
    author={El, Batu and Choudhury, Deepro and Joshi, Chaitanya},
    journal={preprint},
    year={2024}
}
