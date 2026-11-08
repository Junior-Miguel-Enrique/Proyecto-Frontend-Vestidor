# Vestidor Virtual - Frontend Web

Aplicación web Single Page Application (SPA) desarrollada con **Angular**, orientada a la experiencia interactiva de compra y probador virtual inteligente.

---

## 🏛️ Estructura y Arquitectura del Proyecto

El proyecto implementa la arquitectura moderna recomendada por Angular con componentes autónomos (**Standalone Components**) y reactividad basada en **Signals**:

```
src/app/
├── core/            # Servicios singleton, interceptores HTTP, guards de autenticación
├── shared/          # Componentes reutilizables (botones, modales, alertas, pipes)
├── features/        # Módulos y vistas por funcionalidad
│   ├── auth/        # Inicio de sesión, registro y recuperación de contraseña
│   ├── catalog/     # Catálogo de prendas, filtros por categoría y búsqueda
│   ├── fitting/     # Interfaz del probador virtual inteligente
│   ├── cart/        # Carrito de compras y pasarela de pago
│   └── dashboard/   # Panel de usuario y administración
└── environments/    # Variables de configuración por entorno (local, staging, prod)
```

---

## 🚀 Tecnologías Principales

- **Framework:** Angular 19+
- **Control de Estado & Reactividad:** Angular Signals & RxJS
- **Estilos:** Tailwind CSS / CSS modular con diseño responsivo
- **Testing:** Vitest / Karma para pruebas unitarias de componentes
- **Despliegue:** Compatible con Vercel, Firebase App Hosting y Docker

---

## ⚙️ Requisitos Previos

- **Node.js:** v18.x o superior
- **NPM** o **PNPM**
- **Angular CLI:** `npm install -g @angular/cli`

---

## 📦 Instalación y Ejecución

1. **Instalar dependencias:**
   ```bash
   npm install
   ```

2. **Ejecutar el servidor de desarrollo:**
   ```bash
   ng serve
   ```
   Abre tu navegador en `http://localhost:4200/`. La aplicación se recarga automáticamente ante cualquier cambio.

3. **Compilar para producción:**
   ```bash
   ng build --configuration production
   ```
   Los artefactos optimizados se generarán en la carpeta `dist/`.

4. **Ejecutar pruebas unitarias:**
   ```bash
   ng test
   ```
