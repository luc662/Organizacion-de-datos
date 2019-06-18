# Organizacion-de-datos
repositorio para los tp de organiozacion de datos.
Informe:https://www.overleaf.com/read/xqrzdvvpcchv
Para editar:https://www.overleaf.com/6254911486spycqyqxmhcr
Features para TP2:
  Esta seccion dejamos anotado los features implementados hasta el momento para el tp2, asi es mas facil organizarnos
  Auctions:
    mean_hour: para modelos probabilisticos
    std_hour: Idem.
    contador: cuantas veces aparecio una persona en las subastas hasta la fecha.
    Surce_id[0-9]: aplicacion de one hot encoding a la columna de Source id, luego, se cuentan para cada usuario, cuantas veces aparecio en     cada source.
    
  CLicks:
      time_to_click_min: Tiempo minimo que tardo la persona en hacer click
       time_to_click_max: Tiempo maximo que tardo la persona en hacer click
       mean_time_to_click:promedio de time to click
       std_time_to_click: variaza de tiempo para clicks.
       mean_longitude: promedio de la longitud donde se realizo los clicks
       std_longitude: varianza  de la longitud.
       mean_latitude: promedio de la latitud.
       std_loatitude: varianza de la latitud.
       wifi_connection: se separan en dos columnas, una con true y otra con false, luego se suman.
       
       
   Events:
   
        attributed:se expande a true o false, para contarse.
        eventos_utiles: dice si un evento tiene un id igual a alguno de los atribuidos. se debe expandir.
        ciudades_distintas_ingresadas: CUenta cuantas ciudades distintas ingreso una persona.
        contador_aplicaciones:idem, pero para aplicaciones.
        ciudad_mas_visitada:Muestra la ciudad mas visitada por un usuario en un momento dado.
        aplicacion_mas_visitada: parecido, pero para aplicacion.
        
        
        
        faltan agregar un par..
