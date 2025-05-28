# Análisis de Tiendas Alura Store LATAM

Este proyecto realiza un análisis detallado de cuatro tiendas pertenecientes a **Alura Store LATAM** con el objetivo de determinar cuál de ellas representa la mejor opción para ser adquirida por el Sr. Juan. El análisis incluye métricas como ingresos totales, categorías de productos más vendidas, calificaciones promedio de los clientes, productos más y menos vendidos, y costos de envío promedio.

## Tabla de Contenidos

1. [Descripción del Proyecto](#descripción-del-proyecto)
2. [Características Principales](#características-principales)
3. [Requisitos](#requisitos)
4. [Instalación](#instalación)
5. [Uso](#uso)
6. [Estructura del Proyecto](#estructura-del-proyecto)
7. [Generación de Informe PDF](#generación-de-informe-pdf)
8. [Contribuciones](#contribuciones)
9. [Licencia](#licencia)

## Descripción del Proyecto

El propósito de este análisis es evaluar las características y el desempeño de cuatro tiendas (Tienda 1, Tienda 2, Tienda 3 y Tienda 4) utilizando datos históricos. Se consideran múltiples factores clave, como:

- **Ingresos totales**: Evaluación financiera de cada tienda.
- **Categorías de productos más y menos vendidas**: Identificación de preferencias de los clientes.
- **Calificaciones promedio de los clientes**: Indicador de satisfacción del cliente.
- **Productos más y menos vendidos**: Optimización del inventario.
- **Costo de envío promedio**: Competitividad en precios de envío.

Con base en estos análisis, se recomienda la **Tienda 3** como la mejor opción para ser adquirida debido a su alto desempeño financiero, fuerte presencia en categorías populares, alta calificación promedio y bajo costo de envío.

## Características Principales

- **Gráficos interactivos**:
  - Gráfico de barras: Ingresos totales por tienda.
  - Gráfico de dispersión: Calificaciones promedio por tienda.
- **Mapa de calor**: Visualización geográfica de las ventas.
- **Generación de informe PDF**: Resumen detallado del análisis en formato descargable.

---

## Requisitos

Para ejecutar este proyecto, necesitarás lo siguiente:

- Python 3.8 o superior
- Bibliotecas de Python instaladas:
  - `reflex`
  - `pandas`
  - `plotly`
  - `folium`
  - `fpdf`

Puedes instalar las dependencias usando el archivo `requirements.txt` (si está disponible) o manualmente:

```bash
pip install reflex pandas plotly folium fpdf
```

## Instalación

1. Clona este repositorio:
```bash
git clone https://github.com/tu-usuario/alura-store-latam.git 
cd alura-store-latam
```
2. Instala las dependencias:
```bash
pip install -r requirements.txt
```
3. Ejecuta la aplicación:
```bash
reflex run
```

## Uso

1. Abre la aplicación en tu navegador (normalmente en `http://localhost:3000`).
2. Explora los gráficos y visualizaciones: 
    - **Ingresos Totales :** Gráfico de barras con los ingresos de cada tienda.
    - **Calificaciones Promedio :** Gráfico de dispersión con las calificaciones de los clientes.
    - **Distribución Geográfica de Ventas :** Mapa de calor con las ubicaciones de las ventas.
3. Descarga el informe PDF haciendo clic en el botón "Descargar Informe PDF".

## Estructura del Proyecto

El proyecto está organizado de la siguiente manera:

```
alura-store-latam/
├── app.py                  # Archivo principal de la aplicación Reflex
├── requirements.txt        # Dependencias del proyecto
├── mapa_ventas.html        # Mapa de calor generado dinámicamente
├── informe_final_alura_store_latam.pdf  # Informe PDF generado
└── README.md               # Documentación del proyecto
```

## Generación de Informe PDF

El informe PDF incluye un análisis detallado de las siguientes secciones:

1. **Introducción :** Propósito del análisis.
2. **Desarrollo :**
    - Ingresos totales por tienda.
    - Categorías de productos más y menos vendidas.
    - Calificaciones promedio de los clientes.
    - Productos más y menos vendidos.
    - Costo de envío promedio.
3. **Conclusión :** Recomendación final basada en los resultados.

El informe se genera automáticamente al hacer clic en el botón "Descargar Informe PDF" en la interfaz de la aplicación.

## Contribuciones

¡Las contribuciones son bienvenidas! Si deseas mejorar este proyecto, sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza tus cambios y haz commit (`git commit -m "Añadir nueva funcionalidad"`).
4. Sube tus cambios (`git push origin feature/nueva-funcionalidad`).
5. Abre un pull request.