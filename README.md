# Procesamiento Digital de Imágenes · MCDI · INFOTEC · 2027-1

Material del curso **Procesamiento digital de imágenes** (MCDI00010) de la Maestría en Ciencia de Datos e Información (MCDI).

**Sitio del curso:** https://egonzalez1989.github.io/pdi-mcdi/

| Carpeta | Contenido |
|---|---|
| `sesiones/` | Cuadernos Jupyter ejecutados de las 6 sesiones síncronas |
| `presentaciones/` | Presentaciones (.pptx) de las sesiones |
| `plantillas/` | Plantillas de las actividades 1A–5A |
| `listas_cotejo/` | Listas de cotejo (PDF) |
| `datos/` | Imágenes de práctica de uso libre |
| `documentos/` | Programa y agenda (PDF) |
| `*.qmd`, `unidades/` | Fuentes del sitio web (Quarto) |

## Unidades
1. Introducción al procesamiento digital de imágenes
2. Preprocesamiento
3. Segmentación
4. Descripción y representación de imágenes digitales
5. Reconocimiento de imágenes

## Uso rápido
- En **Google Colab**: abre cualquier cuaderno con el botón *Abrir en Colab* del sitio.
- En local: `pip install -r requirements.txt` y `jupyter lab`.

## Publicación del sitio
El sitio se construye con [Quarto](https://quarto.org) y se publica en GitHub Pages mediante la acción `.github/workflows/publish.yml` en cada *push* a `main` (Settings → Pages → Source: *GitHub Actions*). Para previsualizarlo localmente: `quarto preview`.

## Licencia
Contenido bajo [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.es); el código de los cuadernos puede reutilizarse libremente con atribución. Las imágenes de `datos/` conservan las licencias de su origen (scikit-image).

Dr. Edgar González Fernández · edgar.gonzalezf@infotec.mx
