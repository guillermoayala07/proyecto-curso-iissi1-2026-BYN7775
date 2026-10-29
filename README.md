# VISOSPORT

## Miembros del grupo L3-ABS-8

1. Béjar Montilla, Adrián
1. Ayala Cabrera, Guillermo
1. Del Río Serrano, Miguel Ángel

## 1. Introducción al problema

### 1.1. Contexto
<img width="2048" height="768" alt="Logotipo deportivo Visosport moderno" src="https://github.com/user-attachments/assets/ffa52df9-a9b6-40b3-9f1a-790afd26f718" />

VISOSPORT es un centro deportivo privado situado en El Viso del Alcor. Cuenta con múltiples instalaciones en las que se imparten diferentes actividades deportivas dirigidas:
  1. Sala de musculación - Entrenamiento Personal
  2. Piscina y piscina de relajación - Clases de natación y Aquagym
  3. Sala multifuncional (2) - Zumba y Yoga
  4. Pistas de pádel (4) - Clases de pádel (ofrece también la posibilidad de reservar una pista)
  5. Sala de Cardio - Spinning
  6. Sala de Hyrox - Hyrox
Cada instalación tiene un aforo máximo. Fuera de las actividades dirigidas, los socios pueden usar libremente las instalaciones, aunque este uso libre no lo gestiona el sistema, salvo la reserva de las pistas de pádel. 

### 1.2. Situación actual y problemas
Actualmente la gestión de VISOSPORT se hace de forma manual, con hojas de cálculo, grupos de mensajería instantánea y documentos en papel. La información está dispersa y nadie tiene una visión completa del centro, lo que provoca problemas como estos:

  1. Solapamientos en la planificación: un monitor aparece asignado a dos clases a la misma hora, o una sala tiene programadas dos actividades a la vez.
  2. Clases sin monitor: al no haber un registro centralizado de asignaciones, a veces se descubre a última hora que una clase no tiene a nadie asignado.
  3. Aforo sin control: los socios se apuntan a las clases de palabra o por mensaje, así que algunas sesiones superan la capacidad de la sala (por ejemplo, socios que llegan a Spinning y no tienen bicicleta) mientras otras quedan casi vacías.
  4. Planes que no se respetan: no hay forma práctica de comprobar que un socio con plan bronce no realiza actividades dirigidas.
  5. Información poco accesible para los socios: para saber el horario, la sala o el monitor de una clase hay que consultar el tablón del centro o preguntar en recepción.
  6. Rutinas en papel: los entrenadores personales entregan las rutinas en papel o por mensaje, y se pierden o quedan desactualizadas.
  7. Trámites lentos: las altas y los cambios de plan se gestionan en papel, sin registro de su estado.

Aquí un video del cliente explicando la situación actual del centro deportivo:

https://github.com/user-attachments/assets/ec9965a4-e051-422e-9dd2-2b8a21ad7e05

### 1.3. Expectativas
La dirección de VISOSPORT, en calidad de cliente, requiere de un sistema dirigido a todos los usuarios (tanto socios como trabajadores).

Por un lado, que ofrezca a los socios una interfaz que permita reservar los servicios que les otorgue su plan:
  1. Plan bronce: Acceso a todas las instalaciones.
  2. Plan oro: Acceso a todas las instalaciones y actividades dirigidas.
  3. Plan platino: Acceso a todas las instalaciones y actividades, con la posibilidad de contar con un entrenador personal.

Por otro lado, que permita a los trabajadores asegurarse de un correcto desempeño de su función, más concretamente:
  1. Administradores: asignan diariamente a cada monitor las actividades que le tocará dirigir, en un horario y una sala determinados. Además, registran directamente las altas de nuevos socios y tramitan las solicitudes de cambio de plan de los socios.
  2. Monitores: revisan las asignaciones diarias impuestas por los administradores.
  3. Entrenadores personales: diseñan y actualizan las rutinas de los socios con plan platino que tengan asignados.
     
## 2. Glosario de términos

