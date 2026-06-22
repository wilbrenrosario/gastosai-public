# GastosAI

Aplicación móvil de finanzas personales para usuarios dominicanos. Sincroniza automáticamente los correos de notificación de tus bancos, clasifica tus transacciones por categoría, y te ayuda a organizar metas de ahorro y tareas diarias — todo desde una interfaz oscura y fluida.

---

## Características principales

### Resumen de gastos
- Balance total y listado de transacciones recientes en la pantalla de inicio
- Opción para ocultar los montos con un solo toque
- Sincronización automática con Gmail para importar movimientos bancarios

### Estadísticas
- Gráfico circular interactivo por categoría de gasto
- Navegación mes a mes para comparar períodos
- Desglose detallado de cada categoría con montos y porcentajes

### Integración bancaria vía Gmail
- Conexión segura con Google Sign-In (OAuth 2.0)
- Parseo automático de correos de notificación de **BHD**, **Banreservas** y **Popular**
- Clasificación inteligente de transacciones: Comida, Transporte, Combustible, Entretenimiento, Salud, Servicios, Compras, Educación, Transferencias e Ingresos
- Filtros por banco, categoría y tipo de movimiento

### Metas de ahorro
- Crea metas con imagen, monto objetivo y progreso actual
- Barra de progreso visual en cada meta
- Edita todos los valores directamente desde la tarjeta
- Reordena las metas con drag & drop
- Persistencia local por usuario

### Tareas diarias
- Lista de tareas con checkboxes y progreso general
- **Reset automático cada día** — las tareas se desmarcan al iniciar el día
- Reordenamiento por arrastre entre tareas pendientes
- **Recordatorios con notificación local** — configura una hora por tarea; la notificación se dispara diariamente a esa hora
- Sección separada de tareas completadas

---

## Tecnologías

| Área | Tecnología |
|---|---|
| Framework | Flutter 3.x |
| Estado | Riverpod |
| Base de datos local | SQLite (sqflite) |
| Autenticación | Google Sign-In |
| API de correo | Gmail API (googleapis) |
| Gráficos | fl_chart |
| Notificaciones | flutter_local_notifications |
| Zona horaria | flutter_timezone + timezone |
| UI adaptiva | flutter_screenutil |

---

## Configuración

### Requisitos
- Flutter `>=3.2.0`
- Dart `>=3.2.0`
- Xcode 15+ (iOS)
- Android Studio / SDK 33+ (Android)

## Bancos soportados

| Banco | Tipo de correos |
|---|---|
| BHD | Alertas de débito, crédito y transferencias |
| Banreservas | Notificaciones de movimientos |
| Popular | Alertas de consumo y depósitos |

---

## Versión

`1.0.0` — iOS y Android

## ScreenShoots
<img width="591" height="1280" alt="WhatsApp Image 2026-06-22 at 12 08 49" src="https://github.com/user-attachments/assets/2e3d8df9-5858-46f9-9efc-f0c672ef40be" />

<img width="591" height="1280" alt="WhatsApp Image 2026-06-22 at 12 08 49 (1)" src="https://github.com/user-attachments/assets/94e9c412-daf2-49a2-88b2-1c7cd501fea6" />

<img width="591" height="1280" alt="WhatsApp Image 2026-06-22 at 12 08 49 (2)" src="https://github.com/user-attachments/assets/47534df9-1c34-49eb-8d45-e7a46c0080d9" />




