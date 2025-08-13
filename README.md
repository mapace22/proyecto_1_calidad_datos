# proyecto_1_calidad_datos
Limpieza, preparación y estandarización de datos para Store 1  | Python - Jupyter Notebook

# Proyecto: Limpieza y Preparación de Datos de Clientes

## Descripción del Proyecto
Este proyecto forma parte de un proceso de análisis de datos para "Store 1", con el objetivo principal de evaluar la calidad de una muestra de datos de clientes y prepararlos para su posterior análisis. El trabajo se centró en la limpieza, transformación y estandarización de los datos para garantizar su coherencia y utilidad.

## Objetivos del Análisis
- Identificar y corregir problemas de formato y tipo de datos en la información de los usuarios.
- Estandarizar los nombres de usuario, las edades y las categorías de productos.
- Aplicar técnicas de manejo de errores para garantizar la robustez del código.
- Demostrar habilidades básicas de manipulación de datos con Python.

## Tecnologías Utilizadas
- **Python**: El lenguaje de programación principal para el análisis.
- **Métodos de Cadenas**: `strip()`, `replace()`, `split()`.
- **Manejo de Errores**: Bloques `try-except`.
- **Estructuras de Datos**: Listas y sus métodos asociados (`.sort()`, `len()`, `min()`, `max()`, `sum()`).
- **F-strings**: Para la creación de cadenas de texto formateadas.

## Pasos Clave del Análisis
1. **Evaluación de la Calidad de los Datos**: Se revisaron las variables `user_id`, `user_name`, `user_age` y `fav_categories` para identificar inconsistencias como espacios en blanco, tipos de datos incorrectos y errores de capitalización.

2. **Limpieza y Normalización**:
   - Se eliminaron los espacios innecesarios y los guiones bajos de los nombres de usuario.
   - Se corrigió el tipo de dato de la edad de flotante a entero.
   - Se convirtieron todas las categorías de productos a minúsculas para estandarizar los datos.

3. **Procesamiento Avanzado**:
   - Se implementó un bloque `try-except` para manejar posibles errores al convertir la edad, garantizando que el programa no se detenga.
   - Se utilizó un bucle (`for loop`) para aplicar de manera eficiente todas las correcciones a una lista completa de usuarios, demostrando la capacidad de automatización.

4. **Resumen de Datos**: Se calcularon métricas clave como el gasto total, mínimo y máximo por usuario, y se generaron mensajes personalizados para resumir la información de los clientes.

## Conclusiones
Este proyecto demostró un manejo sólido de las bases de la limpieza de datos en Python. Las técnicas aplicadas garantizan la integridad de la información, permitiendo que el equipo de análisis de "Store 1" pueda proceder con confianza a realizar un análisis de datos más profundo y generar insights de negocio.