| Término | Definición | Multimedia |
|---|---|---|
| **Actividad dirigida** | Actividad deportiva impartida por un monitor en una instalación concreta, con horario y plazas limitadas (natación, aquagym, zumba, yoga, pádel, spinning, hyrox). Solo pueden realizarla socios con plan oro o platino. | <img width="150" alt="Actividad Deportiva" src="https://github.com/user-attachments/assets/9171e284-51a1-4ca7-9eef-2f1e5300aac2" /> |
| **Administrador** | Trabajador del centro deportivo encargado de gestionar las asignaciones diarias a los monitores, registrar las altas de nuevos socios y tramitar las solicitudes de cambio de plan. | <img width="150" alt="Administrador" src="https://github.com/user-attachments/assets/f70ef0f9-aec9-408c-860f-ddf0eb7c7c13" /> |
| **Aforo** | Número máximo de personas que admite una instalación. En las sesiones, determina el número máximo de plazas reservables. | <img width="150" alt="Aforo" src="https://github.com/user-attachments/assets/22829f43-c039-4da2-a1b4-5b5c89802652" /> |
| **Alta de socio** | Trámite por el que una persona pasa a ser socia del centro contratando un plan. Lo registra directamente un administrador en el sistema. | <img width="150" alt="Darse de alta" src="https://github.com/user-attachments/assets/c4550f5f-3e36-4d3d-b965-b6525d135d35" /> |
| **Aquagym** | Actividad dirigida de ejercicio físico en el agua, que se imparte en la piscina. | <img width="150" alt="Aquagym" src="https://github.com/user-attachments/assets/6bf3a18d-b779-4cfe-ba7f-523a3d4817e9" /> |
| **Asignación diaria** | Relación que establece un administrador entre un monitor y una sesión, indicando horario y sala. Cada monitor consulta sus asignaciones diarias. | <img width="150" alt="Asignacion diaria" src="https://github.com/user-attachments/assets/46cf7aeb-7875-4ade-a1b7-2b8639c90ace" /> |
| **Cambio de plan** | Trámite por el que un socio solicita pasar a otro plan. Se materializa en una solicitud que tramita un administrador. | <img width="150" alt="Cambio de plan" src="https://github.com/user-attachments/assets/b3026d35-be0d-41f9-9aed-92689db0ca57" /> |
| **Director** | Responsable de VISOSPORT, que necesita tener centralizada la información de los trabajadores del centro. | <img width="150" alt="Director" src="https://github.com/user-attachments/assets/753bcc66-fcc2-486d-9d64-f6032b52c184" /> |
| **Entrenador personal** | Trabajador que entrena individualmente a los socios con plan platino que tiene asignados. Diseña y actualiza sus rutinas. | <img width="150" alt="Entrenador personal" src="https://github.com/user-attachments/assets/e42b7f62-1ccd-401e-912e-3c63144553d8" /> |
| **Entrenamiento personal** | Servicio de entrenamiento individualizado, con rutina propia, disponible solo para socios con plan platino. Se realiza en la sala de musculación. | <img width="150" alt="Entrenamiento personal" src="https://github.com/user-attachments/assets/be9dc857-22bc-4714-b678-06bcf89af6b3" /> |
| **Horario** | Franja de día y hora en la que tiene lugar una sesión o una reserva de pista. | <img width="150" alt="Horario" src="https://github.com/user-attachments/assets/17a97ae9-609b-48d8-93f5-6bbb81be2326" /> |
| **Hyrox** | Actividad dirigida de entrenamiento funcional que combina carrera y ejercicios de fuerza, que se imparte en la sala de Hyrox. | <img width="150" alt="hyrox" src="https://github.com/user-attachments/assets/7a61887c-b60b-43af-aa89-498a74796980" /> |
| **Instalación** | Espacio físico del centro (sala de musculación, piscina, piscina de relajación, salas multifuncionales, pistas de pádel, sala de cardio, sala de Hyrox) con un aforo máximo. | <img width="150" alt="instalacion" src="https://github.com/user-attachments/assets/6a4af816-fd39-4d7d-a409-960d24b67686" /> |
| **Monitor** | Trabajador que imparte las actividades dirigidas. Consulta su agenda diaria con las sesiones asignadas, su horario, la sala y el número de socios apuntados. | <img width="150" alt="monitor" src="https://github.com/user-attachments/assets/c4f82752-78bb-486d-8c4d-4477a4c62f25" /> |
| **Natación** | Actividad dirigida de clases de natación, que se imparte en la piscina. | <img width="150" alt="natacion" src="https://github.com/user-attachments/assets/8706e7a2-b5de-4a12-9622-de8a2bbc6f73" /> |
| **Pádel** | Deporte de raqueta que se practica en las pistas del centro, ya sea mediante clases dirigidas o mediante alquiler de pista. | <img width="150" alt="Padel" src="https://github.com/user-attachments/assets/b8c1a83e-9316-4a87-a1a9-85fa5cae72ec" /> |
| **Piscina** | Instalación acuática en la que se imparten las clases de natación y aquagym. | <img width="150" alt="piscina" src="https://github.com/user-attachments/assets/ec4038f7-cefd-46b7-82ae-1d9c6ce4ce0f" />|
| **Piscina de relajación** | Instalación acuática destinada al descanso, distinta de la piscina de natación y aquagym. | <img width="150" alt="Piscina de relajacion" src="https://github.com/user-attachments/assets/d8f66128-ea01-4271-9395-84e44180f4f5" /> |
| **Pista de pádel** | Instalación de pádel. El centro dispone de cuatro, utilizables para clases o para alquiler por parte de los socios. | <img width="150" alt="pista de padel" src="https://github.com/user-attachments/assets/ea074245-4263-45c0-93ae-e1e5c8eed583" /> |
| **Plan** | Modalidad contratada por un socio, que determina los servicios a los que tiene derecho: bronce, oro o platino. | <img width="150" alt="plan" src="https://github.com/user-attachments/assets/aa0cb18c-ddee-4171-8ecb-ae12e032c265" /> |
| **Plan bronce** | Plan que da acceso a todas las instalaciones, sin derecho a actividades dirigidas. | <img width="150" alt="bronce" src="https://github.com/user-attachments/assets/6e1deaae-2894-40c9-b4f5-8e23977ef012" /> |
| **Plan oro** | Plan que da acceso a todas las instalaciones y a las actividades dirigidas. | <img width="150" alt="oro" src="https://github.com/user-attachments/assets/83a83702-1fda-4c78-9693-b5ca702caa9f" /> |
| **Plan platino** | Plan que da acceso a todas las instalaciones y actividades, con la posibilidad de contar con un entrenador personal. | <img width="150" alt="platino" src="https://github.com/user-attachments/assets/81ef1249-13aa-4121-914f-64d0fb37ea41" /> |
| **Reserva** | Plaza que un socio asegura en una sesión o en una pista de pádel, respetando el aforo y las condiciones de su plan. | <img width="150" alt="reserva" src="https://github.com/user-attachments/assets/1a26a513-f570-4cd3-b048-50c93e591397" /> |
| **Reserva de pista** | Reserva de una pista de pádel por parte de un socio para uso propio, en una franja horaria en la que no haya ninguna clase programada. Puede cancelarse con al menos 2 horas de antelación. | <img width="150" alt="Reserva de pista" src="https://github.com/user-attachments/assets/3b781ebb-bdf1-4e3b-a4db-755878606808" /> |
| **Rutina** | Conjunto de ejercicios diseñado por un entrenador personal para un socio, que puede actualizar y que el socio consulta desde el sistema. | <img width="150" alt="rutina" src="https://github.com/user-attachments/assets/01351d64-02c0-4a59-bd6b-bd16e7492cf1" /> |
| **Sala de cardio** | Instalación equipada con bicicletas de spinning y equipamiento cardiovascular, donde se imparte spinning. | <img width="150" alt="Cardio" src="https://github.com/user-attachments/assets/b01b70a7-b798-4069-a7c1-ce68653a273e" /> |
| **Sala de Hyrox** | Instalación específica en la que se imparte la actividad Hyrox. | <img width="150" alt="Sala de hyrox" src="https://github.com/user-attachments/assets/9f8d53dc-2aca-4a4c-ae4b-e5355629e622" /> |
| **Sala de musculación** | Instalación de entrenamiento con pesas y máquinas, en la que se realiza el entrenamiento personal. | <img width="150" alt="Sala de musculacion" src="https://github.com/user-attachments/assets/78abfee9-4891-4863-b166-9dbfe27ed367" /> |
| **Sala multifuncional** | Instalación polivalente en la que se imparten zumba y yoga. El centro dispone de dos. | <img width="150" alt="sala multifuncional" src="https://github.com/user-attachments/assets/5560ad7a-4219-47c4-9ab4-f77489a6d20e" /> |
| **Sesión** | Celebración concreta de una actividad dirigida en una fecha, horario y sala determinados, con un monitor asignado y un número limitado de plazas. | <img width="150" alt="sesion" src="https://github.com/user-attachments/assets/fcc035b3-e639-46fc-8317-7e82dd1c4e5f" /> |
| **Socio** | Cliente de VISOSPORT con un plan contratado. Consulta el horario de sesiones, reserva plaza, alquila pistas, solicita cambios de plan y, con plan platino, contrata un entrenador personal. | <img width="150" alt="Socio" src="https://github.com/user-attachments/assets/6469ad8b-feb9-41b5-944a-64c24d22d151" /> |
| **Spinning** | Actividad dirigida de ciclismo indoor en grupo, con una bicicleta por asistente, que se imparte en la sala de cardio. | <img width="150" alt="spinning" src="https://github.com/user-attachments/assets/f11cc909-cb8f-4c05-b8fc-70c03816ec26" />|
| **Trabajador** | Persona empleada en el centro: administrador, monitor o entrenador personal. | <img width="150" alt="Trabajador" src="https://github.com/user-attachments/assets/9a65aa24-1610-4dc2-95ec-e09bc3f00420" /> |
| **Uso libre** | Utilización por parte de los socios de las instalaciones fuera de las actividades dirigidas. El sistema no lo gestiona, salvo la reserva de pistas de pádel. | <img width="150" alt="uso libre" src="https://github.com/user-attachments/assets/b816ee28-7d33-4caf-be11-0a95596e73d0" /> |
| **Yoga** | Actividad dirigida de ejercicios de postura, respiración y relajación, que se imparte en las salas multifuncionales. | <img width="150" alt="pexels-vickytm-29785336" src="https://github.com/user-attachments/assets/9051a4aa-77c9-40b8-9feb-0d28e075aa1c" /> |
| **Zumba** | Actividad dirigida de baile y ejercicio aeróbico, que se imparte en las salas multifuncionales. | <img width="150" alt="pexels-katetrysh-4090012" src="https://github.com/user-attachments/assets/f5ea8c6f-c586-400e-b2b3-86fe961d60bc" /> |


