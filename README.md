# mon-projet1-powerbi
# Analyse des Prêts Immobiliers - Credit Breton

## Description du Projet

Ce projet Power BI est une solution d'analyse et de suivi des dossiers de prêts immobiliers pour le **Credit Breton**. L'objectif principal est d'évaluer les demandes de prêts en fonction de critères clés tels que :

- **Situation familiale** des emprunteurs (nombre d'enfants, âge, etc.).
- **Score emprunteur**, qui détermine la solvabilité de l'emprunteur.
- **Montant des prêts demandés**.
- **Alertes pour les gros montants** qui doivent être signalées aux directeurs d'agence.

L'application permet également d'aider les **conseillers** à prendre des décisions basées sur l'analyse du **score emprunteur** et fournit des **alertes visuelles** pour mettre en évidence les dossiers à examiner de plus près.

### Objectifs du Projet

1. **Analyser les dossiers de prêts** : Évaluer les informations des emprunteurs telles que le nombre d'enfants, l'âge et d'autres variables pour déterminer si un prêt doit être accepté ou refusé.
2. **Alertes pour les gros montants** : Générer une alerte visuelle pour signaler les prêts dont le montant dépasse un seuil spécifié, afin de prévenir le directeur d'agence.
3. **Conseils basés sur le score emprunteur** : Fournir des visualisations qui aident les conseillers à comprendre l'impact du score emprunteur sur l'acceptation des prêts et à conseiller les emprunteurs en conséquence.
4. **Visualisations interactives** : Offrir des graphiques, des cartes et des tableaux pour analyser l'ensemble des dossiers de prêts de manière intuitive.

### Sources de Données

Les données proviennent d'un fichier **Excel** et comprennent les informations suivantes pour chaque emprunteur :

- **Score emprunteur** : Un score numérique représentant la capacité de remboursement de l'emprunteur.
- **Nombre d'enfants** : Nombre d'enfants à charge de l'emprunteur, ce qui peut influencer la capacité à rembourser un prêt.
- **Âge de l'emprunteur** : Âge de l'emprunteur, ce qui peut être un facteur dans l'évaluation du risque de prêt.
- **Montant du prêt demandé** : Montant que l'emprunteur souhaite obtenir.
- **Revenu de l'emprunteur** : Revenu mensuel ou annuel de l'emprunteur.
- **Historique de crédit** : Information sur le passé financier de l'emprunteur (par exemple, s'il a déjà eu des problèmes de crédit).
- **Statut de la demande** : Acceptée ou refusée, selon l'analyse du dossier.

### Visualisations

Le projet comprend plusieurs visualisations pour aider à l'analyse des dossiers de prêts :

- **Graphiques de distribution** : Affichage de la distribution des prêts par âge, score emprunteur, montant demandé, etc.
- **Tableaux de bord** : Une vue d'ensemble des prêts acceptés et refusés, filtrée par différents critères (montant, score, situation familiale).
- **Cartes géographiques** : Si disponible, une carte montrant la répartition des dossiers par région (par exemple, pour visualiser où les demandes de prêts sont les plus nombreuses).
- **Alertes sur les gros montants** : Un indicateur visuel dans Power BI pour détecter les prêts qui dépassent un certain montant.
- **Mise en forme conditionnelle** : Utilisation de couleurs ou de styles pour mettre en évidence les prêts avec un score emprunteur faible, ou d'autres critères qui nécessitent une attention particulière.

### Fonctionnalités Clés

- **Alertes automatiques sur les gros montants** : Lorsque le montant d'un prêt dépasse un seuil défini, une alerte visuelle est générée.
- **Conseils pour les conseillers** : L'intégration du score emprunteur dans un tableau de bord interactif aide les conseillers à identifier les clients à haut risque et à leur fournir des conseils sur l'amélioration de leur solvabilité.
- **Filtrage interactif** : Les conseillers et directeurs d'agence peuvent filtrer les données par âge, nombre d'enfants, montant du prêt, et d'autres variables pour obtenir des insights personnalisés.
- **Analyse des dossiers** : Des graphiques interactifs permettent d'analyser la relation entre les variables (score emprunteur, âge, nombre d'enfants) et l'acceptation ou le refus du prêt.
