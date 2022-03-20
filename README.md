
# Alquileres
Aplicación que permite crear, leer, actualizar y eliminar un registro de inquilinos.
**[Accedé acá](https://romeroluciana.github.io/alquileresAPI/)**
**[API](https://mockapi.io/clone/5fada5eb2ec98b001604891c)**



#### Creando la tabla

Consumiendo los datos del endpoint `/users` y usando de referencia la tabla del template se crea una nueva tabla con los datos de la api.

#### Agregar usuarios

Cuando se hace click en el boton `agregar usuario` se abre un modal. Luego de que el usuario lo complete y se haga click en guardar. Se utiliza el endpoint `/users` con el metodo `POST` para guardar los datos. Una vez hecho esto se actualiza la tabla.

#### Actualizar usuarios

Cuando se hace click en el ícono `edicion` sobre la tabla se abre un modal para editar el usuario. Se utiliza el endpoint `/users` con el metodo `PUT` para editar el usuario. Una vez hecho esto se actualiza la tabla.

#### Modificar usuarios

Cuando se hace click en el icono `eliminar` sobre la tabla se abre un modal para eliminar ese usuario. Se utiliza el endpoint `/users` con el método `DELETE` para eliminar el usuario. Una vez hecho esto se actualiza la tabla.
