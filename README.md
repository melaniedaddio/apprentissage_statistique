# COVID-19 Asia Analysis

## 📌 **Description du projet**  
Ce projet vise à analyser les données COVID-19 dans les pays asiatiques afin d'identifier les facteurs ayant influencé la propagation du virus, évaluer l'efficacité des mesures sanitaires et repérer les pays nécessitant un soutien extérieur.

---

## 📊 **Jeu de données**  
Les données proviennent du site [Worldometer](https://www.worldometers.info/coronavirus/), qui compile des statistiques en temps réel sur la pandémie.  
Le jeu contient des informations telles que :
- Nombre de cas, décès et guérisons
- Nombre de tests
- Statistiques rapportées à la population (par million)
- Taille de la population

---

## 📌 **Description des variables principales**

| 🏷️ Nom               | 📝 Description                                         |
|----------------------|--------------------------------------------------------|
| ID                   | Identifiant unique                                     |
| Country              | Pays asiatique                                          |
| TotalCases           | Nombre total de cas COVID-19                           |
| TotalDeaths          | Nombre total de décès COVID-19                         |
| TotalRecovered       | Nombre de personnes guéries                            |
| ActiveCases          | Cas actuellement actifs                                |
| TotalCasesPerMillion | Cas COVID-19 par million d'habitants                    |
| TotalDeathsPerMillion| Décès COVID-19 par million d'habitants                  |
| TotalTests           | Nombre total de tests réalisés                         |
| TotalTestsPerMillion | Nombre de tests par million d'habitants                 |
| TotalPopulation      | Population totale du pays                              |

---

## 🎯 **Objectifs du projet**
- 🔍 Analyser les variables influentes sur la gravité de la pandémie
- 🔄 Effectuer un pré-traitement adapté (gestion des valeurs manquantes, standardisation)
- 📈 Étudier la mortalité et la récupération via des taux spécifiques
- 🧠 Réaliser une **Analyse en Composantes Principales (ACP)** pour mieux segmenter les pays selon leur situation sanitaire
- 📊 Visualiser les pays nécessitant une attention immédiate
- 🛠️ Interpréter les résultats pour fournir des recommandations claires


