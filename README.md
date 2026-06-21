<img width="148" height="148" alt="image" src="https://github.com/user-attachments/assets/9646a6c6-415d-4c89-98af-690cb0cc969e" />


<h1 align="center">
Análisis de Consumo Energético en una Industria
</h1>

<p align="center">
<strong>Universidad del Pacífico</strong><br>
Programa de Ingeniería de Sistemas<br>
Asignatura: Inteligencia Artificial
</p>

<p align="center">

![Python](https://img.shields.io/badge/Python-3.x-blue)
![NumPy](https://img.shields.io/badge/NumPy-Scientific_Computing-green)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical_Analysis-red)

</p>

---

# Descripción del Proyecto

Este proyecto tiene como finalidad realizar un análisis exploratorio de datos sobre el consumo energético de una industria mediante la generación de datos sintéticos y la aplicación de técnicas de análisis estadístico y visualización de datos utilizando las librerías **NumPy**, **Matplotlib** y **Seaborn**.

A partir de una simulación de 500 registros diarios, se estudian las relaciones entre la producción industrial, las horas de operación, la temperatura ambiente y el consumo energético, con el objetivo de identificar patrones, tendencias y oportunidades de optimización.

---

# Objetivos

## Objetivo General

Analizar el comportamiento del consumo energético de una industria mediante herramientas de Ciencia de Datos e Inteligencia Artificial.

## Objetivos Específicos

- Generar datos sintéticos representativos de un año de operación industrial.
- Aplicar análisis estadístico utilizando NumPy.
- Construir visualizaciones con Matplotlib.
- Analizar correlaciones mediante Seaborn.
- Detectar posibles anomalías en el consumo energético.
- Formular estrategias para la optimización energética.

---

# Integrantes

| Nombre |
|----------|
| Kelly Jhoana Mosquera Urbano |
| Anyela Katerine Rentería Cumana |
| Juan Alejandro Roldán |

---

# Información Académica

| Información | Detalle |
|------------|---------|
| Universidad | Universidad del Pacífico |
| Programa | Ingeniería de Sistemas |
| Asignatura | Inteligencia Artificial |
| Docente | Wilman Andrés Quiñónez V. |
| Semestre | Octavo Semestre |
| Año | 2026 |

---

# Variables del Dataset

El conjunto de datos está conformado por las siguientes variables:

| Variable | Descripción | Tipo |
|------------|------------|------------|
| Día | Identificador del día registrado | Numérica |
| Producción_Diaria | Cantidad producida por día | Numérica |
| Horas_Operacion | Horas de funcionamiento de la planta | Numérica |
| Consumo_Energetico | Energía consumida (kWh) | Numérica |
| Temperatura_Ambiente | Temperatura registrada | Numérica |

---

# Herramientas Utilizadas

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook
- Google Colab
- GitHub

---

# Análisis Estadístico con NumPy

Se calcularon las principales métricas descriptivas del consumo energético:

- Consumo promedio.
- Consumo máximo.
- Consumo mínimo.
- Distribución de valores.
- Comportamiento general de la variable objetivo.

---

# Visualizaciones con Matplotlib

## Serie Temporal del Consumo Energético

Permite observar la evolución del consumo energético a lo largo del tiempo.

### Resultado
<img width="1014" height="471" alt="image" src="https://github.com/user-attachments/assets/bcceef90-153b-40aa-bbda-dd032185138d" />

---

## Histograma del Consumo Energético

Permite analizar la distribución de frecuencias del consumo energético.

### Resultado

<img width="691" height="471" alt="image" src="https://github.com/user-attachments/assets/27d49ba3-e580-4dd6-9666-39393f334724" />


---

## Gráfico de Dispersión

Relación entre la producción diaria y el consumo energético.

### Resultado

<img width="705" height="471" alt="image" src="https://github.com/user-attachments/assets/f0ed47e6-9f8f-4a79-8a9e-d356f60b2adb" />


---

# Análisis Exploratorio con Seaborn

## Heatmap de Correlación

Permite identificar relaciones entre las variables numéricas.

### Resultado

<img width="774" height="676" alt="image" src="https://github.com/user-attachments/assets/0a6b52a4-d3b7-4852-92c2-1856eff7d95c" />


---

## Pairplot

Visualización simultánea de relaciones entre variables.

### Resultado

<img width="1231" height="1231" alt="image" src="https://github.com/user-attachments/assets/8478ebbc-2782-4d1e-ac95-3e50f20d4419" />


---

## Regplot

Permite observar tendencias y relaciones lineales.

### Resultado

<img width="704" height="471" alt="image" src="https://github.com/user-attachments/assets/2ac37dff-e2d7-4b31-85ab-c790e762b286" />


---

# Resultados del Análisis

Después de analizar los datos obtenidos se identificó que:

- La producción diaria presenta una relación directa con el consumo energético.
- Las horas de operación influyen significativamente en el gasto energético.
- Existen días con consumos superiores al promedio que pueden considerarse anomalías.
- La temperatura ambiente presenta una influencia moderada sobre el consumo.

---

# Preguntas del Taller

## ¿Qué variables afectan el consumo energético?

Las variables que presentan mayor influencia son:

- Producción diaria.
- Horas de operación.
- Temperatura ambiente.

## ¿Existen días con comportamientos anómalos?

Sí. Algunos registros muestran consumos significativamente superiores al promedio general.

## ¿Cómo podría reducirse el gasto energético?

- Optimizando horarios de operación.
- Implementando mantenimiento preventivo.
- Sustituyendo equipos ineficientes.
- Monitoreando continuamente los indicadores energéticos.

---

# Propuesta de Optimización Energética

Con base en los resultados obtenidos se propone:

1. Implementar un sistema de monitoreo energético en tiempo real.
2. Optimizar la programación de la producción.
3. Reducir tiempos muertos de operación.
4. Realizar mantenimiento periódico de maquinaria.
5. Aplicar modelos predictivos para anticipar consumos elevados.

---

# Conclusiones

- Se logró generar y analizar un conjunto de datos sintéticos que representa el comportamiento energético de una industria durante un período de operación.

- El análisis estadístico permitió identificar tendencias generales del consumo energético, así como valores máximos, mínimos y promedios relevantes para la toma de decisiones.

- Las visualizaciones desarrolladas con Matplotlib facilitaron la comprensión del comportamiento de las variables y las relaciones existentes entre ellas.

- El análisis realizado con Seaborn permitió identificar correlaciones entre la producción diaria, las horas de operación, la temperatura ambiente y el consumo energético.

- Se evidenció que variables como la producción diaria y las horas de operación tienen una influencia significativa sobre el consumo energético de la industria.

- La detección de comportamientos atípicos demuestra la importancia del análisis de datos para optimizar procesos y reducir costos operativos.

---

# Aprendizajes Obtenidos

Durante el desarrollo de este proyecto se fortalecieron conocimientos relacionados con:

- Manipulación y análisis de datos utilizando la librería NumPy.
- Creación de gráficos estadísticos mediante Matplotlib.
- Desarrollo de análisis exploratorio de datos con Seaborn.
- Interpretación de métricas estadísticas para la toma de decisiones.
- Identificación de patrones y correlaciones entre variables.
- Aplicación de herramientas de Ciencia de Datos en contextos industriales.
- Uso de Python como herramienta para el análisis y visualización de información.

Asimismo, se comprendió la importancia de la analítica de datos dentro de los procesos industriales, permitiendo transformar datos en información útil para la optimización de recursos y la mejora de la eficiencia energética.

---

# Trabajo Futuro

Como trabajo futuro se propone:

- Implementar modelos predictivos de consumo energético mediante técnicas de aprendizaje automático.
- Incorporar más variables operativas para mejorar el análisis.
- Desarrollar tableros interactivos para el monitoreo en tiempo real.
- Evaluar diferentes estrategias de optimización energética basadas en los resultados obtenidos.

---

# Instalación

```bash
git clone https://github.com/TU_USUARIO/Analisis_Consumo_Energetico_IA.git
```

```bash
pip install numpy pandas matplotlib seaborn
```

---

# Ejecución

```bash
jupyter notebook
```

o abrir directamente en Google Colab.

---

# Licencia

Proyecto académico desarrollado para la asignatura de Inteligencia Artificial de la Universidad del Pacífico.

---

<p align="center">
<strong>Universidad del Pacífico</strong><br>
Programa de Ingeniería de Sistemas<br>
Buenaventura, Valle del Cauca - Colombia<br>
2026
</p>
