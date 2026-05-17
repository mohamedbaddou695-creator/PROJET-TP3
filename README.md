# Segmentation de Clients de Carte de Crédit par Apprentissage Non-Supervisé

Ce projet présente une étude comparative de six algorithmes de clustering appliqués à un dataset de clients de carte de crédit. L’objectif principal est d’identifier différents profils de clients à travers des techniques d’apprentissage non supervisé afin d’améliorer la compréhension des comportements financiers et d’aider à la prise de décision marketing.

Le pipeline comprend le prétraitement des données, l’encodage des variables catégorielles, la normalisation avec StandardScaler, la suppression des valeurs aberrantes via Isolation Forest, ainsi qu’une réduction de dimensionnalité par PCA. Ensuite, plusieurs algorithmes de clustering sont appliqués et évalués à l’aide de métriques telles que le Silhouette Score, le Davies-Bouldin Index et le Calinski-Harabasz Score.

Les résultats obtenus permettent d’identifier plusieurs segments de clients présentant des comportements d’achat et des niveaux de dépenses différents, démontrant l’efficacité des méthodes de clustering dans l’analyse des données financières.README — Segmentation de Clients de Carte de Crédit par Apprentissage Non-Supervisé
Description du Projet

Ce projet présente une étude comparative de six algorithmes de clustering appliqués à un dataset de clients de carte de crédit.
L’objectif principal est d’identifier différents profils de clients à travers des techniques d’apprentissage non supervisé afin d’améliorer l’analyse comportementale, la segmentation marketing et la prise de décision stratégique.

Le projet inclut :

Prétraitement et nettoyage des données
Détection des valeurs aberrantes
Normalisation des variables
Réduction de dimensionnalité avec PCA
Application de plusieurs algorithmes de clustering
Évaluation comparative des performances
Visualisations et interprétation des résultats
Algorithmes de Clustering Utilisés

Les modèles étudiés dans ce travail sont :

K-Means
Agglomerative Clustering
DBSCAN
Spectral Clustering
Gaussian Mixture Model (GMM)
Birch
Technologies Utilisées
Python 3
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
Dataset

Le dataset utilisé contient des informations financières et comportementales des clients de carte de crédit :

Revenus
Dépenses
Fréquence des achats
Transactions web
Transactions magasin
Produits achetés
Réponses aux campagnes marketing
Pipeline du Projet

Le pipeline expérimental suit les étapes suivantes :

Chargement des données
Nettoyage des valeurs manquantes
Encodage des variables catégorielles
Standardisation des données
Suppression des valeurs aberrantes avec Isolation Forest
Réduction de dimensionnalité avec PCA
Application des algorithmes de clustering
Évaluation des modèles
Visualisation des clusters
Métriques d’Évaluation

Les performances des modèles sont comparées à l’aide de :

Silhouette Score
Davies-Bouldin Index
Calinski-Harabasz Score
Inertia (pour K-Means)
