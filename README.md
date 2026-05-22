# scRNA-seq Analysis — PBMC 3k

Pipeline complet d'analyse single-cell RNA-seq sur 2700 cellules sanguines humaines.

## Résultats
8 types cellulaires identifiés sur le UMAP annoté.

## Pipeline
QC → Normalisation → HVG → PCA → UMAP → Clustering Leiden → Annotation

## Stack
Python, Scanpy, AnnData, Leiden, UMAP

## Reproduire l'analyse
```
conda env create -f environment.yml
conda activate scrna
jupyter lab
```
