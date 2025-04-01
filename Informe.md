# Informe
Con resumen del trabajo que se ha hecho, he elaborado este informe en dónde presentaré, entre otras cosas:
- El trabajo de tratamiento y limpieza de datos realizado
- La realización del Análisis exploratorio
- Las respuestas a las 7 preguntas realizadas
- Gráficos que soporten las respuestas a las preguntas y recomendaciones

## 1. Descripción del trabajo realizado

Importamos las librerias necesarias y el dataset
- Revisamos la descripción, los nulos, los repetidos
- Eliminamos los duplicados, con un total de 27 registros, y para los datos raros hice varias cosas:
  - En algunos registros se habían invertido los datos de channel y type, y como eran pocos lo hice a mano
  - En otros casos, por el ejemplo el channel "referal" estaba mal escrito con una "r"  y he modificado el registro para que tenga dos "r"
  - Había algunas fechas de Febrero 30 que no existe, y la cambie a Febrero 29 ya que fue año bisiesto ese año 2024
- Para los nulos hice varias cosas:
  - Para practicar intenté rellenar los nulos del budget con el promedio del budget para otros registros para el mismo type y channel
  - El resto de nulos los eliminé, eran unos 15 registros ya que representaban menos del 1% de los datos 
- Hice el casting necesario para fechas, y floats
- Traté los outliers, sobre todo de budget, conversion rate, ROI, y fechas superpuestas y futuras, apenas 3 o 4 registros
- Calculé métricas derivadas como el beneficio neto, el cost per conversion, la clasificacion de campañas en categorias de rendimiento, entre otros, campos estacionales derivados de las fechas como mes, dia, año y cuatrimestre, entre otros.

## 2. Respuestas a las 7 Preguntas

### ¿Qué canal de marketing se utiliza con mayor frecuencia y cuál genera mejor ROI?
- **Respuesta:** Podemos ver que el canal que se utiliza con más frecuencia es "promotion" y el que tiene el mejor ROI es "Referral", que es a su vez el segundo más utilizado
- **Gráfico 1:**  
    _![alt text](image.png)_

### ¿Qué tipo de campaña genera más ingresos en promedio y cuál tiene mejor conversión?
- **Respuesta:**
- **Gráfico 2:**  
    _[Insertar gráfico aquí]_

### ¿Cómo se distribuye el ROI entre las campañas? ¿Qué factores están asociados con un ROI alto?
- **Respuesta:**
- **Gráfico 3:**  
    _[Insertar gráfico aquí]_

### ¿Hay diferencias significativas en la tasa de conversión entre audiencias B2B y B2C?
- **Respuesta:**
- _[Opcional: Agregar gráfico si es necesario]_

### ¿Qué campaña tiene el mayor beneficio neto (net_profit)? ¿Qué características la hacen exitosa?
- **Respuesta:**
- _[Opcional: Agregar gráfico si es necesario]_

### ¿Existe correlación entre el presupuesto (budget) y los ingresos (revenue)?
- **Respuesta:**
- _[Opcional: Agregar gráfico si es necesario]_

### ¿Qué campañas tienen un ROI mayor a 0.5 y ingresos encima de 500,000?
- **Respuesta:**
- _[Opcional: Agregar gráfico si es necesario]_

### ¿Existen patrones estacionales o temporales en el rendimiento de las campañas?
- **Respuesta:**
- _[Opcional: Agregar gráfico si es necesario]_

---

## 3. Notas Adicionales
- Anota aquí cualquier comentario o explicación adicional sobre el análisis y los datos.
