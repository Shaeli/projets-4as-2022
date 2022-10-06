# Projet SOC (Security Operation Center)


## Description
### Contexte
Les étudiants de l'option 4AS ont bien travaillés: ils ont mis en place de nombreux systèmes dans la salle. 
Maintenant, il nous faut surveiller et monitorer cette nouvelle infrastructure.

### Description
Dans un premier temps, vous allez créer une solution de monitoring centralisée pour la salle ainsi qu'un système d’alertes.
Cette solution devra agréger les diférentes logs produites par les systèmes de la salle (logs réseaux + logs systèmes serveurs et postes clients), et permettre une recherche / enquete dans les logs en cas d'incidents. Il vous faudra également créer un ensemble d'alertes dans ce système (SIEM).

Dans un second temps, nous aimerions completer le "système de détection d'intrusion" par un NIDS et/ou HIDS dans la salle. 

### Nombre de participants:
* 2 à 3 personnes


---
## Objectifs
- Collecte de logs: 
  - [ ] Logs du réseau de la salle
  - [ ] Logs systèmes des machines de la salle (Serveurs, postes clients, VMs)
  - [ ] Centralisation des logs pour la réponse a incident
- Mise en place d’un set d’alerte sur les logs collectées:
  - [ ] Être capable d’alerter si un certain processus est exécuté 
  - [ ] Root login sur un système
  - [ ] Autres alertes de sécurité que vous jugez interessantes
- [ ] Mise en place d'un HIDS et/ou NIDS

## Objectifs additionels 
_(selon le nombre de personnes dans le projet)_
- [ ] Détection de l’activité du groupe pentest
- [ ] Détection de CVE
- [ ] Alertes envoyées sur le MS teams

## Rendu attendu
- [ ] Rapport 
- [ ] Repository

---
## Mots clés
* SIEM - HIDS / NIDS - SOC
