# keycloak-with-react-theme
react theme in keycloack server

```
docker build -t keycloak-app .
docker run -e KEYCLOAK_ADMIN=admin -e KEYCLOAK_ADMIN_PASSWORD=admin -p 8080:8080 keycloak-app
```