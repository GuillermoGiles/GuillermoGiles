# Guillermo Giles

**Datos y Backend | SQL · Python · PostgreSQL · pandas**

Estudiante avanzado de Ingeniería en Sistemas de Información (UTN, Facultad Regional La Plata). Trabajo con datos de punta a punta: diseño y normalizo bases relacionales, escribo las consultas analíticas que las explotan, construyo los pipelines que las alimentan y analizo los resultados con estadística aplicada. Experiencia con clientes reales en producción. Inglés B2 certificado (Cambridge FCE).

## Proyectos de datos

[**vaca-muerta-analytics**](https://github.com/GuillermoGiles/vaca-muerta-analytics) — Análisis de productividad de 3.315 pozos de Vaca Muerta sobre 421.046 registros mensuales de datos abiertos de la Secretaría de Energía. Ajuste de curvas de declino de Arps (el pozo mediano pierde 73 % de su pico en dos años, con b = 1,19 e intervalo por bootstrap), evolución de la productividad inicial por añada y análisis de concentración. Incluye ingesta reproducible vía API CKAN, detección de sesgo de censura a derecha y la documentación de por qué el benchmark entre operadoras **no** es separable del efecto geológico. `Python` `pandas` `SciPy` `SQL` `matplotlib` `pytest`

[**feedlot-bovino-db**](https://github.com/GuillermoGiles/feedlot-bovino-db) — Base de datos relacional en PostgreSQL (15 tablas, 3FN) y capa analítica para un establecimiento de engorde bovino. Calcula ganancia media diaria, conversión alimenticia y margen bruto por animal con CTEs y funciones de ventana. El análisis detecta un corral con 27 % de sobreconsumo de alimento por kilo producido. Incluye generador de dataset sintético reproducible y visualizaciones en Python. `PostgreSQL` `SQL` `pandas` `matplotlib`

**San José (Gestión Automotriz)** — Sistema de gestión para un centro de lubricación y lavado de vehículos, desarrollado en equipo de 4 (UTN). A cargo del diseño y la normalización del modelo relacional, y de la optimización de consultas SQL para la gestión de turnos y clientes. `Python` `SQL` `Scrum` `Git`

## Modelado de datos en producción

[**sgf-gastos**](https://github.com/GuillermoGiles/sgf-gastos) — Sistema de gestión financiera multi-empresa. Arquitectura multi-tenant con bases de datos aisladas por unidad de negocio, enrutamiento dinámico de conexiones, lógica de agregación financiera con normalización multimoneda ARS/USD y políticas de row-level security por instancia. `PostgreSQL` `Supabase` `Next.js` `RLS`

[**cds-gastos**](https://github.com/GuillermoGiles/cds-gastos) — Registro y consolidación de gastos operativos en tiempo real. Ingesta de datos transaccionales, integración con API externa de cotizaciones para normalizar montos ARS/USD/BRL y generación automatizada de reportes exportables a Excel. `PostgreSQL` `Supabase` `Next.js` `DolarAPI`

## Extracción y procesamiento de datos no estructurados

[**b2b-document-translator**](https://github.com/GuillermoGiles/b2b-document-translator) — Pipeline de extracción sobre PDF, DOCX e imágenes con OCR de alta precisión mediante Gemini 2.5 Flash, con reconstrucción de la estructura del documento.

[**ai-note-digitizer**](https://github.com/GuillermoGiles/ai-note-digitizer) — Transcripción y estructuración de apuntes manuscritos a partir de imágenes usando Google Gemini.

[**ocr-async-tts-engine**](https://github.com/GuillermoGiles/ocr-async-tts-engine) — Procesamiento asíncrono de documentos con OCR y conversión a audio.

`Python` `Asyncio` `Tesseract OCR` `Google Gemini API`

## Stack técnico

**Datos y bases de datos** · PostgreSQL · SQLite · SQL · modelado relacional · normalización · optimización de consultas · funciones de ventana

**Análisis con Python** · pandas · NumPy · SciPy · matplotlib · Streamlit · ajuste de modelos no lineales · bootstrap · análisis de series temporales

**Integración y automatización** · FastAPI · REST APIs · Asyncio · Docker · Git · pytest

**Complementario** · TypeScript · Next.js/React · Supabase · Google Gemini API

## Formación

- Ingeniería en Sistemas de Información — UTN Facultad Regional La Plata (en curso)
- Foundations: Data, Data, Everywhere — Google / Coursera
- First Certificate in English (B2) — Cambridge

## Contacto

LinkedIn: [linkedin.com/in/guillermogiles](https://linkedin.com/in/guillermogiles) · Email: guille123giles@gmail.com
