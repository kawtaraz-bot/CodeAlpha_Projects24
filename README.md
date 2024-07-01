# CodeAlpha_Projects24
CodeAlpha
# README.md

## Data Science Projects

Ce repository contient deux projets de data science : **Titanic Classification** et **Stock Prediction**. Chaque projet implique l'analyse et la prédiction de résultats basés sur des ensembles de données fournis. 

### TASK 1: **Titanic Classification**

#### Objective
Développer un système pour prédire si une personne survivra au naufrage du Titanic. La prédiction sera basée sur divers facteurs, y compris le **statut socio-économique**, l'**âge**, le **sexe**, et plus encore.

#### Dataset
Le dataset pour cette tâche est le dataset du Titanic, qui inclut des informations sur les passagers telles que leur âge, sexe, classe, tarif, et s'ils ont survécu.

#### Approach
1. **Exploration et Prétraitement des Données**:
   - Charger et inspecter le dataset.
   - Gérer les valeurs manquantes.
   - Encoder les variables catégorielles.
   - Mise à l'échelle des caractéristiques.

2. **Sélection des Caractéristiques**:
   - Identifier les caractéristiques significatives qui impactent les taux de survie.

3. **Entraînement du Modèle**:
   - Diviser les données en ensembles d'entraînement et de test.
   - Entraîner divers modèles de classification (par exemple, Régression Logistique, Arbre de Décision, Forêt d'Arbres).
   - Évaluer les performances du modèle en utilisant des métriques telles que la précision, la précision, le rappel, et le score F1.

4. **Évaluation et Sélection du Modèle**:
   - Comparer les performances de différents modèles.
   - Sélectionner le modèle le plus performant.

#### Usage
Exécutez le notebook Jupyter `titanic_classification.ipynb` pour voir l'analyse complète et le processus d'entraînement du modèle. Assurez-vous d'avoir les bibliothèques nécessaires installées en exécutant :
```bash
pip install -r requirements.txt
