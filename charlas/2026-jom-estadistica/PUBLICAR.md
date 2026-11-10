# Publicar esta presentación en GitHub Pages

Esta carpeta conserva la presentación definitiva sin cambios de contenido ni diseño.
`index.html` es una copia exacta del HTML ya renderizado `charla_estadistica.html`.

## Ruta sugerida
Copiar esta carpeta como:

`charlas/2026-jom-estadistica/`

dentro del repositorio `bimasusi.github.io`.

## Publicar
Desde la raíz del repositorio:

```bash
git add charlas/2026-jom-estadistica
git commit -m "Publica charla Teaching Statistics"
git push
```

La URL será:

`https://bimasusi.github.io/charlas/2026-jom-estadistica/`

## Si vuelve a editar el .qmd
Se añadió únicamente `output-file: index.html` en el YAML. En su equipo puede ejecutar:

```bash
quarto render charla_estadistica.qmd
```

No se cambió ninguna diapositiva, texto, gráfica, bibliografía ni estilo.
