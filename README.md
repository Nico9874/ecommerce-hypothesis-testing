# Ecommerce Hypothesis Testing en R

## Descripción  
Este proyecto realiza un **test de hipótesis estadístico** para analizar si las ventas con recomendación de productos (**Group_1**) son mayores que las ventas sin recomendación (**Group_0**) en un eCommerce B2B.  
Se utiliza **R** para la prueba estadística y visualización de resultados.

## Tecnologías utilizadas  
- **R** (ggplot2, gridExtra)  
- **Prueba t de Student** para evaluar diferencias de medias  
- **Dataset de ventas B2B**  

## Cómo ejecutar el análisis  
1. Clonar este repositorio:
   ```sh
   https://github.com/Nico9874/ecommerce-hypothesis-testing.git

## Resultados clave  

### **Hipótesis evaluada:**  
- **H₀ (Hipótesis nula):** La media de ventas en **Group_1** (con recomendación) es menor o igual a la de **Group_0** (sin recomendación).  
- **H₁ (Hipótesis alternativa):** La media de **Group_1** es mayor que la de **Group_0**.  

### **Resultados:**  
- **Estadístico t:** 2.8757 (positivo, porque la media de Group_1 es mayor que la de Group_0).  
- **P-Value:** 0.002019 (menor que 0.05, indicando significancia estadística).  

### **Conclusión:**  
✅ **Se rechaza la hipótesis nula.**  
✅ **Las ventas con recomendación (Group_1) son mayores que las ventas sin recomendación (Group_0).**  
