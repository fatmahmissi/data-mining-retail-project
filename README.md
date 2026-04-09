# data-mining-retail-project


##  Titre du projet
Analyse du comportement des clients et des produits (Online Retail II)

---

##  Réalisé par
Hmissi Fatma

---

##  Objectif du projet
Ce projet vise à analyser les comportements d’achat des clients afin de :
- Segmenter les clients selon leur comportement
- Identifier les profils clients (faible, fidèle, premium)
- Trouver les relations entre produits
- Aider à la prise de décision marketing

---

## Dataset utilisé
Online Retail II (UCI / Kaggle)  
https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci

---

##  Outils utilisés
- Python
- Pandas, NumPy
- Scikit-learn (KMeans, CAH, StandardScaler)
- MLxtend (FP-Growth, Association Rules)
- Matplotlib, Seaborn

---

##  Étapes pour exécuter le projet

1. Ouvrir Jupyter Notebook / JupyterLab
2. Installer les bibliothèques nécessaires :pip install pandas numpy matplotlib seaborn scikit-learn mlxtend
3. Ouvrir le fichier :notebook.ipynb

4. Exécuter les cellules dans cet ordre :
- Nettoyage des données
- Analyse RFM
- Clustering KMeans
- Clustering CAH
- FP-Growth (règles d’association)

---

##  Structure du projet
- notebook.ipynb → code principal
- dataset.csv → données utilisées
- README.md → description du projet

---

##  Résultats obtenus
- Segmentation des clients en 3 clusters
- Identification des clients premium
- Détection des produits fréquemment achetés ensemble
- Analyse du comportement d’achat par groupe

---

##  Conclusion
Ce projet a permis de comprendre les comportements des clients et de proposer des stratégies marketing adaptées. L’utilisation du clustering et des règles d’association a permis d’extraire des insights utiles pour l’entreprise.

---

##  Perspectives
- Tester d’autres algorithmes de clustering (DBSCAN, GMM)
- Ajouter des variables temporelles (saisonnalité)
- Développer un système de recommandation automatique

---
