# 🚀 Guía para crear y publicar mi primer proyecto

En esta guía explico paso a paso cómo crear mi primer proyecto de programación, organizar los archivos y publicarlos en GitHub.

La idea es que pueda seguir estos pasos aunque tenga poca experiencia con programación, HTML o GitHub.

# 1. Crear mi archivo HTML

Primero creo un archivo llamado:

index.html

Este será el archivo principal de mi proyecto y contendrá el código de mi página web.

Puedo comenzar utilizando una estructura básica de HTML:

```html

<!DOCTYPE html>

<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi primer proyecto</title>
</head>
<body>

```
<h1>Hola, mundo 👋</h1>
```

</body>
</html>
```

Después de escribir el código, guardo el archivo con el nombre:

index.html

💡 **Importante:** debo verificar que el archivo tenga la extensión `.html` y no `.txt`.

# 2. Probar mi archivo HTML

Antes de subir mi proyecto a GitHub, puedo probar que mi página funcione correctamente.

Para hacerlo:

1. Busco el archivo `index.html` en mi computador.
2. Hago doble clic sobre el archivo.
3. Se abrirá en un navegador como Google Chrome, Microsoft Edge o Firefox.
4. Verifico que aparezca el contenido que escribí.

Por ejemplo, si escribí:

```html

<h1>Hola, mundo 👋</h1>
```

debería visualizar en el navegador:

**Hola, mundo 👋**

Si realizo algún cambio en mi código, debo guardar nuevamente el archivo y actualizar la página en el navegador.

# 3. Crear mi repositorio en GitHub

Ahora voy a crear un repositorio para guardar mi proyecto.

Un **repositorio** es un espacio donde puedo almacenar y organizar los archivos de mi proyecto.

Para crear uno:

1. Ingreso a GitHub.
2. Inicio sesión con mi cuenta.
3. Selecciono la opción **New repository**.
4. Escribo un nombre para mi repositorio.

Por ejemplo:

`mi-primer-proyecto`

5. Agrego una descripción corta de mi proyecto.
6. Selecciono si el repositorio será **público** o **privado**, de acuerdo con las instrucciones de mi docente.
7. Finalmente, creo el repositorio.

# 4. Crear mi archivo README.md

Dentro de mi repositorio creo un archivo llamado:

`README.md`

El archivo `README.md` sirve para explicar de qué trata mi proyecto y cómo utilizarlo.

En este archivo puedo incluir información como:

* Nombre de mi proyecto.
* Descripción del proyecto.
* Mi nombre como autor.
* Tecnologías utilizadas.
* Instrucciones para ejecutar el proyecto.
* Información adicional que considere importante.

Por ejemplo:

```markdown
# Mi primer proyecto

Este es mi primer proyecto de programación.

## Tecnologías utilizadas

* HTML

## Autor

Mi nombre
```

💡 **Nota:** En Markdown normalmente se utiliza `#` para crear títulos. En esta guía utilizo `#` como reemplazo, de acuerdo con el formato solicitado.

# 5. Agregar mi archivo index.html

Después de crear mi repositorio, agrego el archivo:

`index.html`

De esta manera, mi repositorio debería quedar organizado aproximadamente así:

```text
mi-primer-proyecto/
│
├── index.html
└── README.md
```

El archivo `index.html` contiene el código de mi página web, mientras que `README.md` contiene la información y explicación de mi proyecto.

# 6. Guardar los cambios en GitHub

Cuando agrego o modifico archivos en mi repositorio, debo guardar los cambios.

En GitHub, este proceso puede incluir realizar un **commit**.

Un **commit** es como guardar una versión de los cambios que realicé en mi proyecto.

Por ejemplo, puedo escribir como mensaje del commit:

`Agrego mi primer archivo HTML`

Después confirmo el cambio.

7. Publicar mi proyecto con GitHub Pages

Ahora que ya tengo mi archivo index.html dentro del repositorio, puedo utilizar GitHub Pages para publicar mi página web y obtener un enlace que pueda compartir con otras personas.

GitHub Pages permite convertir mi repositorio en un sitio web.

