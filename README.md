# Transformation du Parcours de Données | CHU Data Pipeline Transformation 

## FR - Présentation du projet
Le groupe CHU (Cloud Healthcare Unit) a fait appel à notre équipe pour les accompagner dans leur transformation digitale en mettant en place leur entrepôt de données.
L'objectif : centraliser, exploiter et visualiser les données issues de leurs systèmes hospitaliers afin de faciliter la prise de décision à l'échelle nationale.

Notre mission a couvert l'ensemble de la chaîne Big Data :
- Définition d'une architecture adaptée aux exigences médicales (sécurité, scalabilité, coût-efficacité)
- Modélisation, ingestion, stockage, exploration et visualisation des données issues des FTP et systèmes de gestion hospitaliers
- Intégration des données hétérogènes dans une source unique et persistante
- Mise en œuvre de Power BI pour restituer les analyses clés (consultation, hospitalisation, satisfaction...)


## Exigences fonctionnelles :
- Suivi par sexe, âge, diagnostic, professionnel, région
- Analyse du taux de satisfaction par localisation
- Données issues de plusieurs années (archives FTP)

## Étapes du projet
**Phase 1 - Architecture & Modélisation**
- Étude de l'architecture big data adaptée au contexte hospitalier
- Conception du modèle conceptuel et modèle physique des données

**Phase 2 - Ingestion & Stockage**
- Scripts de création des tables
- Chargement des données via scripts d'intégration
- Implémentation des partitions et buckets pour optimiser les accès

**Phase 3 - Performance & Visualisation**
- Requêtes d'analyse selon les critères utilisateurs
- Mesures des temps de réponse via des graphes de performance
- Dashboards Power BI pour la restitution finale

Résultat final
Grâce à cette infrastructure, le CHU dispose désormais :
- D'un entrepôt de données performant et sécurisé
- De visualisations claires pour orienter leurs décisions stratégiques
- D'une vue unifiée des patients à l'échelle nationale sur plusieurs années



# EN -Project Overview
The CHU (Cloud Healthcare Unit) engaged our team to support their digital transformation by implementing a custom data warehouse.
The goal: to centralize, explore, and visualize medical data from hospital systems to enable better decision-making on a national scale.

Our mission spanned the full Big Data pipeline:
- Designing a secure and scalable architecture
- Modeling, ingesting, storing, exploring, and visualizing data from FTP and hospital management systems
- Unifying heterogeneous data sources into a single persistent repository
- Delivering key business insights through Power BI dashboards

## Functional Requirements:
- Track patients by gender, age, diagnosis, professional, region
- Analyze satisfaction rates by location
- Work with multi-year historical data

## Project Phases
**Phase 1 – Architecture & Modeling**
- Analysis of a big data architecture suited to the hospital environment
- Design of the conceptual and physical data models

**Phase 2 – Ingestion & Storage**
- Table creation scripts
- Data loading via integration scripts
- Implementation of partitions and buckets to optimize data access

**Phase 3 – Performance & Visualization**
- Analytical queries based on user requirements
- Response time measurements using performance graphs
- Power BI dashboards for final data presentation

## Final Outcome
Thanks to this infrastructure, CHU now benefits from:
- A high-performance and secure data warehouse
- Clear visualizations to support strategic decision-making
- A unified view of patients at the national level across several years
