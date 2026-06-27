# 🍊 Predicción de Ventanas de Cosecha — Mandarinas · Pisco Elqui

<a href="https://franciscoantonioardiles-ctrl.github.io/mandarina-cosecha/" target="_blank">
  <img src="https://img.shields.io/badge/🚀%20Ver%20Dashboard%20Interactivo-3fb950?style=for-the-badge"/>
</a>

## Descripción
Análisis completo con **Machine Learning y Deep Learning** para predecir las ventanas horarias óptimas de cosecha de mandarinas en el Valle del Elqui, utilizando datos meteorológicos de la **Estación Pisco Elqui (2022–2024)**.

## Criterio Agronómico
| Variable | Rango Óptimo |
|---|---|
| Temperatura del Aire | 15°C – 25°C |
| Humedad Relativa | > 60% |
| Velocidad del Viento | < 2.78 m/s |
| Radiación Solar | < 50 W/m² |

## Resultados
| Modelo | Accuracy | F1 Clase Positiva |
|---|---|---|
| Random Forest (n=100) | **100%** | 0.99 |
| Red Neuronal Dense (16→8→1) | **99.65%** | 0.93 |

## Contenido
| Archivo | Descripción |
|---|---|
| `mandarina_notebook.ipynb` | Pipeline completo DS con ML + DL |
| `mandarina_report.pdf` | Reporte con gráficos y análisis |
| `index.html` | Dashboard interactivo (GitHub Pages) |

## Hallazgo Principal
Solo el **12.6% de las horas** cumple simultáneamente las 4 condiciones óptimas, concentrándose principalmente entre las **00:00 y 07:00h** y en los meses de **otoño (Abril–Junio)**.

## Autor
**F. Ardiles** para M. Valenzuela · [GitHub](https://github.com/franciscoantonioardiles-ctrl)
