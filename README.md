# VISOSPORT

## Miembros del grupo L3-ABS-8

1. Béjar Montilla, Adrián
1. Ayala Cabrera, Guillermo
1. Del Río Serrano, Miguel Ángel

## 1. Introducción al problema

### 1.1. Contexto
- VISOSPORT es un centro deportivo privado situado en El Viso del Alcor. Cuenta con múltiples instalaciones en las que se imparten diferentes actividades deportivas dirigidas:
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

### 1.3. Expectativas
La dirección de VISOSPORT, en calidad de cliente, requiere de un sistema dirigido a todos los usuarios (tanto socios como trabajadores).

Por un lado, que ofrezca a los socios una interfaz que permita reservar los servicios que les otorgue su plan:
  1. Plan bronce: Acceso a todas las instalaciones.
  2. Plan oro: Acceso a todas las instalaciones y actividades dirigidas.
  3. Plan platino: Acceso a todas las instalaciones y actividades, con la posibilidad de contar con un entrenador personal.

Por otro lado, que permita a los trabajadores asegurarse de un correcto desempeño de su función, más concretamente:
  1. Administradores: asignan diariamente a cada monitor las actividades que le tocará dirigir, en un horario y una sala determinados. Además, tramitan las solicitudes de alta y cambio de plan para usuarios.
  2. Monitores: revisan las asignaciones diarias impuestas por los administradores.
  3. Entrenadores personales: diseñan las rutinas de los usuarios que tengan asignados y se coordinan con ellos para cada entrenamiento.
     
## 2. Glosario de términos

