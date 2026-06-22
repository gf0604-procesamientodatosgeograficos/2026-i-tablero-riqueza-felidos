# Tablero de control de riqueza de félidos de Costa Rica

Tablero de control desarrollado con [Quarto Dashboards](https://quarto.org/docs/dashboards/)
que presenta la riqueza de especies de félidos silvestres (familia *Felidae*) en Costa Rica,
con base en registros de presencia de [GBIF](https://www.gbif.org/) y los polígonos de las
áreas de conservación del [SINAC](https://www.sinac.go.cr/).

Es el ejemplo del capítulo *Tableros de control* del libro del curso
**GF-0604 Procesamiento de datos geográficos** (Escuela de Geografía, Universidad de Costa Rica).

## Tablero publicado

<https://gf0604-procesamientodatosgeograficos.github.io/2026-i-tablero-riqueza-felidos/>

## Desarrollo

```sh
# Renderizar el tablero
quarto render

# Vista previa
quarto preview
```

La salida se genera en `docs/` y se publica en GitHub Pages desde esa carpeta en la rama `main`.
Los datos se cargan en tiempo de ejecución desde el repositorio del curso
[`2026-i`](https://github.com/gf0604-procesamientodatosgeograficos/2026-i).
