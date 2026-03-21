microservicio:

user-service: Se encarga de usuarios, Guardara datos como el nombre y correo.
product-service: Se encarga de productos, guaradara nombre, precio y stock
order-service: reciba la compra, cuando alguien compra este servicio toma el pedido, consulta al usuario, consulta el producto y registra la orden en su propia base de datos.
