# Modèles génératifs avec PyTorch

**Auteure :** LOTFI Malak
**Filière :** 5IIR - EMSI
**Année universitaire :** 2026/2027

## Description

Ce TP porte sur les modèles génératifs avec PyTorch, appliqués au dataset MNIST (chiffres manuscrits). Un générateur est entraîné pour produire de nouvelles images de chiffres.

## Contenu du dépôt

- `Modeles_generatifs_pytorch.ipynb` : notebook principal du TP
- `main.py` : script Python
- `generator_mnist.pt` : poids du générateur entraîné
- `images_generees/` : images produites par le modèle
- `pyproject.toml` et `uv.lock` : dépendances du projet

## Lancer le projet

```bash
pip install torch torchvision matplotlib jupyter
jupyter notebook Modeles_generatifs_pytorch.ipynb
```

Le dataset MNIST est téléchargé automatiquement par PyTorch au premier lancement.
