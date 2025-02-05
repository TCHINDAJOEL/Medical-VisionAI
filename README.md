# 📌 DeepLungNet - Détection COVID & Pneumonie par IA 🧠

## 🌍 Présentation du Projet

Ce projet implémente plusieurs modèles de **Deep Learning** pour détecter **COVID-19, la pneumonie bactérienne et virale** à partir d’images médicales.

🚀 **Modèles utilisés** :
- **MobileNetV2** (léger et rapide 🏎️)
- **VGG16** (réseau plus profond 🔬)
- **ResNet** (meilleure gestion du gradient 📈)

L’objectif est d’exploiter le **Transfer Learning** pour améliorer la détection même avec un **petit dataset**.

---
## 📦 Pré-requis et Installation

Lien du dataset : https://drive.google.com/drive/folders/1kfdbpCrR5EKE7_Nxywy1Fs5ezdNMnhAD

### 1️⃣ **Cloner le Repo**
```bash
git clone https://github.com/tonpseudo/DeepLungNet.git
cd DeepLungNet
```

### 2️⃣ **Installer les dépendances**
```bash
pip install -r requirements.txt
```

### 3️⃣ **Télécharger et organiser les données**
- 📁 **train/** *(Images d'entraînement)*
- 📁 **test/** *(Images de test)*

👉 **Les images doivent être classées par dossier** :
```
train/
  ├── covid/
  ├── normal/
  ├── pneumonia_bac/
  ├── pneumonia_vir/
test/
  ├── covid/
  ├── normal/
  ├── pneumonia_bac/
  ├── pneumonia_vir/
```

---
## 🏋️ Entraînement des Modèles

L'entraînement se fait à l’aide des notebooks :

### 📌 **MobileNetV2**
```bash
jupyter notebook Traitemant_2_covid.ipynb
```

### 📌 **VGG16**
```bash
jupyter notebook Traitemant_2_covid_VGG16.ipynb
```

### 📌 **ResNet**
```bash
jupyter notebook Traitemant_2_covid_ResNet.ipynb
```
---
## 📊 Résultats & Améliorations
- **Meilleur modèle** : ResNet a obtenu **78% d’accuracy** sur le test set 📈
- **Next Steps** : Ajouter plus de données et ajuster le fine-tuning.

---
## ⚖️ Licence
Ce projet est sous licence **MIT**.

📩 **Contact** : [LinkedIn](https://www.linkedin.com/in/jo%C3%ABl-tchinda-b12311226/) | [GitHub](https://github.com/TCHINDAJOEL))

