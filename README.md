# PF Mates Artesanales — Sitio Web

![Preview](https://img.shields.io/badge/HTML-Single%20File-b8924a?style=flat&logo=html5)
![License](https://img.shields.io/badge/Licencia-Comercial-4a6741?style=flat)
![Mobile](https://img.shields.io/badge/Mobile-First-d4aa6a?style=flat)

Sitio web completo y listo para usar para emprendimientos de **mates artesanales** (o productos artesanales similares). Un único archivo HTML con panel de administración oculto, carrito de compras por WhatsApp, galería con fotos, testimonios y persistencia automática.

---

## ✨ Características

- **Un solo archivo HTML** — sin dependencias, sin servidor, sin instalación
- **Panel de administración oculto** — 5 toques en el logo para acceder
- **Persistencia automática** con localStorage — los cambios se guardan solos
- **Carrito de compras** que genera pedido por WhatsApp
- **Galería con uploader** de fotos real
- **Diseño mobile-first** optimizado para celular
- **SEO básico** incluido (meta tags, Open Graph)
- **Exportar sitio** — descarga el HTML actualizado con un clic

---

## 🚀 Inicio rápido

1. Descargá el archivo `pf-mates-artesanales.html`
2. Abrilo en cualquier navegador moderno
3. Listo — el sitio funciona sin conexión a internet

---

## ⚙️ Panel de Administración

**Acceso:** Tocá el logo de la barra de navegación **5 veces seguidas**

| Campo | Valor por defecto |
|-------|-----------------|
| Usuario | `priflores` |
| Contraseña | `mates2026` |

> ⚠️ Cambiá las credenciales antes de entregar al cliente. Están en la línea que dice `const _A = btoa(...)`.

### Secciones editables

| Pestaña | Qué podés editar |
|---------|-----------------|
| 📊 Resumen | Estadísticas, exportar sitio, restablecer |
| 🏠 Hero | Título, subtítulo, descripción, estadísticas |
| 🛒 Productos | Agregar/editar/eliminar productos con foto |
| 🌳 Nosotros | Historia, valores, año de fundación |
| ⭐ Testimonios | Agregar/editar/eliminar reseñas |
| 📞 Contacto | WhatsApp, ubicación, envíos, Instagram |
| 🎨 Diseño | Colores, nombre del negocio, textos |
| 🖼️ Galería | Subir hasta 5 fotos del trabajo |

---

## 📦 Publicar el sitio

### Opción A — Netlify (recomendado, gratis)
1. Ir a [netlify.com](https://netlify.com)
2. Arrastrar el archivo HTML al área de deploy
3. URL lista en 30 segundos

### Opción B — GitHub Pages
```bash
git init
git add pf-mates-artesanales.html
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/pf-mates.git
git push -u origin main
```
Luego activar GitHub Pages en Settings → Pages → Source: main

### Opción C — Dominio propio
Subir el HTML a cualquier hosting compartido (Hostinger, SiteGround, etc.) como `index.html`.

---

## 💳 Aceptar pagos

El carrito genera un mensaje de WhatsApp con el pedido. Para cobrar:

- **Transferencia bancaria** — la más simple
- **MercadoPago** — enviar link de pago por WhatsApp
- **MercadoPago Checkout** — requiere integración adicional (~5% comisión)

---

## 🎨 Personalizar para otro rubro

1. Abrir el HTML en un editor de texto (VS Code recomendado)
2. Buscar y reemplazar "mate" / "mates" por tu producto
3. Cambiar colores desde el panel admin → Diseño
4. Reemplazar el logo en las 3 líneas con `id="nav-logo-trigger"`

---

## 📁 Estructura del proyecto

```
pf-mates-artesanales.html   ← Todo el sitio en un solo archivo
README.md                    ← Este archivo
```

---

## 📄 Licencia

Uso comercial — este template puede ser vendido, personalizado y entregado a clientes.
No puede ser redistribuido como template gratuito ni publicado en marketplaces sin autorización.

---

## 🛠️ Stack técnico

- HTML5 semántico
- CSS3 con variables (design tokens)
- JavaScript vanilla (sin frameworks)
- Google Fonts (Cormorant Garamond + Jost)
- localStorage para persistencia
- Base64 para imágenes embebidas

---

*Desarrollado con 🪵 para emprendimientos artesanales argentinos*
