# Carreras

## Listado de Entidades

### carreras **(ED)**

- carrera_id **(PK)**
- nombre
- tipo_carrera **(FK)**
- fecha
- tiempo
- mejor_tiempo
- altitud
- lugar
- pais **(FK)**
- foto


### tipos_carreras **(EC)**

- tipo_carrera **(PK)**
- descripcion
- distancia


### Paises **(EC)**

- pais_id **(PK)**
- nombre

## Relaciones

1. Una **carrera** _pertenece_ a un **tipo de carrera** (_1 a 1_)
1. Una **carrera** se _corre_ en un **pais** (_1 a 1_)
