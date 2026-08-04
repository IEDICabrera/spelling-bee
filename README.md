# Spelling Bee World Cup 2026 — Guía de publicación

Esta carpeta ya está lista para subir a GitHub. No necesitas usar la terminal
ni instalar nada — todo se puede hacer arrastrando archivos desde el navegador.

## Contenido de esta carpeta

```
index.html                  ← el juego (v2.2)
manifest.json                ← hace que el juego se pueda "instalar"
service-worker.js            ← permite que funcione sin internet
icons/
  icon-192.png
  icon-512.png
imagenes/                    ← aquí van tus 130 imágenes (01.jpg ... 130.jpg)
audios/                      ← aquí van tus 390 audios (01.mp3 ... 390.mp3)
```

## Paso 1: Crear una cuenta en GitHub (si no tienes una)

Entra a **github.com** y crea una cuenta gratuita. No necesitas ningún plan
de pago para lo que vamos a hacer.

## Paso 2: Crear el repositorio

1. Una vez adentro, busca el botón verde **"New"** (o el símbolo "+" arriba
   a la derecha → "New repository").
2. Ponle un nombre, por ejemplo: `spelling-bee`
3. Déjalo como **Public** (público) — es necesario para que GitHub Pages
   pueda mostrarlo gratis.
4. No marques ninguna casilla adicional (README, .gitignore, licencia).
5. Da clic en **"Create repository"**.

## Paso 3: Subir los archivos

1. En la página del repositorio recién creado, busca el enlace que dice
   **"uploading an existing file"**.
2. Antes de arrastrar nada, primero **coloca tus imágenes reales dentro de
   la carpeta `imagenes/`** y tus **audios reales dentro de `audios/`** en
   tu computador (reemplazando o acompañando los archivos de texto que
   dejé como referencia).
3. Arrastra **toda la carpeta completa** (o selecciona todos los archivos
   y subcarpetas) a la zona de "arrastra aquí" de GitHub.
4. Espera a que termine de cargar (con 30 MB puede tardar unos minutos
   según tu conexión). Escribe un mensaje corto abajo, por ejemplo
   "Primera versión", y da clic en **"Commit changes"**.

> Nota: si tu navegador no te deja arrastrar carpetas completas, puedes
> subir el contenido de cada carpeta por separado (primero los archivos
> sueltos, luego entra o crea la carpeta `imagenes` y arrastra las
> imágenes ahí, y lo mismo con `audios`).

## Paso 4: Activar GitHub Pages

1. Dentro del repositorio, ve a la pestaña **"Settings"** (Configuración).
2. En el menú de la izquierda, busca **"Pages"**.
3. En "Source" (Origen), selecciona la rama **`main`** y la carpeta
   **`/ (root)`**.
4. Da clic en **"Save"**.
5. GitHub te va a mostrar un link parecido a:
   `https://tu-usuario.github.io/spelling-bee/`
   (puede tardar 1-2 minutos en activarse la primera vez).

## Paso 5: Probarlo

1. Abre el link que te dio GitHub en el celular o computador.
2. Verifica que las imágenes y audios carguen bien.
3. Para comprobar que quedó funcionando sin conexión: ábrelo una vez con
   datos/wifi, espera unos segundos (para que el service worker termine
   de guardar todo), luego activa el modo avión y recarga la página.
   Debería seguir funcionando igual.

## Paso 6 (opcional): Instalarlo como app

En el celular, al abrir el link en Chrome, debería aparecer la opción
**"Agregar a pantalla de inicio"** (o un ícono de instalación en la barra
de direcciones). Al usarlo, queda con su propio ícono — el balón que
generamos — y se abre en pantalla completa, sin la barra del navegador.

## Compartir con otros docentes

Una vez publicado, compartir el juego con cualquier colega es tan simple
como enviarles el link de GitHub Pages. No necesitan descargar ninguna
carpeta ni instalar nada manualmente — el link ya contiene todo.

## Actualizaciones futuras

Si en algún momento quieres cambiar algo (agregar palabras, corregir una
imagen, etc.), simplemente vuelve a subir el archivo modificado al mismo
repositorio (GitHub te va a preguntar si quieres reemplazar el archivo
existente). Los cambios se reflejan automáticamente en el mismo link,
normalmente en menos de un minuto.
