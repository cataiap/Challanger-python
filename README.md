# Alura Store — Análisis por tienda (Pandas + Matplotlib)

> Análisis exploratorio de 4 tiendas para recomendar dónde vender, usando Python (Pandas + Matplotlib).
>
> **Notebook:** `AluraStoreLatam.ipynb`

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1zNcY4p64478sK8yFmeCnhxUS8PmOjy4f)

---

## **1) Propósito del análisis**

Evaluar el desempeño de cuatro tiendas y emitir una recomendación para el Sr. Juan considerando:
- Ingresos totales por tienda.
- Ventas por categoría y productos más/menos vendidos.
- Calificación promedio de clientes por tienda y por categoría.
- Costo de envío promedio por tienda.
- (Extra opcional) distribución geográfica de ventas con lat/lon.
 
---

## **2) ¿Qué incluye?**

### Carga de datos (4 tiendas) desde URLs dentro del notebook (no necesitas descargar archivos).

Cálculo de:

- Ingresos totales por tienda (suma de Precio).
- Ventas por categoría (conteo).
- Calificación promedio por tienda y por categoría.
- Top de ventas más alto y más bajas de productos por tienda.
- Costo de envío promedio (el envío lo paga el cliente).
- Informe final 

Visualizaciones:

- Barras horizontales (categorías y Top de ventas más alto y más bajas de productos por tienda).
- Barras comparando calificaciones promedio.
- Ubicación geográfica: dispersión lat/lon por tienda.

---


## 3) **Estructura del proyecto**

Challanger-python/
- AluraStoreLatam.ipynb   # Notebook con todo el análisis
- README.md               # Este archivo


---


## **4) Cómo ejecutarlo**

Google Colab 

- Abre el notebook con el botón Open in Colab de arriba.
- Ve a Entorno de ejecución → Ejecutar todo.


---


## **5) Ejemplos de gráficos e insights**

Ingresos totales (barras):
- Ranking observado: Tienda 1 > Tienda 2 > Tienda 3 > Tienda 4.

Ventas por categoría (barras horizontales):
- Patrón consistente: Muebles y Electrónicos lideran; Artículos para el hogar, Libros e Instrumentos musicales tienden a ser los de menor rotación.

Calificación promedio (barras):
- Tienda 3 (≈4,05) > Tienda 2 (≈4,04) > Tienda 4 (≈4,00) > Tienda 1 (≈3,98).
- Oportunidad de mejorar atención/posventa en Tienda 1.

Top de productos (barras):
Ejemplos:
- T1 Top: Microondas, TV LED UHD 4K, Armario… · Bottom: Celular ABXY, Auriculares con micrófono, Olla de presión…
- T2 Top: Iniciando en programación, Microondas, Batería, Pandereta… · Bottom: Juego de mesa, Impresora, Mesa de comedor…
- T3 Top: Kit de bancas, Cama king, Mesa de comedor… · Bottom: Bloques de construcción, Microondas, Mochila, Set de vasos…
- T4 Top: Cama box, Cubertería, Cama king… · Bottom: Guitarra eléctrica, Armario, Guitarra acústica…

Costo de envío promedio (barras):
- Tienda 4 es la más baja; Tienda 1 la más alta (el costo lo paga el cliente).


---



**Autor: Cataiap**
