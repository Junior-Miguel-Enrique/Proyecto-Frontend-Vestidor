# Guía de Diseño UI/UX - Vestidor Virtual

Lineamientos de diseño visual, accesibilidad y experiencia de usuario implementados en el frontend web.

---

## 🎨 Paleta de Colores y Tokens

- **Primario (Acción & Énfasis):** Índigo / Violeta moderno (`#6366F1`)
- **Fondo Superficie (Light):** Blanco neutro (`#FFFFFF`) / Gris perla (`#F8FAFC`)
- **Texto Principal:** Pizarra oscuro (`#0F172A`)
- **Texto Secundario:** Gris medio (`#64748B`)
- **Éxito (Compras / Confirmaciones):** Esmeralda (`#10B981`)
- **Alerta / Error:** Carmín (`#EF4444`)

---

## ♿ Estándares de Accesibilidad (WCAG 2.1 AA)

1. **Contraste de Color:** Todo texto sobre fondo mantiene un ratio mínimo de 4.5:1.
2. **Navegación por Teclado:** Elementos interactivos (`button`, `a`, `input`) poseen anillo de foco visible (`focus-visible`).
3. **Etiquetas Semánticas:** Uso estricto de elementos HTML5 nativos (`<nav>`, `<main>`, `<header>`, `<article>`) acompañados de atributos `aria-label` en controles iconográficos.

---

## 📱 Breakpoints Responsivos

- **Móvil (sm):** `< 640px` (disposición a una columna, menú hamburguesa).
- **Tablet (md):** `640px - 1024px` (cuadrícula de catálogo a 2 columnas).
- **Escritorio (lg/xl):** `> 1024px` (interfaz a 3-4 columnas con probador virtual en panel lateral fijado).
