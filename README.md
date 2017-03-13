# React Bootcamp 2017 - Spotify Client

## Introducción

Como usuario, quiero poder buscar un artista en spotify y ver sus álbumes y canciones. Además, quiero poder marcar mis canciones favoritas. (opcional)

## Objetivos

1. Crear una aplicación web que pueda ser accedida desde un teléfono y desde una máquina desktop.

2. Obtener los resultados que coincidan con el texto ingresado, usando la API de búsqueda de spotify.

3. Poder marcar mis canciones favoritas y que al refrescar el navegador, sigan apareciendo como favoritas. (opcional)

## Requisitos Funcionales

### Necesarios

1. Como usuario, quiero poder buscar un artista en un formulario y ver el resultado de esa búsqueda.

2. Como usuario, quiero poder seleccionar entre los artistas que aparecieron en el resultado y luego ver un listado de sus álbumes.

3. Como usuario, quiero poder clickear en uno de sus álbumes y ver el nombre del álbum, una foto del álbum y el listado de canciones.

4. Como usuario quiero poder realizar una nueva búsqueda desde cualquier punto de mi aplicación.

5. Como usuario debo poder regresar a la página principal de mi aplicación en cualquier punto del flow.

6. Como usuario quiero poder escuchar un fragmento de cada tema.

### Opcionales

7. Como usuario quiero poder ordenar el listado de temas por duración de los mismos.

8. Como usuario, quiero poder refrescar la página con los resultados de mi búsqueda o el listado de álbumes o el listado de canciones, y quiero que se mantenga el estado.

9. Como usuario, quiero poder marcar una canción como favorita y al refrescar el navegador, quiero seguir viendo cómo favoritas las mismas canciones.

10. Las canciones marcadas como favoritas deben aparecer en una sección en la página principal.

## Spotify API

* Base url: [https://api.spotify.com/v1/](https://api.spotify.com/v1/)

* Lista de endpoints: [https://developer.spotify.com/web-api/endpoint-reference/](https://developer.spotify.com/web-api/endpoint-reference/)

### Ejemplo

Traer los datos de un álbum en base al id del album:

GET [https://api.spotify.com/v1/albums/10GYbpGRnCbUd5WsDzqHAv](https://api.spotify.com/v1/albums/10GYbpGRnCbUd5WsDzqHAv)

## Mockups

### Desktop

#### Home

![Mockup 1](http://i349.photobucket.com/albums/q377/matias-calvo/mockup-1_zpsf2so8ccw.png)

#### Artists List

![Mockup 2](http://i349.photobucket.com/albums/q377/matias-calvo/mockup-2_zpsepw7kpyd.png)

#### Artist

![Mockup 3](http://i349.photobucket.com/albums/q377/matias-calvo/mockup-3_zpsbnaiq6cd.png)

#### Album

![Mockup 4](http://i349.photobucket.com/albums/q377/matias-calvo/mockup-4_zpsauf8hfwi.png)

### Mobile

#### Home

![Mockup 5](http://i349.photobucket.com/albums/q377/matias-calvo/mockup-5_zpsddoyk015.png)

#### Artists List

![Mockup 6](http://i349.photobucket.com/albums/q377/matias-calvo/mockup-6_zpsb4hv5jk3.png)

#### Artist

![Mockup 7](http://i349.photobucket.com/albums/q377/matias-calvo/mockup-7_zpsvxbbgd0q.png)

#### Album

![Mockup 8](http://i349.photobucket.com/albums/q377/matias-calvo/mockup-8_zpswghdison.png)

#### Search Bar

![Mockup 9](http://i349.photobucket.com/albums/q377/matias-calvo/mockup-9_zpsr22acxpt.png)

## Links útiles:

* [Create React App](https://github.com/facebookincubator/create-react-app)

* [React Router - Docs](https://reacttraining.com/react-router/)

* [Egghead - Curso Básico de React](https://egghead.io/courses/react-fundamentals)

* [React LocalStorage](https://github.com/STRML/react-localstorage)

* [Presentational and Container Components](https://medium.com/@dan_abramov/smart-and-dumb-components-7ca2f9a7c7d0#.czw7rr9kf)