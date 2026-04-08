# Propuesta TP DSW

## Grupo
### Integrantes
* 53260 - Lavatti, Valentino
* 53530 - Coso, Franco
* 53219 - Virgolin, Iván
* 49195 - Brassart, Selene

### Repositorios
* [frontend app](https://github.com/valelavatti/dsw-frontend)
* [backend app](https://github.com/valelavatti/dsw-backend)

## Tema
### Descripción
Aplicación web que permite a usuarios solicitar, reprogramar o cancelar turnos en tiempo real y a los profesionales gestionar sus agendas de atención. Permite la gestión eficiente de citas médicas mediante una interfaz intuitiva y accesible para pacientes y profesionales. Los pacientes podrán buscar médicos según la especialidad, fecha o disponibilidad horaria, además de filtrar turnos por día. *

### Modelo

<img width="722" height="908" alt="Modelo de dominio drawio" src="https://github.com/user-attachments/assets/ba4ed9c9-088e-4160-b3f2-2ef011ad9f8a" />
https://drive.google.com/file/d/1Tue00I5WeKPDh1CvGHylC-U-Pm6hb9kB/view

## Alcance Funcional 

### Alcance Mínimo

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Paciente<br>2. CRUD Médico<br>3. CRUD Especialidad<br>4. CRUD Obra social|
|CRUD dependiente|1. CRUD Turno {depende de} CRUD Paciente y CRUD Médico <br>2. CRUD Agenda {depende de} CRUD Médico|
|Listado<br>+<br>detalle| 1. Listado de médicos filtrado por especialidad, muestra cantidad de médicos segun descripción de su especialidad <br> 2. Listado de agenda filtrado por turnos disponibles, muestra fecha y horario del turno
|CUU/Epic|1. Registrar paciente <br>2. Iniciar sesión como paciente|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Paciente<br>2. CRUD Médico<br>3. CRUD Especialidad<br>4. CRUD Obra social<br> 5. CRUD Turno <br>6. CRUD Agenda<br>7. CRUD Notificación|
|CUU/Epic|1. Registrar paciente <br>2. Iniciar sesión como paciente <br>3. Solicitar turno <br> 4. Reprogramar turno|


### Alcance Adicional Voluntario

|Req|Detalle|
|:-|:-|
|Listados |1. Listado de pacientes filtrado por fecha <br>2. Listado de turnos cancelados|
|CUU/Epic|1. Cancelar turno <br>2. Cancelación de reserva|
|Otros|1. Envío de notificación de turno por email |

