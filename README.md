
# [DeepGraphInfomax](https://arxiv.org/abs/1809.10341) (DGI) 

The code for DGI simple application. Uses master files produced by another project, in which we have a domain-domain network, and some domain features. We try to learn the node embeddings and cluster the network.

🖼️ 📦 🎯 🔄

> **Prerequisites** 

	* PyTorch
	* [pyg][https://pytorch-geometric.readthedocs.io/en/latest/notes/installation.html]
	* [torch-scatter][https://pytorch.org/docs/stable/generated/torch.scatter.html]
	* [torch-sparse][https://pytorch.org/docs/stable/sparse.html]
	* pandas, numpy, sklearn, matplotlib, bhtsne.tsne (or sklearn.manifold.TSNE)

### HOW TO USE THIS CODE

> **STEPS** 

1. Creating a dataset in PyG is not straightforward. This is done in ```1_Create_Own_Dataset-Domain.ipynb.``` 
2. ```2_DeepInfoMax_Node_Classification_Domains.ipynb``` uses the class for dataset creation from ```1_Create_Own_Dataset-Domain.ipynb``` to instantiate a dataset that we need. Then a simple implementation of DGI is applied and its output embeddings are plotted using TSNE. The embeddings can be linked with several domain features (e.g., bias, country). This is for now only used in the TSNE visualization stage, i.e., not as part of DGI.

> **NOTE**: Happy new project.


❤️ this project

