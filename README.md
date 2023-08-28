# Projet de Classification d'Images pour la Détection du Risque de Pneumonie


## Table des matières
### Introduction
### Jeu de Données
### Notre Rôle
### Projets Connexes


### Introduction
Ce projet est dédié à la création d'un modèle de classification d'images destiné à déterminer si un patient présente un risque de pneumonie à partir de radiographies thoraciques. Les radiographies ont été préalablement classées en deux catégories : positif (présence de pneumonie) et négatif (absence de pneumonie). L'objectif principal est de développer un modèle de machine learning capable de faire cette classification de manière précise.

### Jeu de Données
Le jeu de données est constitué d'environ 5900 images, déjà divisées en deux classes : positif (pneumonie) et négatif (non pneumonie). Ces images sont essentielles pour l'entraînement, la validation et les tests du modèle.
Lien URL : https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

### Notre Rôle
Notre rôle dans ce projet comprend les étapes suivantes :

Importation du Jeu de Données : Nous avons importé le jeu de données d'images radiographiques pour l'analyser et le préparer en vue de l'entraînement du modèle.

Exploration des Variables : Nous avons exploré les caractéristiques du jeu de données, y compris la distribution des classes, pour mieux comprendre la nature des données.

Préparation des Images : Les images ont été préparées pour être utilisées dans le modèle, notamment en redimensionnant les images, en normalisant les valeurs de pixel et en effectuant d'autres opérations de prétraitement.

Modélisation avec Transfer Learning : Pour construire notre modèle, nous avons utilisé la technique du transfert d'apprentissage (Transfer Learning) en utilisant des architectures de réseaux neuronaux pré-entraînées. Cette approche nous a permis de bénéficier de l'apprentissage à partir de modèles préexistants pour améliorer la précision de notre modèle.


### Projets Connexes
Ce projet s'inscrit dans la continuité de notre travail précédent réalisé lors du Projet 6 d'OpenClassrooms. Le projet précédent comprenait également des opérations de data augmentation pour améliorer les performances du modèle.
