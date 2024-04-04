# Propuesta TP DSW

## Grupo
### Integrantes
* 50739 - Coppari, Sofía Elisa
* 50487 - Dobrovits, Octavio
* 50428 - Chibotta, Santino
* 51175 - García, Ramiro

### Repositorios
* [frontend app](http://hyperlinkToGihubOrGitlab)
* [backend app](http://hyperlinkToGihubOrGitlab)
*Nota*: si utiliza un monorepo indicar un solo link con fullstack app.

## Tema
### Descripción
*Página web full stack para conectar veterinarias con sus respectivos clientes, en donde un usuario se registra y registra a sus mascotas con sus datos e historia clínica, filtra y elige veterinarias según el tipo de mascota, y saca turnos. Por el lado de la veterinaria, esta se registra, registra los turnos y los tipos de mascota que atiende, y actualiza las historias clínicas.*

### Modelo
Modelo de Dominio: <a href="url">https://drive.google.com/file/d/1-QOe2XRFCVDSYApUvm1PXDwjMhxbNh0a/view?usp=sharing</a>.

## Alcance Funcional 

### Alcance Mínimo

*Nota*: el siguiente es un ejemplo para un grupo de 3 integrantes para un sistema de hotel. El 

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Usuario<br>2. CRUD Mascota<br>3. CRUD Veterinaria<br>4. CRUD Turno|
|CRUD dependiente|1. CRUD Historia Clinica {depende de} CRUD Mascota<br>2. CRUD Tipos de Mascota Atendidos {depende de} CRUD Veterinaria|
|Listado<br>+<br>detalle| 1. Listado de veterinarias filtrado por tipo de mascotas atendidas, muestra nombre y domicilio de la veterinaria => detalle CRUD Turno<br> 2. Listado de antecedentes filtrado por rango de fecha, muestra el titulo del antecedente y su fecha => detalle muestra datos completos del antecedente|
|CUU/Epic|1. Reservar un turno para una mascota<br>2. Actualizar historia clínica para una mascota|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Tipo Habitacion<br>2. CRUD Servicio<br>3. CRUD Localidad<br>4. CRUD Provincia<br>5. CRUD Habitación<br>6. CRUD Empleado<br>7. CRUD Cliente|
|CUU/Epic|1. Reservar una habitación para la estadía<br>2. Realizar el check-in de una reserva<br>3. Realizar el check-out y facturación de estadía y servicios|


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados |1. Estadía del día filtrado por fecha muestra, cliente, habitaciones y estado <br>2. Reservas filtradas por cliente muestra datos del cliente y de cada reserve fechas, estado cantidad de habitaciones y huespedes|
|CUU/Epic|1. Consumir servicios<br>2. Cancelación de reserva|
|Otros|1. Envío de recordatorio de reserva por email|

