# Micro de root

Aplicacion principal - donde se unen todos los micros

## En uso local : 
Cuando se se usa este micro de manera local se debe comentar la linea de **produccion** y descomentar la linea **local** dentro de `src/index.ejs`

![image](https://github.com/joyitoficial/ats-rctl-cn-ufrontend-root/assets/98372209/88bcc1de-3a1b-4cf1-99b2-8d337052fd6c)

La linea 21 se debe descomentar y la linea 24 comentarla

## Dependecias usadas :

- React
- SingleSpa - root

## Para levantar el microfrontend sigue estos pasos:

1. Clona el repositorio
2. Instala las dependencias ejecutando:

```bash
pnpm i
```

3. Luego, ejecuta el microfrontend de una de las siguientes maneras:

- Para accederlo desde el root (asegúrate de que el root esté levantado):

```bash
pnpm start
```

- Para ejecutarlo de manera independiente (standalone), sin necesidad de tener otros microfrontends levantados:

```bash
pnpm start:standalone
```