## 3. Visión general del sistema

El sistema de información de VISOSPORT centralizará la gestión del centro deportivo: los socios y sus planes, los trabajadores, las instalaciones y las actividades, la planificación de sesiones, las reservas, el alquiler de pistas de pádel y el entrenamiento personal. En este apartado se describen los objetivos generales del sistema y los tipos de usuarios que lo utilizarán, que se detallan después en el catálogo de requisitos.

### 3.1. Requisitos generales

  1. **RG-1.** Como administrador, quiero gestionar los socios y sus planes, los trabajadores, las instalaciones, las actividades y la planificación de las sesiones, para que el centro funcione de forma organizada y sin solapamientos.
  2. **RG-2.** Como monitor, quiero consultar las sesiones que tengo asignadas cada día, para saber qué actividad tengo que impartir, a qué hora y en qué sala.
  3. **RG-3.** Como entrenador personal, quiero gestionar las rutinas de los socios que tengo asignados, para hacer un seguimiento personalizado de su progreso.
  4. **RG-4.** Como socio, quiero reservar plaza en las actividades, alquilar pistas de pádel y, si mi plan lo permite, contratar un entrenador personal, para aprovechar los servicios que me ofrece mi plan.
     
### 3.2. Usuarios del sistema

  1. Administrador: trabajador encargado de la gestión del centro. Programa las sesiones de las actividades dirigidas, asigna los monitores a cada sesión, gestiona las instalaciones y actividades, registra las altas de nuevos socios y tramita las solicitudes de cambio de plan.
  2. Monitor: trabajador que imparte las actividades dirigidas. Consulta su agenda diaria con las sesiones que tiene asignadas, su horario, la sala y el número de socios apuntados.
  3. Entrenador personal: trabajador que entrena individualmente a los socios con plan platino que tiene asignados. Diseña y actualiza sus rutinas.
  4. Socio: cliente de VISOSPORT con un plan contratado. Consulta el horario de sesiones y reserva plaza en ellas, alquila pistas de pádel, solicita cambios de plan y, si tiene plan platino, contrata un entrenador personal y consulta su rutina.
  5. Director: responsable de VISOSPORT. Consulta la información centralizada de los trabajadores del centro.

