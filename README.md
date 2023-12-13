# PLATO: High dimensional, tabular deep learning with an auxiliary knowledge graph

## Overview
<p align="center">
<img src="img/plato_github_figure.png" width="1100" align="center">
</p>

**PLATO is a method that enables deep learning on a tabular dataset with orders-of-magnitude more features than samples by using an auxiliary knowledge graph.** **(a)** In PLATO, every input feature in a tabular dataset coresopnds to a node in an auxiliary knowledge graph with information about the domain. **(b)** In the first layer of a MLP, every input feature corresponds to a vector of weights. **(c,d)** PLATO is based on the inductive bias that, if two input features corresopnd to similar nodes in the auxiliary KG, they should have similar weight vectors in the first layer of the MLP. PLATO captures the inductive bias by inferring the weight vector for each input feature from its corresponding node in the auxiliary KG. Input features with similar embeddings ultimately produce similar weight vectors, regularizing the MLP and capturing the inductive bias.

For more information about PLATO, please refer to our [paper](link), [5-minute video](link), [slides](link), or [poster](link)!

## Code, Data, and the Graph
We are preparing the final version of the code, data, and graph to release publicly. If you'd like to be notified when the final version is released, you can watch or star the repo.

## Contact
Please contact Camilo Ruiz (caruiz@cs.stanford.edu) and Hongyu Ren (hyren@cs.stanford.edu) with any questions.

## Citation
```
@inproceedings{ruiz2023high,
  title={High dimensional, tabular deep learning with an auxiliary knowledge graph},
  author={Ruiz, Camilo and Ren, Hongyu and Huang, Kexin and Leskovec, Jure},
  booktitle={Thirty-seventh Conference on Neural Information Processing Systems},
  year={2023}
}
```
