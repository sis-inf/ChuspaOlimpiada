# Funcionalidades de ChuspaOlimpiada

## 1. Introducción

ChuspaOlimpiada es un proyecto de plataforma web orientado a facilitar la gestión, el registro de participantes y el seguimiento de la Olimpiada Científica de la Facultad Nacional de Ingeniería (FNI).

El sistema busca organizar los procesos relacionados con las inscripciones, las áreas de competencia, los pagos, los cronogramas y la administración de la información de los participantes.

**Estado del proyecto:** las funcionalidades descritas a continuación corresponden a requerimientos y procesos documentados. No deben interpretarse como características ya implementadas.

## 2. Gestión de participantes e inscripciones

### 2.1. Inscripción individual

Se contempla el registro de estudiantes mediante un formulario que permita ingresar sus datos personales, institución educativa, grado académico y áreas de competencia seleccionadas.

El proceso incluirá la revisión de los datos antes de confirmar la inscripción.

### 2.2. Inscripción por delegación

Se prevé la inscripción de varios estudiantes mediante un tutor o responsable institucional.

Esta modalidad permitirá organizar los registros por institución y aplicar las validaciones correspondientes a cada participante.

### 2.3. Validación de inscripciones

El sistema deberá verificar:

- Identidad y grado académico del participante.
- Campos obligatorios y formatos de datos.
- Inscripciones duplicadas en una misma área.
- Selección de un máximo de tres áreas por estudiante.
- Compatibilidad entre el grado académico y las categorías permitidas.
- Posibles conflictos de horarios entre las áreas seleccionadas.
- Cumplimiento de los plazos establecidos para cada inscripción.

Estas validaciones buscan reducir errores y mantener la consistencia de los registros.

## 3. Gestión de áreas de competencia

La plataforma contempla la organización de las disciplinas de la Olimpiada Científica FNI.

### 3.1. Áreas científicas

- Biología.
- Química.
- Astronomía y Astrofísica.
- Matemáticas.
- Geografía.
- Física.

### 3.2. Áreas de tecnología e innovación

- Diseñadores y Fabricadores.
- Medio Ambiente.
- Energías.
- Programación.
- Redes y Ciberseguridad.
- Robótica.

Cada área puede tener requisitos de participación, categorías, modalidades de evaluación y fechas específicas, conforme a su convocatoria oficial.

## 4. Gestión de pagos

Se contempla el cálculo del costo de inscripción según la cantidad de áreas seleccionadas por cada estudiante.

La documentación de referencia establece un monto de Bs 20 por estudiante y por área para la convocatoria FNI 2026.

Las funcionalidades propuestas incluyen:

- Cálculo del importe total de inscripción.
- Presentación del resumen de áreas seleccionadas.
- Registro de pagos mediante un mecanismo autorizado.
- Posible incorporación de pagos mediante QR bancario, previa aprobación institucional.
- Verificación del pago antes de confirmar su estado.
- Emisión de comprobantes de pago e inscripción cuando el procedimiento esté habilitado.

El pago mediante QR bancario es una propuesta técnica y no debe confundirse con el QR utilizado para acceder a formularios.

## 5. Organización de pruebas y cronogramas

El proyecto contempla un procedimiento para organizar las evaluaciones de las diferentes disciplinas.

Entre las funcionalidades previstas se encuentran:

- Registro de fechas, sedes y aulas disponibles.
- Asignación de pruebas a disciplinas y etapas.
- Verificación de conflictos de horarios y espacios.
- Publicación del cronograma autorizado.
- Comunicación de modificaciones posteriores mediante avisos.

También se propone controlar los plazos de inscripción por área y modalidad, incluyendo el cierre automático cuando corresponda.

## 6. Seguimiento de resultados

Uno de los objetivos generales del proyecto es facilitar el seguimiento de los resultados de la Olimpiada Científica FNI.

Este componente se identifica como parte del alcance previsto de la plataforma. Sin embargo, la documentación revisada todavía no define sus operaciones específicas, criterios de publicación ni mecanismos de consulta.

Por lo tanto, estas características requieren mayor especificación antes de considerarse funcionalidades desarrolladas.

## 7. Gestión de usuarios y seguridad

La documentación de requerimientos identifica tres roles principales:

- **Tutor:** responsable de participar en los procesos de registro según los permisos asignados.
- **Coordinador:** vinculado a la organización y administración de actividades de la Olimpiada.
- **Administrador:** rol previsto para las funciones de administración de la plataforma.

Se establecen como requerimientos de seguridad y control:

- Protección de los datos personales de los participantes, especialmente de menores de edad.
- Restricción del acceso a información y operaciones según el rol.
- Registro de quién crea o modifica una inscripción y cuándo se realiza el cambio.

Estos mecanismos están documentados como requerimientos pendientes.

## 8. Acceso a la plataforma

ChuspaOlimpiada está concebido como una plataforma web accesible mediante un navegador.

El objetivo es centralizar la información y facilitar los procesos administrativos relacionados con la Olimpiada Científica FNI.

La arquitectura técnica y los detalles de implementación todavía requieren definición.

## 9. Estado de las funcionalidades

| Área funcional | Estado documentado |
|---|---|
| Inscripción individual | Pendiente |
| Inscripción por delegación | Pendiente |
| Validación de participantes | Pendiente |
| Control de áreas y categorías | Pendiente |
| Cálculo y registro de pagos | Pendiente |
| Emisión de constancias y credenciales | Pendiente |
| Organización de cronogramas | Procedimiento documentado; implementación no verificada |
| Seguimiento de resultados | Objetivo general; pendiente de especificación |
| Seguridad y control de acceso | Pendiente |
| Auditoría de inscripciones | Pendiente |

## 10. Conclusión

ChuspaOlimpiada busca centralizar la administración de la Olimpiada Científica FNI mediante una plataforma web que facilite el registro de participantes, la organización de áreas y pruebas, la gestión de pagos y el seguimiento de resultados.

Las funcionalidades identificadas constituyen una base para orientar el desarrollo del sistema. Su implementación deberá seguir los requerimientos establecidos y las decisiones aprobadas por los responsables del proyecto.

## 11. Documentación de referencia

- [README del proyecto](../README.md)
- [Requerimientos del proyecto](requerimientos.md)
- [Inscripciones y pagos](inscripciones.md)
- [Organización y cronograma](organizacion-cronograma.md)
- [Tipos de pruebas](docs/tipos-de-prueba.md)
- [Reglamento](REGULATION.md)