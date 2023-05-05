# Esport // Collective Learning #3
[![Nom de l'image](https://media.discordapp.net/attachments/952632151533289513/1103931287770767381/acs.png?width=2424&height=808)](https://youtube.com)


Cet atelier sera axé sur le calcul de **l'ACS** dans les jeux de tirs appliqué à l'exemple de Valorant. L'ACS est une stat importante puisqu'elle juge de la qualité d'un joueur notamment pendant le matchmaking et le gain d'elo pour gravir les échelons sur le FPS de Riot Games.


## Prérequis
+ Jupyter Notebook
+ Python 3

## Étapes
###  I. Configuration
+ Installation des paquets nécessaires (requests, pandas)
+ Création d'un compte et obtention d'une clé API
### II. Premier appel API
+ Effectuer une requête GET pour récupérer l'ID de compte d'un joueur
+ Analyse de la réponse JSON pour extraire les informations nécessaires
+ Utilisation de l'ID de compte pour effectuer une autre requête GET afin de récupérer l'historique des parties
### III. Récupération de données plus complexes
+ Analyse de la réponse JSON pour extraire les ID de partie et les champions joués
+ Effectuer plusieurs requêtes GET pour récupérer les détails de la partie et le KDA correspondant
+ Stocker les données récupérées dans un dataframe pandas
### IV. Considérations supplémentaires
+ Gérer les limites de taux et les restrictions de l'API
+ Gérer les erreurs pour les requêtes API qui ont échoué

Cet atelier est conçu pour donner aux participants une compréhension de base de l'utilisation d'API dans le contexte de l'esport. À la fin de l'atelier, les participants devraient être capables d'effectuer des appels API, d'analyser les réponses JSON, et de récupérer et stocker des données dans un dataframe pandas.