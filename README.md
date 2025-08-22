## SHOP-APP
### Aplicación móvil híbrida construida con Ionic + React que permite visualizar productos, añadirlos al carrito de compras y registrar pedidos en una base de datos en la nube mediante Firebase Firestore.
1. Clonar el repositorio
   ```
   git clone https://github.com/usuario/shop-app.git
   cd shop-app
2. Instalar dependencias
   ```
   npm install
3. Configurar la base de datos con las credenciales de tu base de datos en firebase
```javascript
export const firebaseConfig = {
  apiKey: "TU_API_KEY",
  authDomain: "TU_DOMINIO.firebaseapp.com",
  projectId: "TU_PROJECT_ID",
  storageBucket: "TU_PROJECT_ID.appspot.com",
  messagingSenderId: "ID_MENSAJERIA",
  appId: "TU_APP_ID"
};
```
4. Ejecutar en Android/IOS
```
ionic capacitor run android

ionic capacitor run ios
