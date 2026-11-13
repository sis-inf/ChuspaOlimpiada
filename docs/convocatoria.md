# Apertura y publicación de una convocatoria

## Objetivo y alcance

Este documento describe el procedimiento que debe seguir el Administrador para preparar y publicar una nueva edición de la Olimpiada Científica de la Facultad Nacional de Ingeniería (FNI) en ChuspaOlimpiada. También establece qué información debe quedar configurada antes de habilitar las inscripciones y cómo se aplica el cierre de los plazos.

El procedimiento recoge los requisitos del [issue #50](https://github.com/sis-inf/ChuspaOlimpiada/issues/50) y toma como referencia la [página oficial de Olimpiadas de la FNI](https://www.fni.uto.edu.bo/index.php/publicaciones/olimpiadas). La convocatoria oficial y sus documentos adjuntos son la fuente de verdad para los datos de cada edición. Si existe alguna diferencia, prevalece la información publicada por la FNI.

## 1. Responsables

| Responsable | Responsabilidad |
| --- | --- |
| Administrador | Crear la edición, registrar y revisar su configuración, adjuntar los documentos oficiales de cada área y publicar la convocatoria. Es el único rol autorizado para crear una edición. |
| Organización o responsables de área | Proporcionar y validar la información oficial de las áreas, grados o categorías, costos, fechas y documentos PDF correspondientes. |
| Estudiantes, tutores y unidades educativas | Consultar la convocatoria publicada y realizar las inscripciones dentro de los plazos habilitados, de acuerdo con las reglas de cada área. |

La configuración y publicación son tareas administrativas. Los participantes no pueden crear ediciones ni habilitar por su cuenta una convocatoria.

## 2. Información que se configura en cada edición

Antes de publicar, el Administrador debe registrar y comprobar los siguientes datos:

| Dato | Descripción y regla |
| --- | --- |
| Edición | Identificador o gestión a la que corresponde la convocatoria. |
| Áreas | Lista de áreas que participarán en esa edición. Cada área debe estar identificada y contar con su información específica. |
| Grados y categorías | Cursos, niveles o categorías admitidos en cada área. Deben coincidir con la convocatoria oficial y sus anexos. |
| Costo | **Bs. 20 por estudiante y por área**, según la convocatoria general FNI 2026. Si una nueva convocatoria oficial establece otro importe, se debe registrar el importe vigente de esa edición. |
| Límite de áreas | Un estudiante puede inscribirse en un máximo de **tres áreas** por edición, de acuerdo con la convocatoria general FNI 2026 y el reglamento correspondiente. |
| Fechas de inscripción | Fecha y hora de inicio y fecha y hora límite que correspondan a cada área. Los plazos pueden ser diferentes entre áreas y modalidades. |
| Documento de convocatoria | Archivo PDF oficial correspondiente a cada área. Debe asociarse al área correcta para que los participantes puedan consultarlo. |

**Importante:** los Bs. 20 y el máximo de tres áreas son los datos indicados por la convocatoria general FNI 2026. No deben tratarse como valores invariables para futuras gestiones: el Administrador debe verificar la convocatoria oficial de la nueva edición antes de guardarlos.

Para ampliar la información sobre los cursos y categorías, consultar [Grados y niveles por área](grados-y-niveles.md). Para las reglas del registro y los pagos, consultar [Inscripciones y pagos](inscripciones.md).

## 3. Procedimiento de apertura de una edición

El proceso debe realizarse en el siguiente orden:

1. **Reunir la información oficial.** El Administrador obtiene la convocatoria general vigente, los datos confirmados por los responsables de área y el PDF específico de cada área. No debe completar datos faltantes mediante suposiciones.
2. **Crear la edición.** El Administrador registra una nueva edición en la plataforma. Esta operación está reservada exclusivamente al rol Administrador.
3. **Configurar las áreas.** Se incorporan las áreas que participarán en esa edición y se vincula a cada una su información correspondiente.
4. **Configurar grados y categorías.** Para cada área se registran los cursos, niveles o categorías admitidos, de acuerdo con los documentos oficiales.
5. **Configurar costos y límite de participación.** Se registra el costo por estudiante y área y se establece el máximo de tres áreas por estudiante cuando así lo disponga la convocatoria vigente.
6. **Configurar los plazos.** Se registran las fechas y horas de inscripción para cada área. Si una misma área tiene modalidades o etapas con plazos distintos, estos deben identificarse y configurarse de acuerdo con la convocatoria específica.
7. **Adjuntar los PDF.** Se carga el PDF oficial de cada área y se comprueba que el archivo esté asociado al área correcta, que pueda abrirse y que corresponda a la edición que se está preparando.
8. **Revisar la configuración.** Antes de publicar, el Administrador verifica áreas, cursos, costos, límites, fechas y documentos. Los datos deben coincidir con la convocatoria oficial.
9. **Publicar la convocatoria.** Una vez completada y revisada la información, el Administrador publica la edición y deja disponible la convocatoria y los PDF de sus áreas.
10. **Habilitar las inscripciones.** Las inscripciones se habilitan únicamente después de que la convocatoria haya sido publicada y cuando se hayan cumplido las fechas y condiciones configuradas para el registro.

No se deben aceptar inscripciones de una edición cuya convocatoria todavía no haya sido publicada.

## 4. Revisión previa a la publicación

Antes de publicar, el Administrador debe comprobar:

- [ ] La edición corresponde a la gestión correcta.
- [ ] Se incluyeron todas las áreas confirmadas por la organización.
- [ ] Los grados, niveles y categorías coinciden con los documentos oficiales.
- [ ] El costo por estudiante y área corresponde a la convocatoria vigente.
- [ ] Está configurado el máximo de áreas permitido por estudiante.
- [ ] Cada área tiene sus fechas y horas de inscripción correctamente registradas.
- [ ] Se adjuntó el PDF oficial de cada área.
- [ ] Cada PDF se puede abrir y corresponde al área y edición correctas.
- [ ] La información publicada coincide con la convocatoria oficial de la FNI.

Si se detecta un error o falta un documento, se debe corregir antes de publicar. No se debe habilitar el registro con información incompleta o sin validar.

## 5. Publicación y habilitación de inscripciones

La publicación de la convocatoria y la apertura de las inscripciones son pasos relacionados, pero no equivalentes:

- **Convocatoria no publicada:** la edición todavía no está disponible para recibir inscripciones.
- **Convocatoria publicada:** los participantes pueden consultar la información general y los PDF oficiales de las áreas.
- **Inscripciones habilitadas:** el registro puede realizarse cuando la convocatoria ya está publicada y se encuentra dentro del período de inscripción configurado para el área correspondiente.

La publicación no debe interpretarse como autorización para aceptar inscripciones fuera de las fechas establecidas. La plataforma debe respetar los plazos de cada área.

## 6. Cierre automático de inscripciones

Las inscripciones deben cerrarse automáticamente al llegar la fecha y hora límite configuradas para el área correspondiente.

El comportamiento esperado es el siguiente:

1. Cada área tiene su propio plazo de inscripción, conforme a la convocatoria oficial.
2. Antes de la fecha y hora límite, el registro permanece habilitado si la convocatoria fue publicada y se cumplen las demás condiciones.
3. Al alcanzar la fecha y hora límite, el sistema deja de aceptar nuevas inscripciones para esa área.
4. El participante debe recibir una indicación clara de que el período de inscripción está cerrado.
5. Los registros realizados antes del cierre deben conservarse; el cierre no debe eliminarlos ni modificarlos.
6. El cierre de un área no debe cerrar anticipadamente las inscripciones de otras áreas que todavía tengan un plazo vigente.

Si la convocatoria oficial especifica fechas distintas para etapas o modalidades de una misma área, se deben respetar esos plazos y no sustituirlos por una fecha general.

## 7. Referencia oficial y actualización por edición

La [página oficial de Olimpiadas de la FNI](https://www.fni.uto.edu.bo/index.php/publicaciones/olimpiadas) publica la convocatoria general, las condiciones de participación y los documentos PDF específicos de las áreas. Para la convocatoria general 2026 se indica, entre otros aspectos, un costo de Bs. 20 por estudiante y por área, un máximo de tres áreas por estudiante y fechas límite definidas por área.

Estos datos sirven como referencia de la edición 2026. Para abrir una edición posterior, el Administrador debe consultar la publicación oficial correspondiente a esa gestión y actualizar los valores, fechas, cursos, categorías y documentos según lo que se haya aprobado.

## 8. Reglas que deben respetarse

- Solo el Administrador puede crear una edición.
- La información de cada edición debe proceder de la convocatoria oficial y de los responsables de área.
- Cada área debe tener configurados sus grados o categorías, costos y plazos aplicables.
- Debe adjuntarse el PDF oficial correspondiente a cada área.
- La convocatoria debe publicarse antes de habilitar las inscripciones.
- Las inscripciones se cierran automáticamente al llegar el plazo configurado para cada área.
- El cierre de un área no debe afectar a las demás áreas que continúen dentro de su período de inscripción.
- Los datos de una nueva gestión deben verificarse nuevamente; no se deben reutilizar fechas ni documentos de una edición anterior sin validación.

---

**Fuente institucional:** [IX Olimpiadas de Ciencia y Tecnología — Facultad Nacional de Ingeniería](https://www.fni.uto.edu.bo/index.php/publicaciones/olimpiadas).