## 4. Catálogo de requisitos

### 4.1. Requisitos funcionales

> Todos los requisitos funcionales de este entregable son listados y consultas.

#### R.F.01. Consultar sesiones disponibles

Como socio,
quiero consultar las sesiones de actividades dirigidas con su fecha, horario, instalación, monitor y plazas libres,
para decidir en cuáles quiero reservar plaza.

**Prueba de aceptación**

- Un socio con plan oro o platino consulta las sesiones y obtiene cada una con su fecha, horario, instalación, monitor y número de plazas libres.
- El número de plazas libres de una sesión es su aforo menos las reservas de plaza activas.
- Se puede filtrar por actividad y por fecha, y solo se muestran las sesiones futuras.
- Una sesión sin monitor asignado se muestra indicando que el monitor está pendiente de asignar.
- Se debe aplicar la regla de negocio R.N.02: un socio con plan bronce no obtiene ninguna sesión, ya que su plan no incluye actividades dirigidas.

#### R.F.02. Consultar mis reservas

Como socio,
quiero consultar las reservas activas de plaza en sesiones y de pista de pádel que tengo realizadas,
para saber a qué voy a asistir y cuándo.

**Prueba de aceptación**

- Un socio con reservas de plaza y de pista obtiene ambas, con su fecha, horario e instalación, ordenadas por fecha.
- Una reserva cancelada, de plaza o de pista, no aparece en el listado.
- Un socio sin ninguna reserva obtiene un listado vacío.
- Un socio solo puede ver sus propias reservas, no las de otros socios.

#### R.F.03. Consultar la ocupación de una instalación

Como administrador,
quiero consultar el calendario de ocupación de una instalación en un día o rango de fechas, con sus sesiones y sus reservas de pista activas,
para planificar nuevas sesiones sin solapamientos.

**Prueba de aceptación**

- Se consulta una instalación y se obtienen sus sesiones y, si es una pista de pádel, sus reservas activas, ordenadas por fecha y hora de inicio.
- Una reserva de pista cancelada no aparece como ocupación.
- Una franja horaria sin sesiones ni reservas no aparece como ocupada.
- Se debe aplicar la regla de negocio R.N.03: en el resultado no aparecen dos sesiones solapadas de una misma instalación.
- Se debe aplicar la regla de negocio R.N.06: en el resultado de una pista no aparecen reservas solapadas entre sí ni con sesiones.

#### R.F.04. Listado de sesiones sin monitor

Como administrador,
quiero obtener un listado de las sesiones futuras que todavía no tienen monitor asignado,
para asignarles un monitor a tiempo y evitar clases sin monitor.

**Prueba de aceptación**

- Se crea una sesión sin monitor y aparece en el listado.
- Una sesión con monitor asignado no aparece en el listado.
- Las sesiones ya pasadas no aparecen en el listado.
- El listado está ordenado de la sesión más próxima a la más lejana.

#### R.F.05. Listado de socios con reserva en una sesión

Como monitor,
quiero consultar el listado de socios con plaza reservada en una sesión concreta,
para saber cuántos asistentes tendré y controlar la asistencia.

**Prueba de aceptación**

- Se consulta una sesión con reservas y se obtienen los socios (nombre y apellidos) con reserva activa, junto con el número total de asistentes.
- Una reserva cancelada no aparece en el listado.
- Una sesión sin reservas devuelve un listado vacío.
- Se debe aplicar la regla de negocio R.N.01: el número de socios del listado no supera el aforo de la instalación de la sesión.

#### R.F.06. Consultar mi agenda diaria

Como monitor,
quiero consultar las sesiones que tengo asignadas en un día, con su horario, instalación y número de socios con reserva,
para organizar mi jornada.

**Prueba de aceptación**

- Un monitor con varias sesiones asignadas en un día las obtiene ordenadas por hora de inicio.
- No aparecen las sesiones de otros monitores.
- Un día sin sesiones asignadas devuelve un listado vacío.
- Se debe aplicar la regla de negocio R.N.04: en la agenda de un monitor no hay sesiones solapadas.

