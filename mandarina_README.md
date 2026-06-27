# 🍊 Predicción de Ventanas de Aplicación de Fitosanitarios — Cítricos · Pisco Elqui

<a href="https://franciscoantonioardiles-ctrl.github.io/Predicci-n-Ventanas-Aplicaciona-Mandarinas/" target="_blank">
  <img src="https://img.shields.io/badge/🚀%20Ver%20Dashboard%20Interactivo-3fb950?style=for-the-badge"/>
</a>

## Descripción
Análisis con **Machine Learning y Deep Learning** para identificar las ventanas horarias óptimas de **aplicación de fitosanitarios en cítricos** en el Valle del Elqui, usando datos meteorológicos de la Estación Pisco Elqui (2022–2024).

El objetivo es **evitar pérdidas económicas** por aplicación de pesticidas bajo condiciones de viento, temperatura o humedad desfavorables que dispersan el producto o reducen su adherencia.

## Criterios de Ventana Óptima para Aplicación
| Variable | Condición | Razón Agronómica |
|---|---|---|
| Temperatura del Aire | 15°C – 25°C | Evita evaporación rápida del producto |
| Humedad Relativa | > 60% | Favorece adherencia del fitosanitario |
| Velocidad del Viento | < 2.78 m/s | Evita deriva y dispersión del producto |
| Radiación Solar | < 50 W/m² | Reduce fotodegradación del pesticida |

## Resultados
| Modelo | Accuracy | F1 Clase Positiva |
|---|---|---|
| Random Forest (n=100) | **100%** | 0.99 |
| Red Neuronal Dense (16→8→1) | **99.65%** | 0.93 |

## Impacto Práctico
- Solo el **12.6% de las horas** reúne condiciones óptimas para aplicar sin riesgo de pérdida de producto
- La variable más determinante es la **Radiación Solar**, seguida de **Temperatura** y **Hora del día**
- Aplicar fuera de ventana implica **pérdida de fitosanitario, dinero y potencial contaminación** del entorno

## Contenido
| Archivo | Descripción |
|---|---|
| `mandarina_notebook.ipynb` | Pipeline completo ML + DL |
| `mandarina_report.pdf` | Reporte técnico con gráficos |
| `index.html` | Dashboard interactivo |

## Autor
**F. Ardiles** para M. Valenzuela · [GitHub](https://github.com/franciscoantonioardiles-ctrl)
