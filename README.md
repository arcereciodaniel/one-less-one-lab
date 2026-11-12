# one - one — Lab

Laboratorio de **one - one**, software de finanzas personales desarrollado por **rastro.** Esta versión mantiene categorías genéricas y almacenamiento independiente de la versión Daniel.

**Versión:** v8.2.0 LAB — primera beta de módulos opcionales y Cobros.

## Navegación personalizable

- **Fijos:** Inicio, Presupuesto y Movimientos.
- **Opcionales:** Deudas y Cobros (beta). Activá u ocultá cada uno desde **Módulos ⚙** en la barra superior.
- Ocultar un módulo no elimina sus datos. Las preferencias se guardan en el navegador.

## Cobros — Beta

El módulo permite registrar persona, concepto, fecha del cargo, fecha de recordatorio, importe, moneda y notas. Los cargos pueden agruparse por persona o motivo y configurarse como mensuales. El módulo incluye estados pendiente/pagado y un recordatorio visible en Inicio para cobros vencidos o próximos.

**Alcance:** los avisos aparecen dentro de la aplicación; no se envían notificaciones de sistema ni correos. Marcar un cobro como pagado no registra automáticamente un ingreso en Movimientos.

## Datos

Los registros se guardan localmente en el navegador, sin sincronizarse con la versión Daniel. Antes de limpiar datos o cambiar de navegador, utilizá **Respaldar** para exportar el archivo JSON. Los módulos opcionales no modifican los movimientos ni los presupuestos existentes.

Repositorio: `arcereciodaniel/one-less-one-lab`.