#### R.F.07. Consultar mi rutina

Como socio con plan platino,
quiero consultar la rutina de ejercicios que me ha diseñado mi entrenador personal,
para seguir mi plan de entrenamiento.

**Prueba de aceptación**

- Un socio con plan platino y rutina asignada obtiene la rutina con sus ejercicios (nombre, series y repeticiones) y el nombre de su entrenador.
- Un socio sin rutina asignada recibe un listado vacío.
- Si el socio tiene varias rutinas, se obtiene primero la más reciente.

#### R.F.08. Consultar mis socios asignados

Como entrenador personal,
quiero consultar los socios que tengo asignados junto con su rutina más reciente,
para saber a quién entreno y qué rutina sigue cada uno.

**Prueba de aceptación**

- Un entrenador con socios asignados obtiene sus nombres y apellidos y la fecha de su rutina más reciente.
- Un socio asignado que todavía no tiene rutina aparece indicando que no tiene rutina.
- No aparecen socios asignados a otros entrenadores.
- Se debe aplicar la regla de negocio R.N.07: todos los socios del listado tienen plan platino.

#### R.F.09. Listado de trabajadores

Como director,
quiero obtener un listado de los trabajadores del centro, filtrable por tipo (administrador, monitor o entrenador personal),
para saber con qué personal cuento.

**Prueba de aceptación**

- Sin filtro se obtienen todos los trabajadores con su nombre, tipo, correo y teléfono.
- Al filtrar por un tipo solo se obtienen los trabajadores de ese tipo.
- El listado está ordenado alfabéticamente por apellidos.

#### R.F.10. Listado de solicitudes pendientes

Como administrador,
quiero obtener un listado de las solicitudes de cambio de plan que están pendientes de tramitar,
para gestionarlas y que los socios sepan a qué servicios tienen derecho.

**Prueba de aceptación**

- Se obtienen las solicitudes en estado pendiente con su socio solicitante, plan solicitado y fecha.
- Una solicitud ya tramitada (aprobada o rechazada) no aparece en el listado.
- El listado está ordenado de la solicitud más antigua a la más reciente.

---

#### 4.1.1. Requisitos de información

##### R.I.01. Socios

Como administrador,
quiero disponer de la siguiente información sobre los socios: DNI, nombre, apellidos, correo electrónico, teléfono, fecha de alta y plan contratado,
para gestionar a los socios del centro y saber a qué servicios tienen derecho.

**Prueba de aceptación**

- Se registra un socio nuevo con todos sus datos y aparece al consultar los socios.
- Se intenta registrar un socio con un DNI ya registrado y se recibe un mensaje de error.
- No se permite registrar un socio ni modificarlo dejando sin valor algún dato.
- Un socio tiene siempre un único plan en un momento dado.

##### R.I.02. Planes

Como administrador,
quiero que el plan contratado por cada socio sea uno de los tres que ofrece el centro: bronce, oro o platino,
para conocer los servicios a los que tiene derecho cada socio.

**Prueba de aceptación**

- Se registra un socio con cada uno de los tres planes y aparece con su plan al consultar los socios.
- No se permite registrar un socio con un plan distinto de bronce, oro o platino.
- Los servicios de cada plan son fijos: el plan bronce da acceso a las instalaciones; el plan oro incluye además las actividades dirigidas; el plan platino incluye además la posibilidad de tener entrenador personal (véanse R.N.02 y R.N.07).

**Prueba de aceptación**

- Existen exactamente tres planes: bronce, oro y platino.
- El plan bronce no incluye actividades dirigidas ni entrenador personal; el plan oro incluye actividades dirigidas pero no entrenador personal; el plan platino incluye ambos.
- No se permite crear dos planes con el mismo nombre.

##### R.I.03. Trabajadores

Como director,
quiero disponer de la siguiente información sobre los trabajadores: DNI, nombre, apellidos, correo electrónico, teléfono, fecha de contratación y tipo (administrador, monitor o entrenador personal),
para tener centralizada la información del personal.

**Prueba de aceptación**

- Se registra un trabajador de cada tipo y aparece al consultar los trabajadores.
- Se intenta registrar un trabajador con un DNI ya registrado y se recibe un mensaje de error.
- No se permite registrar un trabajador ni modificarlo dejando sin valor algún dato.
- Un trabajador tiene un único tipo.

##### R.I.04. Instalaciones

Como administrador,
quiero disponer de la siguiente información sobre las instalaciones: nombre, tipo (sala de musculación, piscina, piscina de relajación, sala multifuncional, pista de pádel, sala de cardio o sala de Hyrox) y aforo máximo,
para conocer la capacidad de cada espacio del centro.

**Prueba de aceptación**

- Se registra cada una de las instalaciones del centro y aparecen al consultarlas.
- No se permite registrar una instalación con aforo menor o igual que cero.
- No se permite registrar dos instalaciones con el mismo nombre.

##### R.I.05. Actividades dirigidas

Como administrador,
quiero disponer de la siguiente información sobre las actividades dirigidas: nombre, descripción y tipo de instalación en la que se imparte,
para programar sesiones de cada actividad en la instalación adecuada.

**Prueba de aceptación**

- Se registra una actividad (por ejemplo, zumba, en sala multifuncional) y aparece al consultar las actividades.
- No se permite registrar dos actividades con el mismo nombre.
- No se permite registrar una actividad dejando sin valor algún dato.

