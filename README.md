# Network Flow Management Simulator

## Description  
Ce projet simule et compare différentes stratégies de gestion de flux à l’entrée d’un réseau de communication. Il analyse les performances en fonction du taux de transmission et du paramètre λ d’arrivée des paquets. Une interface graphique intuitive permet de visualiser dynamiquement les simulations et les résultats analytiques.

## Installation  
Avant d’exécuter le projet, installez les dépendances avec :  

```bash
python mecanisme_installation.py
```

## Exécution  
Pour démarrer l’application, lancez :  

```bash
python modules/main.py
```

## Structure du projet  
- **`modules/`** : Contient tous les fichiers du projet  
  - **`structure.py`** : Définit les structures de données (paquets, buffers, sources).  
  - **`strategies.py`** : Implémente plusieurs stratégies de gestion des files d’attente.  
  - **`analysePerformances.py`** : Analyse les performances du système.  
  - **`analysePerformancesstrategies.py`** : Compare les stratégies de gestion des flux.  
  - **`Visual1.py`** : Simulation dynamique de la première partie.  
  - **`Visual2.py`** : Simulation dynamique avec choix de stratégie.  
  - **`Test.py`** : Programme de test des fonctionnalités.  
- **`mecanisme_installation.py`** : Installe les dépendances nécessaires.  
- **`main.py`** : Point d’entrée du projet.  

## Fonctionnalités  
- **Simulation** de l’arrivée et de la transmission des paquets avec un processus de Poisson.  
- **Comparaison de plusieurs stratégies de gestion des files d’attente** :  
  - Sélection de la file la plus chargée.  
  - Sélection cyclique des files.  
  - Sélection aléatoire.  
- **Visualisation** des performances à l’aide de graphes et d’une interface Tkinter.  

## Utilisation  
L’utilisateur peut :  
1. **Visualiser les performances** en fonction de **λ**.  
2. **Lancer une simulation** dynamique du réseau.  
3. **Comparer l’efficacité** des stratégies de gestion des flux.  

## Dépendances  
- Python 3.x  
- NumPy  
- Matplotlib  
- Tkinter  
