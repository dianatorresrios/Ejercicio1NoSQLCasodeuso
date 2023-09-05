Ejercicio 1 NoSQL: Caso de uso

Descripción general:

El sistema de gestión de artículos y tickets en el supermercado tiene como propósito principal administrar de manera eficiente las transacciones de compra de los clientes. Facilita el proceso de registro y venta de productos, calcula automáticamente el subtotal, el impuesto al valor agregado (IVA) y el total de un ticket de compra, y mantiene un registro actualizado de las existencias de los artículos disponibles en el inventario.

Requisitos:

1. Requisitos funcionales:

1.1 Gestión de Artículos:

Registrar nuevos artículos en el inventario, incluyendo nombre, código, precio unitario y cantidad en stock.
Actualizar la información de los artículos existentes (nombre, precio, cantidad en stock, etc.).
Eliminar artículos del inventario.
Gestión de Tickets:

Crear un nuevo ticket de compra para un cliente.
Agregar artículos al ticket, especificando la cantidad de cada uno.
Actualizar la cantidad de artículos en el ticket o eliminar artículos del mismo.
Calcular automáticamente el subtotal de un ticket (suma de los precios de los artículos).
Calcular el IVA basado en las tasas de impuestos aplicables.
Calcular el total del ticket (subtotal + IVA).
Finalizar un ticket de compra, registrando la fecha y hora de la transacción.
Actualización de Existencias:

Reducir la cantidad de artículos en stock al completar una venta.
Restaurar la cantidad de artículos en stock si un ticket es cancelado o anulado.
Requisitos no funcionales:

2. Seguridad:

Garantizar la seguridad de los datos del inventario y las transacciones del cliente mediante medidas de autenticación y autorización.
Rendimiento:

Mantener una respuesta rápida del sistema incluso en momentos de alta carga, como horas pico de ventas.
Usabilidad:

Diseñar una interfaz de usuario intuitiva y fácil de usar para los empleados del supermercado.
Escalabilidad:

Prever la capacidad de expansión del sistema para adaptarse al crecimiento futuro del supermercado.
Posibles mejoras y características futuras:

3. Integración con sistemas de pago:

Integrar métodos de pago electrónicos, como tarjetas de crédito/débito y aplicaciones móviles, para agilizar el proceso de pago.
Gestión de promociones y descuentos:

Permitir la aplicación de promociones, descuentos y ofertas especiales en los tickets de compra.
Análisis de datos:

Implementar herramientas de análisis de datos para obtener información sobre las preferencias de compra de los clientes y optimizar el inventario.
Sistema de fidelización de clientes:

Desarrollar un sistema de fidelización que recompense a los clientes habituales con descuentos o puntos acumulativos.
Módulo de informes y generación de facturas:

Agregar funcionalidades para generar informes de ventas y facturas para clientes empresariales.
Pruebas automatizadas:

Implementar pruebas automatizadas para garantizar la robustez y la calidad del sistema durante su desarrollo y mantenimiento.
Integración con comercio en línea:

Extender el sistema para permitir la venta en línea y la sincronización de inventario entre la tienda física y la plataforma en línea del supermercado.


1. REQUISITOS  FUNCIONALES

 los requisitos funcionales y no funcionales del sistema de gestión de artículos y tickets en el supermercado, teniendo en cuenta la capacidad de almacenamiento de información, operaciones CRUD, cálculo de subtotal, IVA y total de un ticket, y actualización de existencias:

Requisitos funcionales:

1. Gestión de Artículos:

Crear: Registrar nuevos artículos en el inventario, incluyendo nombre, código, precio unitario y cantidad en stock.
Leer: Consultar información detallada de un artículo específico.
Actualizar: Actualizar la información de los artículos existentes, como nombre, precio, cantidad en stock, etc.
Eliminar: Eliminar artículos del inventario.
Gestión de Tickets:

Crear: Crear un nuevo ticket de compra para un cliente.
Leer: Ver detalles de un ticket existente, incluyendo los artículos comprados, subtotal, IVA y total.
Actualizar: Agregar artículos al ticket, especificando la cantidad de cada uno, actualizar la cantidad de artículos en el ticket o eliminar artículos del mismo.
Eliminar: Cancelar o anular un ticket de compra.
Cálculos de Ticket:

Calcular automáticamente el subtotal de un ticket (suma de los precios de los artículos).
Calcular el IVA basado en las tasas de impuestos aplicables.
Calcular el total del ticket (subtotal + IVA).
Actualización de Existencias:

Reducir automáticamente la cantidad de artículos en stock al completar una venta.
Restaurar la cantidad de artículos en stock si un ticket es cancelado o anulado.
Requisitos no funcionales:

2. Seguridad:

Garantizar la seguridad de los datos del inventario y las transacciones del cliente mediante medidas de autenticación y autorización.
Rendimiento:

Mantener una respuesta rápida del sistema incluso en momentos de alta carga, como horas pico de ventas.
Usabilidad:

Diseñar una interfaz de usuario intuitiva y fácil de usar para los empleados del supermercado.
Escalabilidad:

Prever la capacidad de expansión del sistema para adaptarse al crecimiento futuro del supermercado.
Posibles mejoras y características futuras:

3. Integración con sistemas de pago:

Integrar métodos de pago electrónicos, como tarjetas de crédito/débito y aplicaciones móviles, para agilizar el proceso de pago.
Gestión de promociones y descuentos:

Permitir la aplicación de promociones, descuentos y ofertas especiales en los tickets de compra.
Análisis de datos:

Implementar herramientas de análisis de datos para obtener información sobre las preferencias de compra de los clientes y optimizar el inventario.
Sistema de fidelización de clientes:

Desarrollar un sistema de fidelización que recompense a los clientes habituales con descuentos o puntos acumulativos.
Módulo de informes y generación de facturas:

Agregar funcionalidades para generar informes de ventas y facturas para clientes empresariales.
Pruebas automatizadas:

Implementar pruebas automatizadas para garantizar la robustez y la calidad del sistema durante su desarrollo y mantenimiento.
Integración con comercio en línea:

Extender el sistema para permitir la venta en línea y la sincronización de inventario entre la tienda física y la plataforma en línea del supermercado.




