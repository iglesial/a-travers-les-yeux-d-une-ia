# À travers les yeux d’une IA

*Atelier découverte de la vision par ordinateur — AI UpSkill*

[![Ouvrir dans Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iglesial/a-travers-les-yeux-d-une-ia/blob/main/atelier.ipynb)

Découvrez comment une IA apprend à voir. Vous entraînerez un modèle de reconnaissance d’images et observerez les motifs qu’il invente seul : contours, textures, formes. Puis, en équipe, vous construirez votre propre modèle et le mettrez à l’épreuve.

## Pour commencer

1. Cliquez sur le bouton **Ouvrir dans Colab** ci-dessus.
2. *Fichier → Enregistrer une copie dans Drive* : vous travaillez sur votre copie.
3. Exécutez les cellules dans l’ordre avec **Maj + Entrée**.

Aucune installation, pas de carte graphique : un navigateur et un compte Google suffisent.

## Au programme

| Partie | Durée | Contenu |
|---|---|---|
| 1. Les filtres à la main | 10 min | Détecter les bords d’une photo avec 9 nombres, puis inventer son filtre |
| 2. Entraîner un modèle | 15 min | Un petit modèle apprend seul ses filtres sur CIFAR-10 |
| 3. Dans la tête d’un grand modèle | 10 min | Les filtres, les couches et les « rêves » de ResNet-50 |
| 4. En équipe | 20 min | Régler son modèle, 3 minutes d’entraînement, puis le mettre à l’épreuve |

## Données et modèles

- [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) (Krizhevsky, 2009), téléchargé depuis son miroir Hugging Face [`uoft-cs/cifar10`](https://huggingface.co/datasets/uoft-cs/cifar10).
- ResNet-50 pré-entraîné sur ImageNet, poids `IMAGENET1K_V2` de `torchvision`.
- La photo de Chelsea est fournie avec [scikit-image](https://scikit-image.org/).
