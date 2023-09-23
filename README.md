# educonnect-sso-login
Un client capable d'authentifier un utilisateur sur un ent ou même pronote en utilisant Educonnect


# Le module est pour le moment en développement et donc privé.

## Exemple
```javascript
const Educonnect = require("educonnect-sso-client");
const client = new Educonnect()

client.setCredentials("username", "password");

client.findByUAI("UAI").then(response => {

})
```
