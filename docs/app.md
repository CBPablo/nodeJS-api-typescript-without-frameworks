# POADCAST MANAGER


### DESCRIÇÃO  
Um app ao estilo Netflix, aonde eu possa centralizar diferentes epiósdios 
de poadcast, separados por categoria.

### DOMÍNIO 
Poadcasts feitos em vídeo.

### FEATURES 
 - Listar poadcasts em sessões de categoria.
   - [Saúde, Fitnes, Mentalidade, Humor]
 - Filtrar episódios por nome de poadcasts.  

 ## COMO

 #### FEATURE 
 - Listar episódios de poadcasts em sessões de categorias
 
 ### COMO VOU IMPLEMENTAR 
 Vou retornar em uma API Rest(json) o nome do poadcast, o nnome do episódio e 
 a imagem de capa ,link, categoria.   
```
[ 
{
poadcastName: "flow",
episode: "CBUM - Flow #319",
videoId:"pQSuQmUfS30",
cover:"https://i.ytimg.com/vi/pQSuQmUfS30/maxresdefault.jpg",
link:"https://www.youtube.com/watch?v=pQSuQmUfS30",
categores:["sport","health", "bodybuilding"],
},
{
poadcastName: "flow",
episode: "RUBENS BARRICHELLO - Flow #339",
videoId:"4KDGTdiOV4I",
cover:"https://i.ytimg.com/vi/4KDGTdiOV4I/maxresdefault.jpg",
link:"https://www.youtube.com/watch?v=4KDGTdiOV4I",
categores:["sport", "motorsport"],
},
]

```