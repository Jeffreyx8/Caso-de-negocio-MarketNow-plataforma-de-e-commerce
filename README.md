# Caso-de-negocio-MarketNow-plataforma-de-e-commerce
# MarketNow es una tienda en línea que permite a múltiples vendedores publicar productos y a clientes registrados realizar compras. La plataforma gestiona el catálogo de productos, el proceso de compra, los pagos, los envíos y las reseñas.
Reglas del negocio clave:
Un cliente puede tener múltiples direcciones de envío registradas.
Un pedido puede contener varios productos (de distintos vendedores).
Cada pedido tiene un estado: pendiente, pagado, enviado, entregado o cancelado.
Un pago puede realizarse por tarjeta, transferencia o billetera digital.
Los productos pertenecen a categorías (que pueden tener subcategorías).
Un cliente puede dejar una reseña por cada producto que haya comprado.
El inventario se descuenta automáticamente al confirmar el pago.
Problema: Reporte de ventas para MarketNow
El equipo comercial de MarketNow necesita entender cómo están funcionando las ventas. Te han contratado como analista de datos para construir una serie de reportes que respondan preguntas clave del negocio. Solo tienes acceso a la base de datos SQL y debes entregar las consultas que generen cada reporte.

Requerimientos a resolver
R1 — Ventas por categoría El equipo quiere saber cuánto dinero se ha generado por cada categoría de producto. El reporte debe mostrar el nombre de la categoría, la cantidad de productos vendidos y el ingreso total, ordenado de mayor a menor ingreso.
R2 — Mejores clientes Identificar los 5 clientes que más han gastado en la plataforma. Mostrar su nombre, correo, cantidad de pedidos realizados y el total gastado. Solo considerar pedidos en estado pagado o entregado.
R3 — Productos más vendidos Listar los 10 productos más vendidos por cantidad de unidades. Mostrar el nombre del producto, el nombre de la tienda vendedora y el total de unidades vendidas.
R4 — Resumen mensual de ventas Mostrar el total de ingresos y la cantidad de pedidos por mes. Solo incluir pedidos con pago en estado aprobado. Ordenar del mes más reciente al más antiguo.
R5 — Vendedores sin ventas Detectar qué vendedores aún no tienen ningún pedido asociado a sus productos. Útil para el equipo de soporte
