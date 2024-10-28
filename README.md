# Restricted Boltzmann machines for RNA design

Based on https://github.com/jertubiana/PGM. 

This repository contains an example Python code to train and sample a Restricted Boltzmann machine on SAM-I riboswitch aptamer domain family of homologous sequences (RF00162 on Rfam). This is provided as an alterative in Python to the original repository accompanying the paper https://github.com/cossio/SamApp2024.jl, which is in Julia. The Julia repository is preferrable since it is more complete and provides the source code to reproduce additional results in the paper (such as the analysis of the SHAPE data).

If you encounter any problems please open an issue.

## Setup

To setup the Python environment and dependencies, we recommend using `pixi`. See https://pixi.sh/latest/#installation for details on how to install `pixi` locally.

If you want to avoid local setup, these notebooks can also be run using Google Colab.

## Citation

If you use this code, please cite the references in the original PGM repository (https://github.com/jertubiana/PGM), in addition to:

> *Designing Molecular RNA Switches with Restricted Boltzmann Machines*
> 
> by Jorge Fernandez-de-Cossio-Diaz, Pierre Hardouin, Francois-Xavier Lyonnet du Moutier, Andrea Di Gioacchino, Bertrand Marchand, Yann Ponty, Bruno Sargueil, Rémi Monasson, Simona Cocco
> 
> bioRxiv preprint: https://www.biorxiv.org/content/10.1101/2023.05.10.540155v2.abstract

You can use the linked [CITATION.bib](https://github.com/cossio/SamApp2024.jl/blob/main/CITATION.bib).
