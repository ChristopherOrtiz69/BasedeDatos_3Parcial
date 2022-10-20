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
-id_CampeonatodePiloto(pk)
- Piloto(FK)
- Scuderia(FK)
- Circuito(FK)
- Puntos 

# Pais
- ID_Pais(PK)
- Nombre
- Dominio 

# Relaciones
- Una Scuderia puede tener varios pilotos(1-m)
- Un circito puede tener un pais (1-1)
- Un campeonato de pilotos puede tener un piloto(1-1)
- Un campenoato de pilotos puede tener una scuderia (1-1)
- Un campeonato de pilotos puede tener varios Circuitos(1-m)