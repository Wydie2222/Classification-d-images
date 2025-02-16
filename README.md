# Classification d'Images avec Transfer Learning

## 📌 Description du Projet

Ce projet vise à classifier les images de la base de données **CIFAR-10** en exploitant des modèles de machine learning. L’objectif est de comparer les performances :
- d’un **Perceptron Multicouche (MLP)**,
- d’un **réseau de neurones convolutifs (CNN)**,
- et d’explorer l’apport du **Transfer Learning** pour améliorer la précision des prédictions.

## 📊 Présentation de la Base de Données

**CIFAR-10** est un ensemble de données contenant **60 000 images en couleur (32x32 pixels)**, réparties en **10 classes** représentant des objets courants :

✈️ Avions | 🚗 Automobiles | 🐦 Oiseaux | 🐱 Chats | 🦌 Cerfs | 🐶 Chiens | 🤸️ Grenouilles | 🐎 Chevaux | 🚢 Bateaux | 🚚 Camions

Chaque classe comprend **6 000 images**.

## 🛠️ Technologies utilisées

- **Python**
- **TensorFlow/Keras** (Deep Learning)
- **NumPy, Pandas** (Manipulation des données)
- **Matplotlib, Seaborn** (Visualisation)
- **Scikit-learn** (Evaluation des modèles)

## 🚀 Étapes du projet

1. **Chargement et Prétraitement des Données**
   - Importation du dataset CIFAR-10
   - Normalisation des images
   - Encodage des étiquettes

2. **Modélisation**
   - Implémentation d’un **MLP** (Perceptron Multicouche)
   - Construction d’un **CNN** (Réseau de Neurones Convolutifs)
   - Expérimentation du **Transfer Learning** avec un modèle pré-entraîné

3. **Entraînement et Évaluation**
   - Comparaison des performances des modèles (précision, recall, f1-score)
   - Visualisation des erreurs de classification
   - Affichage des courbes de loss et d'accuracy

## 📂 Structure du projet

```
📁 Classification-d-images
️└️ 📄 Classification_Images.ipynb  # Notebook avec le code et l'analyse
️└️ 📄 README.md                    # Documentation du projet

## 🔧 Comment exécuter le projet ?

1. **Cloner le projet :**  
   ```bash
   git clone https://github.com/user/Classification-d-images.git
   ```
2. **Exécuter le notebook dans Jupyter :**  
   ```bash
   jupyter notebook Classification_Images.ipynb
   ```

