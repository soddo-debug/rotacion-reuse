# Dashboard de Rotación + Matriz de Decisiones — CL · MX · PE

App en Streamlit, TODO EN UN SOLO ARCHIVO (`app.py`).

## Solo necesitas 2 archivos en GitHub

- `app.py` (todo el código, incluida la matriz)
- `requirements.txt`

(Ya NO existe matriz_logic.py — está fusionado dentro de app.py.)

## requirements.txt (versiones FIJAS — no cambiar)

streamlit==1.40.2
pandas==2.2.3
numpy==1.26.4
plotly==5.24.1
openpyxl==3.1.5

## Ejecutar local

pip install -r requirements.txt
streamlit run app.py

## Secciones

1. Resumen Ejecutivo  2. Comparativo  3. Por Categoría  4. Por Producto
5. Rotación Teléfonos (iPhone/Samsung)  6. Matriz de Decisiones (CR x Visitas x Stock)
7. Alertas  8. Recomendaciones

## Flujo semanal

Sube por país: Stock + Ventas (Bsale) y, para la matriz, el archivo GA4 de visitas/conversiones.