| Término | Definición | Multimedia |
|---|---|---|
| **Actividad dirigida** | Actividad deportiva impartida por un monitor en una instalación concreta, con horario y plazas limitadas (natación, aquagym, zumba, yoga, pádel, spinning, hyrox). Solo pueden realizarla socios con plan oro o platino. | <img width="150" alt="Actividad Deportiva" src="https://github.com/user-attachments/assets/9171e284-51a1-4ca7-9eef-2f1e5300aac2" /> |
| **Administrador** | Trabajador del centro deportivo encargado de gestionar las asignaciones diarias a los monitores, y tramita los planes de cada socio| <img width="150" alt="Administrador" src="https://github.com/user-attachments/assets/f70ef0f9-aec9-408c-860f-ddf0eb7c7c13" /> |
| **Aforo** | Número máximo de personas que admite una instalación. En las sesiones, determina el número máximo de plazas reservables. | <img width="150" alt="Aforo" src="https://github.com/user-attachments/assets/22829f43-c039-4da2-a1b4-5b5c89802652" /> |
| **Reserva de pista** | Reserva de una pista de pádel por parte de un socio para uso propio, en una franja horaria en la que no haya ninguna clase programada. | <img width="150" alt="Reserva de pista" src="https://github.com/user-attachments/assets/3b781ebb-bdf1-4e3b-a4db-755878606808" /> |
| **Alta de socio** | Trámite por el que una persona pasa a ser socia del centro contratando un plan. Se realiza mediante una solicitud que gestiona un administrador. | <img width="150" alt="Darse de alta" src="https://github.com/user-attachments/assets/c4550f5f-3e36-4d3d-b965-b6525d135d35" /> |
| **Aquagym** | Actividad dirigida de ejercicio físico en el agua, que se imparte en la piscina. | <img width="150" alt="Aquagym" src="https://github.com/user-attachments/assets/6bf3a18d-b779-4cfe-ba7f-523a3d4817e9" /> |
| **Asignación diaria** | Relación que establece un administrador entre un monitor y una sesión, indicando horario y sala. Cada monitor consulta sus asignaciones diarias. | <img width="150" alt="Asignacion diaria" src="https://github.com/user-attachments/assets/46cf7aeb-7875-4ade-a1b7-2b8639c90ace" /> |
| **Cambio de plan** | Trámite por el que un socio solicita pasar a otro plan. Se materializa en una solicitud que tramita un administrador. | <img width="150" alt="Cambio de plan" src="https://github.com/user-attachments/assets/b3026d35-be0d-41f9-9aed-92689db0ca57" /> |
| **Director** | Responsable de VISOSPORT, que necesita tener centralizada la información de los trabajadores del centro. | <img width="150" alt="Director" src="https://github.com/user-attachments/assets/753bcc66-fcc2-486d-9d64-f6032b52c184" /> |
| **Entrenador personal** | Trabajador que entrena individualmente a los socios con plan platino que tiene asignados. Diseña sus rutinas y programa con ellos las sesiones de entrenamiento personal. | <img width="150" alt="Entrenador personal" src="https://github.com/user-attachments/assets/e42b7f62-1ccd-401e-912e-3c63144553d8" /> |
| **Entrenamiento personal** | Servicio de entrenamiento individualizado, con rutina propia, disponible solo para socios con plan platino. Se realiza en la sala de musculación. | <img width="150" alt="Entrenamiento personal" src="https://github.com/user-attachments/assets/be9dc857-22bc-4714-b678-06bcf89af6b3" /> |
| **Horario** | Franja de día y hora en la que tiene lugar una sesión o una reserva de pista. | <img width="150" alt="Horario" src="https://github.com/user-attachments/assets/17a97ae9-609b-48d8-93f5-6bbb81be2326" /> |
| **Hyrox** | Actividad dirigida de entrenamiento funcional que combina carrera y ejercicios de fuerza, que se imparte en la sala de Hyrox. | <img width="150" alt="hyrox" src="https://github.com/user-attachments/assets/7a61887c-b60b-43af-aa89-498a74796980" /> |
| **Instalación** | Espacio físico del centro (sala de musculación, piscina, piscina de relajación, salas multifuncionales, pistas de pádel, sala de cardio, sala de Hyrox) con un aforo máximo. | <img width="150" alt="instalacion" src="https://github.com/user-attachments/assets/6a4af816-fd39-4d7d-a409-960d24b67686" /> |
| **Monitor** | Trabajador que imparte las actividades dirigidas. Consulta su agenda diaria con las sesiones asignadas, su horario, la sala y el número de socios apuntados. | <img width="150" alt="monitor" src="https://github.com/user-attachments/assets/c4f82752-78bb-486d-8c4d-4477a4c62f25" /> |
| **Natación** | Actividad dirigida de clases de natación, que se imparte en la piscina. | <img width="150" alt="natacion" src="https://github.com/user-attachments/assets/8706e7a2-b5de-4a12-9622-de8a2bbc6f73" /> |
| **Pádel** | Deporte de raqueta que se practica en las pistas del centro, ya sea mediante clases dirigidas o mediante alquiler de pista. | <img width="150" alt="Padel" src="https://github.com/user-attachments/assets/b8c1a83e-9316-4a87-a1a9-85fa5cae72ec" /> |
| **Piscina de relajación** | Instalación acuática destinada al descanso, distinta de la piscina de natación y aquagym. | <img width="150" alt="Piscina de relajacion" src="https://github.com/user-attachments/assets/d8f66128-ea01-4271-9395-84e44180f4f5" /> |
| **Piscina** | Instalación acuática en la que se imparten las clases de natación y aquagym. | <img width="150" alt="piscina" src="https://github.com/user-attachments/assets/ec4038f7-cefd-46b7-82ae-1d9c6ce4ce0f" />|
| **Pista de pádel** | Instalación de pádel. El centro dispone de cuatro, utilizables para clases o para alquiler por parte de los socios. | <img width="150" alt="pista de padel" src="https://github.com/user-attachments/assets/ea074245-4263-45c0-93ae-e1e5c8eed583" /> |
| **Plan** | Modalidad contratada por un socio, que determina los servicios a los que tiene derecho: bronce, oro o platino. | <img width="150" alt="plan" src="https://github.com/user-attachments/assets/aa0cb18c-ddee-4171-8ecb-ae12e032c265" /> |
| **Plan bronce** | Plan que da acceso a todas las instalaciones, sin derecho a actividades dirigidas. | <img width="150" alt="bronce" src="https://github.com/user-attachments/assets/6e1deaae-2894-40c9-b4f5-8e23977ef012" /> |
| **Plan oro** | Plan que da acceso a todas las instalaciones y a las actividades dirigidas. | <img width="150" alt="oro" src="https://github.com/user-attachments/assets/83a83702-1fda-4c78-9693-b5ca702caa9f" /> |
| **Plan platino** | Plan que da acceso a todas las instalaciones y actividades, con la posibilidad de contar con un entrenador personal. | <img width="150" alt="platino" src="https://github.com/user-attachments/assets/81ef1249-13aa-4121-914f-64d0fb37ea41" /> |
| **Reserva** | Plaza que un socio asegura en una sesión o en una pista de pádel, respetando el aforo y las condiciones de su plan. | <img width="150" alt="reserva" src="https://github.com/user-attachments/assets/1a26a513-f570-4cd3-b048-50c93e591397" /> |
| **Rutina** | Conjunto de ejercicios diseñado por un entrenador personal para un socio, que puede actualizar y que el socio consulta desde el sistema. | <img width="150" alt="rutina" src="https://github.com/user-attachments/assets/01351d64-02c0-4a59-bd6b-bd16e7492cf1" /> |
| **Sala de cardio** | Instalación equipada con bicicletas de spinning y equipamiento cardiovascular, donde se imparte spinning. | <img width="150" alt="Cardio" src="https://github.com/user-attachments/assets/b01b70a7-b798-4069-a7c1-ce68653a273e" /> |
| **Sala de Hyrox** | Instalación específica en la que se imparte la actividad Hyrox. | <img width="150" alt="Sala de hyrox" src="https://github.com/user-attachments/assets/9f8d53dc-2aca-4a4c-ae4b-e5355629e622" /> |
| **Sala multifuncional** | Instalación polivalente en la que se imparten zumba y yoga. El centro dispone de dos. | <img width="150" alt="sala multifuncional" src="https://github.com/user-attachments/assets/5560ad7a-4219-47c4-9ab4-f77489a6d20e" /> |
| **Sala de musculación** | Instalación de entrenamiento con pesas y máquinas, en la que se realiza el entrenamiento personal. | <img width="150" alt="Sala de musculacion" src="https://github.com/user-attachments/assets/78abfee9-4891-4863-b166-9dbfe27ed367" /> |
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

  1. Como director de VISOSPORT, quiero tener centralizada la información sobre mis trabajadores para saber con qué personal cuento.
  2. Como administrador, quiero gestionar las solicitudes de alta y cambio de plan de los socios del centro para saber a qué servicios tienen derecho.
  3. Como administrador, quiero gestionar las instalaciones del centro, teniendo siempre en cuenta su aforo para aprovechar al máximo los espacios disponibles.
  4. Como administrador, quiero programar las sesiones de cada actividad y asignar a cada una un monitor, una sala y un horario para que se den las clases correctamente y evitar solapamientos.
  5. Como entrenador personal, quiero poder gestionar adecuadamente las rutinas de mis socios asignados así como comunicarme con ellos, para poder estar al tanto de su progreso y concertar las sesiones de entrenamiento.
  6. Como socio, quiero consultar las sesiones disponibles, así como sus horarios, y poder reservar para asegurarme de que voy a poder disfrutar de las actividades que quiero.
  7. Como socio, quiero poder reservar telemáticamente pistas de pádel para asegurarme de que no haya ninguna clase en la franja horario que deseo.
     
