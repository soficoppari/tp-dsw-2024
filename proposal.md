# Propuesta TP DSW

## Grupo
### Integrantes
* 50739 - Coppari, Sofía Elisa
* 50487 - Dobrovits, Octavio
* 50428 - Chibotta, Santino
* 51175 - García, Ramiro

### Repositorios
* [backend app](https://github.com/soficoppari/dsw.git)
* [frontend app](https://github.com/soficoppari/frontendTPdsw.git)

## Tema
### Descripción
*Proyecto de aplicación web full stack para la gestión de una veterinaria. La plataforma permite a los clientes registrarse, registrar sus mascotas, reservar turnos con veterinarios, pagar o cancelar consultas, calificar la atención recibida y visualizar los comentarios realizados por el profesional luego de cada consulta. Por otro lado, los veterinarios pueden registrarse, gestionar su disponibilidad definiendo días y horarios de trabajo, consultar los turnos asignados y registrar observaciones o comentarios sobre cada consulta realizada. El sistema busca centralizar y simplificar la gestión de turnos y el seguimiento de la atención médica de las mascotas.*

### Modelo
Modelo de Dominio: <a href="url">[https://drive.google.com/file/d/1-QOe2XRFCVDSYApUvm1PXDwjMhxbNh0a/view?usp=sharing](https://drive.google.com/file/d/1k-A7NpD7EdFRf29Klpk0n8fPWBbAhcqM/view?usp=sharing)</a>.

## Alcance Funcional 

### Alcance Mínimo

*Nota*: Planteo para un grupo de 4 integrantes

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Usuario<br>2. CRUD Especie<br>3. CRUD Veterinario<br>4. CRUD Raza|
|CRUD dependiente|1. CRUD Mascota {depende de} CRUD Usuario, Raza<br>2. CRUD Horario {depende de} CRUD Veterinario|
|Listado<br>+<br>detalle| 1. Listado de veterinarios filtrado por tipo de mascotas atendidas, muestra nombre y domicilio => detalle CRUD Turno<br> 2. Listado de turnos pendientes y atendidos, muestra la fecha del turno, el pago pendiente/ realizado => detalle muestra calificación del turno atendido|
|CUU/Epic|1. Reservar un turno para una mascota<br>2. Cancelar turno para una mascota|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Usuario<br>2. CRUD Especie<br>3. CRUD Veterinario<br>4. CRUD Raza<br>5. CRUD Horario<br>6. CRUD Mascota<br>7. CRUD Calificacion<br>8.CRUD Turno|
|CUU/Epic|1. Reservar un turno para una mascota<br>2.Cancelar turno para una mascota<br>3. Dejar comentario/calificacion al veterinario<br>4. Moderación de comentarios en las calificaciones<br>5. Registrar usuario/ veterinario<br>6.Registrar mascota<br>7.Definir horarios de trabajo (veterinario)<br>8.Pagar turno<br>9.Consultar calificaciones de un veterinario<br>10.Buscar veterinarios disponibles<br>11.Consultar agenda del veterinario<br>12.Registrar observaciones de la consulta<br>13.Consultar turnos del usuario|

### Adicionales
La app cuenta con 5 tests unitarios para usuario, mascota, veterinario, raza y especie; y un test de integración para usuario. Además, fue deployada en su totalidad, a través de Railway (backend) y Netlify (frontend).
