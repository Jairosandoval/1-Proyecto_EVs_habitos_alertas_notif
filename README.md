**Contexto**

Este proyecto tiene informaciòn sobre el rendimiento de los vehìculos elèctricos de varios clientes corporativos. Para esto disponemos de dos tablas con la siguiente informaciòn:

**Df_operations**
Este df me trae la informaciòn diaria de los vehìculos de:
-Fecha
-Operador o cliente.
-Modelo.
-Placa.
-Distancia recorrida (Km).
-Estimaciòn de energìa consumida diaria (kWh).
-Consumo promedio qur tuvo (kWh/Km).

**Df_alerts** 
Este fn me trae la informaciòn sobre las alertas que presentò cada placa, por tipo de notificaciòn y valor (aceleraciòn o frenada brusca, sobre descarga, sobre temperatura, sobre velocidad).

-Fecha.
-Placa.
-Ntf.
-Val

**Motivaciòn**
Teniendo esta informaciòn, lo que nos motiva es poder estudiarla y asì realizar un anàlisis para determinar el rendimiento de los vehìculos y buscar la relaciòn que puede existir entre las alertas que se presentan y si sus consumos tiene relaciòn con ello. Ejemplo: Si vemos que un vehìculo de mìsmo modelo y del mìsmo cliente tiene un consumo kWh/Km mayor que el otro, ¿Puede estar relacionado en que el que tiene mayor consumo realiza màs aceleraciones bruscas o deja sobre descargar la baterìa?. Con este ejemplo y otros, lo que buscamos es llevar una serie de hallazgos y recomendaciones para transmitirselos al cliente y que pueda tomar acciones correctivas que le ayuden a tener un mejor uso del vehìculo y que termine siendo un beneficio econòmico importante.

**Hipòtesis a resolver**

En principio serìa resolver consultas que bajo un anàlisis exploratorio y diagnòstico tendrè las respuestas, pero bajo esa mìsma lìnea, quisiera ver de responder una pregunta bajo un modelo predictivo que me ayude a tener un gran valor agregado. Estas sòn:

**Anàlisis exploratorio-diagnòstico:**

1)¿Qué vehículos recorren mayor/menor distancia diaria en promedio?

2) ¿Qué vehículos tienen un mayor consumo de energía (kWh) por cada kilómetro que recorren?

3)¿Existen modelos iguales pero de diferentes clientes con consumos de combustible (energía) distintos?

4) ¿Existe una relación entre las notificaciones diarias vs el consumo de energía de los vehículos? Se ve afectado?

6) ¿Qué cliente tiene mayor y menor cantidad de vehìculos?
   
8) Què cliente tiene la mayor y menor cantidad de sobre descargas?
   
10) Què cliente tiene la mayor y menor cantidad de sobre temperaturas?

11) ¿Qué cliente comete la mayor y menor cantidad de aceleraciones o frenadas bruscas? 

8)¿Qué cliente comete el mayor y menor umbral de aceleraciones o frenadas bruscas?

9) Que cliente tiene el mayor/menor ratio de ntf/vehìculo?

**Modelo preditctivo:**

1) ¿Cuàl serà el rendimiento de la distancia recorrida por los vehìculos por cliente y modelo?

2) ¿Cuàl serà la proyecciòn de consumo de los vehìculos por modelo por cliente ( alta, baja, etc).

3) ¿Què vehìculos depreciarian mayormente la baterìa de seguir presentando sobre descargas o sobre temperaturas ya evidenciadas?

4) ¿Còmo serà la evoluciòn de notificaciones o alertas por tipo en los vehìculos por cliente?

5) ¿ Què cliente tendrà un mayor gasto operativo a futuro por el consumo promedio diario (kWh/Km).