##### R.I.06. Sesiones

Como administrador,
quiero disponer de la siguiente información sobre las sesiones: actividad, instalación, fecha, hora de inicio, hora de fin y, cuando ya se haya asignado, monitor,
para planificar las clases del centro.

**Prueba de aceptación**

- Se programa una sesión sin monitor y se consulta; después se le asigna un monitor y la consulta lo refleja.
- No se permite programar una sesión cuya hora de fin sea anterior o igual a su hora de inicio.
- No se permite asignar a una sesión un trabajador que no sea de tipo monitor.
- No se permite programar una sesión en una instalación que no sea del tipo en el que se imparte su actividad.

##### R.I.07. Reservas de plaza

Como socio,
quiero que quede registrada la información de mis reservas de plaza en sesiones: socio, sesión, fecha de la reserva y estado (activa o cancelada),
para tener asegurada mi plaza en la actividad.

**Prueba de aceptación**

- Se registra una reserva de plaza y aparece al consultar las reservas del socio y las de la sesión.
- Se intenta registrar una segunda reserva activa del mismo socio en la misma sesión y se recibe un mensaje de error.
- Una reserva cancelada conserva su registro con el estado cancelada.
- Se deben aplicar las reglas de negocio R.N.01, R.N.02 y R.N.05.

##### R.I.08. Reservas de pista

Como socio,
quiero que quede registrada la información de mis reservas de pista de pádel: socio, pista, fecha, hora de inicio, hora de fin y estado (activa o cancelada),
para poder jugar en la franja que he elegido.

**Prueba de aceptación**

- Se registra una reserva de pista y aparece al consultar las reservas del socio y las de la pista.
- No se permite registrar una reserva cuya hora de fin sea anterior o igual a su hora de inicio.
- No se permite registrar una reserva sobre una instalación que no sea una pista de pádel.
- Una reserva cancelada conserva su registro con el estado cancelada.
- Se deben aplicar las reglas de negocio R.N.05 y R.N.06.

##### R.I.09. Entrenador personal asignado

Como administrador,
quiero disponer de la información sobre el entrenador personal asignado a cada socio con plan platino: socio, entrenador y fecha de inicio de la asignación,
para saber qué socios entrena cada entrenador personal.

**Prueba de aceptación**

- Se asigna un entrenador personal a un socio con plan platino y aparece al consultar los socios del entrenador.
- No se permite asignar como entrenador a un trabajador que no sea de tipo entrenador personal.
- Un socio tiene como máximo un entrenador personal asignado.
- Se cambia el entrenador personal de un socio: el nuevo entrenador sustituye al anterior, se actualiza la fecha de inicio y el socio deja de aparecer en el listado de socios del entrenador anterior.
- Se debe aplicar la regla de negocio R.N.07.

##### R.I.10. Rutinas

Como entrenador personal,
quiero disponer de la siguiente información sobre las rutinas de mis socios: socio, entrenador, fecha de creación y, para cada ejercicio, su nombre, número de series y número de repeticiones,
para planificar el entrenamiento de cada socio y que este pueda consultarlo.

**Prueba de aceptación**

- Se registra una rutina con varios ejercicios para un socio y se consulta con todos sus ejercicios.
- No se permite registrar un ejercicio con series o repeticiones menores o iguales que cero.
- No se permite registrar una rutina para un socio que no tiene asignado a ese entrenador personal.

##### R.I.11. Solicitudes de cambio de plan

Como administrador,
quiero disponer de la siguiente información sobre las solicitudes de cambio de plan: socio solicitante, plan solicitado, fecha de la solicitud, estado (pendiente, aprobada o rechazada) y administrador que la tramita,
para llevar un registro del estado de cada trámite.

**Prueba de aceptación**

- Se registra una solicitud nueva y queda en estado pendiente, sin administrador asignado.
- Al tramitarla pasa a aprobada o rechazada y queda registrado el administrador que la tramitó.
- No se permite registrar una solicitud sin socio solicitante o plan solicitado.

---

#### 4.1.2. Reglas de negocio

##### R.N.01. Límite de plazas por sesión

Como administrador,
quiero que no se puedan registrar más reservas de plaza activas en una sesión que el aforo máximo de su instalación,
para evitar la sobreocupación y los problemas de seguridad.

**Prueba de aceptación**

- Se registran reservas de plaza activas hasta alcanzar el aforo de la instalación de una sesión y no se recibe ningún mensaje de error.
- Se intenta registrar una reserva más y se recibe un mensaje de error por superar el aforo.
- Se cancela una reserva de una sesión completa y se puede registrar una nueva.

##### R.N.02. Compatibilidad entre plan y actividad

Como administrador,
quiero que solo los socios con un plan que incluya actividades dirigidas (oro o platino) puedan reservar plaza en una sesión,
para respetar las condiciones contratadas por cada socio.

**Prueba de aceptación**

- Un socio con plan oro reserva plaza en una sesión y no se recibe ningún mensaje de error.
- Un socio con plan platino reserva plaza en una sesión y no se recibe ningún mensaje de error.
- Un socio con plan bronce intenta reservar plaza en una sesión y se recibe un mensaje de error por no incluir su plan actividades dirigidas.

