# Propuesta TP DSW

## Grupo
### Integrantes
* 50739 - Coppari, Sofía Elisa
* 50487 - Dobrovits, Octavio
* 50428 - Chibotta, Santino
* 51175 - García, Ramiro

### Repositorios
* [backend app](https://github.com/soficoppari/backendTPdsw.git)
* [frontend app](https://github.com/soficoppari/frontendTPdsw.git)

## Tema
### Descripción
*Página web full stack para conectar veterinarias con sus respectivos clientes, en donde un usuario se registra y registra a sus mascotas con sus datos e historia clínica, filtra y elige veterinarias según el tipo de mascota, y saca turnos. Por el lado de la veterinaria, esta se registra, registra los turnos y los tipos de mascota que atiende, y actualiza las historias clínicas.*

### Modelo
Modelo de Dominio: <a href="url">https://drive.google.com/file/d/1-QOe2XRFCVDSYApUvm1PXDwjMhxbNh0a/view?usp=sharing</a>.

## Alcance Funcional 

### Alcance Mínimo

*Nota*: Planteo para un grupo de 4 integrantes

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Usuario<br>2. CRUD Mascota<br>3. CRUD Veterinaria<br>4. CRUD Turno|
|CRUD dependiente|1. CRUD Historia Clinica {depende de} CRUD Mascota<br>2. CRUD Tipos de Mascota Atendidos {depende de} CRUD Veterinaria|
|Listado<br>+<br>detalle| 1. Listado de veterinarias filtrado por tipo de mascotas atendidas, muestra nombre y domicilio de la veterinaria => detalle CRUD Turno<br> 2. Listado de antecedentes filtrado por rango de fecha, muestra el titulo del antecedente y su fecha => detalle muestra datos completos del antecedente|
|CUU/Epic|1. Reservar un turno para una mascota<br>2. Registrar usuario|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Usuario<br>2. CRUD Mascota<br>3. CRUD Veterinaria<br>4. CRUD Turno<br>5. CRUD Historia Clínica<br>6. CRUD Tipos de Mascota Atendidos<br>7. CRUD Comentarios/Calificaciones|
|CUU/Epic|1. Reservar un turno para una mascota<br>2. Registrar usuario<br>3. Registrar veterinaria|


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.
 _
