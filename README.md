# 🌿 Catálogo Web - Tienda de Suplementos

¡Bienvenido al proyecto **Catálogo de Suplementos**! Esta es una aplicación web moderna e interactiva diseñada para presentar y categorizar productos de nutrición deportiva, vitaminas y suplementos para la salud.

---

## 📌 Tabla de Contenidos

1. [Descripción del Proyecto](#-descripción-del-proyecto)
2. [Características Principales](#-características-principales)
3. [Tecnologías Utilizadas](#-tecnologías-utilizadas)
4. [Estructura del Proyecto](#-estructura-del-proyecto)
5. [Instalación y Configuración](#-instalación-y-configuración)
6. [Uso](#-uso)
7. [Próximas Mejoras (Roadmap)](#-próximas-mejoras-roadmap)
8. [Contribución](#-contribución)
9. [Licencia](#-licencia)

---

## 📖 Descripción del Proyecto

Este catálogo digital permite a los usuarios explorar una variedad de suplementos nutricionales (proteínas, creatinas, multivitamínicos, pre-entrenos, etc.) de manera rápida e intuitiva. El objetivo principal es ofrecer una interfaz clara donde los clientes puedan filtrar por categorías, buscar productos específicos y consultar detalles como beneficios, ingredientes y precios.

---

## ✨ Características Principales

* **Visualización de Productos:** Tarjetas atractivas con imagen, título, categoría, precio y valoración del producto.
* **Filtrado Dinámico:** Filtra el catálogo según la categoría (Proteínas, Aminoácidos, Salud/Bienestar, Pre-Workout, etc.).
* **Buscador en Tiempo Real:** Permite a los usuarios buscar suplementos por nombre o marca.
* **Modal de Detalle:** Ventana emergente al hacer clic en un producto para ver la tabla nutricional, ingredientes e modo de uso.
* **Diseño Responsive:** Totalmente adaptado para móviles, tabletas y ordenadores de escritorio.
* **Enlace a Contacto/Carrito:** Botón de acción directo para solicitar pedidos vía WhatsApp o añadir a un carrito de compras.

---

## 🛠️ Tecnologías Utilizadas

* **HTML5:** Estructura semántica del catálogo.
* **CSS3 / Tailwind CSS:** Estilos visuales, animaciones y diseño adaptable (Responsive Design).
* **JavaScript (ES6+):** Lógica del buscador, filtrado dinámico de productos y renderizado del catálogo.

> *(Nota: Ajusta esta sección si utilizas un framework como React, Vue, Angular o un backend específico).*

---

## 📁 Estructura del Proyecto

```text
catalogo-suplementos/
├── assets/
│   ├── images/          # Imágenes de los suplementos y logos
│   └── css/             # Archivos de estilos (si no se usa Tailwind por CDN)
├── js/
│   ├── products.js      # Array/JSON con el listado de productos
│   └── app.js           # Lógica principal del catálogo
├── index.html           # Página principal de la tienda
└── README.md            # Documentación del proyecto
```

---

## 🚀 Instalación y Configuración

Sigue estos pasos para ejecutar el proyecto en tu entorno local:

1. **Clona este repositorio:**
   ```bash
   git clone https://github.com/tu-usuario/catalogo-suplementos.git
   ```

2. **Accede al directorio del proyecto:**
   ```bash
   cd catalogo-suplementos
   ```

3. **Abre el proyecto:**
   * Simplemente abre el archivo `index.html` en tu navegador preferido.
   * O utiliza una extensión como **Live Server** en VS Code para ejecutarlo en un servidor local.

---

## 💡 Uso

1. Navega por las diferentes categorías usando la barra de navegación o los botones de filtro.
2. Utiliza la barra de búsqueda superior para encontrar un producto específico por su nombre o ingrediente clave.
3. Haz clic sobre cualquier suplemento para ver la información detallada (dosis recomendada, tabla nutricional y precio).
4. *(Opcional)* Presiona el botón de **"Pedir por WhatsApp"** para enviar un mensaje directo al vendedor con el producto seleccionado.

---

## 🔮 Próximas Mejoras (Roadmap)

- [ ] Integración con carrito de compras y pasarela de pago (Stripe/PayPal).
- [ ] Panel de administración para agregar/editar suplementos.
- [ ] Sistema de reseñas y calificaciones por parte de los clientes.
- [ ] Filtro por metas deportivas (ej. *Ganar Masa Muscular*, *Perder Peso*, *Rendimiento*).

---

## 🤝 Contribución

Las contribuciones son bienvenidas. Si deseas colaborar:

1. Haz un Fork del proyecto.
2. Crea una rama para tu nueva característica (`git checkout -b feature/NuevaCaracteristica`).
3. Guarda tus cambios (`git commit -m 'Añade una nueva característica'`).
4. Haz Push a la rama (`git push origin feature/NuevaCaracteristica`).
5. Abre un **Pull Request**.

---

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - consulta el archivo [LICENSE](LICENSE) para más detalles.
