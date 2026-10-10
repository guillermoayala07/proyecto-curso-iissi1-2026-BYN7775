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

- Términos específicos del dominio del problema, ordenados alfabéticamente. Se valorará la presencia de información multimedia.

## 3. Visión general del sistema

### 3.1. Requisitos generales

### 3.2. Usuarios del sistema

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


