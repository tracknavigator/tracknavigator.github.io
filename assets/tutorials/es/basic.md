# Introducción a Track Navigator para aprender lo indispensable

En este tutorial descubrirás las bases necesarias para empezar a utilizar **Track Navigator** de manera sencilla. Aprenderás cómo funciona la herramienta, qué utilidades principales ofrece y cómo dar los primeros pasos para generar rutas y puntos de interés (POIs). Este tutorial es ideal para familiarizarse con la aplicación antes de pasar a funciones más avanzadas.

Si no quieres leer y prefieres ver como se hace en video [te invito a que accedas a este enlace](/tutorials/basic-in-video)

---

En las actividades al aire libre, la preparación marca la diferencia entre una salida improvisada y una experiencia segura y agradable. Ya seas turista, corredor de fondo, ciclista o senderista, **conocer los puntos de interés (POIs)** a lo largo de un recorrido es fundamental para planificar descansos, hidratación o incluso alternativas de ruta.

El problema es que muchas plataformas ponen limitaciones. Por ejemplo, **Wikiloc solo permite añadir hasta 25 Waypoints** por ruta, lo cual resulta insuficiente si quieres marcar fuentes de agua potable, refugios, miradores o cruces de senderos.

La solución es [TrackNavigator](/app):

- Una aplicación web **gratuita**.
- **Sin límite** de Waypoints.
- Basada en datos colaborativos de **OpenStreetMap**.
- Compatible con GPS, apps como Google Earth y servicios de rutas como Wikiloc (con limitaciones que os enseño "a saltarlas" [aquí](/tutorials/wikiloc)).

En este tutorial te explicaré qué es TrackNavigator, cómo usarlo para enriquecer tus recorridos con Waypoints ilimitados y como descargarlo en nuestro equipo antes de empezar a utilizarlo en nuestros dispositivos o en aplicaciones como Google Earth.

## ¿Qué es TrackNavigator?

**TrackNavigator es una aplicación web que permite cargar archivos GPX y añadir automáticamente Waypoints basados en POIs cercanos a la ruta.**

**No necesita instalación**: simplemente entras desde tu navegador y empiezas a trabajar.

## Características principales

- **Carga de archivos GPX** → visualiza tu ruta en el mapa en segundos.
- **Filtros personalizados** → selecciona qué POIs quieres ver (fuentes de agua, bares, cumbres, etc.).
- **Radio de proximidad ajustable (hasta 400m)** → añade solo los puntos que realmente están cerca, es decir, **la distancia es teniendo en cuenta la distancia en el radio desde cualquier punto de la ruta**.
- **Waypoints ilimitados** → añade tantos como necesites, sin restricciones.
- **Exportación en GPX o KML** → tus rutas listas para GPS, apps o servicios externos.

## Cómo usar TrackNavigator paso a paso

