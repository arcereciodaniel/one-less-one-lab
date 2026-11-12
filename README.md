# one - one — Lab

Laboratorio de **one - one**, software de finanzas personales desarrollado por **rastro.** Esta versión mantiene categorías genéricas y almacenamiento independiente de la versión Daniel.

**Versión:** v8.3.0 LAB — Cobros 2.0 beta, con organización por personas, abonos parciales e indicadores de recuperación.

## Navegación personalizable

- **Fijos:** Inicio, Presupuesto y Movimientos.
- **Opcionales:** Deudas y Cobros (beta). Activá u ocultá cada uno desde **Módulos ⚙** en la barra superior.
- Ocultar un módulo no elimina sus datos. Las preferencias se guardan en el navegador.

## Cobros — Beta

El módulo permite registrar persona, concepto, fecha de cargo, fecha de recordatorio, importe, moneda y notas; agrupar cargos por persona o concepto; y crear recurrencias mensuales. La vista **Personas** muestra total recibido y pendiente, mientras que **Grupos** conserva la organización original. Se admite historial de abonos parciales, reversión de abonos y estados pendiente/parcial/pagado. Inicio muestra recordatorios que se pueden anticipar (0, 1, 3 o 7 días) o posponer 3 días, y Cobros ofrece indicadores de recuperación y vencimientos.

**Alcance:** los avisos aparecen dentro de la aplicación; no se envían notificaciones de sistema ni correos. Marcar un cobro como pagado no registra automáticamente un ingreso en Movimientos.

## Datos

Los registros se guardan localmente en el navegador, sin sincronizarse con la versión Daniel. Antes de limpiar datos o cambiar de navegador, utilizá **Respaldar** para exportar el archivo JSON. Los módulos opcionales no modifican los movimientos ni los presupuestos existentes.

Repositorio: `arcereciodaniel/one-less-one-lab`.
