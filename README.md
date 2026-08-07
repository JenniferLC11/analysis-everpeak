# telecom-analysis

El objetivo del análisis de la empresa de Telecomunicaciones ConnectaTel, con operación en México y Colombia, es realizar un reporte con el fin de entender el uso que los clientes le dan a los servicios móviles (llamadas y mensajes), identificando patrones de uso, detectando posibles comportamientos atípicos y segmentando a los clientes para mejorar la experiencia del usuario.

Para esto se cuenta con tres fuentes de datos:
•	plans.csv: los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra).

•	users_latam.csv: información de clientes: edad, ciudad, fecha de registro, plan contratado.

•	usage.csv: el detalle de uso real: llamadas (duración) y mensajes (longitud).

A lo largo del proyecto se realizan las siguientes etapas:
1.	Cargar y explorar los datos: Se revisa la estructura de las bases de datos, identificando tipo de datos y valores inconsistentes o nulos.
2.	Evaluar la calidad de los datos: Revisión de valores nulos e inconsistentes, estandarización de formatos y posibles valores futuros.
3.	Limpieza de datos: Corrección de valores inconsistentes y fechas imposibles.
4.	Agrupación por comportamiento de usuario: Resumen estadístico por usuario durante el 2024.
5.	Visualizaciones: Identificación de distribución y visualización de valores atípicos por servicio.
6.	Segmentación de Clientes: Por Nivel de Uso y Clientes (Edad).
7.	Resumen ejecutivo para Stakeholders: Principales hallazgos y conclusiones accionables para ConnectaTel.

Para la ejecución del notebook en Google Colab, se debe abrir Google Colab, dar clic en Nuevo Cuaderno, Archivo, seleccionar Abrir Cuaderno, en la opción Buscar Cuaderno agregar JenniferLC11 y seleccionar telecom-analysis.

Para reproducir el análisis, se debe dar clic en cada uno de los signos Play que aparecen en los diferentes códigos, teniendo en cuenta el orden del mismo, con el fin de no afectar la ejecución.
