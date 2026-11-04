# Inscripciones y pagos — ChuspaOlimpiada

## Alcance y fuentes

Este documento describe las inscripciones individuales y por delegación para la Olimpiada de Ciencia y Tecnología de la Facultad Nacional de Ingeniería (FNI). Se basa en el [issue #15](https://github.com/sis-inf/ChuspaOlimpiada/issues/15) y la [página oficial de Olimpiadas FNI](https://www.fni.uto.edu.bo/index.php/publicaciones/olimpiadas).

**Distinción importante:** los datos publicados por la FNI deben prevalecer sobre este documento. Las validaciones técnicas, el cierre automático, el pago por QR bancario y la emisión electrónica de comprobantes son **flujos propuestos** para ChuspaOlimpiada, no funcionalidades verificadas como implementadas ni procedimientos oficiales confirmados. El QR de acceso al formulario no debe confundirse con un QR de pago.

## 1. Inscripción individual (flujo propuesto)

1. El estudiante o su tutor abre el formulario de inscripción habilitado por la organización.
2. Completa identidad, unidad educativa, grado o curso y datos de contacto exigidos.
3. Selecciona entre una y tres áreas disponibles para su grado.
4. El sistema verifica identidad, grado, duplicados, cantidad de áreas, incompatibilidad horaria y plazo vigente.
5. Se muestra el resumen de áreas y costo total para su revisión.
6. El participante confirma sus datos y sigue las instrucciones oficiales de pago.
7. Una vez verificado el pago por el medio autorizado, se confirma la inscripción y se entrega el comprobante, cuando esta función esté habilitada.

**Por confirmar:** la convocatoria contempla la intervención del director o tutor; la disponibilidad de inscripción autónoma individual debe ser aprobada por los responsables.

## 2. Inscripción por delegación (flujo propuesto)

1. El director o tutor responsable identifica la unidad educativa y registra sus datos de contacto.
2. Añade a cada estudiante con su identidad, grado y áreas solicitadas.
3. Se ejecutan **las mismas validaciones para cada estudiante** que en la inscripción individual.
4. Se presenta un resumen por estudiante y área, junto al importe total.
5. El responsable revisa, corrige errores y confirma el registro de la delegación.
6. Se tramita el pago por el medio oficial; solo después de su verificación se registran los pagos como confirmados.
7. Se emiten los comprobantes correspondientes cuando exista un procedimiento aprobado.

La modalidad grupal no permite omitir requisitos individuales ni exceder los plazos de cada área.

## 3. Validaciones

| Control | Regla | Respuesta ante incumplimiento |
| --- | --- | --- |
| Identidad | Comprobar datos obligatorios y consistencia de la identificación; definir los campos exactos con la organización. | Solicitar corrección antes de confirmar. |
| Grado o curso | Verificar que el curso sea admitido para el área y categoría conforme a su convocatoria. | No permitir esa selección. |
| Duplicados | Propuesta: detectar la misma combinación estudiante + edición + área, evitando doble registro o cobro. | Mostrar el registro existente. |
| Máximo de áreas | La convocatoria FNI 2026 establece **hasta tres áreas por estudiante**. | Impedir seleccionar una cuarta área. |
| Incompatibilidad horaria | Propuesta: comparar horarios de las pruebas obligatorias de las áreas seleccionadas. | Bloquear combinaciones superpuestas y solicitar un cambio. |
| Plazo | Verificar el cierre vigente para cada área y modalidad. | No aceptar inscripciones fuera de plazo. |

Las verificaciones deben repetirse **al confirmar** para evitar registros inválidos si cambian los datos, horarios o fechas durante el llenado.

### Cursos admitidos (referencia general FNI 2026)

| Área | Cursos o categorías |
| --- | --- |
| Biología | 3.º a 6.º de secundaria |
| Química | 1.º a 6.º |
| Astronomía y Astrofísica | 2.º a 6.º |
| Matemática | 1.º a 6.º |
| Geografía | 3.º a 6.º |
| Física | 3.º a 6.º |
| Diseñadores y Fabricadores | 1.º a 6.º; categoría A: 1.º a 4.º, B: 5.º y 6.º |
| Medio Ambiente | 5.º y 6.º |
| Energías | 3.º a 6.º |
| Programación | Básico: 3.º a 5.º; avanzado: 6.º |
| Redes y Ciberseguridad | Nivel 1: 3.º a 5.º; nivel 2: 6.º |
| Robótica | Nivel 1: hasta 2.º; nivel 2: 3.º y 4.º; nivel 3: 5.º y 6.º |

Consultar siempre la convocatoria específica para requisitos, excepciones y categorías adicionales.

## 4. Costo por área

La convocatoria general de la FNI 2026 indica **Bs 20 por estudiante y área**.

| Áreas seleccionadas | Costo total |
| --- | ---: |
| 1 | Bs 20 |
| 2 | Bs 40 |
| 3 | Bs 60 |

**Fórmula:** `total = número de inscripciones válidas por área × Bs 20`.

En delegaciones se suman los importes de cada estudiante. No duplicar cargos para una misma edición, área y participante. Descuentos o exenciones requieren aprobación institucional.

## 5. Fechas límite y cierre automático

Las fechas **varían por área**. Como referencia, la convocatoria general FNI 2026 presenta estos plazos, que deben cotejarse con cada convocatoria específica antes de configurarlos:

| Área | Plazo publicado |
| --- | --- |
| Biología | 18 de agosto, 12:00; verificar el día de la semana indicado en la publicación |
| Química | Teórica: 1 de septiembre, 18:00; experimental: 8 de septiembre, 18:00 |
| Astronomía y Astrofísica | 4 de septiembre, 17:00 |
| Matemática | 3 al 11 de septiembre; atención de 09:00 a 12:00 |
| Geografía | 23 de septiembre, 17:00 |
| Física | 25 de septiembre, 12:00 |
| Diseñadores y Fabricadores | 2 de octubre, 17:30 |
| Medio Ambiente | 1 al 7 de octubre; atención de 09:00 a 12:00 y 15:00 a 17:00 |
| Energías | 9 de octubre, 17:00 |
| Programación | 1 de septiembre al 14 de octubre; atención de 08:30 a 12:00 y 14:30 a 18:00 |
| Redes y Ciberseguridad | 18 de septiembre al 20 de octubre; atención de 14:30 a 18:30 |
| Robótica | 1 al 21 de octubre, hasta las 17:30 |

**Propuesta de cierre automático:** configurar por edición, área y modalidad una fecha/hora de cierre en la zona `America/La_Paz`. Al alcanzarla, bloquear nuevas confirmaciones y mostrar «Inscripción cerrada», conservando registros anteriores. Revalidar el plazo al confirmar incluso si el formulario se abrió antes del cierre. Cuando la convocatoria solo indique **horarios de atención**, no asumir que equivalen a un cierre digital: solicitar confirmación a la organización.

## 6. Pago por QR y comprobante (propuesta pendiente de aprobación)

La página de Olimpiadas FNI menciona un QR para **acceder al formulario**; esto **no acredita** que exista un QR bancario de pago habilitado. Si la organización aprueba el pago por QR, el flujo recomendado es:

1. Mostrar el desglose de áreas y el importe total.
2. Presentar **únicamente** el QR de cobro oficial y las instrucciones proporcionadas por la organización.
3. Registrar el pago inicialmente como `pendiente`.
4. Verificar el abono mediante el mecanismo autorizado; visualizar el QR o subir una captura no equivale por sí solo a pago confirmado.
5. Tras la verificación, cambiar el estado a `confirmado` y emitir un comprobante.
6. Incluir en el comprobante identificador único, edición, participante o delegación, áreas, importe, fecha, estado y referencia de transacción si corresponde.
7. Permitir consultar o descargar el comprobante con protección de datos personales.

**Pendiente de definición:** cuenta beneficiaria, proveedor de pagos, verificación y conciliación, tratamiento de pagos fallidos o duplicados y formato oficial del comprobante. No inventar datos bancarios ni prometer emisión automática antes de su implementación.

## 7. Estado de las reglas

- **Referencia de la convocatoria:** máximo tres áreas, costo de Bs 20 por estudiante y área, requisitos por curso y fechas diferenciadas.
- **Propuesta de plataforma:** flujos digitales individuales y grupales, validaciones automáticas, detección de duplicados, incompatibilidades horarias, cierre automático, pago por QR bancario y comprobantes electrónicos.

Antes de implementar las propuestas, el equipo debe validarlas con los responsables de las Olimpiadas FNI.
