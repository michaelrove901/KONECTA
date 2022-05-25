# KONECTA
Prueba tecnia empresa KONECTA

El Proyecto se realizo utilizando Spring Boot con base de datos MySQL cumple con todos los requerimientos solicitados
la URL inicial donde se ejecuta el programa es http://localhost:8080/listar 
Se adjunta la estructura de la base de datos en el archivo cafeteria.sql

Consultas

SELECT MAX(stock) as Stock,id_producto as IdProductoConMayorStock ,nombre as NombreProducto FROM `producto`;

SELECT MAX(cantidad) as Cantidad,id_producto as IdProductoMasVendido FROM `venta`;
