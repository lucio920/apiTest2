Api de libros

__OBTENER TODOS LOS LIBROS__
GET http://localhost:3000/books HTTP/1.1


__OBTENER LIBROS POR ID__
GET http://localhost:3000/books/id HTTP/1.1


__NUEVO LIBRO__
POST http://localhost:3000/books HTTP/1.1
Content-Type: application/json


__MODIFICAR LIBROS POR ID__
PUT http://localhost:3000/books/id HTTP/1.1
Content-Type: application/json


__ELIMINAR LIBROS POR ID__
DELETE http://localhost:3000/books/id HTTP/1.1