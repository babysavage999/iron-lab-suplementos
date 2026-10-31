# IRON LAB · Plantilla web para tiendas de suplementos

Landing page oscura y de estilo gótico para tiendas de suplementos deportivos (proteínas, creatinas, pre-entrenos y más). Pensada para impactar a primera vista y vender: catálogo con tamaños y precios, tabla nutricional animada al hacer scroll, carrito, combos y pedidos directos por WhatsApp.

> **Demo / plantilla.** Los nombres de marca, productos, imágenes y precios son de ejemplo y se reemplazan por los de cada cliente. Las marcas e imágenes de los productos pertenecen a sus dueños y se usan solo con fines demostrativos.

## ¿Qué incluye?

- **Fondo animado** (Canvas): discos, mancuernas, pesas rusas y barras en hierro con brillo rojo, cadenas que se balancean, brasas, niebla, runas y arcos góticos. Responde al mouse.
- **Inicio tipo carrusel** con producto central que gira, anillos de runas y texto gigante de fondo.
- **Scroll narrativo:** cada producto destacado aparece, gira y muestra su tabla nutricional fila por fila.
- **Catálogo** de 36 productos con filtros por categoría, selector de tamaño y precio por presentación.
- **Carrito y combos**, con pedido por WhatsApp (el mensaje sale armado con productos, tamaños y total).
- **Preguntas frecuentes** y secciones de confianza.
- **Cuentas, pedidos y panel de administración** (solo en el entorno de demostración, ver abajo).

## Herramientas

HTML5 · CSS3 (animaciones, gradientes, perspectiva 3D) · JavaScript puro · Canvas API · SVG · IntersectionObserver · Google Fonts (Cinzel, UnifrakturCook) · enlaces `wa.me` de WhatsApp. Sin frameworks ni dependencias.

## Cómo verla

Abre `index.html` en el navegador. No necesita instalación ni servidor.

## Sobre la base de datos

La versión de demostración dentro de Claude (artefactos) usa su base de datos integrada para mostrar cuentas de cliente, historial de pedidos y un panel de administración (pedidos, ventas, precios y stock). **Esas funciones no se activan al abrir este archivo por fuera**: aquí el catálogo, el carrito y los pedidos por WhatsApp funcionan normalmente.

Para una tienda real, la siguiente fase es un backend propio: **Next.js + Prisma + PostgreSQL** (usuarios con contraseñas encriptadas, productos, pedidos y panel de administración) y una pasarela de pagos. El manejo de datos personales debe cumplir la Ley 1581 de 2012 (Colombia).

## Transparencia

Diseño y código desarrollados con asistencia de IA (Claude), con dirección, revisión y ajustes de la autora.

## Autora

Camila Andrea Urbina Ospino · [@babysavage999](https://github.com/babysavage999)

<!-- Agrega aquí 2 o 3 capturas de pantalla: ![Inicio](docs/inicio.png) -->
