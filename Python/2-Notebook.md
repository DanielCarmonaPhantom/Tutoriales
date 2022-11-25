<a href='README.md'>Regresar</a>

# 1. Crear un Notebook en Visual Code

Ahora que ya sabemos como abrir una carpeta en Visual code, vamos a crear un archivo `.ipynb` que son las extensiones que denotar que es un `notebook`

## ¿Qué es un notebook?

<img src='https://miro.medium.com/max/1400/1*6091-RcrOPyifJTLjo0anA.gif'>

Un notebook de Python es un archivo que te permite interactuar con código en tiempo real. Se cuentan con 2 tipos de celdas donde puedes escribir código Python y texto.

En texto te permite utilizar el Lenguaje Markdown que nos ayuda a denotar ciertos formatos como negritas, links, imagenes, títulos y más, cómo si fuera un documento de word.

<img src='https://arogozhnikov.github.io/images/jupyter/example-notebook.png'>

Cómo puedes ver tenemos un título, que tiene un link y una fórmula Matemática.

## Crear nuestro primer Notebook

En nuestro editor, vamos a crear un archivo que se llamará `Tutorial.ipynb` 

<img src='https://i.ytimg.com/vi/eFGziOe-3uQ/maxresdefault.jpg'>

Nos aparecera nuestro archivo de esta manera.

<img src='https://code.visualstudio.com/assets/docs/datascience/jupyter/native-kernel-picker.png'>

(Suelen salir notificaciones que te dicen que instales ciertas extensiones, yo te recomiendo instalarlas.)

Hasta arriba a la derecha te debe seleccionar por defecto el kernel con el cual ejectuara nuestro código, en este caso será la versión de Python que tenemos instalada. (Si no te aparece, puedes darle click y escoger)

Cuando es un nuevo archivo, aparecera una celda de código por defecto, así que vamos a eliminarla con el icono de `basura` que se encuentra hasta la derecha.

Contamos con 2 botones:

[+ Code]
[+ Markdown]

Seleccionaremos [+ Markdown] y nos creara una celda de texto, aquí colocaremos lo siguiente:

```Marckdown
# Tutorial
```

Cuando quieras ejectuar código python o guardar un texto utilizaras la combinación: `shift` + `enter`.

Esto nos debe pintar un Título así:


# `Tutorial`

Y automáticamente te creara una celda de código abajo.

En la nueva celda colocaremos código Python 

```Python
print("Hola Mundo")
```

Presionamos: `shift` + `enter` y ahora nos dara un resultado:

```Bash
Hola Mundo
```

