# Homicidios y lesiones por siniestros viales en la Ciudad Autónoma de Buenos Aires, Argentina.  

## Introducción

Este proyecto simula el rol de un analista de datos trabajando en un estudio para el **Observatorios de Movilidad y Seguridad Vial (OMSV)**. El estudio pretende generar nueva información que permita a las autoridades locales tomar medidas para disminuir el numero de victimas, fatales o no, de siniestros viales ocurridos en CABA. Para ello, se utilizan los datos de [Siniestros Viales](https://data.buenosaires.gob.ar/dataset/victimas-siniestros-viales), disponibles e el portal Buenos Aires Data. Los datos proporcionados contienen informacion recolectada en el periodo 2016-2021 para Homicidios, y 2019-2021 para Lesiones. 

Como producto final, se espera un tablero interactivo que facilite la intepretación y análisis de la información, acompañado de reporte de las tareas realizadas, las metodologias adoptadas y las principales conclusiones obtenidas.

## Contexto

## Datos 

Este proyecto trabajó con la base de datos **Siniestros Viales**, la cual contiene dos archivos Excel:  
* **Homicidios** : Información sobre homicidios en siniestros viales ocurridos en la Ciudad desde el año 2016 hasta el 2021. Los datos incluyen fecha y ubicación del hecho y tipo de transporte involucrado.

* **Lesiones** : Información sobre las lesiones en siniestros viales ocurridos en la Ciudad desde el año 2019 hasta el 2021. Los datos incluyen fecha y ubicación del hecho y tipo de transporte involucrado.

Cada archivo contiene dos pestañas: 
* **HECHOS**: que contiene una fila de hecho con id único y las variables temporales, espaciales y participantes asociadas al mismo.
* **VICTIMAS**: contiene una fila por cada víctima de los hechos y las variables edad, sexo y modo de desplazamiento asociadas a cada víctima. Se vincula a los HECHOS mediante el id del hecho.

## Tecnologías utilizadas
Para la elaboración de este reporte se utiliz-o Python y Pandas para los procesos de extracción, transformación y carga de los datos,