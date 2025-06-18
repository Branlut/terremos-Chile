# terremos-Chile

# Contexto
Acerca del dataset
Los datos utilizados para crear este conjunto de datos se obtuvieron de la base de datos del Centro Sismológico Nacional, que contiene información sobre terremotos significativos (perceptibles) en Chile.

Chile es un país famoso por su alta actividad sísmica. De hecho, es uno de los lugares más sísmicos del mundo, lo que lo convierte en un lugar de interés para muchos investigadores que investigan este tema.

Este conjunto de datos esta compuesto por las siguientes columnas:

Fecha (UTC): Fecha de registro del terremoto (precisión de hasta 1 segundo).
Latitud/Longitud: Ubicación del terremoto.
Profundidad: Profundidad (medida en km) del terremoto.
Magnitud: Magnitud del terremoto.

# Tecnologias
- Python
- Pandas
- seaborn
- matplotlib
- plotly express

# Hallazgos
- El dataframe cuenta con 4018 entredas y 5 columnas.
- La columna Date(UTC) esta con formato object y esta se transformo a tipo datetime para un mejor análisis
- no se encontraron valores nulos
- Se encontraron 3 registros duplicados por lo que al ser minimos se eliminaron para una mejor consistencia de los datos
- La mayor cantidad de temblores fueron de una magnitud de 4 lo se designo como baja en cuanto a intensidad.
- Por su parte hay mas temblores catalogados como medios es decir superior a 4 pero menor a 6.
- la maginitud mas baja registrada dentro del dataframe fue de 2.3 y las mas alta de 8.4
- Los temblores catalogados como medios fueron disminuyendo a partir del 2015
- Los temblores catalogados como bajos fueron aumentando a partir del 2016 con el leve descenso en los ultimos años
- Los temblores catalogados como altos fueron aumentando a partir del 2016 pero son muy poco frecuentes
- La mayor concentracion de temblores estan entre la region de Coquimbo y Tarapaca
- El terremoto de mayor maginitud fue el de 2015 serca de Illapel 
- La profundidad no tiene una relación fuerte con la magnitud del temblor por lo que un temblor puede tener una mayor profundidad pero con una magnitud menor o al contrario
- Para un análisis en mas profundidad se necesitaria mas caracteristicas del las que posee el dataframe, como la distancia a la falla tectónica más cercana, historial de magnitudes por zona, tipo de suelo, etc
- En promedio la profundad de los sismos esta entre 100 km lo que se mantiene constante a lo largo del tiempo
  
