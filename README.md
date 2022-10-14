# [Keycloak custom login theme](https://github.com/fhswf/keycloak_custom_theme)

This repository provides a custom keycloak theme for the login page.

## How to use

Mount volume to keycloak and select the login theme in the admin panel.

JBoss mount:
> ./themes/fhswf:/opt/jboss/keycloak/themes/fhswf

Quay.io mount:
> ./themes/fhswf:/opt/keycloak/themes/fhswf