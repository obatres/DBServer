# DBServer

# Crear cliente

## Tipo de request: POST

### Ruta

> 34.122.140.150:5001/mongodb

### Body

**Json**

> ```
> {
>   "database": "ERP",
>   "collection": "Clientes",
>   "Document": {
>     "Nombre": "Orlando Batres",
>     "Cargo": "Developer"
>   }
> }
> ```

# Obtener todos los clientes

## Tipo de request: GET

### Ruta

> 34.122.140.150:5001/mongodb

### Body

**Json**

> ```
> {
>   "database": "ERP",
>   "collection": "Clientes"
> }
> ```

# Eliminar clientes

## Tipo de request: DELETE

### Ruta

> 34.122.140.150:5001/mongodb

### Body

**Json**

> ```
> {
>   "database": "ERP",
>   "collection": "Clientes",
>   "Filter": {
>     "Nombre": "Orlando Batres"
>   }
> }
> ```

# Actualizar clientes

## Tipo de request: PUT

### Ruta

> 34.122.140.150:5001/mongodb

### Body

**Json**

> ```
> {
>   "database": "ERP",
>   "collection": "Clientes",
>   "Filter": {
>     "Nombre": "Orlando Batres"
>   },
>   "DataToBeUpdated": {
>     "Cargo": "PM",
>     "Edad": 27
>   }
> }
> ```
