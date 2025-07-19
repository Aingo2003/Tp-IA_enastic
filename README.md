# Tp-IA_enastic

Travaux Pratiques en Intelligence Artificielle 🤖
Ce dépôt contient les travaux pratiques réalisés dans le cadre du cours d'Intelligence Artificielle. Chaque TP aborde des concepts fondamentaux de l'IA et du Machine Learning à travers des applications concrètes.

Structure du Dépôt 📂
Chaque TP est organisé dans son propre dossier, contenant le code source (souvent sous forme de notebooks Jupyter), les données nécessaires et un court rapport ou des commentaires expliquant la démarche et les résultats.

.
├── TP1_Classification_Iris/
├── TP2_Prediction_Prix_Maison/
├── TP3_Classification_MNIST/
├── TP4_Classification_CIFAR10/
└── README.md
Description des TP
🌸 TP1 : Classification des Fleurs Iris
Objectif : Introduire les bases de la classification en utilisant l'ensemble de données Iris.

Concepts abordés : Chargement et exploration des données, prétraitement simple, entraînement de modèles de classification (ex: k-NN, machines à vecteurs de support - SVM, régression logistique), évaluation des performances (précision, rappel, F1-score).

Données : Dataset Iris (souvent inclus dans les bibliothèques ML comme Scikit-learn).

🏠 TP2 : Prédiction des Prix d'une Maison avec la Régression
Objectif : Appliquer les techniques de régression pour prédire une valeur continue, ici le prix d'une maison.

Concepts abordés : Régression linéaire, régression polynomiale, évaluation des modèles de régression (erreur quadratique moyenne - MSE, erreur absolue moyenne - MAE, coefficient de détermination R 
2
 ), gestion des variables numériques et catégorielles.

Données : Un dataset typique de prix de maisons (par exemple, Boston Housing, ou un dataset similaire).

✍️ TP3 : Classification avec le Dataset MNIST
Objectif : S'initier à la classification d'images numériques à grande échelle en utilisant le célèbre dataset MNIST (chiffres manuscrits).

Concepts abordés : Traitement d'images simples, introduction aux réseaux de neurones (multi-couches - MLP), entraînement et évaluation de modèles sur des données d'images.

Données : Dataset MNIST (largement disponible et intégré dans des bibliothèques comme Keras/TensorFlow).

🖼️ TP4 : Classification d'Images CIFAR-10
Objectif : Approfondir la classification d'images en utilisant le dataset CIFAR-10, qui est plus complexe que MNIST.

Concepts abordés : Réseaux de neurones convolutifs (CNN), augmentation de données, transfer learning (potentiellement, selon l'étendue du TP), techniques d'optimisation et de régularisation pour les CNN.

Données : Dataset CIFAR-10 (disponible via des bibliothèques comme Keras/TensorFlow).

Technologies Utilisées 🛠️
Python

Jupyter Notebook ou Google Colab

NumPy

Pandas

Matplotlib / Seaborn

Scikit-learn

TensorFlow / Keras (pour les TP sur les réseaux de neurones)

Comment Utiliser ce Dépôt 🚀
Cloner le dépôt :

Bash

git clone https://github.com/votre_nom_utilisateur/IA_TPs.git
cd IA_TPs
Installer les dépendances (il est recommandé d'utiliser un environnement virtuel) :

Bash

pip install -r requirements.txt
(Si le fichier requirements.txt n'existe pas, installez les bibliothèques mentionnées dans la section "Technologies Utilisées" manuellement).

Naviguer vers le dossier du TP souhaité et ouvrir le notebook Jupyter ou exécuter le script Python.
