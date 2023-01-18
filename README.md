# MongoDB

Utilizando Mongo Shell, crear una base de datos llamada ecommerce que contenga dos colecciones: mensajes y productos.

- Agregar 10 documentos con valores distintos a las colecciones mensajes y productos.
- Definir las claves de los documentos en relación a los campos de las tablas de esa base. En el caso de los productos, poner valores al campo precio entre los 100 y 5000 pesos(eligiendo valores intermedios, ej: 120, 580, 900, 1280, 1700, 2300, 2860, 3350, 4320, 4990).
- Listar todos los documentos en cada colección.
- Mostrar la cantidad de documentos almacenados en cada una de ellas.
- Agregar un producto más en la colección de productos.
- Listar los productos con precio menor a 1000 pesos.
- Listar los productos con precio entre los 1000 a 3000 pesos.
- Listar los productos con precio mayor a 3000 pesos.
- Realizar una consulta que traiga sólo el nombre del tercer producto más barato.
- Hacer una actualización sobre todos los productos, agregando el campo stock a todos ellos con un valor de 100.
- Cambiar el stock a cero de los productos con precios mayores a 4000 pesos.
- Borrar los productos con precio menor a 1000 pesos.

## Consideraciones

Los productos tendrán el siguiente formato:

```json
{
  "name": "Escuadra",
  "price": 120,
  "thumbnail": "https://cdn3.iconfinder.com/data/icons/education-209/64/ruler-triangle-stationary-school-256.png"
}
```

Los mensajes tendrán el siguiente formato:

```json
{
  "email": "a@a.com",
  "message": "Hola",
  "date": "18/1/2023, 01:20:39"
}
```
