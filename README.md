# one - one — Lab

Laboratorio de **one - one**, software de finanzas personales desarrollado por **rastro.** Esta versión mantiene categorías genéricas y almacenamiento independiente de la versión Daniel.

**Versión:** v8.4.0 LAB — Movimientos 2.0 y Cobros 2.0 beta.

## Navegación personalizable

- **Fijos:** Inicio, Presupuesto y Movimientos.
- **Opcionales:** Deudas y Cobros (beta). Activá u ocultá cada uno desde el botón **+** del menú, después del último módulo visible.
- Ocultar un módulo no elimina sus datos. Las preferencias se guardan en el navegador.

## Movimientos 2.0

- Registro rápido de gastos, ingresos y pagos de deudas, con cuenta y método de pago opcionales.
- **Editar**, **Repetir** y **Programar** desde el historial. La edición y eliminación generan un registro local de cambios.
- Plantillas recurrentes semanales, cada 14 días, mensuales o anuales. **Nunca generan movimientos reales sin confirmación**; al registrarlas, se calcula la próxima fecha.
- Distribución de un gasto entre varias categorías: la suma debe coincidir exactamente con el movimiento original y la liquidez se descuenta **una sola vez**.
- Filtros por período, tipo, categoría, fecha, cuenta, moneda, texto y monto original. El CSV exporta la selección filtrada.
- Cuentas configurables y método de pago. La actividad neta por cuenta **no equivale a un saldo bancario conciliado**.
- Advertencias ante posibles duplicados y registro local de creaciones, ediciones y eliminaciones efectuadas desde la versión 8.4.0.

## Cobros — Beta

El módulo permite registrar persona, concepto, fecha de cargo, fecha de recordatorio, importe, moneda y notas; agrupar cargos por persona o concepto; y crear recurrencias mensuales. La vista **Personas** muestra total recibido y pendiente, mientras que **Grupos** conserva la organización original. Se admite historial de abonos parciales, reversión de abonos y estados pendiente/parcial/pagado. Inicio muestra recordatorios que se pueden anticipar (0, 1, 3 o 7 días) o posponer 3 días, y Cobros ofrece indicadores de recuperación y vencimientos.

**Alcance:** los avisos aparecen dentro de la aplicación; no se envían notificaciones de sistema ni correos. Marcar un cobro como pagado no registra automáticamente un ingreso en Movimientos.

## Datos

Los registros se guardan localmente en el navegador, sin sincronizarse con la versión Daniel. Antes de limpiar datos o cambiar de navegador, utilizá **Respaldar** para exportar el archivo JSON. Los módulos opcionales no modifican los movimientos ni los presupuestos existentes.

Repositorio: `arcereciodaniel/one-less-one-lab`.
