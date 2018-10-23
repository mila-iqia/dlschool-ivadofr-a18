# Gradient Descent

Ce notebook permet de créer une visualisation de différents algorithmes de gradient descent. Malhereusement, la librarire `ipyvolume` ne fonctionne pas sur les colabs, donc pour vous en servir, vous devrez configuer le notebook localement sur votre machine. 

## Installation

Tout d'abord, installez [jupyter notebook](http://jupyter.org/install)

Ensuite, installez les librairies suivantes:

* [autograd](https://github.com/HIPS/autograd) - un wrapper autour de numpy qui permet de calculer des dérivées de fonctions.
* [ipyvolume](https://ipyvolume.readthedocs.io/en/latest/index.html) - une librairie permettant de faire la visualisation de volumes 3D.
* [matplotlib](https://matplotlib.org/) - outil de visualisation de figures

Installation avec `conda`:

`conda install -c conda-forge ipyvolume`

`conda install -c conda-forge matplotlib`

Installation avec `pip`:

`pip install autograd`

Assurez-vous d'avoir une version `matplotlib>=3.0.0` 

## Utilisation du notebook

Ouvrez le notebook et exécutez les cellules en ordre. Voici un exemple de output:

![alt-text](exemples/images/sample_output.png)
