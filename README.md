# **Predicción del Crecimiento Urbano y del Uso del Suelo en Penjamillo (2010–2030)**

**Proyecto Técnico-Institucional del IMPLAN (2025–2027)**
**Elaborado por:** *Vidal Mendoza Tinoco*
**Fecha:** Octubre 2025

---

# **Resumen Ejecutivo**

El presente documento constituye el proyecto técnico-institucional para el estudio **Predicción del Crecimiento Urbano y del Uso del Suelo en Penjamillo (2010–2030)**, alineado al *Reglamento del IMPLAN de Penjamillo* y al *Plan de Innovación para el Desarrollo Municipal 2025–2027*.

El objetivo es construir modelos predictivos robustos que permitan anticipar patrones de expansión urbana, cambio de cobertura vegetal y dinámicas de uso del suelo mediante técnicas de **sensado remoto, aprendizaje profundo (Deep Learning), estadística espacial y análisis geográfico**. Los resultados servirán para:

* orientar la planeación territorial del Ayuntamiento;
* actualizar el ordenamiento ecológico y urbano;
* prevenir el crecimiento desordenado;
* proponer estrategias de conservación, zonificación y contención urbana;
* cumplir con las funciones legales del IMPLAN, particularmente las previstas en los **Artículos 6, 7, 23 y 24 del Reglamento del Instituto**.

El proyecto utiliza exclusivamente **datos públicos**, imágenes satelitales y marcos geoestadísticos abiertos.

---

# **1. Introducción Académica**

La expansión urbana constituye una de las transformaciones territoriales más relevantes del siglo XXI. La literatura en urbanismo y economía espacial (Bettencourt et al., 2013; Henderson, 2010; Seto et al., 2012) señala que el crecimiento urbano no es aleatorio: sigue patrones estructurales vinculados a accesibilidad, infraestructura, actividad económica y condiciones ambientales.

En municipios rurales como Penjamillo, donde coexisten localidades dispersas, suelos agrícolas de alto valor y una cabecera urbana en crecimiento moderado, el análisis del uso del suelo reviste una importancia estratégica para la **planeación municipal**. Una expansión urbana sin control puede:

* fragmentar ecosistemas,
* generar conflictos por uso de suelo,
* elevar costos de provisión de servicios públicos,
* reducir superficies agrícolas productivas.

El Reglamento del IMPLAN otorga la responsabilidad de **proponer estrategias de conservación, mejoramiento, crecimiento y zonificación** (Art. 7-IV), así como de **evitar el crecimiento descontrolado de los centros de población** (Art. 7-V). Esto obliga a contar con evidencia técnica robusta sobre las trayectorias pasadas y futuras del uso del suelo.

El *Plan de Innovación 2025–2027* establece explícitamente como **Proyecto 3** el desarrollo de un modelo de *“Predicción del crecimiento urbano y del uso del suelo”* mediante imágenes satelitales y aprendizaje profundo .

Este documento cumple dicha función, adoptando estándares académicos y metodológicos contemporáneos.

---

# **2. Justificación Técnica**

## 2.1 Problema público

Penjamillo ha experimentado en los últimos 20 años cambios significativos en cobertura vegetal, áreas agrícolas y superficie urbana. Sin embargo, **no existe un diagnóstico integral que permita anticipar los patrones de expansión**.

La ausencia de este diagnóstico complica:

* la actualización de planes de desarrollo urbano,
* la identificación de zonas de riesgo,
* la planeación de infraestructura,
* la conservación de áreas ecológicas,
* la gestión de servicios públicos básicos.

## 2.2 Justificación institucional

Según el Reglamento del IMPLAN:

* El Instituto debe **generar información geoestadística** (Art. 6-B-III).
* Debe **elaborar estudios prospectivos** (Art. 5-VII).
* Debe **proponer estrategias de conservación y crecimiento urbano** (Art. 7-IV, V).
* Debe **identificar zonas prioritarias** (Art. 23-VII).
* Debe **crear y mantener actualizado el Sistema de Información Geográfica Municipal** (Art. 23-VI).

Este proyecto satisface de forma directa esas obligaciones.

## 2.3 Justificación teórico-metodológica

Los avances en *Deep Learning* permiten analizar imágenes satelitales con precisión antes inimaginable:

