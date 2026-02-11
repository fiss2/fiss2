# README

## Projet : LE SCHEMA CKKS ET LE MACHINE LEARNING APPLIQUES A LA DETECTION DE LA FRAUDE DE DONNEES A LA CARTE DE CREDIT

### Description
Ce projet a pour but de détecter les fraudes bancaires dans des transactions en utilisant une approche de Machine Learning. Nous avons implémenté un modèle de régression logistique avec une optimisation des variables directives via l'algorithme de Particle Swarm Optimization (PSO). Le modèle est formé sur un ensemble de données de cartes de crédit et utilise à la fois des techniques chiffrées et non chiffrées.

### Fonctionnalités
- **Chargement des données** : Importation et prétraitement des données de transactions de cartes de crédit.
- **Équilibrage des classes** : Utilisation de techniques d'échantillonnage pour équilibrer les classes dans les données.
- **Sélection de variables** : Implémentation de l'algorithme PSO pour sélectionner les variables les plus pertinentes.
- **Modèle de prédiction** : Entraînement d'un modèle de régression logistique pour prédire les fraudes.
- **Évaluation des performances** : Calcul de métriques telles que la précision, le rappel, le F1-score et l'AUC.
- **Visualisation** : Graphiques montrant l'évolution de la perte et la précision au cours des époques d'entraînement.

### Prérequis
- Python 3.x
- Bibliothèques :
  - `torch`
  - `tenseal`
  - `pandas`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`

### Installation
1. Clonez le dépôt :
   ```bash
   git clone https://votre_lien_dépôt.git
   cd votre_dossier
   ```
2. Installez les dépendances :
   ```bash
   pip install -r requirements.txt
   ```

### Utilisation
1. Exécutez le script principal :
   ```bash
   python implementation.py
   ```
2. Suivez les instructions affichées pour charger vos données et exécuter le modèle.

### Résultats
Les résultats des performances du modèle seront affichés à la fin de l'exécution, y compris les métriques de performance et une visualisation de la courbe ROC.

### Contribution
Les contributions sont les bienvenues ! Si vous souhaitez contribuer à ce projet, merci de soumettre une pull request ou d'ouvrir une issue.

### Licence
Ce projet est sous licence MIT - Consultez le fichier LICENSE pour plus de détails.

---

Pour toute question ou assistance, n'hésitez pas à contacter l'auteur du projet.
