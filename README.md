# `Weather-app`
---

### `Descripción`
- Weather-app es una sigle-page-aplication que mustra el clima de tu ubicación.
---

### `Tecnologías`
- HTML
- CSS
- JavaScript
- React
- NodeJS
---

### `scripts`
1. start : start arranca el proyecto con un servidor local en desarrollo.
2. build : build crea el compilado de producción.
3. predeploy: ejecuta "npm run build". Por ser un 'pre' se ejecutará por defecto cuando sea ejecutado 'deploy'
4. deploy: ejecuta "gh-pages -d build" para mandar el compilado a producción.
---

### `URL`
- [Weather-app](https://thhomasgt99.github.io/weather-app/)

#### *Nota: gh-pages necesita la confiuración del packcage.json "homepage" para montar la ruta de github-pages.*
#### *Nota: Para que se vean los cambios en github-pages debemos siempre ejecutar 'npm run build', 'npm run deploy' y mandar los cambios normalmente a github, esto para crear el compilado en local y luego que en github posicione los archivos en la rama con el nombre gh-pages.*
##### *Nota: Se puedo solo correr el comando 'deploy' y por defecto se ejecutara el 'predeploy' que es otro comando creado  para que ejecute los comandos necesarios antes del deploy*