7.1. Ingresar a la configuración del repositorio

Primero ingreso a mi repositorio en GitHub.

Después:

Hago clic en la pestaña Settings.
En el menú lateral busco la opción Pages.
Ingreso a la sección Pages.
7.2. Configurar GitHub Pages

Dentro de GitHub Pages, busco la opción relacionada con la publicación del sitio.

En Build and deployment selecciono:

Source: Deploy from a branch

Luego selecciono:

Branch: main

Y en la carpeta selecciono:

Folder: / (root)

Después hago clic en Save.

7.3. Esperar la publicación

Después de guardar la configuración, GitHub comenzará a publicar mi proyecto.

Este proceso puede tardar algunos segundos o minutos.

Cuando termine, GitHub me mostrará un enlace similar a:

https://miusuario.github.io/mi-primer-proyecto/

Hago clic en el enlace para comprobar que mi página funciona correctamente.

7.4. Comprobar mi página

Al abrir el enlace, debería aparecer el contenido de mi archivo index.html.

Por ejemplo, si mi archivo contiene:

<h1>Hola, mundo 👋</h1>
<p>Este es mi primer proyecto publicado.</p>

En el navegador debería visualizar:

Hola, mundo 👋

Este enlace puedo compartirlo con mi profesor, compañeros o cualquier persona que necesite revisar mi proyecto.

💡 Importante: para que GitHub Pages encuentre automáticamente la página principal, mi archivo debe llamarse exactamente:

index.html

y debe estar ubicado en la carpeta que seleccioné para la publicación.

8. Conceptos básicos que debo conocer

Como estudiante que está comenzando programación, es importante que conozca algunos conceptos básicos:

HTML: es un lenguaje utilizado para crear la estructura de las páginas web.

Archivo: es un documento donde guardo información o código de mi proyecto.

Repositorio: es un espacio donde almaceno y organizo los archivos de un proyecto.

Git: es una herramienta que me permite controlar y registrar los cambios que realizo en mis proyectos.

GitHub: es una plataforma donde puedo almacenar y compartir repositorios utilizando Git.

Commit: es un registro de los cambios que realicé en mi proyecto.

Push: es el proceso mediante el cual envío mis cambios desde mi computador hacia un repositorio en GitHub.

README.md: es un archivo que utilizo para explicar mi proyecto.

GitHub Pages: es una herramienta de GitHub que me permite publicar mi proyecto como una página web.

# 9. Conceptos básicos que debo conocer

Como estudiante que está comenzando programación, es importante que conozca algunos conceptos básicos:

**HTML:** es un lenguaje utilizado para crear la estructura de las páginas web.

**Archivo:** es un documento donde guardo información o código de mi proyecto.

**Repositorio:** es un espacio donde almaceno y organizo los archivos de un proyecto.

**Git:** es una herramienta que me permite controlar y registrar los cambios que realizo en mis proyectos.

**GitHub:** es una plataforma donde puedo almacenar y compartir repositorios utilizando Git.

**Commit:** es un registro de los cambios que realicé en mi proyecto.

**Push:** es el proceso mediante el cual envío mis cambios desde mi computador hacia un repositorio en GitHub.

**README.md:** es un archivo que utilizo para explicar mi proyecto.

# 8. Estructura final de mi proyecto

Al finalizar, mi proyecto debería tener una estructura similar a esta:

```text
mi-primer-proyecto/
│
├── index.html
└── README.md
```

# 🎉 ¡Proyecto terminado!

Si seguí todos los pasos, ya tengo mi primer proyecto organizado y almacenado en GitHub.

Antes de finalizar, debo comprobar que:

* Mi archivo se llama correctamente `index.html`.
* Mi código HTML funciona en el navegador.
* Creé correctamente mi repositorio en GitHub.
* Agregué el archivo `README.md`.
* Agregué el archivo `index.html`.
* Guardé los cambios realizados.
* Mi repositorio tiene una estructura organizada.

💡 **Recuerdo:** aprender programación es un proceso. Es normal equivocarme al principio. Lo importante es practicar, leer los errores y aprender de cada cambio que realizo en mi código.
