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

## 🎵 Análisis de la Duración de Canciones en Spotify (2009–2025)

Este repositorio investiga empíricamente si las canciones se volvieron más cortas con el tiempo. Utilizando técnicas de limpieza, filtrado y análisis estadístico sobre un dataset de Spotify, el estudio confirma la hipótesis central.

### 📌 Hallazgos Clave

* **Tendencia decreciente:** La duración promedio cayó de forma sostenida desde 2013, pasando de más de **3:48 min** a mínimos cercanos a los **3:00 min** en la actualidad.
* **Reconfiguración del mercado:** Las canciones cortas ($<3$ min) pasaron del **14.8%** (2009–2014) al **47.1%** (2020–2025). En contraste, los temas largos ($>4$ min) cayeron del **36.7%** al **13.1%**.
* **Ausencia de penalización comercial:** La correlación ($r = 0.11$) demuestra que hacer temas más cortos no castiga su popularidad; rinden igual que los formatos tradicionales.

### 💡 Conclusión
La duración no es una variable artística aislada, sino una **respuesta estratégica** a los incentivos del streaming, los algoritmos y la economía de la atención.
---

## Entregables

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

 ESTO CHEQUEAR AL FINAL: Librerías utilizadas: `pandas`, `numpy`, `matplotlib`, `seaborn`.

---

## Uso de IA

Se utilizó inteligencia artificial como asistente en distintas etapas del trabajo. En el notebook se indica qué celdas contaron con asistencia y qué prompt se utilizó. El informe fue revisado por todos los integrantes contrastando cada afirmación con el notebook y los datos originales. Más detalle en la sección 6 del informe (reflexión metodológica).

---

