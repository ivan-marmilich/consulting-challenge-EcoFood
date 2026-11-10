cat <<'EOF' > README.md
# Consulting Challenge — EcoFood (Data Analytics Lab)

Repositorio de la consultoría de datos para **EcoFood**. El objetivo principal de este proyecto es analizar datos del negocio para resolver sus desafíos operativos e identificar oportunidades estratégicas sustentables.

---

## 📁 Estructura del Repositorio

```text
consulting-challenge/
│
├── data/
│   ├── raw/          # Datasets crudos de EcoFood (APIs, scraping o fuentes abiertas)
│   └── processed/    # Datasets limpios y transformados listos para el EDA
├── notebooks/        # Jupyter Notebooks con la extracción, limpieza y EDA
├── images/           # Gráficos e ilustraciones generadas para los hallazgos
├── presentation/     # Deck de la presentación ejecutiva (máx. 10 slides)
└── README.md         # Documentación principal del proyecto ```

# 🥗 EcoFood: Estrategia de Expansión en CABA

## 📄 Descripción del Proyecto (El Porqué)
Este proyecto nace para resolver un desafío de negocio real: determinar dónde y cómo una nueva línea de alimentos sostenibles debe introducirse en el mercado de la Ciudad de Buenos Aires. Para lograrlo, unimos el análisis de la oferta gastronómica real con las tendencias de consumo digital, evitando intuiciones y basando cada decisión en datos sólidos.

## 🎯 Objetivo del Cliente
Identificar las comunas, barrios y categorías con mayor potencial comercial desatendido para minimizar el riesgo en el lanzamiento de productos EcoFood.

## 📊 Fuentes de Datos
* **Oferta Gastronómica (GCBA):** Catastro oficial de establecimientos (restaurantes, cafés, dietéticas y afines) de la Ciudad de Buenos Aires (`data.buenosaires.gob.ar`).
* **Tendencias de Consumo:** Google Trends (Argentina) para medir el interés temporal en alimentación saludable, orgánica y sin TACC.

## 🛠️ Metodología
1. **Extracción y Limpieza:** Procesamiento del dataset en Python (Pandas) para eliminar nulos, estandarizar textos y unificar categorías.
2. **Análisis Geoespacial:** Agrupación dual por comuna (visión logística macro) y barrio (detalle micro local) para calcular densidades comerciales.
3. **Cruce de Variables:** Contraste entre la densidad de oferta instalada y el interés de búsqueda digital para detectar baches de oportunidad.

