# Tokens del Sistema de Diseño (Design Tokens) - Vestidor Virtual

Especificación de variables y tokens de diseño visual para modo Claro y Oscuro (Light & Dark Mode).

---

## 🎨 Paleta de Colores Semántica

```css
:root {
  /* Modo Claro (Light Mode) */
  --color-bg-primary: #FFFFFF;
  --color-bg-surface: #F8FAFC;
  --color-border: #E2E8F0;
  --color-text-primary: #0F172A;
  --color-text-secondary: #64748B;
  --color-accent: #6366F1;
  --color-accent-hover: #4F46E5;
  --color-success: #10B981;
  --color-danger: #EF4444;
}

[data-theme="dark"] {
  /* Modo Oscuro (Dark Mode) */
  --color-bg-primary: #0B0F19;
  --color-bg-surface: #1E293B;
  --color-border: #334155;
  --color-text-primary: #F8FAFC;
  --color-text-secondary: #94A3B8;
  --color-accent: #818CF8;
  --color-accent-hover: #6366F1;
  --color-success: #34D399;
  --color-danger: #F87171;
}
```

---

## 🔤 Escala Tipográfica (Typography Scale)

| Token | Tamaño (px / rem) | Peso (Font Weight) | Uso Principal |
| :--- | :--- | :--- | :--- |
| `text-display` | `36px / 2.25rem` | Bold (700) | Hero probador virtual |
| `text-title` | `24px / 1.5rem` | SemiBold (600) | Títulos de catálogo y modal |
| `text-body` | `16px / 1rem` | Regular (400) | Descripción de prendas |
| `text-caption` | `12px / 0.75rem` | Medium (500) | Badges de talla y stock |
