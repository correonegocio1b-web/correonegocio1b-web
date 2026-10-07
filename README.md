# Hola, soy Emmanuel 👋

**Analista de datos** en formación en el programa de Data Analytics de TripleTen. Me gusta tomar datos desordenados, limpiarlos y convertirlos en respuestas concretas para el negocio: qué está pasando, por qué y qué conviene hacer.

**Herramientas:** Python · pandas · NumPy · SciPy · statsmodels · matplotlib · seaborn · Jupyter · Git/GitHub

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Emmanuel%20Sánchez-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/emmanuel-sanchez-137452352/)

---

## Proyectos

### 🧪 [Experimento A/B en una landing page](https://github.com/correonegocio1b-web/ab-testing-landing-page_new)
Evaluación de un experimento A/B con 40,000 usuarios para decidir qué versión de una página de inicio implementar.
- Validé el experimento antes de probar nada: grupos balanceados, sin usuarios expuestos a ambas versiones y reglas de negocio consistentes.
- Elegí la prueba según los supuestos: t de Welch (tras Levene), prueba z de proporciones y χ² de independencia.
- **Hallazgo:** la página B convierte más (15.96% vs 12.57%, ≈ +27%) y sus clientes gastan más (68.75 vs 61.09, ≈ +12.5%), ambos con p < 0.0001 → recomendación de implementar B y priorizar Email y Ads.

### 📡 [Análisis de clientes de una telco — ConnectaTel](https://github.com/correonegocio1b-web/connectatel-analysis)
Análisis de uso de 4,000 clientes móviles en México y Colombia (enero–junio 2024).
- Limpieza de valores centinela, fechas imposibles y formatos inconsistentes en 3 datasets.
- Detección de outliers con IQR y segmentación por nivel de uso y edad.
- **Hallazgo:** ningún cliente excede su plan y el 73.6% tiene un uso medio muy por debajo de lo que paga → propuesta de un plan *Light* y campañas segmentadas por comportamiento.

### 🛒 [Comportamiento del cliente vs. ingreso — NovaRetail+](https://github.com/correonegocio1b-web/novaretail-customer-analysis)
Análisis correlacional de 15,000 clientes de un e-commerce latinoamericano (2024).
- Elegí el coeficiente según el tipo de variable: Pearson, Spearman, punto biserial y V de Cramér.
- **Hallazgo:** las compras mensuales son la señal más fuerte del ingreso (r = 0.967) y las visitas tienen una asociación moderada (r = 0.34). Señalé que una correlación tan alta podría indicar redundancia entre las variables y propuse cómo validarlo.

### 🚦 [Movilidad urbana vs. productividad económica — Latinoamérica](https://github.com/correonegocio1b-web/mobility-economy-latam)
Cruce de más de 1 millón de registros de tráfico de TomTom con indicadores económicos de la OECD para 15 ciudades latinoamericanas (2024).
- Limpieza y estandarización de dos fuentes con formatos incompatibles, agregación ciudad–año y unión INNER.
- **Hallazgo:** no hay una relación clara entre PIB per cápita y congestión, así que el PIB por sí solo no sirve para priorizar inversión en transporte. Ciudad de México registra el mayor retraso promedio del análisis.

---

## Lo que sé hacer

- **Limpieza de datos:** tipos incorrectos, nulos, centinelas, separadores decimales y de miles, fechas fuera de rango.
- **Análisis exploratorio y estadístico:** agregaciones, `groupby`/`merge`, estadísticas descriptivas, outliers, coeficientes de correlación adecuados a cada tipo de variable y pruebas de hipótesis para experimentos A/B (t de Welch, prueba z de proporciones, χ²).
- **Visualización:** histogramas, boxplots, gráficos comparativos con lectura crítica de escalas.
- **Comunicación:** resúmenes ejecutivos con hallazgos y recomendaciones accionables.

---

📫 Contacto: [LinkedIn](https://www.linkedin.com/in/emmanuel-sanchez-137452352/)
