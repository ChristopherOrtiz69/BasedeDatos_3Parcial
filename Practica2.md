# F1


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
- Un campenoato de pilotos puede tener una scuderia (1-1)
- Un campeonato de pilotos puede tener varios Circuitos(1-m)

# Diagrama
![img](https://cdn.discordapp.com/attachments/882327210516701194/1034485013342867496/Diagrama_sin_titulo.jpg)

# Modelo de negocio
## Pilotos
Tomas un piloto 
Puedes ver su Scuderia 
## Circuitos
Tomas el circuito 
Vez el pais que le corresponde 
## Tabla de posiciones 
Tomas el campeonato de pilotos 
Revisas los diferentes pilotos
Puedes ver los diferentes circuitos
Revisas que Scuderias participaron 





