# A New Multi-View Method for Extractive Text Summarization (MVESum)

Ce dépôt contient l'implémentation officielle de mon projet de Master de Recherche (IKM) intitulé **"A New Multi-View Method for Extractive Text Summarization"**, réalisé à l'ISG Tunis.

## 📌 Présentation du Projet
L'explosion de l'information numérique rend la synthèse automatique de documents essentielle. Ce projet propose **MVESum**, une nouvelle méthode de résumé extractif basée sur une approche **Multi-Vues**. L'idée centrale est de combiner différentes représentations textuelles pour capturer la richesse sémantique et structurelle des documents.

### Points clés :
* **Multi-View Learning** : Utilisation de plusieurs perspectives (Vues) pour représenter le texte.
* **Approche Extractive** : Sélection des phrases les plus pertinentes directement depuis le texte source.
* **Algorithmes utilisés** : Clustering K-Means, TextRank, et représentations sémantiques avancées.

## ⚙️ Architecture de MVESum
La méthode se décompose en plusieurs étapes majeures :
1. **Prétraitement** : Nettoyage du texte, tokenisation et élimination des mots vides (stop-words).
2. **Représentation Multi-Vues** : Génération de vecteurs (Embeddings) via différentes méthodes (TF-IDF, SBERT, etc.).
3. **Clustering & Ranking** : Utilisation de K-Means pour regrouper les thèmes et de TextRank pour classer l'importance des phrases au sein de chaque vue.
4. **Fusion des Vues** : Agrégation des résultats pour produire le résumé final optimal.

## 🚀 Installation

Clonez le dépôt :
```bash
git clone [https://github.com/votre-username/MVESum.git](https://github.com/votre-username/MVESum.git)
cd MVESum 