### 3.2. Usuarios del sistema

  1. Administrador: trabajador encargado de la gestión del centro. Programa las sesiones de las actividades dirigidas, asigna los monitores a cada sesión, gestiona las instalaciones y actividades, y tramita las solicitudes de alta y de cambio de plan de los socios.
  2. Monitor: trabajador que imparte las actividades dirigidas. Consulta su agenda diaria con las sesiones que tiene asignadas, su horario, la sala y el número de socios apuntados.
  3. Entrenador personal: trabajador que entrena individualmente a los socios con plan platino que tiene asignados. Diseña y actualiza sus rutinas y programa con ellos las sesiones de entrenamiento personal.
  4. Socio: cliente de VISOSPORT con un plan contratado. Consulta el horario de sesiones y reserva plaza en ellas, alquila pistas de pádel, solicita cambios de plan y, si tiene plan platino, contrata un entrenador personal y consulta su rutina.

## 4. Catálogo de requisitos

### 4.1. Requisitos funcionales

#### R.F.01. Título requisito funcional

Como [tipo de usuario]
quiero [servicio]
para [razón]

**Prueba de aceptación**
- Descripción de la primera comprobación a realizar
- Descripción de la segunda comprobación a realizar
- Se debe aplicar la regla de negocio R.N.XX.
- ...

#### 4.1.1. Requisitos de información

##### R.I.01. Título requisito de información

Como [tipo de usuario]
quiero [servicio]
para [razón]

**Prueba de aceptación**
- Descripción de la primera comprobación a realizar
- Descripción de la segunda comprobación a realizar
- ...

#### 4.1.2. Reglas de negocio

##### R.N.01. Título regla negocio

Descripción de la regla de negocio.

### 4.2. Mapa de historias de usuario (opcional)

### 4.3. Requisitos no funcionales (opcional)

**R.N.F. 01. Título requisito no funcional**
Como [tipo de usuario]
quiero [servicio]
para [razón]

-- fin entregable 1 --

## 5. Modelo conceptual

### 5.1. Diagramas de clases UML

- con restricciones.

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

## Referencias


