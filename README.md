## Inicialización de la base de datos

Para inicializar la conexión con Firebase desde el backend, asegúrate de tener el archivo de credenciales `serviceAccountKey.json` proporcionado por Firebase.

Luego, usa el siguiente código en tu proyecto (por ejemplo, en `firebase.js`):

```javascript
var admin = require("firebase-admin");

var serviceAccount = require("path/to/serviceAccountKey.json");

admin.initializeApp({
  credential: admin.credential.cert(serviceAccount)
});
