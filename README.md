# Proyecto Final de Recuperación de la Información

En este repositorio se encuentra el programa y los resultados del proyecto final de
Recuperación de la Información.

## Equipo:

- Ramos Benavides Alfredo de Jesús - 201637137
- Suárez Calderón Rosa             - 201631874
- Suárez Polo Axel                 - 201744436
- Torres Marín Ana Laura           - 201628183

## Contenidos:

- `main.py`: Contiene el programa principal en Python
- `extractor.py`: Contiene el programa en Python para extraer los documentos
- `ProyectoF.txt`: Contiene los documentos originales
- `PalabrasCerradas.txt`: Contiene las palabras cerradas del Español

## Resultados
- `procesado.txt`: Contiene el texto transformado de XML a texto plano.
- `noticias_procesadas.txt`: Contiene los documentos procesados.
- `vocabulario.txt`: El vocabulario obtenido de los documentos.
- `tf.csv`: La tabla TF como archivo separado por comas.
- `idf.csv`: La tabla IDF como archivo separado por comas.
- `representacion_documentos.csv`: La representación de los documentos como
    vectores con TF/IDF.
- `similitud_documentos.csv`: Contiene la tabla con todas las similitudes entre
    los pares de documentos.

## Ejecución
Para ejecutar el programa, basta con invocar python o python3 según sea el caso
con el nombre del script principal en la carpeta que contiene los documentos y
el archivo principal.

```powershell
python main.py
```

## Notas adicionales:

Para poder ejecutar el programa es necesario hacer la instalación de Python y de la
librería **nltk**.

1. Instalación de Python

Para instalar Python se pueden seguir las instrucciones que se encuentran en este enlace:

https://tutorial.djangogirls.org/es/python_installation/

2. Instalación de la librería nltk

Para instalar la librería nltk, es necesario ejecutar los siguientes comandos en una
consola del sistema con privilegios de administrador en Windows o como el usuario root
en Linux.

```powershell
> pip3 install nltk

> python -c "import nltk; nltk.download('popular')"
```

En Linux puede ser necesario cambiar el comando `python` por `python3`.

## Links adicionales

- [nltk](https://www.nltk.org/)
- [python](https://www.python.org/)
