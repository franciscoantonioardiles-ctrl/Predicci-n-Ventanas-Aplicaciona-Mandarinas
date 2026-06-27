# 🌿 Ventanas de Aplicacion de Fitosanitarios — Citricos · Pisco Elqui

<a href="https://franciscoantonioardiles-ctrl.github.io/Predicci-n-Ventanas-Aplicaciona-Mandarinas/" target="_blank">
  <img src="https://img.shields.io/badge/🚀%20Ver%20Dashboard%20Interactivo-3fb950?style=for-the-badge"/>
</a>

## Descripcion
Analisis con **Machine Learning y Deep Learning** para identificar las ventanas horarias optimas de **aplicacion de fitosanitarios en citricos** en el Valle del Elqui, usando datos meteorologicos de la Estacion Pisco Elqui (2022-2024).

El objetivo es **evitar perdidas economicas** por aplicacion de pesticidas bajo condiciones de viento, temperatura o humedad desfavorables que dispersan el producto o reducen su adherencia en la planta.

## Criterios de Ventana Optima para Aplicacion
| Variable | Condicion | Razon Agronomica |
|---|---|---|
| Temperatura del Aire | 15C - 25C | Evita evaporacion rapida del fitosanitario |
| Humedad Relativa | > 60% | Favorece adherencia del producto en la hoja |
| Velocidad del Viento | < 2.78 m/s | Evita deriva y dispersion del producto aplicado |
| Radiacion Solar | < 50 W/m2 | Reduce fotodegradacion del pesticida |

## Resultados
| Modelo | Accuracy | F1 Clase Positiva |
|---|---|---|
| Random Forest (n=100) | **100%** | 0.99 |
| Red Neuronal Dense (16->8->1) | **99.65%** | 0.93 |

## Impacto Practico
- Solo el **12.6% de las horas** reune condiciones optimas para aplicar sin riesgo de perdida de producto
- La variable mas determinante es la **Radiacion Solar** (indicador indirecto del viento termico)
- Aplicar fuera de ventana implica **perdida de fitosanitario, dinero y posible contaminacion** del entorno

## Contenido del Repositorio
| Archivo | Descripcion |
|---|---|
| `mandarina_notebook.ipynb` | Pipeline completo ML + DL |
| `fitosanitarios_citricos.pdf` | Reporte tecnico con graficos |
| `index.html` | Dashboard interactivo (GitHub Pages) |

## Autor
**F. Ardiles** para M. Valenzuela · [GitHub](https://github.com/franciscoantonioardiles-ctrl/Predicci-n-Ventanas-Aplicaciona-Mandarinas)
