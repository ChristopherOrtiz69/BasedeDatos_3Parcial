# F1
##  
 - Scuderias(PK)
 - Pilotos 
 - circuitos 
 - Tabla de posiciones
 - Campeonato de pilotos 2022

 # Pilotos
 - Pilotos_id(PK)
 - Nombre
 - Apellido
 - Nacionalidad
 - Campeonatos

  # Scuderias
 - Scuderias_id(PK)
 - Pilotos_id(FK)
 - Fundador
 - Fecha de fundacion
 - Victorias
 - Presidente

# Cicuitos
- Cicuitos_id(Pk)
- Nombre de Circuito
- id_Pais(FK)
- Longitd
- Clima

# Tabla de Posiciones
- Piloto(FK)
- Scuderia(FK)
- Circuito(FK)
- Puntos 

# Pais
- ID_Pais(PK)
- Nombre
- Dominio 