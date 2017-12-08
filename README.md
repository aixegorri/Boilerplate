# Boilerplate Aixegorri

## ¿Qué es?
Starter kit para empezar un proyecto nuevo. En construcción

## Contenido
CSS basado en [@Wakkos](https://github.com/Wakkos/Wakkos-CSS-Framework), que está basado en Sass con un claro enfoque a Mobile First. En cuanto a las librerías Javascript, incluyo modernizr y jQuery, pero sólo se utilizaran si el proyecto lo requiere.

## NPM tasks
### Desplegar un servidor web de desarrollo
```
$ npm run nombre_tarea
```
Lanza un servidor web con browserSync para trabajar en tu proyecto. Los archivos SCSS y JS estarán siendo escuchados para ser automáticamente compilados y recargar los navegadores conectados cuando se requiera.

### Procesar una distribución lista para producción
```
$ npm run nombre_tarea
```
Elimina y reprocesa la carpeta dist con una version optimizada de tus archivos HTML/CSS/JS.

### Comprimir una distribución para producción
```
$ npm run nombre_tarea
```
Elimina y reprocesa la carpeta dist con una version optimizada de tus archivos HTML/CSS/JS y la comprime en un archivo .zip

## Estructura del sitio
El **package.json** utiliza una configuración de archivo JSON para ajustar las rutas de la fuente y el destino de los archivos del proyecto.

Comprueba el config.json y edítalo con lo necesario.

Estructura de carpetas:
```
/
|- src
|   |- css
|   |- fonts
|   |- img
|   |   |- svg
|   |   `- touch
|   |- js
|   |   `- vendor
|   |- scss
|   |   |- components
|   |   |- core
|   |   `- layout
|   `- pug
|      |- layout
|      `- partials|
`- dist
   `- assets
       |- css
       |- img
       |   `- layout
       `- js
           `- vendor
```

## TODO
- [ ] Personalizar HTML
- [ ] Crear rutas en config.json
- [ ] Crear tarea de distribución a producción
- [ ] Crear tarea de distribución comprimida en ZIP a producción
- [ ] Añadir soporte a PUG
- [ ] Añadir CSS Linters
- [ ] Añadir JS Linters
