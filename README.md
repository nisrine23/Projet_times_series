# **Projet: Times series**

Ce notebook contient l'exploration et la modélisation de séries temporelles de ventes. Voici un résumé des sections principales :

- **Génération de données synthétiques** : Création d'une série temporelle avec tendance, saisonnalité et bruit.
- **Modèle Naïf (Baseline)** : Évaluation des performances d'un modèle simple de prédiction du dernier mois.
- **Régression Linéaire** : Application d'un modèle de régression avec des fonctionnalités élaborées (lags, saisonnalité).
- **Modèles TensorFlow** : Implémentation de réseaux de neurones (MLP, LSTM, GRU) pour la prédiction de séries temporelles.
- **Fonctions de Fenêtrage** : Utilitaires pour préparer les données pour les modèles de séries temporelles.
- **Analyse du Dataset M5** : Exploration et visualisation d'un dataset de ventes réel.

### Résultats Clés

- Le modèle GRU a montré les meilleures performances sur l'ensemble de validation sur les données synthétiques.
- Le modèle de régression linéaire a surpassé la baseline naïve.

### Améliorations Futures

- Optimisation des hyperparamètres des modèles TensorFlow.
- Intégration de caractéristiques externes (prix, événements) pour les prévisions.
- Utilisation de modèles plus avancés pour les séries temporelles (ex: Prophet, ARIMA, Transformers).
