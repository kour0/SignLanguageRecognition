# SignLanguageRecognition

Ce projet est un projet de construction d'un modèle d'IA permettant de reconnaitre les lettres issus du langage des signes. Deux modèles ont été réalisés, avec ou sans Data Augmentation et sont des modèles de réseaux de neurones convolutifs.

## Technologies utilisées

- Python
- Tensorflow
- Keras

## Description du projet

Le langage des signes est un moyen de communication essentiel pour les personnes sourdes ou malentendantes. Cependant, il peut être difficile pour les personnes entendantes de comprendre ce langage. Ce projet vise à résoudre ce problème en utilisant l'IA pour reconnaitre les lettres du langage des signes.

Deux modèles ont été réalisés pour ce projet. Le premier modèle a été entrainé sur les données brutes, tandis que le second modèle a été entrainé sur les données avec Data Augmentation.

### Modèle 1

![Model 1](/img/model1.png)

Le premier modèle est un modèle de réseau de neurones convolutifs simple. Il a été entrainé sur les données brutes.

### Modèle 2

![Model 2](/img/model2.png)

Le second modèle est un modèle de réseau de neurones convolutifs plus complexe. Il a été entrainé sur les données avec Data Augmentation.

## Données utilisées

Télécharger les données ci-joint : https://www.kaggle.com/datasets/datamunge/sign-language-mnist

Décompresser le fichier et renommer le dossier "archive" en "data" :

```shell
unzip archive.zip
mv archive data
```

## Installation

Pour utiliser ce projet, vous devez avoir Python, Tensorflow et Keras installés sur votre ordinateur. Vous pouvez installer les dépendances avec la commande suivante :

```shell
pip install -r requirements.txt
```

## Utilisation

Pour utiliser ce projet, il vous suffit de cloner ce dépôt sur votre ordinateur. Vous pouvez ensuite entrainer les modèles en utilisant les commandes suivantes :

```shell
python model1.py
python model2.py
```

Vous pouvez ensuite tester les modèles en utilisant les commandes suivantes :

```shell
python test.py
```

Pour finir, après avoir entrainé les modèles, vous pouvez les utiliser pour prédire les lettres du langage des signes en utilisant votre webcam :

```shell
python livecam.py
```

## Licence

Ce projet est sous licence MIT. Voir le fichier LICENSE pour plus de détails.