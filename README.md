\# Mini-projet IAM 1 : Portail SSO adossé à un annuaire



OpenLDAP + Keycloak + Portail RH (SAML 2.0) + Portail Notes (OIDC), le tout en Docker.



\## Lancer

docker compose up -d --build



\## Contenu

\- docker-compose.yml : LDAP, Keycloak, 3 applications

\- ldif/ : annuaire (utilisateurs et groupes)

\- apps/ : applications du TP4 (source : cours Gestion des Accès-Identités), avec contrôle du groupe rh ajouté dans sp\_saml.py

\- docs/ : compte rendu



Les mots de passe du dépôt sont des mots de passe de TP, à ne jamais réutiliser.

