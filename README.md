
# Analyse du trafic maritime des ports français – Projet Data Visualisation

## Présentation du projet

Ce projet consiste à analyser et visualiser le trafic maritime des ports français à partir d'un jeu de données Open Data.

L'objectif est d'exploiter les données relatives aux mouvements portuaires, aux tonnages transportés et aux catégories de marchandises afin de mettre en évidence les principales tendances du trafic maritime.

Le projet couvre les différentes étapes d'une démarche Data Analyst : préparation des données, stockage dans une base MySQL, analyse et conception de tableaux de bord interactifs avec Power BI.

## Objectifs de l'analyse

- Étudier la répartition du trafic maritime entre les ports français.
- Comparer les volumes de tonnage selon les régions et les façades maritimes.
- Analyser les mouvements d'entrées et de sorties.
- Mesurer l'évolution annuelle du tonnage.
- Identifier les périodes de croissance et de baisse.
- Étudier la répartition des marchandises par catégorie.
- Comparer l'activité des ports selon leur statut juridique.

## Environnement technique

| Outil | Utilisation |
|---|---|
| MySQL | Stockage des données |
| Navicat | Administration et manipulation de la base |
| Power BI | Analyse et visualisation des données |
| Power Query | Préparation et transformation des données |
| DAX | Création des indicateurs et mesures analytiques |

## Données utilisées

La source est un jeu de données portant sur le trafic des ports français, au format CSV.

La table principale utilisée est `trafic_ports`.

Elle contient notamment les informations suivantes :

- `LOCODE_PORT` : identifiant international du port.
- `PORT` : nom du port.
- `FACADE` : façade maritime.
- `REGION` : région.
- `STATUT` : statut juridique du port.
- `MOUV` : type de mouvement portuaire.
- `ANNEE` : année de référence.
- `TONNAGE_TOT` : tonnage total.
- `MAR_TOT` : tonnage des marchandises.
- `TARE_TOT` : poids de tare.
- `VRACS_LIQUIDES` : vracs liquides.
- `VRACS_SOLIDES` : vracs solides.
- `CONT_TOT` : trafic de conteneurs.
- `RORO_TOT` : trafic roulier.
- `EVP_TOT` : nombre d'équivalents vingt pieds.

**Volume de données :** 1 540 lignes importées dans MySQL.

## Démarche du projet

### 1. Préparation et intégration des données
- Importation du fichier CSV.
- Vérification de la structure et des colonnes.
- Contrôle des valeurs manquantes.
- Préparation des données pour leur exploitation.

### 2. Stockage dans MySQL
- Création de la base `transport_maritme_db`.
- Importation des données dans la table `trafic_ports`.
- Vérification de la cohérence des données.

### 3. Analyse et visualisation avec Power BI
- Connexion à la base de données.
- Création des mesures analytiques avec DAX.
- Conception de visualisations interactives.
- Mise en place de filtres permettant d'explorer les données par année, port et catégorie.

## Tableaux de bord

Les analyses sont organisées autour de plusieurs axes :

1. **Vue générale du trafic maritime** : indicateurs clés et répartition du tonnage.
2. <img width="472" height="314" alt="image" src="https://github.com/user-attachments/assets/c6013e84-353a-4d9f-9327-b9c4928f9f26" />

3. **Analyse géographique** : comparaison des ports, régions et façades maritimes.
4. <img width="466" height="296" alt="image" src="https://github.com/user-attachments/assets/a0b470c0-d22c-4760-93bb-ca96f238319e" />

5. **Évolution du trafic** : évolution annuelle, comparaison des entrées et sorties, variations en pourcentage.
6. <img width="429" height="280" alt="image" src="https://github.com/user-attachments/assets/d9be6784-f154-4b3e-a333-5d07f5de3d39" />

7. **Nature des marchandises** : analyse des vracs liquides, vracs solides, conteneurs et trafic roulier.

## Indicateurs clés

- Tonnage total.
- Nombre de ports.
- Nombre de régions.
- Tonnage par statut juridique.
- Tonnage par façade maritime.
- Évolution annuelle du tonnage en pourcentage.
- Variation annuelle maximale et minimale.

## Résultats et enseignements

Cette section sera complétée à partir des résultats observés dans les tableaux de bord Power BI :

- Principaux ports en matière de tonnage.
- Régions et façades maritimes les plus actives.
- Évolution du trafic au fil des années.
- Répartition des mouvements entrants et sortants.
- Catégories de marchandises les plus représentées.

## Compétences mobilisées

- Analyse exploratoire de données (EDA).
- Nettoyage et préparation de données.
- SQL et gestion de bases de données relationnelles.
- Power Query et langage DAX.
- Data Visualisation et conception de dashboards.
- Analyse et interprétation des indicateurs.

---

**Projet personnel – Data Analytics & Business Intelligence**

*Technologies : MySQL | Navicat | Power BI | Power Query | DAX*