* **U-Net** (Ronneberger et al., 2015): arquitectura dominante de segmentación semántica.
* **CNNs para predicción urbana** (Wurm et al., 2019).
* **Deep Remote Sensing** (Zhu et al., 2017): revisión exhaustiva del campo.

Estas técnicas permiten generar predicciones fiables del crecimiento urbano a corto y mediano plazo.

---

# **3. Marco Teórico**

## 3.1 Urbanización y modelos de crecimiento urbano

Autores clave:

* **Paul Romer (1986)** — las ciudades como motores de productividad.
* **Henderson et al. (2010)** — modelos de equilibrio espacial de urbanización.
* **Bettencourt (2013)** — escalamiento urbano y previsibilidad de crecimiento.
* **Seto et al. (2012)** — urbanización global y escenarios prospectivos.

Estos enfoques coinciden en que el crecimiento urbano tiende a seguir patrones estructurales, no aleatorios.

## 3.2 Sensado remoto y clasificación del uso del suelo

La literatura reciente destaca:

* Deep Learning aplicado a imágenes multiespectrales (Zhu et al., 2017).
* Modelos U-Net y variantes (Ronneberger et al., 2015).
* Copernicus y Landsat como fuentes robustas para análisis temporal.
* Uso de *change detection* para evaluar transiciones de uso del suelo.

## 3.3 Modelos predictivos de expansión urbana

Wurm et al. (2019) demuestran que modelos CNN entrenados en series temporales pueden predecir patrones urbanos con alta precisión.

## 3.4 Planeación territorial y normatividad

La planeación territorial municipal debe guiarse por:

* Artículos 7-IV y 7-V del Reglamento IMPLAN:

  * **conservación, mejoramiento, crecimiento y zonificación**;
  * **evitar el crecimiento descontrolado**.
* Artículo 23-VI: creación y actualización del SIG Municipal.
* Artículo 23-VII: identificación de zonas prioritarias para desarrollo social y económico.


---

# **4. Marco Normativo**

El proyecto se fundamenta en:

### **Reglamento del IMPLAN de Penjamillo**

* Art. 6-B-III: generación de información geoestadística.
* Art. 7-IV, V: estrategias de crecimiento y control urbano.
* Art. 23-VI: Banco Municipal de Información + SIG Municipal.
* Art. 23-VII: identificación de zonas prioritarias.
* Art. 24-VII y VIII: propuestas de zonificación y conservación.


### **Plan de Innovación 2025–2027**

El proyecto forma parte del **Punto 3: Predicción del crecimiento urbano y del uso del suelo**.


---

# **5. Preguntas de Investigación**

1. ¿Cómo ha evolucionado el uso del suelo en Penjamillo entre 2000 y 2023?
2. ¿Qué patrones espaciales caracterizan la expansión urbana reciente?
3. ¿Qué variables geográficas predicen la probabilidad de urbanización futura?
4. ¿Qué zonas del municipio presentan mayor riesgo de expansión desordenada?
5. ¿Cómo puede el Ayuntamiento usar estas predicciones para planear servicios, obras y conservación?

---

# **6. Hipótesis**

* **H1:** La expansión urbana de Penjamillo sigue patrones espaciales asociados a la red vial, pendientes topográficas y proximidad a servicios urbanos.
* **H2:** Los cambios de uso agrícola a urbano se concentran en zonas de accesibilidad alta.
* **H3:** Un modelo CNN (U-Net) puede predecir con >85% de precisión la expansión urbana futura.

---

# **7. Metodología Detallada**

## 7.1 Diseño general

1. Integración histórica de mapas de uso de suelo (2002–2023).
2. Descarga de imágenes Landsat y Sentinel-2.
3. Procesamiento (corrección atmosférica, mosaicos, índices NDVI/NDBI).
4. Etiquetado y creación de dataset supervisado.
5. Entrenamiento de modelo U-Net para segmentación.
6. Evaluación con métricas IoU, F1-Score.
7. Generación de predicción para 2030.
8. Traducción de predicciones en **directrices de planeación territorial**.

## 7.2 Conjunto de datos (solo fuentes públicas)

* **INEGI**: Series de Uso de Suelo y Vegetación I–VI.
* **INEGI Marco Geoestadístico**.
* **CONABIO**: cobertura vegetal y capas ambientales.
* **Google Earth Engine (acceso público)**: Landsat 5–7–8, Sentinel-2.
* **NASA / USGS**: DEM SRTM 30m.

