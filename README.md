# Título Proyecto

## Miembros del grupo L3-ABS-8

1. Béjar Montilla, Adrián
1. Ayala Cabrera, Guillermo
1. Del Río Serrano, Miguel Ángel

## 1. Introducción al problema

- VISOSPORT es un centro deportivo privado. Cuenta con múltiples instalaciones en las que se realizan diferentes actividades deportivas (pero que a su vez los usuarios pueden usar libremente):
  1. Sala de musculación - Entrenamiento Personal
  2. Piscina y piscina de relajación - Clases de natación y Aquagym
  3. Sala multifuncional (2) - Zumba y Yoga
  4. Pistas de pádel (4) - Clases de pádel (ofrece también la posibilidad de reservar una pista)
  5. Sala de Cardio - Spinning
  6. Sala de Hyrox - Hyrox
 
A día de hoy, la gestión el centro deportivo VISOSPORT se hace de forma manual con herramientas como hojas de cálculo, mensajería instantánea o directamente en papel. Esto provoca errores de coordinación, solapamiento de horarios, falta de personal. 

Es por eso que los dirigentes de VISOSPORT se han puesto el objetivo de optimizar su administración para sacarle el máximo partido a sus instalaciones, mediante la centralización de los datos del centro, la coordinación de sus trabajadores y la facilitación de la información a los clientes.

VISOSPORT requiere de un sistema dirigido tanto a usuarios como a trabajadores. Por un lado, que ofrezca una interfaz que permite a los usuarios reservar los servicios que les otorgue su plan:
  1. Plan bronce: Acceso a todas las instalaciones y actividades, pero con restricción de una actividad por semana
  2. Plan oro: Acceso a todas las instalaciones y actividades, sin restricción.
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


