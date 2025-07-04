Pruebas de API de Urban.Scooter:

1. Probar las siguientes funciones de la API de urban.scooter
-La URL debe estar presente: al acceder, el repartidor o repartidora puede registrarse en la aplicación.

-La URL debe aceptar el nombre de usuario, la contraseña y el nombre del repartidor o repartidora.

-En el inicio de sesión, el hash de la contraseña y el nombre del repartidor o repartidora deben
escribirse en los campos login , passwordHash y firstName de la tabla Couriers Servicio de entrega).

- El campo passwordHash almacena el hash de la contraseña. Se genera mediante funciones estándar, por lo que se puede comprobar la coincidencia hash-contraseña mediante la autorización.

- El campo de inicio de sesión debe ser único.

- Si el registro es exitoso, la entrada correspondiente debe aparecer en la base de datos; si no tiene éxito, se debe devolver un error. 

- Debe haber una URL para iniciar sesión en la cuenta de repartidor o repartidora.

- El nombre de usuario y la contraseña de repartidor o repartidora deben enviarse al iniciar sesión.
  
- Se debe devolver la ID del repartidor o repartidora cuando se haya iniciado sesión correctamente.

- Si el inicio de sesión falla, se debe devolver un error.

- La URL para eliminar la cuenta del repartidor o repartidora debe estar
presente. 

- Al acceder se debe obtener la ID del repartidor o repartidora en la tabla Couriers.

- Al eliminar, los pedidos vinculados en la tabla Orders Pedidos) deben borrarse.

- Debe haber una URL para recuperar los datos del pedido desde su número de seguimiento.

- Se debe obtener un número en el acceso.

- Si se encuentra un pedido que coincida, se deben devolver sus datos; de lo contrario, se
debe devolver un error.

2. Reportar los errores encontrados en Jira.
