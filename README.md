# A Deep Learning Approach to Clustering Visual Arts

This repository contains our code for the article we published in [IJCV](https://link.springer.com/article/10.1007/s11263-022-01664-y). 

Clustering artworks is difficult for several reasons. On the one hand, recognizing meaningful patterns based on domain knowledge and visual perception is extremely hard. On the other hand, applying traditional clustering and feature reduction techniques to the highly dimensional pixel space can be ineffective. To address these issues, in we proposed DELIUS: a DEep learning approach to cLustering vIsUal artS. The method uses a pre-trained convolutional network to extract features and then feeds these features into a deep embedded clustering model, where the task of mapping the input data to a latent space is jointly optimized with the task of finding a set of cluster centroids in this latent space. 

We do not provide data, but several available visual art datasets can be found on the Web. For the paper, we used a subset of the WikiArt collection, [previously scraped](https://github.com/cs-chan/ArtGAN).
