## Start keycloack docker
```
docker-compose up
```
## Attention!!!
- the application will run on localhost: "http://yourip:8080". Example: "http://192.168.12.34:8080/"

## Realm
- Conjunto de configuracões para autenticacão de aplicacões
- Realm master gerencia os outros realms
- Evitar utilizacão do master para tarefas corriqueiras

## Back-end and Front-end Authentication
 - Open Id Connect:
    OAuth2 - Padrão de autorizacão
        + resource owner: Usuário que solicita acesso "João"
        + client: Aplicacão que solicitou autenticacão
        + resource server: Servidor de autenticacão
        + authorization server:  Servidor de autenticacão
    - Login

 - SAML2: auth server, xml
 - Conectar Azure, Google Cloud, LDAP


## OAuth2
    1 - create a client