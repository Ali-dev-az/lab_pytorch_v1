# TP – Deep Learning avec PyTorch

## Présentation du projet

Ce projet consiste à découvrir et à mettre en pratique les concepts fondamentaux du Deep Learning à l'aide de **PyTorch**, une bibliothèque Python dédiée à l'apprentissage automatique et aux réseaux de neurones.

L'objectif est de comprendre les différentes étapes de création, d'entraînement et d'évaluation de modèles de Deep Learning.

## Objectifs pédagogiques

- Découvrir les tenseurs et les opérations fondamentales de PyTorch.
- Comprendre le fonctionnement des réseaux de neurones.
- Construire et entraîner des modèles avec `torch.nn`.
- Utiliser les fonctions de perte et les optimiseurs.
- Effectuer la propagation avant (*Forward Propagation*) et la rétropropagation (*Backpropagation*).
- Évaluer les performances des modèles.
- Découvrir les réseaux de neurones convolutifs (CNN).

## Technologies utilisées

- **Python 3.11**
- **PyTorch** : création et entraînement des modèles.
- **NumPy** : manipulation des données numériques.
- **Matplotlib** : visualisation des résultats et des graphiques.
- **Jupyter Notebook** : environnement de développement interactif.

## Contenu du TP

Le notebook regroupe plusieurs notions pratiques :

1. Initialisation et manipulation des tenseurs.
2. Opérations mathématiques avec PyTorch.
3. Création de réseaux de neurones.
4. Entraînement des modèles.
5. Calcul des fonctions de perte.
6. Optimisation des paramètres avec Adam.
7. Évaluation des performances avec l'Accuracy.
8. Introduction aux réseaux convolutifs (CNN).
9. Classification d'images avec une architecture CNN.

## Installation

Cloner le dépôt :

```bash
git clone <URL_DU_DEPOT>
cd <NOM_DU_DEPOT>
```

Installer les dépendances :

```bash
pip install torch torchvision numpy matplotlib jupyter
```

Lancer Jupyter Notebook :

```bash
jupyter notebook
```

Ouvrir ensuite le notebook contenant les exercices pratiques.

## Concepts clés

| Concept | Description |
|---|---|
| Tensor | Structure de données multidimensionnelle |
| nn.Module | Classe de base pour construire un modèle |
| Linear | Couche entièrement connectée |
| Conv2d | Couche de convolution |
| ReLU | Fonction d'activation |
| MaxPool2d | Réduction des dimensions spatiales |
| CrossEntropyLoss | Fonction de perte pour la classification |
| Adam | Algorithme d'optimisation |
| Backpropagation | Calcul des gradients |

## Conclusion

Ce travail pratique permet d'acquérir une première expérience concrète avec PyTorch et de comprendre le processus de développement d'un modèle de Deep Learning, depuis la préparation des données jusqu'à l'évaluation des performances.

Il constitue une base pour approfondir les architectures de réseaux de neurones et aborder des applications plus avancées en intelligence artificielle.

---

**Projet réalisé dans le cadre de l'apprentissage du Deep Learning avec PyTorch.**# lab_pytorch_v1
