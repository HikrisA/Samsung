# Reporte de Proyecto

Este repositorio contiene la documentación en LaTeX del reporte del proyecto de para el SIC 2024.

## Estructura del Proyecto

```
Reporte/
│── Carlos/
│   ├── Introduccion.tex
│── Enrique/
│   ├── Imagenes/
│   ├── Conclusiones.tex
│   ├── Metodologia.tex
│   ├── Resultados.tex
│── Francisco/
│   ├── Imagenes metodologia calificacion/
│   ├── Imagenes resultados/
│   ├── Conclusiones.tex
│   ├── Metodologia.tex
│   ├── Resultados.tex
│── Zdenko/
│   ├── CSV/
│   ├── Imágenes/
│   ├── Conclusion.tex
│   ├── Metodologia.tex
│   ├── Resultados.tex
│── output/
│── .gitignore
│── Cancer de pulmon.png
│── main.aux
│── main.bbl
│── main.bcf
│── main.blg
│── main.log
│── main.out
│── main.pdf
│── main.run.xml
│── main.synctex.gz
│── main.tex  <-- Archivo principal del reporte
│── main.toc
│── Portada_SIC.pdf
│── referencias.bib
│── README.md
```

## Descripción

- El archivo principal del documento es **main.tex**.
- Todas las secciones del reporte están organizadas en carpetas según el autor correspondiente.
- El archivo `referencias.bib` contiene la bibliografía usada en el documento.

## Compilación

Para compilar el documento en **VS Code** con LaTeX Workshop:

1. Asegurar que tienes instalados los siguientes paquetes:
   - `TeX Live` (o MiKTeX si usas Windows)
   - `latexmk`
   - `biber` (para bibliografía)
2. Abre el archivo `main.tex` en VS Code.
3. Usa `Ctrl + Shift + P` y ejecuta `LaTeX Workshop: Build LaTeX project`.
4. Asegúrate de que `main.pdf` se genera correctamente en la raíz del proyecto.

Si prefieres compilar manualmente:

```sh
pdflatex main.tex
biber main
pdflatex main.tex
pdflatex main.tex
```

Esto asegurará que las referencias se procesen correctamente.
