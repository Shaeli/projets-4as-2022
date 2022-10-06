# Projet SSH via certificats


## Description
### Contexte
Les administrateurs systèmes de la 4AS sont à bout de souffle ! Ils n'en peuvent plus de copier les clés de chaque membre de la 4AS sur chacune des machines virtuelles, et chacun des serveurs.
En plus, les étudiants ne sont pas disciplinés et perdent régulièrement leur clé !!

Ils ont essayés d'automatiser le processus avec Ansible, mais ce n'est pas suffisant : les étudiants sont tellement productifs qu'ils ont créés des centaines de VMs: Impossible de s'y retrouver, et de savoir quel groupe doit avoir accés à quelle machine ...

Après pas mal de recherches, ils ont entendu dire qu'en entreprise on résoud ce problème en utilisant une **PKI et des certificats** pour gérer le SSH.

### Description
Il vous faut aider les administrateurs de la 4AS. 
Ils ont fait quelques recherches pour vous, et vous demande d'utiliser **Hashicorp Vault** pour gérer les certificats ainsi que le SSH.
Idéalement, à la fin de votre projet:
- Un utilisateur peut perdre sa clé SSH et ça n'aura pas d'influence sur l'infrastructure de la 4AS.
- Pour ajouter un nouvel utilisateur, les utilisateurs n'auront plus à changer de configuration sur les machines / VMs.
Egalement, n'oubliez pas qu'il faudra expliquer aux administrateurs systèmes en quoi des certificats vont régler leurs problèmes, pour le moment ils pensent que les certificats s'utilisent seulement avec le HTTPS.


### Nombre de participants:
* 3 à 5 personnes


---
## Objectifs
- [ ] Compréhension de la PKI / CA / SSH via certificats
- [ ] Prise en main de HashiCorp Vault
- [ ] Mise en place de Role based access control pour les utilisateurs (e.g. Role `project_k8s_admin` donne acces aux VMs / serveurs du groupe k8s)
- [ ] Authentification mutuelle (serveurs et clients)

## Objectifs additionels 
_(selon le nombre de personnes dans le projet)_
- [ ] (Recommandé) Automatisation de la solution avec terraform 
- [ ] Remplacement des users par la fédération du projet IAM / Identity

## Rendu attendu
- [ ] Rapport 
- [ ] Repository

---
## Mots clés
* PKI - Certificate Authority - Hashicorp Vault - SSH - Certificats X509
