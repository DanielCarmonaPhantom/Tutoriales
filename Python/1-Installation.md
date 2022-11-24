<img src='https://www.datocms-assets.com/14946/1590686329-python-analytics-cover.png?auto=format&fit=max&w=1200'>
<a href='./README.md'>Regresar</a>

# 1. Instalación de Python

Para poder programar en python en un entorno local, tendremos que instalar alguna de sus versiones. Hay IDES que ya traen instalado Python, pero aqui instalaremos todo desde 0

## Contenido

1. Instalación en Windows
2. Instalación en MAC
3. Instalación en Linux

### 1. Instalación en Windows
Para descargar Python, podemos acceder a la página principal https://www.python.org/downloads/ y descargar la versión más reciente. 

Tambien puedes guiarte por este video si tienes algúna duda:
[Video de instalación de Python en Windows](https://www.youtube.com/watch?v=nXgxe3JM7Rc)

Para saber que contamos con python podemos abrir la aplicación de `Simbolos del sistema` que se encuentra en nuestras aplicaciones o ejecutar el comando: `Tecla Windows + R` y escribir cmd.

Esto nos abrira una consola donde escribiremos el siguiente comando y daremos enter:

```Bash
py --version
```

Y te debe dar como resultado la versión que instalaste.

### 2. Instalación en MAC

Algpunos sistemas operativos basados en UNIX suelen contener una versión vieja de python, en este caso lo que tenemos que hacer es actualizarlo, así que procederemos a descargarlo desde la página principal https://www.python.org/downloads/

Tambien puedes guiarte por este video si tienes algúna duda:
[Video de instalación de Python en MAC](https://www.youtube.com/watch?v=xxZnunBwC4U)


Para saber que contamos con python podemos abrir la aplicación de `Terminal` que se encuentra en nuestras aplicaciones o ejecutar el comando: `command + barra espaciadora` y escribir `Terminal`

Esto nos abrira una consola donde escribiremos el siguiente comando y daremos enter:

```Bash
python3 --version
```

Y te debe dar como resultado la versión que instalaste.

### 2. Instalación en Linux

Algpunos sistemas operativos basados en UNIX suelen contener una versión vieja de python, en este caso lo que tenemos que hacer es actualizarlo, así que procederemos a la terminal para actualizarlo.

Abrimos la terminal y escribiremos los siguientes comandos:

```Bash
sudo apt-get update
```


```Bash
sudo apt-get install python3
```
** La versión que se pone aquí es la que esta en este momento.

Sí da error, probrar con la `3.11`

Ahora verificaremos si si quedo instalada la nueva versión

```Bash
python3 --version
```