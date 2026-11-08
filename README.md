# Clasificación de textos en Esperanto – Grupo 1

Práctica de Minería de Textos (CUNEF, 2026/2027).
Grupo 1: Anaïs Soler, Ana Sánchez y Claudia García 
Tema: **Turismo y viajes**

## Clases
- `hoteles`: Hoteles y alojamiento
- `transporte`: Transporte y aerolíneas
- `destinos`: Destinos turísticos

## Ficheros
| Fichero | Resumen |
|---|---|
| `dataset.csv` | Dataset final: 1743 párrafos de la Wikipedia en Esperanto (581 por clase). CSV en UTF-8, separador `;`, columnas `text;class`. |
| `parrafos_limpios.csv` | Todos los párrafos limpios antes de equilibrar, con el artículo del que salen (`text;class;article`). |
| `fase1_dataset_grupo1.ipynb` | Cuaderno que genera los dos CSV desde la API de la Wikipedia en Esperanto. |

## Cómo se usa
En el cuaderno, `GENERAR_DATASET = False` carga los CSV de este repositorio; `GENERAR_DATASET = True` los vuelve a generar desde la Wikipedia (unos 20 minutos).
