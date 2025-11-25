# Herramienta Índice de Calidad de Datos ICD en registros de química de suelos

En este repositorio encontrará toda la información relacionada con la herramienta propuesta, así como los requerimientos para garantizar un funcionamiento adecuado de la aplicación.

# Base de datos

Los datos utilizados en este repositorio pueden ser consultados y descargado en el siguiente link

https://www.datos.gov.co/Agricultura-y-Desarrollo-Rural/Resultados-de-An-lisis-de-Laboratorio-Suelos-en-Co/ch4u-f3i5/about_data

# Notas

  - El código fue desarrollado en un formulario Jupiter (ipynb) para mostrar el paso a paso de la herramienta.
  - El formulario puede ejecutarse desde google colab siguiendo las siguientes instrucciones (recomendado):
    1. Abrir google colab
    2. Ir a Archivo -> Subir Nootbook
    3. Seleccionar la pestaña githube 
    4. pegar en la URL el siguiente link https://github.com/ChenaoB/Herramienta-ndice-de-Calidad-de-Datos-ICD-en-registros-de-qu-mica-de-suelos-/blob/main/Metodo_ICD_Variables_Quimica_Suelo.ipynb 
    5. Seleccionar archivo Metodo_ICD_Variables_Quimica_Suelo.ipynb  
  - Las librería utilizadas fueron de las siguientes versiones:
    1. pandas: 2.2.2
    2. numpy: 2.0.2
    3. matplotlib: 3.10.0
    4. seaborn: 0.13.2
    5. plotly: 5.24.1
    6. requests: 2.32.4
    7. scikit-learn: 1.6.1
  
  # Consideración 
  
  El análisis se realizó para las siguientes columnas de datos químicos del suelo

   1.  ph agua suelo
   2.  materia organica
   3.  fosforo bray ii
   4.  azufre fosfato monocalcico
   5.  calcio intercambiable
   6.  magnesio intercambiable
   7.  potasio intercambiable
   8.  sodio intercambiable
   9.  capacidad de intercambio cationico
   10. conductividad electrica
   11. hierro disponible olsen
   12. cobre disponible
   13. boro disponible

  # Créditos

  Este proyecto fue desarrollado conjuntamente por:

     -Carlos Alberto Henao Baena
     -Paola Yazmín Izquiedo Betancur
     -Yenier Valencia (Ingeniería Smaf S.A.S)

  Como propuesta al reto propuesto por el ministerior de la TIC y Telecomunicaciones
