# 🛒 Servidor_forit_v1 - Proyecto Academia ForIT

Backend para un sistema de e-commerce especializado en comida rápida, que permite a los usuarios realizar pedidos con opciones de **delivery a domicilio** o **retiro en tienda**. Desarrollado con arquitectura limpia, modular y siguiendo buenas prácticas como TDD y diseño orientado a dominio.

---

## 🚀 Características principales

- 🔐 **Autenticación y autorización** con JWT (roles: usuario y administrador)  
- 📦 **Gestión completa de productos:** CRUD para administradores  
- 🛒 **Carrito de compras:** Añadir, eliminar y modificar productos  
- 🚚 **Opciones de entrega:** Delivery a domicilio y retiro en tienda  
- 📡 **API REST** robusta para integración con frontend o apps móviles  
- 🔧 **Arquitectura limpia y modular:** Facilita mantenimiento y escalabilidad  
- ⚙️ **Testing:** Implementación de pruebas automatizadas con TDD  
- 🌐 **Frontend en desarrollo:** Próximamente con React y TailwindCSS

---

## 🏗️ Estructura del proyecto (Monorepo)

```plaintext
Servidor_forit_v1/
├── apps/
│   ├── backend/       # API y lógica de negocio
│   └── frontend/      # Interfaz de usuario (en desarrollo)
├── domain/            # Capa de dominio y lógica central
│   ├── src/
│   │   ├── entities/      # Modelos principales (Usuario, Producto, Pedido, Carrito)
│   │   ├── repositories/  # Interfaces y adaptadores de datos
│   │   └── use-cases/     # Casos de uso (reglas de negocio)
│   ├── tests/             # Pruebas unitarias y de integración
├── node_modules/
├── .gitignore
├── package.json
├── README.md
└── vitest.config.ts
🔧 Tecnologías clave
Área	Tecnologías
Backend	Node.js, Express, TypeScript, JWT
Arquitectura	Clean Architecture, TDD
Frontend	React, TypeScript, TailwindCSS (próximamente)
Herramientas	Git, GitHub, Postman, Vitest (testing)

📦 Modelo de pedidos y opciones de entrega
Los usuarios pueden elegir entre:

Delivery a domicilio: Ingresan su dirección y reciben el pedido en casa.

Retiro en tienda: Recogen el pedido directamente en el local.

El sistema gestiona el estado del pedido: recibido, en preparación, en camino, entregado o retirado.

🚀 Próximos pasos
Desarrollo del frontend para la interacción con usuarios

Implementación de notificaciones en tiempo real sobre el estado de pedidos

Añadir reportes y gestión avanzada para administradores

Mejoras en la seguridad y escalabilidad del sistema

📜 Licencia
Proyecto educativo para Academia ForIT 2025. Licencia MIT.

📞 Contacto
DreickDev – https://github.com/dreickdev