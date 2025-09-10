# Fairness in Machine Learning - Hackathon

Ce projet explore différentes stratégies pour améliorer l’équité dans les modèles de machine learning, en utilisant des techniques de pré-traitement, d’entraînement et de post-traitement.  
Les notebooks montrent comment mesurer et corriger le biais lié à des variables sensibles (genre, âge, etc.) avec les librairies [dalex](https://github.com/ModelOriented/DALEX), [fairlearn](https://fairlearn.org/), [aif360](https://aif360.readthedocs.io/), et scikit-learn.

## Contenu

- **Notebooks** : exemples de pré-traitement, post-traitement et analyse de l’équité
- **Mesure du biais** : utilisation de dalex et fairlearn pour évaluer la fairness
- **Correction du biais** : suppression de variables sensibles, méthodes ROC-pivot, etc.
- **Visualisation** : graphiques pour comparer les performances et l’équité

## Installation

1. Clone le dépôt :
   ```bash
   git clone https://github.com/nawalchahboune/ml-bias-mitigation.git
   cd ml-bias-mitigation
   ```

2. Crée un environnement virtuel :
   ```bash
   python -m venv .venv
   ```

3. Active l’environnement virtuel :
   - **Windows** :
     ```bash
     .venv\Scripts\activate
     ```
   - **Mac/Linux** :
     ```bash
     source .venv/bin/activate
     ```

4. Installe les dépendances :
   ```bash
   pip install -r requirements.txt
   ```

## Utilisation

- Ouvre les notebooks avec JupyterLab ou VS Code.
- Suis les exemples pour tester différentes stratégies de mitigation du biais.
- Modifie les cellules pour expérimenter avec tes propres données ou paramètres.


## Ressources

- [dalex](https://github.com/ModelOriented/DALEX)
- [fairlearn](https://fairlearn.org/)
