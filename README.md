# 🔍 Détection de fraude dans un réseau social

Ce projet vise à détecter les utilisateurs frauduleux dans un réseau social simulé à l'aide de graphes.  
Nous avons modélisé un réseau social de 100 utilisateurs, analysé leurs interactions, puis entraîné un modèle d'apprentissage automatique pour prédire les comportements frauduleux.

---

## 🎯 Objectifs

- Générer un graphe représentant les relations entre utilisateurs.
- Simuler des comportements frauduleux dans le réseau.
- Extraire des caractéristiques pertinentes des nœuds (centralité, degré, etc.)
- Entraîner un modèle de machine learning pour détecter les fraudes.
- Évaluer les performances du modèle.

---

## 🛠️ Technologies utilisées

- Python
- NetworkX
- Scikit-learn
- Pandas, NumPy, Matplotlib
- Jupyter Notebook

---

## 📊 Démarche

1. **Génération du réseau** : création d'un graphe aléatoire de 100 nœuds représentant les utilisateurs.
2. **Simulation des fraudes** : étiquetage aléatoire de certains nœuds comme frauduleux (variable cible `is_fraud`).
3. **Extraction des features** :
   - Degré d’un nœud
   - Centralité
   - Clustering coefficient
   - PageRank, etc.
4. **Entraînement du modèle** : Utilisation de modèles comme la régression logistique, random forest, etc.
5. **Évaluation** :
   - Matrice de confusion
   - Précision, rappel, F1-score

---

## 📁 Contenu du projet

- `Projet_Graphes_Python_Presentable.ipynb` : notebook principal avec tout le code, les visualisations et les résultats.
- `data/` *(à créer si besoin)* : dossier pour stocker les jeux de données (si externes).
- `README.md` : ce fichier.

---

## 📌 Résultats

Le modèle entraîné a permis d’identifier les comportements suspects avec un bon équilibre entre précision et rappel.  
Les résultats montrent que certaines métriques comme la centralité de proximité sont de bons indicateurs de fraude.

---

## 👩🏽‍💻 Réalisé par

- **Grace TEKAM**  
- Projet académique réalisé dans le cadre de [nom du cours ou de l’établissement].

---

## 📬 Contact

Pour toute question ou suggestion, n’hésitez pas à me contacter sur [ton mail professionnel ou LinkedIn].

