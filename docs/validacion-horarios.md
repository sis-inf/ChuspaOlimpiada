# Validación de choque de horarios en la inscripción

## 1. Objetivo

Documentar el procedimiento de validación de horarios durante la inscripción de estudiantes en las áreas de la Olimpiada Científica de la Facultad Nacional de Ingeniería (FNI), evitando que un participante se inscriba en pruebas que coincidan en fecha y hora.

Este documento describe el comportamiento esperado del sistema ChuspaOlimpiada, correspondiente al requerimiento funcional RF-010 definido en `docs/requerimientos.md`.

## 2. Validación durante la inscripción

Un estudiante puede inscribirse hasta en tres áreas, de acuerdo con las condiciones de participación establecidas para la Olimpiada Científica de la FNI.

Al seleccionar una nueva área, el sistema debe realizar las siguientes verificaciones:

1. Obtener las áreas en las que el estudiante ya está inscrito.
2. Consultar las fechas y los horarios de las pruebas correspondientes.
3. Comparar el horario de la nueva área con los horarios de las áreas previamente registradas.
4. Detectar si existe alguna coincidencia o superposición entre las pruebas.
5. Permitir continuar con la inscripción únicamente si no existe incompatibilidad horaria.

La validación debe realizarse antes de confirmar la nueva inscripción.

## 3. Detección de choque de horarios

Se considera que existe un choque de horarios cuando dos pruebas correspondientes a distintas áreas se realizan en la misma fecha y sus intervalos de tiempo se superponen.

Para determinarlo, se deben comparar las fechas, las horas de inicio y las horas de finalización de las pruebas.

Si las fechas son diferentes o los intervalos no se superponen, no existe conflicto horario.

## 4. Comportamiento del sistema ante un choque

Cuando se detecta una incompatibilidad horaria, el sistema debe impedir la inscripción en la nueva área y mostrar un mensaje indicando con qué área existe el conflicto.

El estudiante o tutor debe seleccionar otra área que no presente incompatibilidad horaria.

### Ejemplo

Un estudiante ya está inscrito en el área de Matemáticas, cuya prueba está programada para el 15 de octubre de 09:00 a 11:00.

Posteriormente, intenta inscribirse en Física, cuya prueba está programada para el mismo día de 10:00 a 12:00.

Como ambos horarios se superponen, el sistema debe rechazar la nueva inscripción y mostrar el siguiente mensaje:

> No se puede completar la inscripción en Física porque su horario coincide con la prueba de Matemáticas, en la que el estudiante ya está inscrito.

Este ejemplo utiliza fechas y horarios ficticios únicamente para explicar la validación.

## 5. Cambios posteriores en el cronograma

Si la organización modifica las fechas u horarios de una prueba después de que los estudiantes hayan sido inscritos, el sistema debe verificar nuevamente las posibles incompatibilidades.

El procedimiento esperado es el siguiente:

1. Registrar la modificación del horario de la prueba.
2. Identificar a los estudiantes inscritos en el área afectada.
3. Comparar el nuevo horario con los horarios de sus demás áreas.
4. Detectar los estudiantes que presentan un nuevo choque de horarios.
5. Notificar a los tutores responsables de los estudiantes afectados, indicando las áreas y los horarios involucrados.

La notificación debe permitir que el tutor conozca el conflicto y consulte las indicaciones de la organización para resolverlo.

## 6. Reglas de validación

- La verificación debe realizarse al intentar inscribir al estudiante en una nueva área.
- Deben compararse los horarios de las pruebas de todas las áreas en las que el estudiante ya está inscrito.
- No debe permitirse una nueva inscripción cuando exista incompatibilidad horaria.
- El mensaje de rechazo debe indicar el área con la que existe el conflicto.
- Los cambios posteriores del cronograma deben activar una nueva verificación.
- Los tutores de los estudiantes afectados deben recibir una notificación cuando un cambio genere una incompatibilidad.

## 7. Documentación relacionada

- [Requerimientos del proyecto](requerimientos.md): requerimiento funcional RF-010.
- [Inscripciones y pagos](inscripciones.md): reglas generales de inscripción y validaciones.
- [Áreas de competencia](areas-competencia.md): áreas disponibles en la Olimpiada Científica de la FNI.

**Nota:** este documento establece el comportamiento esperado de la plataforma. Su implementación técnica y el mecanismo de notificaciones deben ser definidos y validados durante el desarrollo del sistema.
