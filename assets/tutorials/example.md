## Track Navigator — Planifica rutas con Waypoints ilimitados

### Explotando el potencial de mi herramienta al 100% juntos con Wikiloc

## Introducción

[youtube:uc123toJ-oA]

En las actividades al aire libre, la preparación marca la diferencia entre una salida improvisada y una experiencia segura y agradable. Ya seas turista, corredor de fondo, ciclista o senderista, **conocer los puntos de interés (POIs)** a lo largo de un recorrido es fundamental para planificar descansos, hidratación o incluso alternativas de ruta.

El problema es que muchas plataformas ponen limitaciones. Por ejemplo, **Wikiloc solo permite añadir hasta 25 Waypoints** por ruta, lo cual resulta insuficiente si quieres marcar fuentes de agua potable, refugios, miradores o cruces de senderos.

La solución es [TrackNavigator](https://track-navigator-beta.netlify.app/#/app):

- Una aplicación web gratuita.

- Sin límite de Waypoints.

- Basada en datos colaborativos de OpenStreetMap.

- Compatible con GPS, apps como Google Earth y servicios de rutas como Wikiloc.

En este artículo te explicaré qué es TrackNavigator, cómo usarlo para enriquecer tus recorridos con Waypoints ilimitados y, como extra, cómo exportar tu trabajo para compartirlo en **Wikiloc**, si quieres dar más visibilidad a tu ruta.

## ¿Qué es TrackNavigator?

**TrackNavigator es una aplicación web que permite cargar archivos GPX y añadir automáticamente Waypoints basados en POIs cercanos a la ruta.**

No necesita instalación: simplemente entras desde tu navegador y empiezas a trabajar.

## Características principales

- **Carga de archivos GPX** → visualiza tu ruta en el mapa en segundos.

- **Filtros personalizados** → selecciona qué POIs quieres ver (fuentes de agua, bares, cumbres, etc.).

- **Radio de proximidad ajustable (hasta 400m)** → añade solo los puntos que realmente están cerca, es decir, la distancia es teniendo en cuenta la distancia en el radio desde cualquier punto de la ruta.

- **Waypoints ilimitados** → añade tantos como necesites, sin restricciones.

- **Exportación en GPX o KML** → tus rutas listas para GPS, apps o servicios externos.

## ¿Por qué TrackNavigator?

Soy **Anartz Mugika Ledo**, creador de TrackNavigator.

La idea nació de una experiencia personal:

> Un día, en el monte, en un lugar que no conocía, eché en falta saber si había una fuente de agua potable cerca. En ese momento pensé: en una situación delicada, con mucho calor, disponer de esa información en la mano puede ser vital, tanto por seguridad como por tranquilidad. Se pueden evitar muchos sustos.

Esa experiencia me hizo ver clara una necesidad: **no existía una herramienta sencilla que mostrara de antemano todos los POIs cercanos a una ruta**.

Esa experiencia me hizo ver clara una necesidad: no existía una herramienta sencilla que mostrara de antemano todos los POIs cercanos a una ruta.

Además, conocía el proyecto [Summitbag](https://summitbag.com/), una aplicación que se conecta con Strava y registra automáticamente los picos de montaña que asciendes, almacenando tu historial de ascensiones. Esto me dio la idea base de lo que quería crear: extraer picos de montaña, fuentes de agua potable… en definitiva, todo lo que pueda ser útil en una salida, tanto por seguridad como por comodidad.

Soy una persona proactiva: cuando detecto un problema real, busco crear una solución. Aunque podría monetizar mis proyectos, mi filosofía ha sido otra: **ofrecerlos gratis**. A veces lo gratuito parece tener menos valor, aunque la calidad sea mejor que alternativas de pago.

Eso si, me gustaría que alguno de mis proyectos pueda aspirar a monetizarlos realmente para tener una compensación al esfuerzo que realmente hago viendo que muchas de estas soluciones son muy útiles respecto a otras premium que no ofrecen apenas nada.

## El proceso de creación

La primera versión funcional de la aplicación salió relativamente rápido, pero el **núcleo de la herramienta** — la librería que conecta con **OpenStreetMap**, hace las consultas y devuelve los POIs según coordenadas — requirió **meses de investigación y muchas pruebas fallidas**. Ese esfuerzo fue clave para que Track Navigator hoy sea estable y práctico.

## OpenStreetMap como base

Antes incluso de este proyecto ya contribuía a **OSM**, sobre todo gestionando información de mi pueblo y alrededores.

Usar datos abiertos tiene mucho sentido: cada vez que alguien añade un POI en OSM, TrackNavigator lo pone al alcance de todos.

👉 Si quieres contribuir al proyecto global, aquí tienes una guía: [Cómo colaborar en OpenStreetMap](https://mugan86.medium.com/open-street-map-contribuir-a%C3%B1adiendo-puntos-de-inter%C3%A9s-pois-desde-0-31b4730795ef)

## La visión a futuro

Mi deseo es que **la gente lo use** y que algunos quieran contribuir con donaciones para mejorar el servicio (por ejemplo, para alojarlo en un hosting profesional).

Quiero que TrackNavigator **se mantenga abierto y accesible**, pero al mismo tiempo me gustaría convertirlo en algo más grande: una herramienta de referencia para planificar rutas con información detallada, útil y segura.

## Cómo usar TrackNavigator paso a paso

> Requisito: es necesario tener un fichero GPX (si no sabes como conseguirlo, [aquí se explica](https://ayuda.wikiloc.com/article/519-descargar-bajar-ruta-rutas-wikiloc-web))

### Entra en [TrackNavigator](https://track-navigator-beta.netlify.app/#/app).

<img src="https://cdn-images-1.medium.com/max/3806/1*VOBp2j0T_UMhzvo6mcm3oQ.png" class="tutorial-img" />

Haz clic en **Importar archivo**.

<img src="https://cdn-images-1.medium.com/max/2000/1*efQlwGJ0R5ciaqJkTDicLw.png" class="tutorial-img" />

**Selecciona un archivo GPX (1)** y verás la **ruta en el mapa (2)** cuando cargue todos los puntos correctamente.

<img src="https://cdn-images-1.medium.com/max/3764/1*0yN9Sa-UtDYifNukfgwWNA.png" class="tutorial-img" />

### Buscar y organizar Waypoints

En el punto 2 del configurador, debes de tener en cuenta estos 3 puntos:

- **Seleccionar perfil del usuario (opcional)**. Esta opción tiene variantes que nos facilita el tipo de Puntos de Interés que queremos buscar para incrustarlo como Waypoint.

<img src="https://cdn-images-1.medium.com/max/2000/1*pVJeUs-F20kkQjCI4RUN4w.png" class="tutorial-img" />

Te invito a que pruebes seleccionando las diferentes variantes y verás como en **“Puntos de Interés”** se va añadiendo / quitando los puntos de interés en base a lo seleccionado.

- **Selección de “Puntos de Interés”**. Aquí hay una lista de un montón de opciones que yo considero importantes, pero por encima de todas destacaría **“Fuentes de agua potable”.**

- **Añadimos el radio de búsqueda**. Esta distancia determina la distancia que habrá máximo en cualquier momento de la ruta. Imagina que ponemos 100m, solo mostrará opciones que no estén más lejos de 100m sea el km 0 o el 20.

### 💡 Ejemplos prácticos

- **Usando un perfil (Cazador de Fuentes de Agua Potable)** (1)

<img src="https://cdn-images-1.medium.com/max/2000/1*LGBN0Uo_F-brDsriFi4WKQ.png" class="tutorial-img" />

No cambiamos el radio en metros cercanos de los Puntos de Interés, dejamos los 150m por defecto y buscamos (2)

Y este es el resultado:

<img src="https://cdn-images-1.medium.com/max/3698/1*XaE466pRd0-zptQmCOE5_w.png" class="tutorial-img" />

- **Corredor de Asfalto**

<img src="https://cdn-images-1.medium.com/max/3738/1*jT9hH-wHPygi4r-NxFs-qg.png" class="tutorial-img" />

## 3. Exportar tu trabajo

Tenemos que tener la ruta cargada y con por lo menos un puntos de interés añadido. Una vez que lo tenemos, tenemos la opción de descarga el archivo:

<img src="https://cdn-images-1.medium.com/max/2000/1*rbXyzxkTcSXdoOkPjOGuPw.png" class="tutorial-img" />

- Pulsa **Descarga fichero con Waypoints**.

- Elige GPX o KML.

![](https://cdn-images-1.medium.com/max/2000/1*jYj9Q6j-uRd5-Ho-HjuqyA.png)

- Guarda el archivo en tu ordenador.

### Descargando en formato GPX

En este caso genera un fichero zip con esta estructura

    .
    ├── waypoints (1)
    │   ├── <nombre-fichero>__waypoints_1_track_navigator.gpx
    │   ├── <nombre-fichero>__waypoints_2_track_navigator.gpx
    │   └── ... # hasta n ficheros
    ├── <nombre-fichero>__track_only_track_navigator.gpx (2)
    └── <nombre-fichero>__track_with_waypoints_track_navigator.gpx (3)

Y el propósito para el que se usará cada uno de ellos es el siguiente:

1.  Los **waypoints en ficheros separados con 25 elementos máximo**, para poder añadirlos en Wikiloc e integrarlos posteriormente, si te interesa tener una ruta de más de 25 Waypoints publicada en Wikiloc. Si hay 45 waypoints tendremos 2 ficheros con el primero añadiendo 25 y el segundo 20.

2.  El **track original, SIN Waypoints**.

3.  El **track original CON Waypoints**, el que usaremos para añadirlo en nuestros dispositivos.

### ¿Cómo añadirlo en nuestro dispositivo?

Os añado las referencias de los relojes más populares, aunque si tenéis algún otro, no debería de haber problemas.

### Coros

 <iframe src="https://medium.com/media/ddaef26e03ba29d7c4ed784c3bb52933" frameborder=0></iframe>

### Garmin

 <iframe src="https://medium.com/media/d24324075eb8a22682cb5c53e1a894f2" frameborder=0></iframe>

### Suntoo

[**¿Cómo importo un archivo .gpx a la app Suunto para Android?**
*For full functionality, please enable Javascript. Suunto mantiene su compromiso de alcanzar el nivel de conformidad AA…*www.suunto.com](https://www.suunto.com/es-es/Asistencia/faq-articles/suunto-app/como-importo-un-archivo-.gpx-a-la-app-suunto-para-android/)

### Resultados visibles en dispositivo

Os muestro a continuación como se visualiza la ruta en un Coros, después de haber añadido una ruta:

![](https://cdn-images-1.medium.com/max/2000/1*HBhxAJGgfecfsFFL5oIN7g.jpeg)

![](https://cdn-images-1.medium.com/max/2000/1*jvDXf2svHQ0nEhw1-OkQTA.jpeg)

![](https://cdn-images-1.medium.com/max/2000/1*FfWVlm55EzUP2XeCV37GUQ.jpeg)

Dependiendo del dispositivo detectará correctamente los símbolos, en el caso del Coros Pace 2 no.

He probado en Wikiloc (aunque solo deja meter 25 Waypoints) y si detecta bien los tipos. Esta es una limitación de Wikiloc, pero si te interesa, en el siguiente apartado os muestro como “hackear” Wikiloc.

### Descargando en formato KML

Este será un fichero con la extensión “**kml**” que usaremos para visualizar en Google Earth.

![](https://cdn-images-1.medium.com/max/3774/1*lz8a875dSN_RlLFQYRkRzA.png)

## Usando tu ruta con Waypoints ilimitados

Lo mejor de TrackNavigator es que el archivo exportado con tus Waypoints **lo puedes usar directamente en tu dispositivo o aplicación favorita **como acabo de mencionar:

- Relojes GPS (Garmin, Suunto, Coros).

- Aplicaciones móviles de navegación.

- Programas de planificación en ordenador.

De esta manera, **disfrutarás de todos los Waypoints**, no de solo 25.

## Extra: Todos los pasos en video

 <iframe src="https://medium.com/media/a17475348f33542465f465dbee8d014b" frameborder=0></iframe>

## Plus: compartir tu ruta en Wikiloc

Si quieres que otras personas disfruten de tu ruta con los waypoints asociados, puedes publicarla en **Wikiloc. Añadiré los pasos a seguir con una ruta de 25 waypoints máximo (la primera parte) y luego con más de 25.**

Estos pasos serán comunes en las dos variantes:

1.  Inicia sesión en tu cuenta.

2.  Pulsa **Subir ruta**.

![](https://cdn-images-1.medium.com/max/3352/1*ssW1-88BWzXCriAeugEEWw.png)

**Con 25 waypoints máximo** (un fichero **“gpx”** dentro de la carpeta “waypoints”)

1.  Selecciona el archivo **GPX/KML** exportado desde **TrackNavigator**.

2.  Completa la información (título, descripción, actividad).

3.  Publica la ruta.

**Con más de 25 waypoints** (mínimo 2 ficheros “gpx” dentro de la carpeta “waypoints”).

Esto es lo que tenemos que tener en cuenta, pero os muestro como hacerlo paso a paso.

Cargamos el fichero original, el que no tiene puntos de interés y se debe de visualizar como aquí **(1)**. Ahora nos queda añadir los puntos de interés **(2).**

![](https://cdn-images-1.medium.com/max/2038/1*G3ifDksGyzR34VHnPoiOPw.png)

Tenemos que subir el fichero, pulsamos **“Sube fichero”**:

![](https://cdn-images-1.medium.com/max/2000/1*4LHgTxGsZtejGOPw85DxuQ.png)

Dentro de la carpeta **“waypoints” (1)**, empezaremos en orden por el que tiene **“…\_1…” (2)**:

![](https://cdn-images-1.medium.com/max/2000/1*hKqxCtq5ojPUPz6EhBn7-A.png)

Al cargar el fichero, aparecerán integrados la ruta (1), los waypoints (2) e incrustados en el mapa (3):

![](https://cdn-images-1.medium.com/max/2106/1*TZSEy1QuXbHczgic6iY2uA.png)

Hacemos scroll hacia abajo y continuamos mediante **“Continúa”:**

![](https://cdn-images-1.medium.com/max/2086/1*HG9t1JqpYxJBGZSoXr-VKw.png)

Al completar el paso de añadir los waypoints, pasamos a la ficha principal donde se rellena el nombre, descripción, tipo de actividad… nada complejo. Rellenamos y seguimos adelante.

![](https://cdn-images-1.medium.com/max/2012/1*bvLejrENQg3BPxdgB1YabQ.png)

Ahora nos dan la opción de cambiar los iconos de los waypoints, si vemos que alguno no cuadra o queremos añadirle alguna foto a algún punto (eso ya es manual, con Track Navigator no se puede) lo hacemos mediante el lápiz y cuando tengamos, seguimos.

![](https://cdn-images-1.medium.com/max/2318/1*qYm9P5XJproPpz0xAfstZg.png)

Saltar el paso para terminar:

![](https://cdn-images-1.medium.com/max/2146/1*9QtvC2dztg70Z_2qv-JHPw.png)

Y este será el resultado con el primer lote de waypoints:

![](https://cdn-images-1.medium.com/max/2000/1*TIGQb5E0phw7A1iGoNv08Q.png)

**Ya tenemos el track con los 25 primeros waypoints añadidos, pero nuestro objetivo es saltarnos esa limitación.**

**Si en nuestro track hay 25 o menos waypoints, enhorabuena, ya has terminado con este apartado, pero si tienes más de 25 estás invitado a seguir ;).**

¿Cómo añadir más waypoints para solventar el problema de la limitación de 25 por ruta?

Hacemos el **mismo proceso, seleccionando la misma ruta original, pero en este caso seleccionamos el fichero de waypoints, el número 2**:

![](https://cdn-images-1.medium.com/max/2000/1*SsCehesy3oCrx4rgCRsURg.png)

Y se mostrará así, como se puede apreciar, el trazado de la ruta es el mismo pero hay diferentes puntos de interés:

![](https://cdn-images-1.medium.com/max/2000/1*bejJPwPdhP__sYmqoAq7ig.png)

Seguir los pasos de configuración, la ficha y demás como creáis conveniente y llegados al final, debemos de tener algo así (no le he cambiado el nombre, tendremos dos rutas iguales pero con diferentes waypoints):

![](https://cdn-images-1.medium.com/max/2000/1*ZR4ZMYd4i5ebTM_NLBGsFA.png)

Ir a **“Tus rutas”:**

![](https://cdn-images-1.medium.com/max/2000/1*vXiSuWyuR3bMoQRHv_XH6g.png)

Ahora en este apartado, como se puede apreciar, tenemos las dos rutas generadas:

![](https://cdn-images-1.medium.com/max/2000/1*H8K_CWal_C3xLa8K93CSwA.png)

En lo que se está marcando, **ese icono refleja que hay elementos “agrupados”**, en este caso la ruta con waypoints.

Se puede apreciar con la ruta cargada en el mapa:

![](https://cdn-images-1.medium.com/max/3312/1*Ifnsy5IupVa0fu3D57OV5Q.png)

**Si no hay elementos agrupados y solo se encuentra la ruta**, aparecerá como esta ruta, fíjate en el icono y después en el mapa, donde solo está trazada la ruta:

![](https://cdn-images-1.medium.com/max/3056/1*K-4pezMyRn5fHxMadNjxoA.png)

Después de explicar esta diferencia, procedo a mostrar como puedes fusionar los waypoints de las dos rutas en una.

**Coger la segunda ruta y poner el cursor sobre ese elemento (1)**. Se muestran varias opciones como **“Desagrupa”**, **“Ver detalles”** y etc.

La **opción que nos interesa** es pulsar **“Desagrupa” (2):**

![](https://cdn-images-1.medium.com/max/2000/1*GCDxHLjm3kTGAyyPu-PneA.png)

Confirmamos que queremos hacer la acción:

![](https://cdn-images-1.medium.com/max/2000/1*-wDvzz_6m3Rv-AS4lNpYew.png)

Y una vez confirmado, se han desagrupado los puntos de interés de la ruta que estaba en segunda posición, ahora estará después de todos los waypoints:

![](https://cdn-images-1.medium.com/max/2000/1*rqDJmzJLmW0Ql-mejxECGQ.png)

Ahora lo que hay que hacer es ir **seleccionando los Puntos de Interés uno por uno haciendo click en el ojo que aparece a la derecha de los Puntos de Interés**.

Antes de nada, tenemos que tener seleccionada la ruta a la que queremos agrupar:

![](https://cdn-images-1.medium.com/max/2000/1*yMtScvETI001uhOHZDDhFw.png)

Si el ojo está del color anaranjado resaltado, quiere decir que estamos seleccionando. Hacerlo con todos los puntos que queramos unir a la ruta principal. Si hay elementos en otras páginas, pasamos a las siguientes sin perder la selección:

![](https://cdn-images-1.medium.com/max/2000/1*vNpa09C3s8uun3-0lw8upQ.png)

Seleccionamos hasta que veamos la ruta que tiene el icono que nos dice que no tiene elementos agrupados, que es el que hemos hecho que suelte los puntos de interés.

Llegados a este punto, bajamos todo hasta encontrar la opción “Agrupa” y pinchamos sobre ella:

![](https://cdn-images-1.medium.com/max/2000/1*r4ddEKJgQvKGlpK7iOBjkA.png)

Nos aparecerá lo siguiente:

![](https://cdn-images-1.medium.com/max/2192/1*sDBLnoJ0vhpW9wKgmUqkag.png)

Seguimos hacia adelante pulsando en **“Añade Grupo”** y al terminar, encontraremos la ruta con más de 25 waypoints (podéis contar en la imagen que hay más de 25):

![](https://cdn-images-1.medium.com/max/3236/1*IS6XzonVB-YCfjuxhSmAmg.png)

Para finalizar, **eliminamos la ruta que no tiene elementos agrupados**, para dejar nuestro directorio limpio.

![](https://cdn-images-1.medium.com/max/2000/1*C2Ti6axBY5pHJV_BHjfkkQ.png)

Quedando de la siguiente forma:

![](https://cdn-images-1.medium.com/max/3292/1*gKc98PT4F_W8F2vUjs34pQ.png)

Puede resultar confuso, que no tiene sentido, pero es la única manera que he encontrado de añadir más de 25 elementos como waypoint en mis rutas. **Recordad que Track Navigator nos facilita el trabajo sucio de tener los puntos de interés de una manera asombrosamente fácil y que lo que es el trabajo a mano es mínimo**.

## Conclusión

Con **TrackNavigator** puedes:
✅ Crear rutas con Waypoints ilimitados.
✅ Ahorrar tiempo al añadir POIs automáticamente.
✅ Planificar aventuras más seguras y completas.
✅ Exportar y usar tu trabajo en cualquier GPS o aplicación.

Y, si lo deseas, puedes dar un paso más:
📤 **Compartir tu ruta en Wikiloc** para que la comunidad disfrute de tu trabajo, con todos los Waypoints incluidos en la descarga.

👉 Empieza ahora: [Accede a TrackNavigator](https://track-navigator-beta.netlify.app/#/app)