##### R.N.03. No solapamiento de sesiones en una instalación

Como administrador,
quiero que una misma instalación no pueda tener dos sesiones que se solapen en el tiempo,
para evitar conflictos de uso del espacio.

**Prueba de aceptación**

- Se programan dos sesiones consecutivas en la misma instalación (la segunda empieza cuando termina la primera) y no se recibe ningún mensaje de error.
- Se programan dos sesiones a la misma hora en instalaciones distintas y no se recibe ningún mensaje de error.
- Se intenta programar una sesión que se solapa, aunque sea parcialmente, con otra de la misma instalación y se recibe un mensaje de error.

##### R.N.04. No solapamiento de sesiones de un monitor

Como administrador,
quiero que un monitor no pueda estar asignado a dos sesiones que se solapen en el tiempo,
para evitar que falte personal en alguna sesión.

**Prueba de aceptación**

- Se asigna un monitor a dos sesiones consecutivas y no se recibe ningún mensaje de error.
- Se intenta asignar un monitor a una sesión que se solapa con otra suya y se recibe un mensaje de error.
- Dos sesiones solapadas con monitores distintos no producen ningún error.

##### R.N.05. Cancelación con antelación mínima

Como socio,
quiero que solo se pueda cancelar una reserva de plaza o de pista con al menos 2 horas de antelación a su inicio,
para que el centro pueda gestionar la plaza o la pista liberada.

**Prueba de aceptación**

- Se cancela una reserva de plaza 3 horas antes del inicio de la sesión y no se recibe ningún mensaje de error.
- Se cancela una reserva de plaza exactamente 2 horas antes del inicio y no se recibe ningún mensaje de error.
- Se intenta cancelar una reserva de plaza con menos de 2 horas de antelación y se recibe un mensaje de error.
- Se cancela una reserva de pista 3 horas antes de su hora de inicio y no se recibe ningún mensaje de error.
- Se intenta cancelar una reserva de pista con menos de 2 horas de antelación y se recibe un mensaje de error.

##### R.N.06. No solapamiento en las pistas de pádel

Como socio,
quiero que una pista de pádel no pueda tener una reserva activa que se solape con otra reserva activa ni con una sesión,
para asegurarme de que no hay ninguna clase ni otra reserva en la franja que he elegido.

**Prueba de aceptación**

- Se reserva una pista en una franja libre y no se recibe ningún mensaje de error.
- Se intenta reservar una pista en una franja que se solapa con una clase programada y se recibe un mensaje de error.
- Se intenta reservar una pista en una franja que se solapa con otra reserva activa y se recibe un mensaje de error.
- Se reserva una pista en una franja en la que solo hay una reserva cancelada y no se recibe ningún mensaje de error.
- Se programa una sesión en una pista en una franja que ya tiene una reserva activa y se recibe un mensaje de error.

##### R.N.07. Entrenador personal solo para el plan platino

Como administrador,
quiero que solo los socios con plan platino puedan tener un entrenador personal asignado,
para respetar las condiciones contratadas por cada socio.

**Prueba de aceptación**

- Se asigna un entrenador personal a un socio con plan platino y no se recibe ningún mensaje de error.
- Se intenta asignar un entrenador personal a un socio con plan bronce u oro y se recibe un mensaje de error.
- Se intenta cambiar a un plan distinto de platino a un socio que tiene entrenador personal asignado y se recibe un mensaje de error.

---

### 4.2. Mapa de historias de usuario

Los requisitos generales (objetivos, o historias épicas) organizan jerárquicamente el resto de requisitos. Cada fila del mapa es un objetivo y detalla los requisitos de información, reglas de negocio y requisitos funcionales que lo concretan.

| Objetivo (requisito general) | Requisitos de información | Reglas de negocio | Requisitos funcionales |
|---|---|---|---|
| **RG-1.** Gestionar los socios y sus planes, los trabajadores, las instalaciones, las actividades y la planificación de las sesiones (administrador) | R.I.01 Socios<br>R.I.02 Planes<br>R.I.03 Trabajadores<br>R.I.04 Instalaciones<br>R.I.05 Actividades dirigidas<br>R.I.06 Sesiones<br>R.I.11 Solicitudes de cambio de plan | R.N.03 No solapamiento de sesiones en una instalación<br>R.N.04 No solapamiento de sesiones de un monitor<br>R.N.06 No solapamiento en las pistas de pádel<br>R.N.07 Entrenador personal solo para el plan platino | R.F.03 Consultar la ocupación de una instalación<br>R.F.04 Listado de sesiones sin monitor<br>R.F.09 Listado de trabajadores<br>R.F.10 Listado de solicitudes pendientes |
| **RG-2.** Consultar las sesiones asignadas cada día (monitor) | R.I.06 Sesiones<br>R.I.07 Reservas de plaza | R.N.01 Límite de plazas por sesión<br>R.N.04 No solapamiento de sesiones de un monitor | R.F.05 Listado de socios con reserva en una sesión<br>R.F.06 Consultar mi agenda diaria |
| **RG-3.** Gestionar las rutinas de los socios asignados (entrenador personal) | R.I.09 Entrenador personal asignado<br>R.I.10 Rutinas | R.N.07 Entrenador personal solo para el plan platino | R.F.07 Consultar mi rutina<br>R.F.08 Consultar mis socios asignados |
| **RG-4.** Reservar plaza en las actividades, alquilar pistas de pádel y contratar un entrenador personal (socio) | R.I.07 Reservas de plaza<br>R.I.08 Reservas de pista<br>R.I.09 Entrenador personal asignado | R.N.01 Límite de plazas por sesión<br>R.N.02 Compatibilidad entre plan y actividad<br>R.N.05 Cancelación con antelación mínima<br>R.N.06 No solapamiento en las pistas de pádel<br>R.N.07 Entrenador personal solo para el plan platino | R.F.01 Consultar sesiones disponibles<br>R.F.02 Consultar mis reservas |

