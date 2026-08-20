# 📡 LTE Radiopropagation Analysis — COST-231

Proyecto académico de análisis y validación experimental de modelos de propagación para una red **LTE** en un entorno urbano alrededor de la **Universidad Nacional Mayor de San Marcos (UNMSM)**.

El estudio compara mediciones reales de señal con modelos teóricos de propagación y emplea herramientas de análisis geoespacial para representar la cobertura de la red.

---

## 🌐 Sitio web del proyecto

El proyecto cuenta con una página web interactiva publicada mediante **GitHub Pages**, donde pueden visualizarse los mapas generados durante el análisis de radiopropagación.

### 👉 [Abrir sitio web interactivo](https://josueeeoo-0.github.io/radiopropagation_LTE_COST231_UNMSM/)

En el sitio se encuentran los mapas interactivos desarrollados con Python y Folium, además de accesos al informe, Jupyter Notebook y archivos principales del proyecto.


## 📑 Contenido

Este repositorio incluye:

* 📄 **Informe final del proyecto**
* 🐍 **Jupyter Notebook** utilizado para el procesamiento, cálculos y generación de gráficas
* 🗺️ **Proyecto QGIS** y archivos utilizados para el análisis geoespacial

```text
radiopropagation_LTE_COST231_UNMSM/
│
├── informe_final_radiopropagacion.pdf
├── analisis_radiopropagacion.ipynb
├── README.md
├── mediciones.xlsx
└── qgis_project/
    └── archivos del proyecto QGIS
```

---

## 📶 Análisis realizado

Durante el proyecto se realizaron mediciones LTE georreferenciadas de:

* **RSRP** — Reference Signal Received Power
* **RSRQ** — Reference Signal Received Quality
* **SINR / RSSNR** — Signal-to-Interference-plus-Noise Ratio

Las mediciones fueron comparadas con modelos de propagación:

* **COST-231 Hata**
* **COST-231 Walfisch-Ikegami**

También se generaron:

* Gráficas de RSRP respecto a la distancia
* Comparaciones entre mediciones y modelos
* Análisis del error del modelo
* Radio Environment Maps (REM)
* Mapas de cobertura
* Mapas de nodos LTE

---

## 🗺️ Herramientas utilizadas

* Python
* Jupyter Notebook
* QGIS
* Network Cell Info Lite
* CellMapper
* COST-231 Hata
* COST-231 Walfisch-Ikegami

---

## 📄 Informe

El informe completo del proyecto puede consultarse aquí:

[**Ver informe final**](./informe_final_radiopropagacion.pdf)

---

## 🐍 Jupyter Notebook

El código utilizado para el procesamiento de datos, cálculos y generación de gráficas se encuentra en:

[**Ver análisis en Jupyter Notebook**](./analisis_radiopropagacion.ipynb)

---

## 🎓 Proyecto académico

Proyecto desarrollado para el curso de **Radiopropagación** de la
**Facultad de Ingeniería Electrónica y Eléctrica — UNMSM**.