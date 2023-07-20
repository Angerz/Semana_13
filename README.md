# PROGRAMA DE ANÁLISIS DE CADENAS

Este proyecto realiza el análisis de cadenas utilizando datos de entrada proporcionados por el usuario y tablas de referencia. Contiene diferentes archivos y funcionalidades para facilitar el proceso de cálculo y selección. Además, permite guardar los resultados en un archivo Excel.

## Archivos del Proyecto

- `tablas.py`: Este archivo contiene las tablas requeridas para el cálculo y selección de las cadenas. Las tablas están organizadas en listas de diccionarios.

- `main.py`: Este archivo contiene el código principal del programa, donde se definen todas las funciones para realizar los cálculos y la selección de la cadena. También muestra los resultados en la terminal y permite guardar los datos en un archivo Excel.

## Uso del Programa

1. Asegúrate de tener Python 3.x y las librerías necesarias instaladas en tu sistema.
2. Ejecuta el programa desde la terminal o el IDE de tu preferencia.
3. Ingresa los siguientes parámetros cuando se te soliciten:
   - Potencia nominal (HP)
   - Factor de diseño RPM (Revoluciones por minuto)
   - Tipo de par de torsión: elige entre "Par de torsión normal" o "Par de torsión alto o no uniforme".
   - Número de dientes de la catarina impulsora
   - Número de dientes de la catarina impulsada
   - Distancia de centro de pasos (Cp)
4. El programa calculará la longitud de paso, la longitud de la correa y la distancia entre centros.
5. Luego, podrás seleccionar el tipo de maquinaria impulsada (Uniforme, Impacto ligero, Impacto medio o Impacto pesado) para obtener el factor de servicio Ks.
6. Después, el programa buscará en las tablas correspondientes para determinar la cantidad de hileras y el tipo de faja adecuado para los parámetros ingresados.
7. Podrás visualizar una tabla con los resultados obtenidos y elegir una opción de faja específica para obtener sus características adicionales.
8. Una vez completado el proceso, tendrás la opción de realizar otro cálculo o finalizar el programa.

## Requisitos del Sistema

- Python 3.9
- NumPy
- Openpyxl

## Contribuciones

Las contribuciones son bienvenidas. Si deseas mejorar o agregar funcionalidades al programa, puedes realizar un fork del repositorio, realizar los cambios en tu propio repositorio y luego enviar un pull request para revisar y fusionar los cambios.

## Licencia

Este programa se encuentra bajo la licencia MIT.
