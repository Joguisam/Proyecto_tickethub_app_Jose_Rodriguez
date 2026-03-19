# Conciertos Conectados - Plataforma de Gestión y Venta de Entradas

Sistema web integral diseñado para la compañía **Conciertos Conectados**, permitiendo la digitalización de la venta de entradas y la gestión administrativa de eventos para mejorar el alcance con sus clientes.

---

## 📋 Descripción del Proyecto

Este proyecto surge de la necesidad de expandir el alcance de la operadora de eventos, proporcionando una interfaz intuitiva para que los clientes adquieran boletos de forma rápida y un panel de control robusto para la administración de la logística.

La aplicación se divide en dos frentes principales:
1. **Panel de Administración:** Control interno de categorías, eventos y visualización de ventas.
2. **Portal de Clientes:** Catálogo público, búsqueda de eventos y proceso de compra.

---

## 🚀 Stack Tecnológico

* **Estructura:** HTML5
* **Estilos:** CSS3
* **Lógica:** JavaScript (Vanilla)
* **Arquitectura:** Web Components
* **Persistencia:** LocalStorage

---

## 🛠️ Funcionalidades Principal

### 🔐 Front de Administración
* **Login de Acceso:** Restricción de entrada solo para usuarios autorizados.
    * **Usuario por defecto:** `admin@mail.com`
    * **Contraseña por defecto:** `123456`
* **Dashboard:** Menú principal con acceso a los módulos operativos.
* **Módulo de Categorías:** CRUD completo (Crear, Leer, Actualizar, Eliminar) mediante ventanas modales.
* **Módulo de Eventos:** Gestión detallada de conciertos (código, precio, fecha, hora, ciudad e imagen).
* **Módulo de Ventas:** Histórico de transacciones ordenadas cronológicamente con detalles completos de cada pedido y cliente.

### 🎫 Front de Eventos (Clientes)
* **Catálogo Público:** Visualización de eventos disponibles con filtros por palabras clave, ciudad y categorías.
* **Detalle de Producto:** Vista expandida con descripción completa y botón de retorno.
* **Carrito de Compras:** Sistema modal para gestionar selecciones, cálculo de total y formulario de finalización de compra (ID, nombre, dirección, teléfono y email).

---

## 📐 Consideraciones Técnicas y UI/UX

* **Web Components:** Desarrollo basado en componentes reutilizables para una estructura modular.
* **Persistencia de Datos:** Uso de `localStorage` para simular una base de datos persistente en el navegador.
* **Feedback al Usuario:** Emisión de mensajes de confirmación o error en cada acción realizada.
* **Planificación:** El proyecto incluye **wireframes** para la propuesta de interfaz y experiencia de usuario.

---

## 📁 Estructura Sugerida del Repositorio

```text
├── /assets          # Imágenes y recursos estáticos
├── /components      # Web Components