# Projet "Compliance as code"

## Description
### Contexte

Les étudiants de la 4AS réalisent plein de projets (la plupart du temps, la nuit avant le jour de rendu) et n'ont donc pas le temps de vérifier la securité de leur code/configuration.
De plus, en 2022, même l'infrastructure est definie en code.

Ils ont donc besoin que vous leur fabriquiez un outil qui automatise le scan de leur code ( code != software, ici on parle également de configuration et d'infrastructure).

### Objectif
Lancez votre projet dans nimporte quel repository git et un rapport de la sécurité du repository est generé.

### Description
### Nombre de participants:
* 2 à 5 personnes

---
## Objectifs
- [ ] Etre capable de scanner pour les problèmes de sécurité suivants:
    - [ ] Secrets dans le code (Cela vous evitera d'exposer vos mots de passe Redis, AWS et clés SSH comme Twitch.)
    - [ ] Problèmes de sécurité lié à l'infrastructure mal congigurée 
    - [ ] Dependences vulnérables (detections de CVEs)
    - [ ] Images docker vulnérables 

## Objectifs additionels 
_(selon le nombre de personnes dans le projet)_
- [ ] SAST (Static application security testing) par ex: bufferoverflow.

Appuyez vous sur des outils existants.

## Rendu attendu
- [ ] Rapport 
- [ ] Repository


