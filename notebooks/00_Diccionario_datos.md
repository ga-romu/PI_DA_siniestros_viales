# Diccionario de datos
## Homicidios

### Homicidios_Hechos
variables y definiciones | descripción	
|---|---|
ID	| identificador unico del siniestro	
N_VICTIMAS	 |cantidad de víctimas	
FECHA	|fecha en formato dd/mm/aaaa	
AAAA|	año	
MM	|mes	
DD	|día del mes	
HORA	|hora del siniestro	
HH	|franja horaria entera	
LUGAR_DEL_HECHO	| Dirección del hecho	
TIPO_DE_CALLE	| Tipo de arteria. En el caso de intersecciones a nivel se clasifica según la de mayor jerarquía	
Calle	|nombre de la arteria donde se produjo el hecho	
Altura|	altura de la arteria donde se produjo el hecho	
Cruce	|cruce en caso de que sea una encrucijada	
Dirección Normalizada|	direccion en formato normalizado USIG	
COMUNA|	Comuna de la ciudad (1 a 15)	
XY (CABA)	|geocodificación plana	
pos x|	longitud con separador punto. WGS84	
pos y	|latitud con separador punto. WGS84	
PARTICIPANTES	| conjunción de víctima y acusado	
VICTIMA| 	Vehículo que ocupaba quien haya fallecido a se haya lastimado a raíz del hecho, o bien peatón/a. Clasificación agregada del tipo de vehículos.	
ACUSADO |	Vehículo que ocupaba quien resultó acusado/a del hecho, sin implicar culpabilidad legal	

---
---

Variables |	valores	| descripción
|---|---|---|
TIPO_DE_CALLE	| calle	| Arteria cuya calzada tiene un ancho comprendido entre cinco (5) y trece (13) metros. Inlcluye pasajes.
|  | avenida	| Arteria cuya calzada tiene un ancho total de por lo menos trece (13) metros.|
|  |  autopista| 	Vía multicarril con calzadas para ambas manos separadas físicamente, sin cruces a nivel, con accesos controlados y sin ingreso directo desde los predios frentistas lindantes. Incluye AU 25 de mayo, AU Perito Moreno, AU Dellepiane, Av Lugones, Av. Cantilo, AU Frondizi, AU Buenos Aires - La Plata en el tramo que circula dentro de la Ciudad de Buenos Aires y Paseo del Bajo. Incluye ingresos y egresos de las mismas y distribuidores.| 
|  | general paz	| Avenida General Paz, ambos sentidos. Incluye ingresos y egresos de las mismas, distribuidores y calle colectora.| 
VICTIMA |	PEATON|	Víctima distinta de cualquier ocupante de un vehículo, ya sea un conductor/a o un pasajero/a. Se incluyen los ocupantes o personas que empujan o arrastran un coche de bebé o una silla de ruedas o cualquier otro vehículo sin motor de pequeñas dimensiones. Se incluyen también las personas que caminan empujando una bicicleta o un ciclomotor.
| | MOTO|	Vehículo a motor no carrozado que incluye motocicleta, ciclomotor y cuatriciclo.
| | AUTO |	Vehículo a motor destinado al transporte de personas, diferente de los motovehículos, y que tenga hasta nueve plazas (incluyendo al asiento del conductor) (Sedan, SUV, coupe, etc)
| |   CARGAS| 	Vehículo a motor destiando al transporte de cargas, incluye camiones pesados (con o sin acoplado o semirremolque, etc., camión de recolección de residuos) y livianos (utilitarios, furgonetas, pick-ups, camioneta con caja de carga).
| | BICICLETA |	Vehículo con al menos dos ruedas, que generalmente es accionado por el esfuerzo muscular de las personas que lo ocupan, en particular mediante pedales o manivelas. Incluye bicicletas de pedaleo asistido y/o con motor
| | PASAJEROS |	Personas lesionadas que se encuentran dentro, descendiendo o ascendiendo de las unidades de autotrasporte público de pasajeros/as y ómnibus de larga distancia
| | MOVIL |	Vehículos de emergencia: móviles policiales, ambulancias, autobombas. 
| | OTRO |	otros vehiculos
| | SD	|Sin datos sobre el tipo de víctima
|ACUSADO|	AUTO|	Vehículo a motor destinado al transporte de personas, diferente de los motovehículos, y que tenga hasta nueve plazas (incluyendo al asiento del conductor) (Sedan, SUV, coupe, etc)
| |BICICLETA|	Vehículo con al menos dos ruedas, que generalmente es accionado por el esfuerzo muscular de las personas que lo ocupan, en particular mediante pedales o manivelas. Incluye bicicletas de pedaleo asistido y/o con motor
| | CARGAS	|Vehículo a motor destiando al transporte de cargas, incluye camiones pesados (con o sin acoplado o semirremolque, etc., camión de recolección de residuos) y livianos (utilitarios, furgonetas, pick-ups, camioneta con caja de carga).
| | MOTO |	Vehículo a motor no carrozado que incluye motocicleta, ciclomotor y cuatriciclo.
| | OBJETO FIJO |	Colisión contra objetos inmóviles fijados de manera permanente o semipermanente (columna, árbol, semáforo, etc.) o pérdidas de equilibrio de vehículos de dos ruedas que desencadenen la caída de sus ocupantes.
| | PASAJEROS |	Personas lesionadas que se encuentran dentro, descendiendo o ascendiendo de las unidades de autotrasporte público de pasajeros/as y ómnibus de larga distancia
| |TREN |	Equipo móvil que se desplaza exclusivamente sobre rieles
| | OTRO |otros vehiculos
| | SD	| Sin datos sobre el vehículo participante
| PARTICIPANTES	| MULTIPLE	|cuando participan más de un vehículo como contraparte de la víctima.

