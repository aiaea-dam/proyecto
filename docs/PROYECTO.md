# Propuesta de Proyecto: <!-- TITULO PROYECTO -->

## Título del Proyecto

Timely

<!-- IMAGEN -->

## Datos del Equipo

* **Nombre del Proyecto:** <!-- TODO -->
* **Equipo:** AIAEA
* **Miembros del Equipo:**
  * Aaron Quirant Chacón
  * Álvaro Monsonis Mas
  * Ayrton Didier Sella
  * Erick Palma Banda
  * Illia Zhuraveluno
* **Curso:** 2 DAM A
* **Fecha de inicio:** 22|29/11/2026

## Alineación con los Objetivos de Desarrollo Sostenible (ODS)

* **ODS 4:** Educación - Nuestra app permite organizar el horario escolar, consultar las clases y gestionar las faltas de asistencia de forma sencilla y eficiente.
* **ODS 12:** Producción responsable - Al utilizar una aplicación móvil para gestionar el horario y las faltas, reducimos el uso de papel y fomentamos hábitos más sostenibles.
* **ODS 15:** Vida terrestre -  Al reducir el consumo de papel, contribuimos a disminuir la tala de árboles y a proteger los bosques y la biodiversidad.

## Descripción del Problema

Muchas veces resulta difícil organizar las tareas y actividades del día a día. Es fácil olvidarse de exámenes, trabajos, reuniones o incluso del horario de clase o de trabajo.

## Descripción de la Solución Propuesta

Nuestra aplicación permite organizar de forma sencilla los horarios escolares y laborales desde el móvil. También permite añadir eventos importantes, como exámenes, entregas de trabajos o reuniones, y recibir notificaciones para no olvidarlos. Además, incluye una función para gestionar las faltas de asistencia y llevar un mejor control de ellas.

## Actores y Roles

* **Estudiantes:** Usuario
* **Trabajadores:** Usuario

## Arquitectura general

En pricipio seria una app Android a la que conectaríamos una BD SQlite para guardar los datos. Después haríamos una implementación con una base de datos en remoto.

## Casos de Uso Principales

### Para Estudiantes (App Móvil)

| Caso de Uso | Descripción | Prioridad |
| --- | --- | --- |
| 1 | Crear asignaturas | Alta |
| 2 | Asignar asignaturas | Alta |
| 3 | Introducir eventos | Alta |
| 4 | Crear horario | Alta |
| 5 | Respaldar usuario en BD SQLite | Alta |
| 6 | Ver horario | Media |
| 7 | Modificar horario | Media |
| 8 | Modificar asignaturas | Media |
| 9 | Introducir falta | Media |
| 10 | Ver faltas restantes | Media |
| 11 | Modificar faltas | Media |
| 12 | Mostrar notificaciones | Media |
| 13 | Registrar usuario | Baja |
| 14 | Eliminar usuario | Baja |
| 15 | Modificar usuario | Baja |
| 16 | Asignar correos | Baja |
| 17 | Mandar correos | Baja |
| 18 | Exportar horarios | Baja |
| 19 | Importar horarios | Baja |

### Para Trabajadores (App Móvil)

| Caso de Uso | Descripción | Prioridad |
| --- | --- | --- |
| 1 | Crear horas de trabajo | Alta |
| 2 | Asignar horas trabajo | Alta |
| 3 | Introducir eventos | Alta |
| 4 | Crear horario | Alta |
| 5 | Respaldar usuario en BD SQLite | Alta |
| 6 | Ver horario | Media |
| 7 | Modificar horario | Media |
| 8 | Modificar horas trabajo | Media |
| 9 | Mostrar notificaciones | Media |
| 10 | Registrar usuario | Baja |
| 11 | Eliminar usuario | Baja |
| 12 | Modificar usuario | Baja |
| 13 | Asignar correos | Baja |
| 14 | Mandar correos | Baja |
| 15 | Exportar horarios | Baja |
| 16 | Importar horarios | Baja |

## Riesgos y mitigación

| Riesgo | Mitigación |
| --- | --- |
| Gestionar usuarios | Diferenciar entre permisos de trabajadores y estudiantes |
| Falta experiencia | Uso de IA para hacer el código |
| Falta de compromiso | Reuniones semanales y revisión de progreso |
| Falta experiencia en Git | Practicar y usar Git |
| Notificaciones | Usar un sistema de recordatorios |
| Resolver conflictos varios horarios | Permitir crear varios horarios |

## Planificación aproximada Sprints por quincena

### Calendario de Sprints y Fases de Desarrollo

|   Sprint   |  Semanas   |   Fechas   | Objetivo Principal | Entregable Clave |
| :--------: | :--------: | :--------: | :----------------- | :--------------- |
| 1 | 1/2 | 29/11/26 | Planificar el proyecto  | Repositorio Github con archivo PROYECTO.md y pdf en aules       |
| 2 | 2/3 | 05/11/26 | <!-- * --> | <!-- * --> |
| 3 | 3/4 | 12/11/26 | <!-- * --> | <!-- * --> |
| 4 | 4/5 | 19/11/26 | <!-- * --> | <!-- * --> |
| 5 | 5/6 | 26/11/26 | <!-- * --> | <!-- * --> |


### Reparto de Funcionalidades Individuales (Fase FE)

<!-- * -->

1. **<!-- * -->:**
   - <!-- * -->
2. **<!-- * -->:**
   - <!-- * -->
3. **<!-- * -->:**
   - <!-- * -->
4. **<!-- * -->:**
   - <!-- * -->

## Organización repositorio

```txt
https://github.com/aiaea-dam/proyecto.git
|-- docs/
|     |-- PROYECTO.md
|     |-- DISEÑO.md
|     |-- diarios
|            |-- Aaron_Quirant.md
|            |-- Alavaro_Monsonis.md
|            |-- Ayrton_Sella.md
|            |-- Erick_Palma.md
|            |-- Illia_Zhuravel.md
|-- backend/
|-- frontend-android/
```
