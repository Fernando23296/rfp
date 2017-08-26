# FACTURACIÓN
### DESCRIPCIÓN

1.- El usuario accede al sistema y selecciona la opción de "Factura".

2.- El sistema despliega la ventana de factura, dicha ventana cuenta con los campos necesarios para la facturación.

3.- El usuario ingresa el CI o NIT del cliente, esto para saber si ya se encuentra en la BDD y de esta manera evitar un doble registro y tambien para ganar tiempo.

4.- En caso de no estar registrado el cliente se procederá a su registro, llenando asi los campos de nombre y CI o NIT para que estos queden registrados en la BDD.

5.- En caso de estar registrado se pasara al proceso de llenar la información de los productos a ser vendidos.

6.- Al finalizar el llenado de información se procedera a la impresión de la factura.

7.- La ventana de facturación tiene como opcion "imprimir" la que accede de manera directa a la impresora.

8.- Al mandar a imprimir la factura el sistema tomará como completada la tarea de facturación, por lo que registrará la factura en la BDD.

9.- Este registro supone una actualización en el stock de productos.

### DIAGRAMA

![factura](https://user-images.githubusercontent.com/22714140/29737892-8c578b5c-89e4-11e7-8ec1-3c439b300b72.png)
