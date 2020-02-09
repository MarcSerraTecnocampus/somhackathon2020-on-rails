# On Rails

On Rails és una plataforma open source que permite acceder a datos creados sobre usuarios acerca de sus actividades:
 - Salut
 - Bienestar social
 - Formación
 - Ocio

## Modulos de la API:

### REST Api:
La aplicación REST genera respuestas a peticiones web mediante objeto JSON.

Lista de peticiones:
```http
get 'test/:id', to: 'main#test'
get 'associations/:name/:email/:phone', to: 'main#new_association'
get '/token', to: 'main#header_test'
get '/user', to: 'main#my_user'
get '/user/all', to: 'main#user_all'
get '/user/friends', to: 'main#get_my_friends'
get '/user/achievements', to: 'main#user_achievements'
get '/user/:user_id', to: 'main#get_user'
get '/user/friends/:user_id', to: 'main#get_user_friends'
get '/event', to: 'main#get_events_by_distance'
get '/reverse', to: 'main#reverse'
post '/login', to: 'login#login'
post '/register', to: 'login#register'
```
GIT de Backend [https://github.com/SomHackathon2020/onrails-be]()

 ### OSRM Api:
OSRM (Open Source Routing Machine) és una API REST opensource que permite crear y obtener rutas y localizaciones mediante coordenadas geográficas. Nuestra plataforma utiliza OSRM para poder generar rutas y ubicaciones reales de eventos generados.
Para información más detallada de OSRM: [http://project-osrm.org/docs/v5.22.0/api/#general-options]()

### ADMINER
Adminer és otra API REST que permite a los usuarios acceder a datos opensource obtenidos mediante Bases de Datos abiertos. 
HACKATHON ([https://github.com/SomHackathon2020/material/blob/master/informacioInteressant.md]())




It's a gem.
