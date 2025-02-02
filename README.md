# dbn - [Draw By Number](https://jessebassett.net/Thesis.html)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/armaank/dbn/blob/main/dbn/Text2Representation.ipynb)
[![License](https://img.shields.io/badge/License-BSD_3--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)


This repo contains code used to analyze architecture prose and construct generative models used to create synthetic architecture schematics.

<img src="https://github.com/armaank/dbn/blob/main/img/outline.gif" alt="outline" width="250"> <img src="https://github.com/armaank/dbn/blob/main/img/site.gif" alt="site" width="250"> <img src="https://github.com/armaank/dbn/blob/main/img/elevation.gif" alt="elevation" width="250">


## Generative Models

With all colab notebooks, make sure that you're connected to a GPU runtime. If you have issues with installation, then restart the runtime and re-run the notebook cells. 

* Use text to generate new architecture imagery via a CLIP + genetic algorithms [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/armaank/dbn/blob/main/dbn/Text2Representation.ipynb)
* Explore fixed latent directions in a StyleGAN2 model trained trained on the ArchML dataset [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/armaank/dbn/blob/main/dbn/Explore.ipynb)
* Discover new StyleGAN2 controls [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/armaank/dbn/blob/main/dbn/RepresentationSpace.ipynb)
* Visualize the principal components of a StyleGAN2 latent space [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/armaank/dbn/blob/main/dbn/pca.ipynb)
* Generate some static figures from a StyleGAN2 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/armaank/dbn/blob/main/dbn/figure_gen.ipynb)

## Dataset Visualization
Visualize the [ArchML dataset](https://jessebassett.net/pixplot2/index.html#) interactively. Explore the data used to train the models


## Text Analysis 

Basic [topic models](https://colab.research.google.com/github/armaank/dbn/blob/main/text-analysis/topicmodel.ipynb) and [clustering](https://colab.research.google.com/github/armaank/dbn/blob/main/text-analysis/umap.ipynb) of architecture lectures and a cohort of architecture project descriptions. 

## TODO:
* host img datasets on ee site 
* clean up generative
* add docs to datsets

## Acknowledgements
We'd like to thank:

* Federico Galatolo and the authors of [CLIP-GLASS](https://github.com/galatolofederico/clip-glass),
for providing open source implementations of their methods and guidance. (`generative/styleclip`) 
* Erik Härkönen and the authors of [ganspace](https://github.com/harskish/ganspace) (`generative/ganspace)`
* The authors of the following PyTorch implementation of [StyleGAN2](https://github.com/adriansahlman/stylegan2_pytorch) (`generative/styleclip`)
* The authors of [pix-plot](https://github.com/YaleDHLab/pix-plot) for their interactive data visualizer. 

All of their work should be distributed following the terms of their original licenses. 

## License

The original code of this repository is  released under the [BSD 3.0-Clause License](https://github.com/armaank/dbn/blob/main/LICENSE). Modifications, adaptations and derivative work is encouraged! 


## Contributors

Jesse Bassett, Anna Konvicka, Armaan Kohli 

