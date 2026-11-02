**Trabajo Práctico Grupal · Laboratorio de Métodos Cuantitativos Aplicados a la Gestión**
Tecnicatura Universitaria en Gestión y Análisis de Datos en Organizaciones · FCE UBA · 2do Cuatrimestre 2026

---

## Integrantes

| Nombre y apellido | N.º de registro | Usuario de GitHub |
|---|---|---|
| Rocio Ojeda | 921426 | OjedaRocio |
| Valentina Fernández Zurita | 921469 | valentinafernandezu |
| Hilda Anabel Martinez Uriarte | 921802 | hildaanabel |
| Tania Andrea Campos Aliaga | 921715 | tania-1604 |

---

## Pregunta de investigación

> **¿Es verdad que las canciones se volvieron mas cortas a lo largo del tiempo**



## Resumen

_COMPLETAR EL FINAL: qué dataset se usó, qué se hizo y qué se encontró._

---

## Entregables ( ESTO CHEQUEAR SI SE QUEDA O NO)

| Parte | Descripción | Enlace / archivo |
|---|---|---|
| Parte 1 | Notebook de análisis (ejecutado) | [`notebook/tp_grupal.ipynb`](notebook/tp_grupal.ipynb) · [Abrir en Colab](https://colab.research.google.com/) |
| Parte 2 | Informe académico (PDF) | [`informe/informe.pdf`](informe/informe.pdf) |
| Parte 2 | Proyecto en Overleaf (si se usó LaTeX) | https://www.overleaf.com/project/6adf531f9fb5bca0fde01489/share#e35f65eacd8635c0a76f744ade2d2921b75845e5ca54922e |
| Parte 3 | Presentación de diapositivas | _pegar link o_ [`presentacion/presentacion.pdf`](presentacion/presentacion.pdf) |

---

## Dataset

- **Archivo:** `data/track_data_final.csv`
- **Fuente:** https://www.kaggle.com/datasets/wardabilal/spotify-global-music-dataset-20092025?resource=download
- **Dimensiones:** 8.778 filas × 15 columnas
- **Variables principales:** `track_name`, `track_duration_ms` (duración en milisegundos), `track_popularity`, `explicit`, `artist_name`, `artist_genres`, `album_release_date`, `album_type`, entre otras.
- **Cobertura temporal:** fecha de lanzamiento del álbum (`album_release_date`).
- **Nota:** se usó la versión original (`track_data_final.csv`) y la limpieza se hizo en el notebook, según lo que requiere la pregunta.

---

## Estructura del repositorio

```
.
├── README.md
├── data/
│   └── track_data_final.csv
├── notebook/
│   └── tp_grupal.ipynb
├── informe/
│   └── informe.pdf
├── presentacion/
│   └── presentacion.pdf
└── figuras/
    └── (gráficos exportados con plt.savefig)
```

---

 ESTO CHEQUEAR AL FINAL: Librerías utilizadas: `pandas`, `numpy`, `matplotlib` _(agregar las que correspondan, por ejemplo `seaborn`)_.

---

## Uso de IA

Se utilizó inteligencia artificial como asistente en distintas etapas del trabajo. En el notebook se indica qué celdas contaron con asistencia y qué prompt se utilizó. El informe fue revisado por todos los integrantes contrastando cada afirmación con el notebook y los datos originales. Más detalle en la sección 6 del informe (reflexión metodológica).

---

