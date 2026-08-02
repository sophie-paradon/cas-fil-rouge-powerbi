# Cas Fil Rouge — Dashboard Power BI

Dashboard interactif pour une usine de fabrication de câbles, avec une **marge commerciale de 21,52% atteinte contre un objectif de 20%** (+7,62 points).

## Problématique
L'équipe commerciale d'une usine de câbles veut un dashboard pour suivre la facturation, évaluer la rentabilité (marge) et identifier les clients et produits les plus rentables, afin de savoir où concentrer les efforts commerciaux.

## Compétences mobilisées
- Power Query : nettoyage et fusion de 5 sources (facturation 2022/2023, clients, produits, table de correspondance secteur d'activité)
- Modélisation : modèle en étoile
- DAX : mesures avec `CALCULATE`, `ALLSELECTED`, `RANKX`, `ISBLANK`, KPI avec objectif natif
- Visualisation : formatage conditionnel, analyse Pareto client/produit
- Déploiement : rôles de sécurité RLS/OLS, dashboard épinglé, rapport paginé, publication sur workspace Power BI Service

## Données sources
5 fichiers : facturation 2022 (année complète), facturation 2023 (partielle), référentiel clients, référentiel produits, table de correspondance secteur d'activité.

## Résultats
- Marge commerciale : 21,52% (objectif : 20%)
- Identification des clients et produits les plus rentables via analyse Pareto
- Dashboard avec suivi du CA par segment client/produit

## Limites
Facturation 2023 partielle (année non complète au moment de l'analyse) — les tendances 2023 sont donc indicatives, pas définitives.

## Outils
Power BI Desktop, Power Query, DAX, Power BI Service