## 7.3 Técnicas aplicadas

### a) Sensado remoto

* NDVI (vegetación)
* NDBI (índice de urbanización)
* Modelos de *change detection* por diferencia espectral

### b) Deep Learning

* **U-Net**, **DeepLabV3+**, **ResUNet** para segmentación
* Entrenamiento con 70/15/15 (train/val/test)
* Regularización con data augmentation

### c) Estadística y análisis espacial

* Moran’s I y LISA para detectar clusters urbanos.
* Kernel Density Estimation de manchas urbanas.
* Análisis de accesibilidad vial (distancias de red).

### d) Modelos predictivos

* Predicción espacio-temporal utilizando CNN 3D.
* Proyección a 2030 mediante secuencias multitemporales.

---

# **8. Cronograma 2025–2027**

| Etapa                      | Periodo             | Actividades                                                                   |
| -------------------------- | ------------------- | ----------------------------------------------------------------------------- |
| Preparación institucional  | Nov 2025 – Ene 2026 | Revisión normativa; integración de datos satelitales; definición metodológica |
| Procesamiento y análisis   | Ene – Mar 2026      | Preprocesamiento, índices espectrales, LISA, clusters                         |
| Modelado Deep Learning     | Mar – Sep 2026      | Entrenamiento U-Net; validación cruzada                                       |
| Predicción 2030            | Oct – Dic 2026      | Construcción de escenarios prospectivos                                       |
| Elaboración del informe    | Ene – Abr 2027      | Escritura técnica, mapas, indicadores                                         |
| Presentación y publicación | May – Sep 2027      | Versión final, presentación a Cabildo, publicación online                     |
| Implementación             | Oct – Dic 2027      | Uso del modelo en planeación municipal                                        |

---

# **9. Beneficios para el Ayuntamiento**

1. **Prevención del crecimiento desordenado** (Art. 7-V).
2. **Identificación de zonas futuras de expansión y riesgo**.
3. **Soporte técnico para el Programa de Obra Pública**.
4. **Actualización del SIG Municipal** (Art. 23-VI).
5. **Mejor planificación de infraestructura** (agua, drenaje, vialidades).
6. **Protección de zonas agrícolas y ecológicas**.
7. **Alineación con políticas estatales y federales de ordenamiento territorial**.
8. **Fortalecimiento institucional del IMPLAN** como órgano técnico.

---

# **10. Resultados Esperados**

* Mapas multitemporales 2000–2023 del uso del suelo.
* Predicción del crecimiento urbano 2030 con escenarios alternativos.
* Identificación de zonas críticas de expansión y conservación.
* Actualización del SIG Municipal.
* Informe técnico para Cabildo y ciudadanía.
* Recomendaciones normativas para evitar crecimiento descontrolado.

---

# **11. Conclusiones**

El estudio de **Predicción del Crecimiento Urbano y del Uso del Suelo en Penjamillo** constituye un insumo central para garantizar una planeación territorial efectiva, basada en evidencia y alineada al Reglamento del IMPLAN y al Plan de Innovación 2025–2027.

La incorporación de metodologías avanzadas (Deep Learning, análisis espacial y sensado remoto) permite al Ayuntamiento anticipar escenarios urbanos, proteger áreas de alto valor ecológico y orientar la expansión urbana de manera ordenada, sostenible y acorde a las necesidades de la población.

---

# **12. Bibliografía**

* Bettencourt, L. (2013). *The Origins of Scaling in Cities*.
* Henderson, V. (2010). *Cities and Development*.
* Seto, K. et al. (2012). *Global Forecasts of Urban Expansion*. PNAS.
* Zhu, X. et al. (2017). *Deep Learning in Remote Sensing*. IEEE GRSM.
* Wurm, M. et al. (2019). *Deep Learning for Urban Growth Prediction*.
* Ronneberger, O. et al. (2015). *U-Net: Convolutional Networks for Biomedical Image Segmentation*.
* Reglamento del IMPLAN de Penjamillo (Periódico Oficial del Estado) 
* Plan de Innovación para el Desarrollo Municipal 2025–2027 
* INEGI, CONABIO, Google Earth Engine (datos públicos).