### Homicidios_victimas
---
variables y definiciones |	descripción	
|---|---|	
ID_hecho |	identificador unico del siniestro		
FECHA	 |fecha en formato dd/mm/aaaa		
AAAA|	año		
MM	|mes		
DD	|día del mes		
ROL	|Posición relativa al vehículo que presentaba la víctima en el momento del siniestro		
VICTIMA|	Vehículo que ocupaba quien haya fallecido a se haya lastimado a raíz del hecho, o bien peatón/a. Clasificación agregada del tipo de vehículos.		
SEXO|	Sexo informado por fuente policial de la víctima		
EDAD	|Edad de la víctima al momento del siniestro		
FECHA_FALLECIMIENTO	| Fecha de fallecimiento de la víctima	
---
---
Variables |	valores|	descripción	
|---|---|---|
VICTIMA	| PEATON	| Víctima distinta de cualquier ocupante de un vehículo, ya sea un conductor/a o un pasajero/a. Se incluyen los ocupantes o personas que empujan o arrastran un coche de bebé o una silla de ruedas o cualquier otro vehículo sin motor de pequeñas dimensiones. Se incluyen también las personas que caminan empujando una bicicleta o un ciclomotor.	
||MOTO|	Vehículo a motor no carrozado que incluye motocicleta, ciclomotor y cuatriciclo.	
||AUTO|	Vehículo a motor destinado al transporte de personas, diferente de los motovehículos, y que tenga hasta nueve plazas (incluyendo al asiento del conductor) (Sedan, SUV, coupe, etc)	
||CARGAS|	Vehículo a motor destiando al transporte de cargas, incluye camiones pesados (con o sin acoplado o semirremolque, etc., camión de recolección de residuos) y livianos (utilitarios, furgonetas, pick-ups, camioneta con caja de carga).	
||BICICLETA|	Vehículo con al menos dos ruedas, que generalmente es accionado por el esfuerzo muscular de las personas que lo ocupan, en particular mediante pedales o manivelas. Incluye bicicletas de pedaleo asistido y/o con motor	
||PASAJEROS|	Personas lesionadas que se encuentran dentro, descendiendo o ascendiendo de las unidades de autotrasporte público de pasajeros/as y ómnibus de larga distancia	
||MOVIL|	Vehículos de emergencia: móviles policiales, ambulancias, autobombas. 	
||OTRO|	otros vehiculos	
||SD|	Sin datos sobre el tipo de víctima	

