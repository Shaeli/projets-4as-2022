# Projet Identity / SSO

## Description
### Contexte
Single Sign-On, un outil que nous utilisons tous les jours ! En meme temps, c'est bien pratique de n'avoir à se connecter qu'une seule fois. 
Mais, savez vous vraiment ce qui se cache derrière cette technologie ? 0Auth ? OIDC, SAML ? 


### Description
Dans ce projet, vous allez créer une fédération d’identité, un Single Sign-On pour l’option 4AS. 
Ce projet doit devenir la "source of truth" pour tous les composants de la 4AS. Il vous faudra donc collaborer avec les autres projets pour intégrer leur authentification et autorisation avec le SSO.

Profitez en pour améliorer la sécurité des services de la salle en imposant une authentification à 2 facteurs.

### Outil recommandé
- Keycloak

### Nombre de participants:
* 2 à 4 personnes


---
## Objectifs
- [ ] Démontrer une compréhension des systèmes d’authentification modernes (SSO / SAML / OIDC / TOTP / U2F)
- [ ] Fournir un SSO, compatible avec un maximum d'outils de la 4AS. Vos utilisateurs se connectent une fois via le SSO, et n'ont plus besoin de se re-connecter pour chaque service de la 4AS.
- Intégration obligatoire:
  - [ ] [Hashicorp Vault (Projet Certificate Authority / SSH)](./04-ca_ssh.md)
  - [ ] [SIEM (Projet IDS)](./09-SOC.md)
  - [ ] [Wiki (Projet Kubernetes)](./03-kubernetes.md)
  - [ ] Wifi de la salle
- [ ] 2FA obligatoire pour tous les utilisateurs de la 4AS.



## Objectifs additionels 
_(selon le nombre de personnes dans le projet)_
- [ ] SSO pour kubernetes / OIDC
- [ ] Création d'un bridge Kerberos
- [ ] Configuration de Keycloak as code, permettant aux autres équipes de créer une Pull/Merge request pour s'intégrer avec votre service.

## Rendu attendu
- [ ] Rapport 
- [ ] Repository

---
## Mots clés
* Single Sign-on - OIDC - SAML - TOTP - U2F/FIDO

