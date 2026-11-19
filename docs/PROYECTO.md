# Propuesta de Proyecto: <!-- TITULO PROYECTO -->

## Título del Proyecto

Timely

<!-- IMAGEN -->

## Datos del Equipo

* **Nombre del Proyecto:** Timely
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

* **Usuario General:** Estudiantes, trabajadores o cualquier persona que requiera gestionar su tiempo, horarios y actividades bajo un modelo flexible y unificado.

## Arquitectura general

Aplicación móvil Android nativa desarrollada con Kotlin y Jetpack Compose (Material 3). Implementa una arquitectura MVVM (Model-View-ViewModel) con persistencia local reactiva mediante Room Database (SQLite) y Kotlin Coroutines / Flow. En una fase posterior, se integrará una sincronización con backend remoto.

## Casos de Uso Principales (Modelo Unificado)

| Caso de Uso | Descripción | Prioridad |
| --- | --- | --- |
| 1 | **Crear y gestionar actividades:** Crear materias, turnos de trabajo o tareas con nombre, color, ubicación, contacto y horas planificadas | Alta |
| 2 | **Asignar actividades al horario:** Ubicar actividades en franjas horarias semanales recurrentes (día de la semana, hora inicio/fin) | Alta |
| 3 | **Visualizar cuadrícula de horario:** Vista interactiva diaria y semanal con Jetpack Compose | Alta |
| 4 | **Modificar y eliminar franjas horarias:** Editar horas o eliminar franjas recurrentes del horario | Alta |
| 5 | **Cancelar instancia puntual de horario:** Anular una clase o turno en una fecha específica sin afectar la regla recurrente semanal | Alta |
| 6 | **Cálculo y seguimiento del total de horas:** Visualizar automáticamente el cómputo total de horas semanales y por actividad | Alta |
| 7 | **Persistencia local (Room SQLite):** Guardado reactivo y local de todas las actividades, horarios y eventos | Alta |
| 8 | **Introducir eventos en la agenda:** Registrar exámenes, entregas o reuniones asociados a una actividad o fecha específica | Media |
| 9 | **Consultar y modificar eventos:** Calendario y feed cronológico de eventos próximos | Media |
| 10 | **Registrar faltas de asistencia:** Anotar faltas justificadas/no justificadas vinculadas a actividades con control de asistencia | Media |
| 11 | **Control y alerta de faltas restantes:** Cálculo automático de horas de falta restantes según el límite establecido | Media |
| 12 | **Notificaciones y recordatorios:** Avisos push locales previos al inicio de actividades o eventos (WorkManager / AlarmManager) | Media |
| 13 | **Detección y resolución de solapamientos:** Advertir o prevenir colisiones entre actividades en la misma franja horaria | Media |
| 14 | **Configurar perfil y preferencias:** Ajustar tema visual (claro/oscuro), horas visibles del horario y datos de usuario | Baja |
| 15 | **Contactar vía correo electrónico:** Apertura directa del gestor de correo (Intent Android) con el contacto asignado a la actividad | Baja |
| 16 | **Exportar horario y datos:** Exportación de cuadrícula y eventos a JSON / iCalendar (.ics) mediante SAF (Storage Access Framework) | Baja |
| 17 | **Importar horario y datos:** Carga de horarios compartidos en formato estándar | Baja |
| 18 | **Sincronización remota (Fase 2):** Respaldo y sincronización con base de datos / API en la nube | Baja |

## Riesgos y mitigación

| Riesgo | Mitigación |
| --- | --- |
| Conflictos y solapamiento de horarios | Algoritmo de validación de solapamiento en ViewModel antes de persistir franjas |
| Cancelación puntual alterando recurrencia | Tabla de excepciones (`SlotCancellationEntity`) que anula solo la fecha indicada |
| Falta de experiencia en Android / Compose | Uso de documentación oficial de Jetpack Compose, patrones recomendados e IA como apoyo |
| Falta de compromiso | Reuniones semanales y revisión de progreso según calendario de Sprints |
| Falta de experiencia en Git | Flujo de trabajo con ramas por funcionalidad y revisiones de código |
| Fiabilidad de notificaciones en segundo plano | Uso de `WorkManager` y `AlarmManager` con gestión de canales y permisos de Android 13+ |

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
