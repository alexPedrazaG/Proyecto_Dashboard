🚗🔋**Exploración de Datos: Tendencias en el Registro de Vehículos Eléctricos**



📖 **Descripción**

Este proyecto realiza un análisis exploratorio sobre el registro de los nuevos vehiculos eléctricos en Estados Unidos. El objetivo es identificar tendencias, patrones y realizar predicciones basadas en estos datos para la introducción de un nuevo modelo de coche al mercado.



🗂️ **Estructura del Proyecto**

├── data/ # Datos crudos

├── README.md # Descripción del proyecto, url del proyecto realizado en google sheet



🛠️ **Instalación y Requisitos**

En este proyecto solo es necesario poder utilizar Google Sheets 

Proyecto Dashboard: https://docs.google.com/spreadsheets/d/1CewdhIerDNzyna_TL89zybb9PlMqdhVI8ep8V7gBkoM/edit?usp=sharing



📝 **EDA**

Partimos de un dataset que recoge todos los nuevos vehículos eléctricos registrados. Este dataset contiene más de 50.000 registros, pero se ha reducido a 10.000 registros para optimizar el rendimiento y evitar que el documento se vuelva demasiado lento. Los datos abarcan desde julio de 2021 hasta junio de 2024. El archivo original se obtuvo del siguiente enlace: http://catalog.data.gov/dataset/electric-vehicle-registration-data

Para el análisis, el archivo fue importado a Google Sheet. Tras una primera revisión de los datos, seconvirtió a  una tabla llamada ‘Table_Vehicle’ y se realizaron los siguientes procesos de limpieza de datos:
    • Eliminación de duplicados a partir de la columna ‘ID’
    • Sustitución de celdas vacias por el valor ‘Desconocido’ en las columnas ‘Primary Customer City’ y ‘Primary Customer State’
    • Modificación del formato fecha de inglés a español en las columnas ‘Registration Start Date’ y ‘Registration Expiration Date’

Al Analizar los datos, se obserrvó que la mayoría de los 10.000 vehiculos registadros pertenecen al estado de Connecticut con un total de 9861 registros. Esta información se puede visualizar en el gráfico de mapa.

Investigando más a fondo, se identificó que Connecticut ofrece diversos incentivos estatales y federales para la compra de vehículos eléctricos, además de contar con una sólida infraestructura de carga.

El gráfico de áreas, muestra la cantidad de vehículos registrados por mes y año. Se destaca que entre julio de 2021 y septiembre de 2022 fue el período con mayor número de ventas, con un repunte significativo en septiembre de 2023.

Para entender la causa de este aumento en septiembre de 2023, se aplicaron filtros por año. Se comprobó que se debió principalmente al incremento en las ventas del Tesla Model Y, un SUV, que en ese año se convirtió en el vehículo más vendido.

El siguiente gráfico, de barras horizontales, muestra las marcas de automóviles con más registros. El Top 3 está compuesto por:
Tesla – 3,955 registros
Toyota – 1,187 registros
Hyundai y Jeep (empate)

En la parte derecha del dashboard, se presentan dos gráficos de barras:
    • El superior muestra los registros por tipo de vehículo, donde los vehículos de pasajeros y los SUV son los más representativos.
    • El inferior refleja los registros según el uso del vehículo, destacando que los coches regulares son los más registrados.

Se han añadido cuatro filtros interactivos:
    • Tipo
    • Modelo de vehículo
    • Color
    • Año de vehículo
Estos filtros permiten identificar tendencias y visualizar patrones que pueden ser clave para la introducción de un nuevo modelo de vehículo eléctrico.



📊 **Resultados y Conclusiones**

Tras analizar el dashboard generado, se han identificado patrones clave que pueden guiar la estrategia para lanzar un nuevo modelo de coche eléctrico en el mercado:

1️⃣ Ubicación estratégica:
Connecticut es el estado ideal para enfocarse en las ventas, ya que concentra la mayoría de los registros de vehículos eléctricos (9.861 de 10.000).
Esto se debe a los incentivos estatales y federales disponibles para la compra de vehículos eléctricos y a su robusta infraestructura de carga.

2️⃣ Tipo de vehículo recomendado:
Se recomienda introducir un modelo SUV o un vehículo de pasajeros, ya que son los tipos más registrados en el estado.
Además, el uso predominante de estos vehículos es regular, por lo que deben adaptarse a necesidades diarias.

3️⃣ Tecnología de propulsión ideal:
Los vehículos más vendidos utilizan tecnologías BEV (Battery Electric Vehicle) o PHEV (Plug-in Hybrid Electric Vehicle).
Esto sugiere que los consumidores buscan opciones completamente eléctricas o híbridas enchufables con mayor autonomía.

4️⃣ Preferencias de color:
Los colores más populares entre los vehículos registrados son:
🔹 Blanco
🔹 Gris
🔹 Negro
🔹 Azul
Esto puede ser clave para definir la oferta cromática del nuevo modelo.



🔄 **Próximos Pasos**

    • Utilizar todos los datos disponibles para afianzar las conclusiones y resultados.
    • Explorar el impacto de factores externos, como campañas de marketing, a través de encuestas.
    • Estar informado sobre las tendencias de incentivos en los estados.
    • Análisis competitivo entre el tipo de vehículo (de pasajeros y SUV) y la tecnología de propulsión (BEV y PHEV).



🤝 **Contribuciones**

Las contribuciones son bienvenidas. Si deseas mejorar el proyecto, por favor
abre un pull request o una issue.



✒️ **Autores**

- Alejandro Pedraza
- [@alexPedrazaG](https://github.com/alexPedrazaG/Proyecto_Dashboard.git)
