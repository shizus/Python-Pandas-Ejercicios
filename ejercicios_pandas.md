
# Ejercicios Básicos de Pandas

## 1. Carga y exploración de datos
- Carga el archivo `employees.csv` en un DataFrame de Pandas y muestra las primeras 10 filas.
- ¿Cuántas filas y columnas tiene el DataFrame?

---

## 2. Filtrado de datos
- Filtra los empleados del archivo `employees.csv` que trabajan en el departamento con ID 50.
- Muestra solo las columnas `employee_id`, `first_name`, `last_name`, y `department_id`.

---

## 3. Agrupamiento y resumen
- Usando el archivo `departments.csv`, agrupa los datos por el `location_id` y cuenta cuántos departamentos hay en cada ubicación.

---

## 4. Combinación de DataFrames
- Une los datos de `employees.csv` con los de `departments.csv` utilizando la columna `department_id`.
- Muestra el nombre del empleado junto con el nombre del departamento.

---

## 5. Columnas derivadas
- Usando `job_history.csv`, calcula el tiempo (en días) que cada empleado ha trabajado en sus diferentes posiciones. Agrega una nueva columna llamada `duration_days`.

---

## 6. Datos faltantes
- Identifica si hay valores nulos en el archivo `locations.csv`.
- Si hay valores nulos, rellénalos con un valor por defecto (por ejemplo, "Unknown").

---

## 7. Estadísticas descriptivas
- Utiliza el archivo `jugadores.csv` y calcula:
  - La media y mediana del peso de los jugadores.
  - La desviación estándar de la altura.

---

## 8. Ordenamiento de datos
- Ordena el archivo `jobs.csv` por la columna `min_salary` de mayor a menor.
- Muestra las 5 posiciones con los salarios mínimos más altos.

---

## 9. Filtrado avanzado
- Usando el archivo `countries.csv`, filtra los países que están en la región con ID 1.  
- Muestra solo las columnas `country_name` y `region_id`.

---

## 10. Gráficos básicos
- Usando `regions.csv`, crea un gráfico de barras que muestre el número de países en cada región.  
- Utiliza datos del archivo `countries.csv` para agruparlos por `region_id`.
