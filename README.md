# 🩺 IA et Santé — Classification d’images médicales avec modèles ML/DL

[![Python](https://img.shields.io/badge/Python-3.11-blue)](https://www.python.org/)
[![Licence](https://img.shields.io/badge/Licence-MIT-green)](LICENSE)

---

##  Objectif du Projet
Développer un système d’**analyse et classification d’images médicales** pour détecter la COVID-19 à partir de radiographies pulmonaires.  

- Extraction de caractéristiques à partir d’images médicales  
- Classification avec **modèles de Machine Learning**  
- Comparaison des performances avec **modèles Deep Learning** : VGG19, ResNet50  
- Interprétation des résultats via **XAI (Explainable AI)**  

---

## 🛠 Fonctionnalités

- Prétraitement et préparation du dataset d’images pulmonaires  
- Classification des images avec différents modèles ML (SVM, Random Forest…)  
- Évaluation des modèles Deep Learning (VGG19, ResNet50)  
- Analyse des performances (accuracy, confusion matrix, ROC)  
- Visualisation et interprétation des décisions des modèles via **XAI**  

---

##  Contenu du Repository

| Fichier                                      | Description                                                |
|---------------------------------------------|------------------------------------------------------------|
| `Préparation_du_dataset.ipynb`              | Prétraitement et organisation du dataset d’images         |
| `Classification_avec_modèles_Deep_Learning.ipynb` | Entraînement et évaluation des modèles VGG19 & ResNet50   |
| `Classification_avec_modèles_machine_learning.ipynb` | Classification via modèles classiques de ML (SVM, RF…)    |
| `XAI.ipynb`                                 | Interprétation des décisions des modèles (Explainable AI) |
| `Pésentation_détection_du_Covid.pptx`      | Présentation synthétique du projet                         |

---

##  Logiciel

- **Langage** : Python  
- **Librairies principales** :  
  - `Scikit-learn` pour ML classique  
  - `TensorFlow` pour Deep Learning  
  - `Keras` pour l’implémentation des réseaux profonds  
  - `Matplotlib` et `Seaborn` pour visualisation  
  - `XAI` pour l’interprétation des modèles  

---

## ⚙️ Installation

1. Cloner le projet :  
```bash
git clone https://github.com/issrafguir/Classification-de-la-COVID-19-partir-de-radiographies-pulmonaires.git