---

### 4.3. Requisitos no funcionales

Describen aspectos de calidad del sistema (compatibilidad, fiabilidad, eficiencia, usabilidad y seguridad, según la clasificación de la norma ISO/IEC 25010).

#### R.N.F.01. Funcionamiento en MariaDB

Como director,
quiero que el sistema funcione sobre un servidor de bases de datos MariaDB,
para poder instalarlo en la infraestructura del centro sin cambios.

**Prueba de aceptación**

- Los scripts de creación de tablas, funciones, procedimientos, triggers y poblado se ejecutan en MariaDB, en el orden indicado, sin ningún error.

#### R.N.F.02. Operaciones completas o ninguna

Como administrador,
quiero que las operaciones de reserva y cancelación se realicen por completo o no se realicen en absoluto,
para que nunca queden datos a medias ni inconsistentes.

**Prueba de aceptación**

- Una reserva de plaza que incumple una regla de negocio no deja ningún dato registrado.
- Tras cancelar una reserva, la plaza queda liberada en la sesión y la reserva figura como cancelada, sin estados intermedios.

#### R.N.F.03. Mensajes de error comprensibles

Como administrador,
quiero que, cuando una operación sea rechazada por incumplir una regla de negocio, el sistema muestre un mensaje que indique el motivo,
para saber qué debo corregir.

**Prueba de aceptación**

- Cada una de las reglas de negocio R.N.01 a R.N.07, al incumplirse, produce un mensaje de error distinto que identifica la regla incumplida.

#### R.N.F.04. Tiempo de respuesta de las consultas

Como socio,
quiero que las consultas de sesiones y de reservas respondan en menos de 2 segundos,
para no perder tiempo al reservar.

**Prueba de aceptación**

- Con el volumen de datos de un año de actividad del centro (unos 600 socios y varios miles de reservas), las consultas R.F.01 y R.F.02 tardan menos de 2 segundos.

#### R.N.F.05. Acceso restringido a los propios datos

Como director,
quiero que cada usuario solo pueda consultar la información que le corresponde según su función,
para proteger los datos personales de socios y trabajadores.

**Prueba de aceptación**

- Un socio solo obtiene sus propias reservas y su propia rutina, nunca las de otros socios.
- Un monitor solo obtiene en su agenda las sesiones que tiene asignadas.
- Un entrenador personal solo obtiene los socios que tiene asignados.

## 5. Modelo conceptual

### 5.1. Diagramas de clases UML

<img width="6624" height="4688" alt="Modelo Conceptual" src="https://github.com/user-attachments/assets/aea33815-22bf-4e85-9347-419018260578" />

### 5.2. Escenarios de prueba

- con descripción textual y diagrama de objetos UML.

## 6. Matrices de trazabilidad

- Matriz de trazabilidad entre los elementos del modelo conceptual y los requisitos.

|       | EntidadX   | AsociaciónX  | RestricciónX  | Entidad2 ...   | 
|:------|:-----------|:-----------|:-----------|:-----------|
| RI-1  | X          | X          | X          | X          |
| RI-2  |            | X          |            | X          |
| RF-1  |            | X          |            | X          |
| RF-2  | X          |            | X          | X          |
| RN-1  |            | X          |            |            |
| RN-2  | X          | X          | X          |            |
| ...   |            |            |            |            |

-- fin entregable 2 --

## 7. Modelo relacional en 3FN

- Relaciones obtenidas al aplicar la transformación del modelo conceptual.

### 7.1.  Justificación de la estrategia de transformación de jerarquías

- si se identificaron jerarquías en el MC.


### 8. Matriz de trazabilidad MC/SQL (opcional):

- Restricciones sobre el MC / Elementos del modelo tecnológico (SQL) (Triggers, checks, etc.)
- Incluir Reglas de negocio — Constraints/Triggers en las matrices de trazabilidad para el entregable 3

|       | EntidadX   | AsociaciónX  | RestricciónX  | Entidad2 ...   | 
|:-------|:-------|:-------|:-------|:-------|
| TABLA-1 |        |        |        |        |
| TABLA-2 |        |        |        |        |
| TABLA-3 |        |        |        |        |
| TABLA-4 |        |        |        |        |
| TRIG-1 |        |        |        |        |
| TRIG-2 | X      | X      |        | X      |
| TRIG-3 |        | X      |        | X      |
| TRIG-4 |        |        | X      |        |
| CONST-1 |        |        |        |        |
| CONST-2 | X      | X      |        | X      |
| CONST-3 |        | X      |        | X      |
| CONST-4 |        |        | X      |        |

Se consideran todo tipo de constraints declarativas (aquellas definidas durante el CREATE TABLE).
-- fin entregable 3 --


