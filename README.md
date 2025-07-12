# Titre : Masterclass sur l’Architecture Transformer et ses Fondements Mathématiques
![Transformer](https://miro.medium.com/v2/resize:fit:1400/1*uk-iU8FJuH1S_wXeiFZWOw.png)
## Présentation :
Cette masterclass propose une exploration approfondie de l’architecture Transformer — le socle des modèles de pointe tels que BERT et DistilBERT. Conçue pour les chercheurs, ingénieurs et apprenants avancés, elle allie théorie rigoureuse et mise en pratique, en mettant l’accent sur les principes mathématiques qui sous-tendent les mécanismes d’attention et en guidant les participants à travers des implémentations concrètes.

Ce que vous allez apprendre :
- Les limites des modèles séquentiels traditionnels et l’émergence des mécanismes d’attention
- La structure interne des Transformers : attention multi-tête, couches feedforward, normalisation, encodage positionnel
- Les fondements mathématiques : espaces vectoriels, opérations matricielles, produit scalaire, softmax, rétropropagation
- Le fonctionnement de BERT et DistilBERT dans des tâches NLP concrètes

## Structure du cours :
La masterclass est organisée en modules thématiques :

1. Introduction au traitement séquentiel et aux limites des RNN
2. Architecture Transformer : conception encodeur-décodeur
3. Fondements mathématiques : vecteurs, matrices et géométrie de l’attention
4. Mécanisme d’attention : théorie et calcul
5. Encodage positionnel et modélisation du contexte linguistique
6. Optimisation et dynamique d’apprentissage dans les Transformers
7. Étude de cas : BERT et DistilBERT en pratique
8. Ateliers pratiques

## Ateliers pratiques :
- Atelier 1 : Manipulation de vecteurs et matrices en Python (NumPy et PyTorch)
- Atelier 2 : Implementation d'un transformer based model de zero pour predire le mot suivant dans une phrase donnèe
- Atelier 3 : Implémentation du mécanisme d’attention (attention scalaire et attention multi-tête)
- Atelier 4 : Fine-tuning de BERT ou DistilBERT sur une tâche NLP (ex. : analyse de sentiments, questions-réponses)


## Prérequis :
- Maîtrise du langage Python
- Connaissances en algèbre linéaire (vecteurs, matrices, produits scalaires)
- Compréhension de base des réseaux de neurones et de la rétropropagation
- Expérience avec PyTorch ou un framework similaire recommandée

## Ressources fournies :
- Diapositives de cours et notebooks annotés
- Jeux de données et modèles pré-entraînés
- Lectures recommandées et articles de recherche
- Accès à un forum privé pour les échanges et questions


## Les Labs sont executables dans google colab ou en local
### Pour google colab

Il sufit de cliquer sur l'icon de colab au debut du notebook et faire une `copie` dans votre `drive` avant toute modification

### Pour local

Suivez les intructions suivantes:
# clone du repo
```bash
git clone  https://github.com/Umbaji/Togo-Data-Lab-Masterclass.git
```
# Installation des dépendances

## Prérequis
- Python 3.10 ([Téléchargement](https://www.python.org/downloads/))
- `pip` (normalement inclus avec Python 3.10)

## Création de l'environnement virtuel

### Linux/macOS
```bash
python3.10 -m venv venv
source venv/bin/activate
```

### Windows
```bash
python -m venv venv
.\venv\Scripts\Activate.ps1
```

#### Puis installer avec:(optionnel puisque les commandes d'installations se trouvent dans les notebooks)
```bash
pip install -r requirements.txt
```
## Licence :
Tous les supports sont distribués sous licence Creative Commons Attribution - NonCommercial - ShareAlike 4.0 International.

## Contact :
Pour toute question, retour ou proposition de collaboration, veuillez écrire à : contact@umbaji.org ou  contact@datalab.gouv.tg

Décortiquons ensemble les mathématiques derrière les modèles qui transforment l’intelligence artificielle.
