# la-buenamesa
toma de requerimentos restaurante "Buena Mesa"
contexto:
el restaurante esta un poco desactualizado en sistemas, toma de pedidos, gestionar estado de pedidos. controlar inventario y eso lleva un problema al querer llevar un registro solido

# Problema
Problema principal El restaurante quiere digitalizar el menú, recibir pedidos (para mesa y para delivery), gestionar el estado de pedidos y controlar inventario/estadísticas básicas.

# Usuarios :
1. Administrador: CRUD completo de usuarios, productos, pedidos, y reportes.
2. Vendedor: Registrar ventas, editar pedidos, consultar clientes.
3. Cliente: Realizar pedidos, ver historial, editar su perfil.

 ¿Quién usará el sistema y prioridad?
  -Administrador: gestion de productos
  -Vendedor: registro de ventas
  -Cliente: carrito de compras


| Prioridad | Función                     | Rol |

| Alta      | Registro e inicio de sesión | Todos |
| Alta      | Gestión de productos        | Admin |
| Alta      | Registro de ventas          | Vendedor |
| Media     | Reportes de ventas          | Admin |
| Media     | Carrito de compras          | Cliente |
| Baja      | Notificaciones por correo   | Todos |

# requisitos funcionales :

- El sistema debe permitir el registro e inicio de sesión de usuarios.
- El administrador puede crear, editar y eliminar usuarios y productos.
- Los vendedores pueden registrar pedidos y consultar su historial.
- Los clientes pueden visualizar y comprar productos.
- El sistema debe calcular el total del pedido automáticamente.
- Debe haber control de stock al confirmar una venta.


