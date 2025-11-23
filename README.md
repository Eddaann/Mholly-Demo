# Mholly - Plataforma de Prótesis Veterinarias 🐾🦿

![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![Volt](https://img.shields.io/badge/Livewire_Volt-FB70A9?style=for-the-badge&logo=laravel&logoColor=white)
![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)
![MercadoPago](https://img.shields.io/badge/Mercado_Pago-009EE3?style=for-the-badge&logo=mercadopago&logoColor=white)

> **Proyecto:** Plataforma B2C para PyME de manufactura ortopédica animal.
> **Modalidad:** Co-desarrollo (Equipo de 2 personas).
> **Mi Enfoque:** Integración de Pagos, Seguridad (RBAC) y Experiencia del Cliente Reactiva.

## 📖 Sobre el Proyecto
**Mholly** es una solución digital desarrollada en colaboración para conectar dueños de mascotas con un taller de prótesis 3D. El sistema permite realizar pedidos personalizados y dar seguimiento al proceso de manufactura.

Mi rol principal fue asegurar la **infraestructura transaccional**, la seguridad mediante roles y la creación de interfaces reactivas modernas.

![Landing Page](assets/landing_hero.png)

---

## 🤝 Experiencia del Cliente (Mis Contribuciones Frontend)

Implementé **Laravel Volt** para modernizar la experiencia de usuario, reduciendo la latencia en interacciones clave del proceso de compra y seguimiento.

### Flujo de Pedido y Tracking
Desarrollé las vistas para que los clientes inicien sus pedidos personalizados y, crucialmente, una **Línea de Tiempo Reactiva** que les permite ver el estado real de su manufactura (En Fabricación, Enviado, etc.), reduciendo la incertidumbre de la compra.

| Inicio de Pedido (Volt) | Tracking en Tiempo Real |
|:---:|:---:|
| ![Nuevo Pedido](assets/client_new_order.png) | ![Timeline](assets/client_tracking.png) |

---

## 🔐 Gestión Administrativa y Seguridad

Colaboré en la creación del panel administrativo, enfocándome en la seguridad y la lógica de negocio detrás de la gestión de órdenes.

### Arquitectura de Roles (RBAC) y Dashboard
Diseñé el sistema de permisos para diferenciar estrictamente entre Administradores y Compradores, asegurando la protección de datos sensibles. El administrador cuenta con un dashboard centralizado para monitorear KPIs y el flujo de pedidos.

| Dashboard Admin (KPIs) | Gestión de Pedidos |
|:---:|:---:|
| ![Admin Dash](assets/admin_dashboard.png) | ![Admin Orders](assets/admin_orders.png) |

---

## 💳 Integraciones Críticas (Backend)

Aunque no se muestran visualmente por seguridad, fui responsable de las implementaciones "invisibles" más críticas del sistema:

### 1. Pasarelas de Pago
Conecté las APIs REST de **PayPal y MercadoPago**. Implementé la lógica de *webhooks* para que, al confirmarse un pago exitoso, el sistema actualice automáticamente el estado del pedido en la base de datos sin intervención humana.

### 2. Sistema de Soporte Interno
Implementé un módulo de mensajería interna que conecta directamente al cliente con el administrador para resolver dudas sobre medidas o detalles del producto.
![Chat Soporte](assets/support_chat.png)

---

## 🛠 Stack & Metodología
* **Backend:** Laravel 10, PHP 8.2, MySQL.
* **Frontend:** Laravel Volt (Functional API), Alpine.js, TailwindCSS.
* **Colaboración:** Uso de Git Flow para integrar el módulo de gestión de pacientes (desarrollado por mi compañero) con mis módulos de facturación, pedidos y seguridad.

---

### 📬 Contacto
[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/eddaann)
