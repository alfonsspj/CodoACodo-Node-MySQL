

### Instrucciones

1. Ejecutar 
```
npm i
```
para reconstruir los modulos de node.

2. Renombrar el archivo `.env.template` a `.env` e ingresar los datos que se requieren.
   
3. Para levantar el proyecto ejecute: 
```
npm run dev
```
- Se definio en el `package.json` el siguiente script:
```javascript
"scripts": {
    "dev": "node --watch --env-file .env index.js"
},
``` 
