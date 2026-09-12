# Nutrite — Dietética Online

Proyecto de la materia **Aplicaciones Web 1** (IES), basado en el caso de negocio real
Nutrite (dietética online, cuenta de Instagram [@nutrite_dieteticaonline](https://instagram.com/nutrite_dieteticaonline)
y tienda en Tiendanube). Este repositorio contiene el **TP2**: la estructura HTML estática
del sitio, construida a partir del sitemap y la estrategia MPA/SPA definidos en el TP1.

## 📄 Informe

El informe en PDF con el desarrollo del TP2 y los cambios respecto a la propuesta del
TP1 se encuentra en la **raíz del repositorio**: `Informe_TP2_Nutrite.pdf`.

## 📁 Estructura del proyecto

```
nutrite/
├── index.html
├── contacto.html
├── buscador.html
├── carrito.html
├── checkout.html
├── catalogo/
│   ├── index.html
│   ├── sin-tacc.html
│   ├── veganos.html
│   └── suplementos.html
├── producto/
│   └── ejemplo-producto.html
├── blog/
│   ├── index.html
│   └── articulo-ejemplo.html
├── envios/
│   └── index.html
├── cuenta/
│   ├── login.html
│   └── registro.html
├── legales/
│   ├── terminos.html
│   ├── privacidad.html
│   └── cambios-devoluciones.html
├── assets/
│   ├── img/
│   ├── audio/
│   └── video/
└── Informe_TP2_Nutrite.pdf
```

## ✅ Qué incluye este TP

- Páginas MPA completas: catálogo, categorías, ficha de producto, blog, información
  de envíos, páginas legales y cuenta (login/registro).
- Versión estática de las páginas que en el TP1 quedaron definidas como módulos SPA
  (buscador, carrito, checkout) — sin la interactividad en tiempo real, que se
  incorporará en una etapa posterior con JavaScript.
- Etiquetado semántico (`header`, `nav`, `main`, `article`, `section`, `footer`) y
  accesibilidad ARIA (`aria-label`, `aria-labelledby`, `alt` descriptivo en imágenes).

## ▶️ Cómo verlo

1. Cloná o descargá el repositorio.
2. Abrí la carpeta en VS Code.
3. Click derecho sobre `index.html` → **Open with Live Server**.

## 🖼️ Imágenes

Las imágenes en `assets/img/` provienen de bancos gratuitos de uso libre
(Unsplash / Pexels). El logo fue extraído y editado a partir de la foto de perfil
de Instagram de Nutrite.