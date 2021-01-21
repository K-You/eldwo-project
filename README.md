# Eldwo project
Specs repo for the project

## Contexte

Build une app fullstack


## Description

Creer un "wow armory" en premier lieu 

User se log, accede aux infos publiques si il le souhaite.
Peut choisir un serveur et entrer un nom de perso pour voir des infos plus precises
peut se logger avec blibli pour avoir les infos de son compte.


## Components

- [eldwo-project-front](https://github.com/K-You/eldwo-project-front) : web frontend
- [eldwo-project-back](https://github.com/K-You/eldwo-project-back)  : backend API


## Architecture
 
                            ((BattleNet API))
                           /       |    
                          /      [Job]
                         /         |
    ReactJs -> [GQL][NodeJs] -> (MongoDB)  | Confs, infos Wow
                             -> (Postgres) | User 

## Plan de developpement

1) Api Node + GQL serveur + https
2) K8s 
3) MongoDB + confs
4) Requests BattleNet + insertion de data dans Mongo
5) Frontend (ReactJs / VueJs (?)) + https --> MVP
6) Postgres + User info
7) Authentication users
8) Auto deploy des confs / versionning et CI clean