> Requisito: es necesario tener un fichero GPX (si no sabes como conseguirlo, <a href="https://ayuda.wikiloc.com/article/519-descargar-bajar-ruta-rutas-wikiloc-web" target="_blank" rel="noopener">aquí se explica</a>

### Entra en [TrackNavigator](/app)

Debe de aparecer una ventana similar a la que puedes ver a continuación. Con el tiempo quizás la apariencia puede cambiar en lo estético pero en lo que es la funcionalidad, seguirá funcionando igual.

<img src="https://cdn-images-1.medium.com/max/3806/1*VOBp2j0T_UMhzvo6mcm3oQ.png" class="tutorial-img" />

Haz clic en **Cargar Fichero GPX** / Arrastrar el fichero:

<img src="https://cdn-images-1.medium.com/max/2000/1*efQlwGJ0R5ciaqJkTDicLw.png" class="tutorial-img" />

**Selecciona un archivo GPX (1)** y verás la **ruta en el mapa (2)** cuando cargue todos los puntos correctamente.

<img src="https://cdn-images-1.medium.com/max/3764/1*0yN9Sa-UtDYifNukfgwWNA.png" class="tutorial-img" />

### Buscar y organizar Waypoints

En el punto 2 del configurador, debes de tener en cuenta estos 3 puntos:

- **Seleccionar perfil del usuario (opcional)**. Esta opción tiene variantes que nos facilita el tipo de Puntos de Interés que queremos buscar para incrustarlo como Waypoint.

<img src="https://cdn-images-1.medium.com/max/2000/1*pVJeUs-F20kkQjCI4RUN4w.png" class="tutorial-img" />

Te invito a que pruebes seleccionando las diferentes variantes y verás como en **“Puntos de Interés”** se va añadiendo / quitando los puntos de interés en base a lo seleccionado.

- **Selección de “Puntos de Interés”**. Aquí hay una lista de un montón de opciones que yo considero importantes, pero por encima de todas destacaría **“Fuentes de agua potable”.**

- **Añadimos el radio de búsqueda**. Esta distancia determina la distancia que habrá máximo en cualquier momento de la ruta. Imagina que ponemos 100m, solo mostrará opciones que no estén más lejos de 100m sea el km 0 o el 20. Por defecto estará configurado en 150m con el mínimo de 50m y máximo de 400m.

### 💡 Ejemplos prácticos

- **Usando un perfil (Cazador de Fuentes de Agua Potable)** (1)

<img src="https://cdn-images-1.medium.com/max/2000/1*LGBN0Uo_F-brDsriFi4WKQ.png" class="tutorial-img" />

No cambiamos el radio en metros cercanos de los Puntos de Interés, dejamos los 150m por defecto y buscamos (2)

Y este es el resultado:

<img src="https://cdn-images-1.medium.com/max/3698/1*XaE466pRd0-zptQmCOE5_w.png" class="tutorial-img" />

- **Corredor de Asfalto**

<img src="https://cdn-images-1.medium.com/max/3738/1*jT9hH-wHPygi4r-NxFs-qg.png" class="tutorial-img" />

## 3. Exportar tu trabajo

**Tenemos que tener la ruta cargada y con por lo menos un puntos de interés añadido**. Una vez que lo tenemos, tenemos la opción de descarga el archivo:

<img src="https://cdn-images-1.medium.com/max/2000/1*rbXyzxkTcSXdoOkPjOGuPw.png" class="tutorial-img" />

- Pulsa **Descarga fichero con Waypoints**.
- Elige GPX o KML.

<img src="https://cdn-images-1.medium.com/max/2000/1*jYj9Q6j-uRd5-Ho-HjuqyA.png" class="tutorial-img" />

- Guarda el archivo en tu ordenador.

### Descargando en formato GPX

En este caso genera un fichero zip con esta estructura

```bash
.
├── waypoints (1)
│   ├── <nombre-fichero>__waypoints_1_track_navigator.gpx
│   ├── <nombre-fichero>__waypoints_2_track_navigator.gpx
│   └── ... # hasta n ficheros
├── <nombre-fichero>__track_only_track_navigator.gpx (2)
└── <nombre-fichero>__track_with_waypoints_track_navigator.gpx (3)
```

Y el propósito para el que se usará cada uno de ellos es el siguiente:

1. Los **waypoints en ficheros separados con 25 elementos máximo**, para poder añadirlos en Wikiloc e integrarlos posteriormente, si te interesa tener una ruta de más de 25 Waypoints publicada en Wikiloc. Si hay 45 waypoints tendremos 2 ficheros con el primero añadiendo 25 y el segundo 20. ¿Cómo puedes hacerlo? Te lo explico de manera sencilla [aquí](/tutorials/wikiloc)

2. El **track original, SIN Waypoints**.

3. El **track original CON Waypoints**, el que usaremos para añadirlo en nuestros dispositivos, sin limitaciones de 25 Puntos de Interés (POIs) como en Wikiloc. Esta será la opción que usaremos para aprovechar del potencial de la herramienta
    * [Cargar en dispositivos](/tutorials/devices)
    * [Descargar en KML y usarlo en Google Earth](/tutorials/kml)

### Extra: Todos los pasos en video

Si no te gusta seguir las instrucciones por escrito y si mediante tutoriales, te invito a hacerlo desde [aquí](/tutorials/basic-in-video)
