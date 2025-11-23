# Mholly - Plataforma de Prótesis Veterinarias 🐾🦿

![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![Volt](https://img.shields.io/badge/Livewire_Volt-FB70A9?style=for-the-badge&logo=laravel&logoColor=white)
![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)
![MercadoPago](https://img.shields.io/badge/Mercado_Pago-009EE3?style=for-the-badge&logo=mercadopago&logoColor=white)

> **Proyecto:** Plataforma B2C para PyME de manufactura ortopédica animal.
> **Modalidad:** Co-desarrollo (Equipo de 2 personas).
> **Mi Enfoque:** Integración de Pagos, Seguridad (RBAC) y Componentes Reactivos.

## 📖 Sobre el Proyecto
**Mholly** es una solución digital desarrollada en colaboración para conectar dueños de mascotas con un taller de prótesis 3D.
Mientras mi compañero se enfocaba en la gestión de pacientes, mi rol fue asegurar la **infraestructura transaccional y la seguridad de la plataforma**.

---

## 💳 Mis Contribuciones Principales

### Integración de Pasarelas de Pago
Fui responsable de conectar las APIs de **PayPal y MercadoPago**.
* Implementé la lógica para capturar los webhooks y actualizar el estado del pedido automáticamente (de "Pendiente" a "Pagado").
![Checkout](assets/checkout_methods.png)

### Arquitectura de Roles (RBAC)
Diseñé el sistema de permisos para diferenciar entre:
* **Administrador:** Control total del negocio.
* **Comprador:** Acceso limitado a sus pedidos y mascotas.
Esto asegura que la data sensible esté protegida.
![Admin Panel](assets/admin_roles.png)

### Frontend Reactivo con Laravel Volt
Implementé **Laravel Volt** para modernizar la experiencia de usuario en el carrito de compras y el seguimiento de pedidos, reduciendo la latencia en interacciones clave.
![Nuevo Pedido](assets/client_new_order.png)

---

## 🤝 Trabajo Colaborativo
El desarrollo se realizó utilizando **Git Flow**, coordinando *merges* y revisiones de código para integrar el módulo de gestión de pacientes con el sistema de facturación y pedidos.

---

### 📬 Contacto
[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/eddaann)
