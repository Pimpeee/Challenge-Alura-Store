# Análisis de Datos de Alura Store Latam

Este repositorio contiene un análisis de datos exploratorio (EDA) de la cadena de tiendas "Alura Store Latam". El objetivo del proyecto es evaluar el desempeño de sus cuatro sucursales a través de métricas clave de rentabilidad, ventas y satisfacción del cliente para fundamentar una recomendación estratégica de negocio.

## 📈 Análisis Realizado

El análisis se centró en responder preguntas de negocio clave utilizando datos de ventas de cuatro tiendas (`tienda_1`, `tienda_2`, `tienda_3`, `tienda_4`). Se llevaron a cabo las siguientes evaluaciones:

### 1. Análisis de Facturación y Rentabilidad
Se calculó la **Ganancia Bruta** por transacción (definida como `Precio - Costo de envío`) para medir la rentabilidad real de cada tienda.

- **Resultado:** La **Tienda 1** es la más rentable, mientras que la **Tienda 4** genera la menor ganancia bruta total.

### 2. Desempeño por Categoría de Producto
Se analizó la contribución porcentual de cada categoría de producto a la ganancia bruta total de la empresa.

- **Resultado:** El negocio muestra una alta dependencia de las categorías de **Electrónicos (37.3%)** y **Electrodomésticos (30.7%)**, que juntas representan más del 68% de las ganancias totales.

### 3. Satisfacción del Cliente por Tienda
Se comparó la distribución de las calificaciones (de 1 a 5 estrellas) otorgadas por los clientes a cada una de las tiendas.

- **Resultado:** Aunque las cuatro tiendas tienen una distribución de calificaciones muy similar, el análisis final sugiere que la Tienda 4 presenta una mayor proporción de valoraciones negativas (1 y 2 estrellas), lo que indica un riesgo para la reputación de la marca.

### 4. Análisis de Productos
Se identificaron los productos con mejor y peor desempeño según dos criterios diferentes:

- **Productos más valiosos:** Los 5 productos que generan mayor ganancia bruta, liderados por el **TV LED UHD 4K** y el **iPhone 15**.
- **Productos con peor calificación:** Los 5 productos con el promedio de calificación más bajo, siendo el **Set de vasos** y el libro **Modelado predictivo** los peor valorados.

### 5. Impacto de los Costos de Envío
Se calculó el impacto promedio del costo de envío como un porcentaje de la ganancia por venta en cada tienda para medir la eficiencia operativa.

- **Resultado:** La **Tienda 2** es la menos eficiente, ya que el costo de envío consume un porcentaje mayor de sus ganancias por venta (6.51%). La **Tienda 3** es la más eficiente en este aspecto.

## 📊 Visualizaciones Incluidas

Para facilitar la interpretación de los datos, se generaron las siguientes visualizaciones:

- Gráfico de barras de **Ganancia Bruta Total por Tienda**.
- Gráfico circular de **Distribución Porcentual de Ganancia por Categoría**.
- Gráfico de barras apiladas de **Distribución de Calificaciones por Tienda**.
- Gráficos de barras horizontales para los **Top 5 productos más rentables** y los **5 productos peor calificados**.
- Gráfico de barras del **Impacto Promedio del Costo de Envío por Tienda**.

## 🎯 Conclusión y Recomendación Estratégica

La recomendación principal es **cerrar la Tienda 4**. Esta decisión se basa en tres puntos críticos:

1.  **Fracaso Financiero:** Es consistentemente la tienda con la **menor rentabilidad**. Su operación no genera valor significativo en comparación con las otras sucursales.
2.  **Ineficiencia Operativa:** Aunque no tiene el costo de envío más alto en términos absolutos, su modelo de ventas se basa en productos de bajo margen que no justifican la operación.
3.  **Riesgo de Reputación:** Acumula una mayor proporción de calificaciones negativas, lo que indica fallas en la experiencia del cliente y representa un riesgo para la imagen de la marca Alura Store.

Cerrar esta sucursal permitiría liberar capital y recursos para reinvertir en las tiendas más exitosas (como la Tienda 1) y optimizar la estrategia de costos en las tiendas con mayor impacto logístico (como la Tienda 2).

## 💾 Fuente de Datos

El análisis se realizó a partir de cuatro archivos CSV que contienen los datos de ventas de cada tienda. Los datos fueron proporcionados por Alura Latam y se encuentran en los siguientes enlaces:

- [Tienda 1](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_1%20.csv)
- [Tienda 2](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_2.csv)
- [Tienda 3](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_3.csv)
- [Tienda 4](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_4.csv)

