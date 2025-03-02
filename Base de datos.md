La base de datos de Pokeconnect fue hecha en MySQL.
Tiene un total de 6 tablas:
- Entrenador
- Especie
- Region
- Movimiento
- Pokémon
- Posee
### Entrenador
En esta tabla se guardan los usuarios de la aplicación, cada entrenador tiene un nombre, id, contraseña, foto de perfil y Pokémon favorito.

### Especie
En esta tabla se guardan las especies Pokémon, contiene la region a la que pertenecen, que numero en la pokedex es y también de que tipo es. 

### Región
En esta tabla se guarda el nombre de la region, a que generación pertenece y también el numero de Pokémon's que posee 

### Movimiento
En esta tabla se guardan los posibles movimientos que pueden tener los Pokémon's

### Pokémon
En esta tabla se guardan los datos el individuo Pokémon, se puede guardar su nombre, personalidad, estadísticas, a que entrenador le pertenece, es la tabla mas larga pero se busco que fuera lo mas fiel a los videojuegos

### Posee
Esta tabla relaciona los movimientos con los Pokémon's


