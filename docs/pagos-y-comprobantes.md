# Pagos y comprobantes — Olimpiadas FNI

Este documento describe el costo de inscripción, el método de pago y la validación de los comprobantes de pago dentro del sistema.

## 1. Costo de inscripción

La inscripción tiene un costo de **Bs 20 por estudiante y por área**.

| Áreas seleccionadas | Costo total |
| --- | ---: |
| 1 | Bs 20 |
| 2 | Bs 40 |
| 3 | Bs 60 |

En las inscripciones por delegación, el importe total es la suma de los importes de cada estudiante.

## 2. Método de pago

El método de pago principal es **QR Simple / banca móvil**:

1. El sistema muestra el resumen de áreas y el importe total a pagar.
2. El Tutor o el participante paga escaneando el QR con la aplicación de banca móvil de su entidad.
3. Conserva el comprobante de pago que emite su entidad.

## 3. Validación de comprobantes de pago

### 3.1 Estados del pago

| Estado | Significado |
| --- | --- |
| Pendiente | El pago fue informado, pero aún no se verificó. |
| Confirmado | El pago fue verificado y la inscripción queda confirmada. |

### 3.2 Proceso de validación

1. Al confirmar la inscripción, el pago queda en estado **pendiente**.
2. El Tutor o el participante registra en el sistema el comprobante de pago, con su referencia de transacción.
3. El sistema valida que:
   - el monto pagado coincida con el importe total de la inscripción;
   - la referencia de transacción no haya sido usada en otra inscripción;
   - el comprobante corresponda a la inscripción que se está pagando.
4. Si la validación es correcta, el pago pasa a **confirmado** y la inscripción queda confirmada.
5. Si la validación falla, el pago permanece **pendiente** y el sistema informa el motivo para que el usuario corrija el dato o consulte a la organización.

Subir una captura o mostrar el QR no equivale por sí solo a un pago confirmado.

### 3.3 Comprobante de inscripción

Una vez confirmado el pago, el sistema emite un comprobante con los datos de la inscripción, el importe, la fecha, el estado y la referencia de transacción. El Tutor puede consultarlo desde el sistema.
