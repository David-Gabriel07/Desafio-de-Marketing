# Informe
Con resumen del trabajo que se ha hecho, he elaborado este informe en dónde presentaré, entre otras cosas:
- El trabajo de tratamiento y limpieza de datos realizado
- La realización del Análisis exploratorio
- Las respuestas a las 7 preguntas realizadas
- Gráficos que soporten las respuestas a las preguntas y recomendaciones

## 1. Descripción del trabajo realizado


## 1. Filas Eliminadas
Importamos las librerias necesarias y el dataset
- Revisamos la descripción, los nulos, los repetidos
- Eliminamos los duplicados, con un total de 27, y para los datos raros hice varias cosas:
-- En algunos registros se habían invertido los datos de channel y type, y como eran pocos lo hice a mano
-- En otros casos, por el ejemplo el channel "referal" estaba mal escrito con una "r"  y he modificado el registro para que tenga dos "r"
-- Había algunas fechas de Febrero 30 que no existe, y la cambie a Febrero 29 ya que fue año bisiesto ese año 2024
- Para los nulos hice varias cosas:
-- Para practicar intenté rellenar los nulos del budget con el promedio del budget para otros registros para el mismo type y channel
-- El resto de nulos los eliminé, eran unos 15 registros ya que representaban menos del 15 de los datos 
- Hice el casting necesario para fechas, y floats
- Traté los outliers, sobre todo de budget, conversion rate, ROI, y fechas superpuestas y futuras, apenas 3 o 4 registros
- Calculé métricas derivadas
- **Filas repetidas removidas:** 
- **Filas con valores extraños removidos:** 
- **Total de filas removidas:** 

- Importamos las librerias necesarias y el dataset
- Revisamos la descripción, los nulos, los repetidos
- Eliminamos los duplicados, con un total de 27, y para los datos raros hice varias cosas:
-- En algunos registros se habían invertido los datos de channel y type, y como eran pocos lo hice a mano
-- En otros casos, por el ejemplo el channel "referal" estaba mal escrito con una "r"  y he modificado el registro para que tenga dos "r"
-- Había algunas fechas de Febrero 30 que no existe, y la cambie a Febrero 29 ya que fue año bisiesto ese año 2024
- Para los nulos hice varias cosas:
-- Para practicar intenté rellenar los nulos del budget con el promedio del budget para otros registros para el mismo type y channel
-- El resto de nulos los eliminé, eran unos 15 registros ya que representaban menos del 15 de los datos 
- Hice el casting necesario para fechas, y floats
- Traté los outliers, sobre todo de budget, conversion rate, ROI, y fechas superpuestas y futuras, apenas 3 o 4 registros
- Calculé métricas derivadas

## 2. Respuestas a las 7 Preguntas

### Pregunta 1
- **Respuesta:**
- **Gráfico 1:**  
    _[Insertar gráfico aquí]_

### Pregunta 2
- **Respuesta:**
- **Gráfico 2:**  
    _[Insertar gráfico aquí]_

### Pregunta 3
- **Respuesta:**
- **Gráfico 3:**  
    _[Insertar gráfico aquí]_

### Pregunta 4
- **Respuesta:**
- _[Opcional: Agregar gráfico si es necesario]_

### Pregunta 5
- **Respuesta:**
- _[Opcional: Agregar gráfico si es necesario]_

### Pregunta 6
- **Respuesta:**
- _[Opcional: Agregar gráfico si es necesario]_

### Pregunta 7
- **Respuesta:**
- _[Opcional: Agregar gráfico si es necesario]_

---

## 3. Notas Adicionales
- Anota aquí cualquier comentario o explicación adicional sobre el análisis y los datos.
