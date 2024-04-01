# Tesis-LaTeX-IECI
Plantilla de tesis hecha en TeX para la carrera de Ingeniería de Ejecución en Computación e Informática de la
Universidad del Bío-Bío.

## Introducción
El presente proyecto fue escrito para servir como una plantilla o guía general para aquellos alumnos de la carrera de
Ingeniería de Ejecución en Computación e Informática que deseen escribir su informe de tesis utilizando LaTeX.

Esta plantilla contiene todos los elementos requeridos por el formato del informe, todos escritos en la sintaxis de TeX, 
listos para ser rellenados. Algunos de estos elementos son:
  * Tabla de requerimientos funcionales.
  * Tabla de requerimientos no funcionales.
  * Tabla de riesgos.
  * Tabla de contenidos.
  * Tabla de especificación de casos de uso.
  * Tabla de desglose del VAN (planilla).
  * Índice de figuras.
  * Índice de tablas.
  * Bibliografía (incluye formato para referencias online!).

Algunas de las secciones también contienen un pequeño texto de ayuda o ejemplo para orientar al tesista.

## Compilación
Ejecuta el siguiente comando desde la terminal, o configura tu editor de TeX para compilar con él:

Windows
```bash
pdflatex.exe -synctex=1 -interaction=nonstopmode -shell-escape %.tex
```

Linux & MacOS
```bash
pdflatex -synctex=1 -interaction=nonstopmode -shell-escape %.tex
```

## Dependencias
Se utilizó el paquete `minted` para la renderización de fragmentos de código en el documento. Este paquete depende de
`pygmnets`, el cual tendrás que instalar via python.

- [Python 3.8 o superior](https://www.python.org/downloads/)
- Módulos de Python:
  - pygments