## Lesiones


### Lesiones_hechos
variables y definiciones |	descripción
|---|---|
siniestro vial	 |Incidente ocurrido en una vía de acceso público en el que participa al menos un vehículo y que resulta en al menos una persona lesionada o fallecida.
id |	identificador unico del siniestro
n_victimas| cantidad de víctimas
aaaa |	año
mm |	mes
dd|	día del mes
fecha |	fecha en formato dd/mm/aaaa
hora |	hora del siniestro
franja_hora	| franja horaria entera
direccion_normalizada|	direccion en formato normalizado USIG
comuna|	comuna de CABA con jurisdicción según la ubicación
tipo_calle|	Tipo de arteria. En el caso de intersecciones a nivel se clasifica según la de mayor jerarquía
otra_direccion|	direccion en formato alternativo
calle|	nombre de la arteria donde se produjo el hecho
altura|	altura de la arteria donde se produjo el hecho
cruce|	cruce en caso de que sea una encrucijada
geocodificacion_CABA|	geocodificación plana
longitud|	longitud con separador punto. WGS84
latutid|	latitud con separador punto. WGS84
victima	|Vehículo que ocupaba quien haya fallecido a se haya lastimado a raíz del hecho, o bien peatón/a
acusado	|Vehículo que ocupaba quien resultó acusado/a del hecho, sin implicar culpabilidad legal
participantes|	conjunción de víctima y acusado
moto|	participación de algún motovehículo, sea víctima u acusado
auto|	participación de algún automovil, sea víctima u acusado
transporte_publico|	participación de algún vehículo de transporte público de pasajeros, sea víctima u acusado
camion|	participación de algún vehículo de cargas camión, sea víctima u acusado
ciclista|	participación de algún ciclista, sea víctima u acusado
gravedad|	Nivel máximo conocido de gravedad de la lesión de la(s) víctima(s) del siniestro en función del tiempo de hospitalización
---
---
Variables|	valores|	descripción
|---|---|---|
tipo_calle|	calle|	Arteria cuya calzada tiene un ancho comprendido entre cinco (5) y trece (13) metros. Inlcluye pasajes.
||avenida|	Arteria cuya calzada tiene un ancho total de por lo menos trece (13) metros.
||autopista|	Vía multicarril con calzadas para ambas manos separadas físicamente, sin cruces a nivel, con accesos controlados y sin ingreso directo desde los predios frentistas lindantes. Incluye AU 25 de mayo, AU Perito Moreno, AU Dellepiane, Av Lugones, Av. Cantilo, AU Frondizi, AU Buenos Aires - La Plata en el tramo que circula dentro de la Ciudad de Buenos Aires y Paseo del Bajo. Incluye ingresos y egresos de las mismas y distribuidores.
||general paz|	Avenida General Paz, ambos sentidos. Incluye ingresos y egresos de las mismas, distribuidores y calle colectora.
victima|	AUTO|	Vehículo a motor destinado al transporte de personas, diferente de los motovehículos, y que tenga hasta nueve plazas (incluyendo al asiento del conductor) (Sedan, SUV, coupe, etc)
||CAMION|	Vehículo a motor diseñado, exclusiva o principalmente, para el transporte de mercancías que posee una masa máxima autorizada superior a 3.500kg, (con o sin acoplado o semirremolque, etc.), camión de recolección de residuos. 
||UTILITARIO|	Vehículo a motor diseñado, exclusiva o principalmente, para el transporte de mercancías que posee una masa máxima autorizada de hasta 3.500kg, (utilitarios, furgonetas, pick-ups, UTILITARIO con caja de carga) 
||CICLISTA|	Vehículo con al menos dos ruedas, que generalmente es accionado por el esfuerzo muscular de las personas que lo ocupan, en particular mediante pedales o manivelas. Incluye bicicletas de pedaleo asistido y/o con motor
||MIXTO|	más de un tippo de usuario/a de la vía víctima
||MONOPATIN|	Dispositivo de movilidad personal, eléctrico o no
||MOTO|	Vehículo a motor no carrozado que incluye motocicleta, ciclomotor y cuatriciclo.
||MOVIL|	Vehículos de emergencia: móviles policiales, ambulancias, autobombas. 
||PEATON||	Víctima distinta de cualquier ocupante de un vehículo, ya sea un conductor/a o un pasajero/a. Se incluyen los ocupantes o personas que empujan o arrastran un coche de bebé o una silla de ruedas o cualquier otro vehículo sin motor de pequeñas dimensiones. Se incluyen también las personas que caminan empujando una bicicleta o un ciclomotor.
||TAXI|	Automóvil de alquiler no sujeto a itinerario predeterminado, sin tarifa prefijada para el recorrido total, usado por ocupación total del vehículo, que no toma o deja pasajeros con boletos, billetes o pagos individuales.
||TRANSPORTE PUBLICO|	Personas lesionadas que se encuentran dentro, descendiendo o ascendiendo de las unidades de autotrasporte público de pasajeros/as
||OTRO||	otros vehiculos
||SD|	Sin datos sobre el tipo de víctima
acusado	|AUTO|	Vehículo a motor destinado al transporte de personas, diferente de los motovehículos, y que tenga hasta nueve plazas (incluyendo al asiento del conductor) (Sedan, SUV, coupe, etc)
||CAMION|	Vehículo a motor diseñado, exclusiva o principalmente, para el transporte de mercancías que posee una masa máxima autorizada superior a 3.500kg, (con o sin acoplado o semirremolque, etc.), camión de recolección de residuos. 
||UTILITARIO|	Vehículo a motor diseñado, exclusiva o principalmente, para el transporte de mercancías que posee una masa máxima autorizada de hasta 3.500kg, (utilitarios, furgonetas, pick-ups, UTILITARIO con caja de carga) 
||CICLISTA|	Vehículo con al menos dos ruedas, que generalmente es accionado por el esfuerzo muscular de las personas que lo ocupan, en particular mediante pedales o manivelas. Incluye bicicletas de pedaleo asistido y/o con motor
||MONOPATIN	Dispositivo de movilidad personal, eléctrico o no
||MOTO|	Vehículo a motor no carrozado que incluye motocicleta, ciclomotor y cuatriciclo.
||MOVIL|	Vehículos de emergencia: móviles policiales, ambulancias, autobombas. 
||OBJETO FIJO|	Colisión contra objetos inmóviles fijados de manera permanente o semipermanente (columna, árbol, semáforo, etc.) o pérdidas de equilibrio de vehículos de dos ruedas que desencadenen la caída de sus ocupantes.
||SD|	Sin datos sobre el vehículo participante
||TAXI|	Automóvil de alquiler no sujeto a itinerario predeterminado, sin tarifa prefijada para el recorrido total, usado por ocupación total del vehículo, que no toma o deja pasajeros con boletos, billetes o pagos individuales.
||TRANSPORTE PUBLICO|	Vehículo a motor destinado al transporte de personas que tenga más de nueve plazas (incluyendo al asiento de quien conduce). Incluye colectivos, microómnibus y ómnibus de corta y larga distancia
|Gravedad|	leve|	Toda persona que requiere una atención médica mínima o nula (como esguinces, hematomas, heridas superficiales y rasguños) o cuya hospitalización exige menos de 24 hs de permanencia en un nosocomio.
||grave|	Toda persona que cuya lesión exige la hospitalización de al menos 24 hs o una atención especializada, como fracturas, conmoción, shock grave y laceraciones importantes.
||fatal|	Víctima que fallece dentro de los 30 días de producido el siniestro vial por causas directa o indirectamente atribuibles al hecho.
||sd|	Sin datos sobre la gravedad de las lesiones provocadas. A efectos analíticos, los casos sin datos se corresponden con una alta probabilidad a casos leves.
    
