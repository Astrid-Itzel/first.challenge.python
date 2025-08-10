# first.challenge.python


# 📊 Análisis de Ventas y Recomendación de Tienda para el Sr. Juan

## 📌 Descripción del Proyecto
Este proyecto tiene como objetivo analizar los datos de ventas de **cuatro tiendas** con el fin de determinar en cuál de ellas el Sr. Juan debería vender sus productos.  
El análisis se realiza a partir de los datos proporcionados en formato CSV y procesados en **Google Colab** utilizando Python y bibliotecas de análisis y visualización de datos.

---

## 🗂 Datos Utilizados
Los datos de cada tienda incluyen:
- **Producto**
- **Categoría del Producto**
- **Precio**
- **Costo de Envío**
- **Fecha de Compra**
- **Vendedor**
- **Lugar de Compra**
- **Calificación**
- **Método de pago**
- **Cantidad de cuotas**
- **Coordenadas de ubicación (lat, lon)**

Cada archivo contiene el registro de ventas, donde cada fila representa una transacción.

---

## 🔍 Análisis Realizado
1. **Ingresos Totales por Tienda**  
   Se calcularon las ganancias considerando el precio de los productos vendidos.
   
2. **Categorías de Productos más y menos vendidas**  
   Identificación de las categorías con mayor y menor número de transacciones.
   
3. **Calificación promedio de los clientes**  
   Análisis de la satisfacción del cliente en cada tienda.

4. **Productos más y menos vendidos**  
   Ranking de los productos más populares y los de menor demanda.

5. **Costo de envío promedio**  
   Evaluación del gasto medio en envíos por tienda.

---

## 📈 Visualizaciones
Se generaron gráficos para facilitar la interpretación de los resultados, incluyendo:
- **Gráfico de barras**: productos más y menos vendidos por tienda.
- **Gráfico de líneas**: evolución de ingresos a lo largo del tiempo.
- **Gráfico de dispersión**: relación entre precio y calificación.
- **Gráfico circular**: distribución de categorías vendidas.

---

## 🏆 Conclusión y Recomendación
Tras el análisis de ingresos, satisfacción del cliente, costos de envío y comportamiento de ventas, se determinó la tienda más conveniente para que el Sr. Juan venda sus productos.  
*(Aquí deberías incluir el nombre de la tienda que seleccionaste y una breve justificación de la elección).*

---

## 🛠 Tecnologías Utilizadas
- **Python** (Pandas, Matplotlib, Seaborn)
- **Google Colab**
- **GitHub** para almacenamiento del código
- **CSV** como formato de datos

---

## 🚀 Cómo Ejecutar el Proyecto
1. Abrir el archivo `.ipynb` en Google Colab.
2. Asegurarse de tener instaladas las bibliotecas necesarias:
```python
pip install pandas matplotlib seaborn
