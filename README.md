Este proyecto tiene la finalidad de recoletar distintos achivos de bases de datos de varios clientes donde se estudia:

-Distancia recorrida [Km]
-Estimación de energía consumida [kWh]
-Kgs de C02 abatidos por uso de vehículos eléctricos.
-Promedio de energía consumida por cada Kilómetro recorrido (kWh/Km).
-Promedio de Kilómetros recorridos por kilowatt hora.
-Scoring de manejo (Acá se mide el número de aceleraciones frenadas y bruscas presentadas), dependiendo del número y del umbral, baja el scoring (va de 0 a 100).

Teniendo esta información, la idea es que podamos resolver algunas consultas hipótesis que nos den un valor agregado.
Las consultas iniciales son las siguientes:

1)¿Qué vehículos recorren mayor distancia diaria en promedio? Cuales recorrerán mayor distancia?
2) ¿Qué vehículos tienen un mayor consumo de energía (kWh) por cada kilómetro que recorren?
3)¿Existen modelos iguales pero de diferentes clientes  consumos de combustible (energía) distintos?
4) ¿Existe una relación entre el scoring de manejo vs el consumo de energía de los vehículos?¿Se ve afectado por el mal manejo?
5) ¿Qué cliente abate mayor cantidad de Kgs de CO2 por cada Kilómetro recorrido?¿Qué cliente tendrá tendencia mayor o menor abatimiento de emisiones en el tiempo?
6) ¿Qué cliente tiene y tendrá la peor y mejor scoring de rendimiento en el tiempo si se mantiene como va?
7) ¿Qué cliente comete la mayor y menor cantidad de aceleraciones o frenadas bruscas? 
8)¿Qué cliente comete el mayor y menor umbral de aceleraciones o frenadas bruscas?