### Lesiones_victimas

variables y definiciones|	descripción	
|---|---|
ID hecho| identificador unico del siniestro	
AÑO|	año	
MES| mes	
DIA	| día del mes	
FECHA |	fecha en formato dd/mm/aaaa	
VEHICULO_VICTIMA |	Vehículo que ocupaba quien haya fallecido a se haya lastimado a raíz del hecho, o bien peatón/a	
SEXO|	Sexo de la víctima según registro policial	
EDAD_VICTIMA|	Edad en años enterios de la víctima en registro policial	
GRAVEDAD|	Nivel máximo conocido de gravedad de la lesión de la víctima del siniestro en función del tiempo de hospitalización	
---
---
Variables	|valores	|descripción
|---|---|---|
VEHICULO_VICTIMA|	AUTO|	Vehículo a motor destinado al transporte de personas, diferente de los motovehículos, y que tenga hasta nueve plazas (incluyendo al asiento del conductor) (Sedan, SUV, coupe, etc)
||CAMION|	Vehículo a motor diseñado, exclusiva o principalmente, para el transporte de mercancías que posee una masa máxima autorizada superior a 3.500kg, (con o sin acoplado o semirremolque, etc.), camión de recolección de residuos. 
||UTILITARIO|	Vehículo a motor diseñado, exclusiva o principalmente, para el transporte de mercancías que posee una masa máxima autorizada de hasta 3.500kg, (utilitarios, furgonetas, pick-ups, UTILITARIO con caja de carga) 
||CICLISTA|	Vehículo con al menos dos ruedas, que generalmente es accionado por el esfuerzo muscular de las personas que lo ocupan, en particular mediante pedales o manivelas. Incluye bicicletas de pedaleo asistido y/o con motor
||MIXTO|	más de un tippo de usuario/a de la vía víctima
||MONOPATIN|	Dispositivo de movilidad personal, eléctrico o no
||MOTO|	Vehículo a motor no carrozado que incluye motocicleta, ciclomotor y cuatriciclo.
||MOVIL|	Vehículos de emergencia: móviles policiales, ambulancias, autobombas. 
||PEATON|	Víctima distinta de cualquier ocupante de un vehículo, ya sea un conductor/a o un pasajero/a. Se incluyen los ocupantes o personas que empujan o arrastran un coche de bebé o una silla de ruedas o cualquier otro vehículo sin motor de pequeñas dimensiones. Se incluyen también las personas que caminan empujando una bicicleta o un ciclomotor.
||TAXI|	Automóvil de alquiler no sujeto a itinerario predeterminado, sin tarifa prefijada para el recorrido total, usado por ocupación total del vehículo, que no toma o deja pasajeros con boletos, billetes o pagos individuales.
||TRANSPORTE PUBLICO|	Personas lesionadas que se encuentran dentro, descendiendo o ascendiendo de las unidades de autotrasporte público de pasajeros/as
||OTRO|	otros vehiculos
||SD|	Sin datos sobre el tipo de víctima
|Gravedad|	leve	Toda persona que requiere una atención médica mínima o nula (como esguinces, hematomas, heridas superficiales y rasguños) o cuya hospitalización exige menos de 24 hs de permanencia en un nosocomio.
||grave|	Toda persona que cuya lesión exige la hospitalización de al menos 24 hs o una atención especializada, como fracturas, conmoción, shock grave y laceraciones importantes.
||fatal|	Víctima que fallece dentro de los 30 días de producido el siniestro vial por causas directa o indirectamente atribuibles al hecho.
||sd|	Sin datos sobre la gravedad de las lesiones provocadas. A efectos analíticos, los casos sin datos se corresponden con una alta probabilidad a casos leves.

