# MiTienda - Maquetación Web con Bootstrap 5 🛒

Este proyecto es un ejercicio práctico correspondiente a la **Unidad Didáctica 7** del ciclo formativo de **Desarrollo de Aplicaciones Multiplataforma (DAM)**. El objetivo principal ha sido diseñar y maquetar una interfaz limpia, moderna y completamente *responsive* para una tienda de ropa en línea utilizando **Bootstrap 5** y validación nativa de formularios con **JavaScript**.

---

## 🚀 Características del Proyecto

* **Diseño Responsive:** Adaptabilidad completa para dispositivos móviles, tablets y pantallas de escritorio utilizando el sistema de rejilla (*Grid*) y utilidades de visualización de Bootstrap.
* **Componentes Avanzados:** * Menú de navegación (*Navbar*) adaptativo y fijo con barra de búsqueda y accesos de usuario.
    * Tarjetas de producto (*Cards*) organizadas de forma dinámica con selectores de talla estáticos y botones de acción.
    * Menú lateral de acceso rápido para navegación interna (visible solo en pantallas medianas y grandes).
    * Banners promocionales con composiciones asimétricas avanzadas utilizando `object-fit-cover`.
* **Interactividad y Validación:** Ventana modal nativa para el registro de usuarios que incluye validación de formularios en el cliente mediante expresiones regulares (Regex) y clases de *feedback* visual de Bootstrap.

---

## 🛠️ Tecnologías Utilizadas

* **HTML5** - Estructura semántica del sitio web.
* **Bootstrap 5.3.2** - Framework CSS para el diseño ágil y componentes dinámicos.
* **Bootstrap Icons** - Iconografía limpia para los menús y acciones.
* **JavaScript (ES6)** - Validación nativa de campos del formulario en tiempo de envío.

---

## 📋 Validación de Formularios Implementada

El formulario de registro de usuario en la ventana modal cuenta con restricciones específicas para asegurar la calidad de los datos:

1.  **Nombre:** Campo obligatorio. Solo acepta letras y espacios (bloquea números mediante patrón `pattern="[A-Za-zÀ-ÿ\s]+"`).
2.  **Correo electrónico:** Campo obligatorio con estructura estándar de email válida.
3.  **Contraseña:** Campo obligatorio. Requiere un mínimo de 8 caracteres, al menos una letra mayúscula y al menos un número (`pattern="(?=.*\d)(?=.*[A-Z]).{8,}"`).

---

## 🔧 Instalación y Despliegue Local

Para clonar y ejecutar este proyecto de forma local, no necesitas dependencias externas ya que Bootstrap se carga mediante CDN.
