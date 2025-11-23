# 📋 PLAN DE DESARROLLO - PACO EL MORLACO
## Actividad 3 - Prototipo de Alta Fidelidad

**Proyecto**: Plataforma web para gestión de prótesis y donaciones  
**Stack Tecnológico**: HTML & CSS  
**Fecha de Inicio**: 23 de Noviembre, 2025  
**Equipo**: Grupo 7 - Actividad 3 Ingeniería Software Web

---

## 🎯 OBJETIVO

Desarrollar un prototipo de alta fidelidad navegable en HTML & CSS que cumpla con todos los requisitos de la Actividad 3, basado en los diseños iniciados en Figma y los requisitos documentados en la Actividad 2.

---

## 📊 ESTADO ACTUAL DEL PROYECTO

### ✅ Completado
- [x] Análisis de requisitos (Actividad 2)
- [x] Diseño de 5 wireframes de alta fidelidad en Figma
- [x] Definición de sistema de diseño (colores, tipografía, efectos)

### 🔄 En Progreso
- [ ] Replicación de diseños de Figma a HTML & CSS

### ⏳ Pendiente
- [ ] Desarrollo de vistas faltantes
- [ ] Integración de navegación entre vistas
- [ ] Exportación final a Figma
- [ ] Documentación del informe

---

## 🎨 SISTEMA DE DISEÑO

### Paleta de Colores

#### Gradientes de Fondo
```css
/* Azules */
--blue-1: #DDE3F7;
--blue-2: #AABBEE;
--blue-3: #8AA0EA;
--blue-4: #829EE6;
--blue-5: #C7C9F1;
--blue-6: #A1CEFF;
--blue-7: #6E89FD;

/* Púrpuras/Lilas */
--purple-1: #C6AFE3;
--purple-2: #DCC3F9;
--purple-3: #E8DEF6;
--purple-4: #F0ECF7;
--purple-5: #E5D4F5;
--purple-6: #CEB2ED;

/* Rosas */
--pink-1: #F3F6FA;
--pink-2: #EACCD1;
--pink-3: #D7CAE1;
```

#### Colores de Texto
```css
--text-primary: #8AA0EA;
--text-secondary: #B2BDE2;
--text-dark: #000000;
--text-light: #FFFFFF;
--text-muted: #818183;
```

### Tipografía
```css
--font-primary: 'Montserrat', sans-serif;
--font-secondary: 'Montserrat Alternates', sans-serif;

/* Pesos */
--font-light: 300;
--font-regular: 400;
--font-medium: 500;
--font-bold: 700;
--font-extrabold: 800;
```

### Efectos Visuales
```css
/* Glassmorphism */
--glass-bg: rgba(217, 217, 217, 0.02);
--glass-blur: blur(50px);

/* Sombras */
--shadow-inset: 0px 2px 8px rgba(255, 255, 255, 0.40) inset;
--shadow-outer: 0px -2px 8px rgba(0, 0, 0, 0.25);

/* Bordes */
--border-white: 1px solid white;
--border-radius-sm: 10px;
--border-radius-md: 20px;
--border-radius-lg: 40px;
--border-radius-xl: 80px;
--border-radius-full: 180px;
```

---

## 📁 ESTRUCTURA DEL PROYECTO

```
/PacoMorlaco/
├── index.html                          # Home (Landing Page)
├── login.html                          # CUI-2: Iniciar Sesión
├── registro.html                       # CUI-1: Registrarse
├── donante-dashboard.html              # Dashboard Donante
├── donante-campanas.html               # Listado de Campañas
├── donante-donacion.html               # Formulario de Donación
├── donante-favoritos.html              # Mis Favoritos
├── donante-historial.html              # Historial de Donaciones
├── beneficiario-dashboard.html         # Dashboard Beneficiario
├── beneficiario-solicitar.html         # CUI-3: Solicitar Prótesis
├── beneficiario-mis-solicitudes.html   # Mis Solicitudes
├── admin-dashboard.html                # Dashboard Admin
├── admin-solicitudes.html              # CUI-4: Gestionar Solicitudes
├── admin-inventario.html               # CUI-7: Gestionar Inventario
├── admin-reportes.html                 # CUI-8: Generar Reportes
├── admin-actualizar-caso.html          # CUI-9: Publicar Actualización
├── admin-moderacion.html               # Moderar Comentarios
├── campana-detalle.html                # CUI-6 + CUI-10: Detalle de Campaña
├── css/
│   ├── reset.css                       # Reset CSS
│   ├── variables.css                   # Variables CSS (colores, fuentes)
│   ├── components.css                  # Componentes reutilizables
│   ├── layout.css                      # Layouts y grids
│   └── pages/
│       ├── home.css
│       ├── donante.css
│       ├── beneficiario.css
│       └── admin.css
├── assets/
│   ├── images/
│   │   ├── logo.png
│   │   ├── hero-illustration.png
│   │   └── campaigns/
│   └── icons/
│       ├── heart.svg
│       ├── money.svg
│       └── user.svg
├── PLAN_DESARROLLO.md                  # Este archivo
└── 03MASW-Grupo7-Actividad2.pdf        # Documentación de requisitos
```

---

## 🎯 VISTAS A DESARROLLAR

### ✅ FASE 1: Replicación de Diseños de Figma (5 vistas)

| # | Vista | Archivo | Estado | Prioridad |
|---|-------|---------|--------|-----------|
| 1 | Home (Landing Page) | `index.html` | ✅ Completado | 🔴 Alta |
| 2 | Dashboard Donante | `donante-dashboard.html` | ✅ Completado | 🔴 Alta |
| 3 | Listado de Campañas | `donante-campanas.html` | ✅ Completado | 🔴 Alta |
| 4 | Formulario de Donación | `donante-donacion.html` | ✅ Completado | 🔴 Alta |
| 5 | Panel de Reportes Admin | `admin-reportes.html` | ✅ Completado | 🔴 Alta |

### ✅ FASE 2: Vistas Críticas Faltantes (7 vistas) - COMPLETADA

| # | Vista | Archivo | Requisitos | Estado | Prioridad |
|---|-------|---------|------------|--------|-----------|
| 6 | Iniciar Sesión | `login.html` | I2, T7-T9 | ✅ Completado | 🔴 Alta |
| 7 | Registrarse | `registro.html` | I1, T1-T6 | ✅ Completado | 🔴 Alta |
| 8 | Solicitar Prótesis | `beneficiario-solicitar.html` | I3, T10-T12 | ✅ Completado | 🔴 Alta |
| 9 | Gestionar Solicitudes | `admin-solicitudes.html` | I4, T13-T16 | ✅ Completado | 🔴 Alta |
| 10 | Gestionar Inventario | `admin-inventario.html` | I7, T23-T25 | ✅ Completado | 🔴 Alta |
| 11 | Publicar Actualización | `admin-actualizar-caso.html` | I9, T26-T27 | ✅ Completado | 🔴 Alta |
| 12 | Detalle de Campaña + Comentarios | `campana-detalle.html` | I6, I10, T29-T30 | ✅ Completado | 🔴 Alta |

### ✅ FASE 3: Vistas Secundarias (5 vistas) - COMPLETADA

| # | Vista | Archivo | Estado | Prioridad |
|---|-------|---------|--------|-----------|
| 13 | Dashboard Admin | `admin-dashboard.html` | ✅ Completado | 🟡 Media |
| 14 | Dashboard Beneficiario | `beneficiario-dashboard.html` | ✅ Completado | 🟡 Media |
| 15 | Mis Solicitudes (Beneficiario) | `beneficiario-mis-solicitudes.html` | ✅ Completado | 🟡 Media |
| 16 | Moderación de Comentarios | `admin-moderacion.html` | ✅ Completado | 🟡 Media |
| 17 | Mis Favoritos | `donante-favoritos.html` | ✅ Completado | 🟡 Media |

**Total de vistas**: 17

---

## 🧩 COMPONENTES REUTILIZABLES

### Navegación
- [x] Header Público (Inicio, Campañas, Contacto, Login, Sign Up)
- [ ] Header Donante (Dashboard, Campañas, Favoritos, Historial, Fondo General)
- [ ] Header Beneficiario (Dashboard, Solicitudes, Mi Perfil)
- [ ] Header Admin (Dashboard, Solicitudes, Inventario, Reportes, Moderacion)
- [ ] Avatar con Dropdown

### Botones
- [ ] Button Primary (glassmorphism)
- [ ] Button Secondary (outline)
- [ ] Button Icon (circular)
- [ ] Button CTA (con icono)

### Cards
- [ ] Card Campaña (imagen, progreso, botón, favorito)
- [ ] Card KPI (icono + métrica)
- [ ] Card Donación (historial)

### Formularios
- [ ] Input Text (glassmorphism)
- [ ] Input Email
- [ ] Input Password
- [ ] Textarea
- [ ] Dropdown/Select
- [ ] Checkbox
- [ ] Radio Button
- [ ] File Upload

### Tablas
- [ ] Table Donaciones
- [ ] Table Solicitudes
- [ ] Table Inventario

### Otros
- [ ] Progress Bar
- [ ] Badge de Estado
- [ ] Modal/Overlay
- [ ] Tooltip
- [ ] Alert/Notification

---

## 📝 REGISTRO DE CAMBIOS

### 2025-11-23 - Sesión 1: Estructura Base y Primera Vista

**Actividades realizadas**:
- ✅ Creación de estructura del proyecto
- ✅ Documentación del plan de desarrollo (PLAN_DESARROLLO.md)
- ✅ Definición del sistema de diseño
- ✅ Análisis de vistas existentes en Figma
- ✅ Creación de archivos CSS base:
  - `css/reset.css` - Reset CSS completo
  - `css/variables.css` - Variables CSS (colores, fuentes, espaciados, efectos)
  - `css/components.css` - Componentes reutilizables (botones, inputs, cards, tablas, etc.)
  - `css/layout.css` - Layouts, gradientes de fondo, header, hero, dashboard
- ✅ **Vista 1 completada**: `index.html` (Home/Landing Page)
  - Header con logo y navegación pública
  - Hero section con título, subtítulo y descripción
  - Botones CTA: "Ser paciente" y "Ser Donante"
  - Ilustración hero con círculo glassmorphism
  - Botón de navegación flotante
  - Gradientes de fondo multicapa

**Archivos creados**:
```
/PacoMorlaco/
├── index.html ✅
├── css/
│   ├── reset.css ✅
│   ├── variables.css ✅
│   ├── components.css ✅
│   └── layout.css ✅
└── PLAN_DESARROLLO.md ✅
```

**Progreso**:
- **Fase 1**: 1/5 vistas completadas (20%)
- **Total general**: 1/17 vistas completadas (5.9%)

**Próximos pasos** (pendiente de aprobación del usuario):
1. Replicar vista 2: Dashboard Donante (`donante-dashboard.html`)
2. Replicar vista 3: Listado de Campañas (`donante-campanas.html`)
3. Replicar vista 4: Formulario de Donación (`donante-donacion.html`)
4. Replicar vista 5: Panel de Reportes Admin (`admin-reportes.html`)

**Decisiones pendientes del usuario**:
- ✅ Confirmar si continuar con vista 2 (Dashboard Donante)
- Orden de prioridad para desarrollo de vistas faltantes
- Contenido de texto final para cada sección

---

### 2025-11-23 - Sesión 2: Integración de Imágenes

**Actividades realizadas**:
- ✅ Creación de carpeta `assets/images/`
- ✅ Integración de imágenes reales del proyecto:
  - `logo.png` - Logo circular de Paco el Morlaco
  - `hero-illustration.png` - Ilustración principal (padre e hijo)
- ✅ Actualización de `index.html` con rutas correctas de imágenes
- ✅ Mejora de estilos CSS para visualización correcta:
  - Logo con `object-fit: cover` y z-index
  - Hero image con `object-fit: contain` y posicionamiento mejorado
  - Ajuste del círculo glassmorphism de fondo

**Archivos modificados**:
- `index.html` - Rutas de imágenes actualizadas
- `css/layout.css` - Estilos mejorados para logo e ilustración hero

**Archivos creados**:
- `assets/images/logo.png` ✅
- `assets/images/hero-illustration.png` ✅

**Progreso**:
- **Fase 1**: 1/5 vistas completadas (20%)
- **Total general**: 1/17 vistas completadas (5.9%)

**Próximos pasos** (pendiente de aprobación del usuario):
1. Replicar vista 2: Dashboard Donante (`donante-dashboard.html`)
2. Replicar vista 3: Listado de Campañas (`donante-campanas.html`)
3. Replicar vista 4: Formulario de Donación (`donante-donacion.html`)
4. Replicar vista 5: Panel de Reportes Admin (`admin-reportes.html`)

---

### 2025-11-23 - Sesión 3: Mejoras de Responsive Design

**Actividades realizadas**:
- ✅ Mejora del diseño responsive para visualización al 100%
- ✅ Ajustes en `css/layout.css`:
  - Header con max-width y padding responsive
  - Container con width 100% y max-width
  - Hero section con max-width de 1400px
  - Hero image redimensionada (600px círculo, 500px imagen)
  - Hero content con max-width de 650px
- ✅ Agregadas media queries para:
  - Pantallas medianas (max-width: 1400px)
  - Tablets (max-width: 1024px)
  - Móviles (max-width: 768px)
- ✅ Eliminado inline style en hero__content del HTML

**Archivos modificados**:
- `index.html` - Eliminado max-width inline
- `css/layout.css` - Mejoras responsive y media queries

**Mejoras implementadas**:
- ✅ Visualización correcta al 100% de zoom
- ✅ Visualización correcta al 67% de zoom
- ✅ Diseño adaptable a diferentes tamaños de pantalla
- ✅ Espaciado y proporciones mejoradas
- ✅ Imágenes con tamaños optimizados

**Progreso**:
- **Fase 1**: 1/5 vistas completadas (20%)
- **Total general**: 1/17 vistas completadas (5.9%)

**Próximos pasos** (pendiente de aprobación del usuario):
1. Verificar visualización mejorada
2. Replicar vista 3: Listado de Campañas (`donante-campanas.html`)
3. Replicar vista 4: Formulario de Donación (`donante-donacion.html`)
4. Replicar vista 5: Panel de Reportes Admin (`admin-reportes.html`)

---

### 2025-11-23 - Sesión 4: Vista 2 - Dashboard Donante

**Actividades realizadas**:
- ✅ Creación de `donante-dashboard.html`
- ✅ Implementación de header con navegación de donante (5 items)
- ✅ Implementación de menú de usuario con avatar
- ✅ Sección de bienvenida personalizada
- ✅ 3 KPIs con iconos:
  - Total Donado ($2,450)
  - Campañas Apoyadas (8)
  - Personas Ayudadas (12)
- ✅ Tabla de actividad reciente con 5 registros
- ✅ Botón CTA "Ver Todas las Campañas"
- ✅ Mejoras en estilos de tabla (`components.css`):
  - Table container con glassmorphism
  - Bordes y espaciado mejorados
  - Hover effects en filas

**Componentes utilizados**:
- Header con navegación donante
- User menu con avatar
- Card KPI (x3)
- Table con badges de estado
- Botón primary-text

**Archivos creados**:
- `donante-dashboard.html` ✅

**Archivos modificados**:
- `css/components.css` - Mejoras en tabla

**Progreso**:
- **Fase 1**: 2/5 vistas completadas (40%)
- **Total general**: 2/17 vistas completadas (11.8%)

**Próximos pasos** (pendiente de aprobación del usuario):
1. Replicar vista 4: Formulario de Donación (`donante-donacion.html`)
2. Replicar vista 5: Panel de Reportes Admin (`admin-reportes.html`)

---

### 2025-11-23 - Sesión 5: Vista 3 - Listado de Campañas

**Actividades realizadas**:
- ✅ Creación de `donante-campanas.html`
- ✅ Implementación de carrusel de campañas
- ✅ 3 Cards de campaña con:
  - Imagen placeholder
  - Título y subtítulo
  - Descripción con truncado (4 líneas)
  - Barra de progreso con porcentaje
  - Botón "Donar"
  - Botón de favoritos (corazón)
- ✅ Botones de navegación del carrusel (prev/next)
- ✅ Mejoras en estilos de carrusel (`layout.css`):
  - Posicionamiento responsive
  - Botones con glassmorphism
  - Hover effects
- ✅ Mejoras en cards de campaña (`components.css`):
  - Hover effect con elevación
  - Truncado de texto con line-clamp
  - Espaciado optimizado
  - Min-width para mantener tamaño

**Componentes utilizados**:
- Carousel con navegación
- Card campaign (x3)
- Progress bar
- Botones primary-text e icon
- SVG icons (corazón, flechas)

**Archivos creados**:
- `donante-campanas.html` ✅

**Archivos modificados**:
- `css/layout.css` - Mejoras en carrusel
- `css/components.css` - Mejoras en card-campaign

**Progreso**:
- **Fase 1**: 3/5 vistas completadas (60%)
- **Total general**: 3/17 vistas completadas (17.6%)

**Próximos pasos** (pendiente de aprobación del usuario):
1. Replicar vista 5: Panel de Reportes Admin (`admin-reportes.html`)

---

### 2025-11-23 - Sesión 6: Vista 4 - Formulario de Donación

**Actividades realizadas**:
- ✅ Creación de `donante-donacion.html`
- ✅ Formulario completo de donación con:
  - Selector de campaña (dropdown)
  - Botones de monto predefinido ($50, $100, $250, $500, $1,000)
  - Input para monto personalizado
  - Información personal (nombre, email)
  - Métodos de pago (tarjeta, PayPal, transferencia)
  - Detalles de tarjeta (número, fecha, CVV)
  - Resumen de donación con totales
  - Checkbox para donación anónima
  - Botón de confirmación
- ✅ Nuevos estilos en `components.css`:
  - `.donation-form` - Estructura del formulario
  - `.form-group`, `.form-label`, `.form-row` - Elementos de formulario
  - `.amount-options`, `.amount-btn` - Botones de monto
  - `.payment-methods`, `.payment-method` - Métodos de pago
  - `.card-details` - Detalles de tarjeta
  - `.donation-summary` - Resumen con totales
  - `.checkbox-label` - Etiqueta de checkbox

**Componentes utilizados**:
- Form elements (input, select, radio, checkbox)
- Amount buttons con estado activo
- Payment method cards
- Summary box con glassmorphism
- Botón submit con icono

**Archivos creados**:
- `donante-donacion.html` ✅

**Archivos modificados**:
- `css/components.css` - Estilos de formulario de donación

**Progreso**:
- **Fase 1**: 4/5 vistas completadas (80%)
- **Total general**: 4/17 vistas completadas (23.5%)

**Próximos pasos** (pendiente de aprobación del usuario):
1. Replicar vista 5: Panel de Reportes Admin (`admin-reportes.html`)
2. Continuar con Fase 2: Vistas críticas faltantes

---

### 2025-11-23 - Sesión 7: Vista 5 - Panel de Reportes Admin ✅ FASE 1 COMPLETADA

**Actividades realizadas**:
- ✅ Creación de `admin-reportes.html`
- ✅ Navegación de administrador (5 items)
- ✅ Filtros de reportes:
  - Selector de período (semana, mes, trimestre, año, personalizado)
  - Selector de tipo de reporte (todos, donaciones, campañas, solicitudes)
  - Botón "Exportar" con icono
- ✅ 4 KPIs principales:
  - Total Recaudado: $45,230
  - Campañas Activas: 24
  - Donantes Activos: 156
  - Beneficiarios Ayudados: 38
- ✅ Gráfico de barras interactivo:
  - 12 barras (meses del año)
  - Valores de donación por mes
  - Hover effects con valores
  - Gradiente púrpura
- ✅ Tabla de campañas top:
  - 5 campañas con mayor recaudación
  - Columnas: Campaña, Beneficiario, Meta, Recaudado, Progreso, Estado
  - Barras de progreso inline
  - Badges de estado
- ✅ Nuevos estilos en `components.css`:
  - `.report-filters` - Filtros de reportes
  - `.chart-container`, `.chart-placeholder` - Contenedor de gráficos
  - `.chart-bars`, `.chart-bar` - Barras del gráfico
  - `.chart-bar__fill`, `.chart-bar__label`, `.chart-bar__value` - Elementos de barra
  - Hover effects interactivos

**Componentes utilizados**:
- Report filters con selects
- Card KPI (x4)
- Chart de barras con gradientes
- Table con progress bars inline
- Badges de estado

**Archivos creados**:
- `admin-reportes.html` ✅

**Archivos modificados**:
- `css/components.css` - Estilos de reportes y gráficos

**Progreso**:
- **Fase 1**: 5/5 vistas completadas (100%) 🎉
- **Total general**: 5/17 vistas completadas (29.4%)

**🎉 FASE 1 COMPLETADA - Replicación de Diseños de Figma**

**Próximos pasos** (pendiente de aprobación del usuario):
1. Iniciar Fase 2: Vistas críticas faltantes
2. Desarrollar vistas secundarias (Fase 3)

---

### 2025-11-23 - Sesión 8: Vista 6 - Login (Iniciar Sesión)

**Actividades realizadas**:
- ✅ Creación de `login.html`
- ✅ Formulario de inicio de sesión con:
  - Campo de correo electrónico
  - Campo de contraseña
  - Checkbox "Recordarme"
  - Link "¿Olvidaste tu contraseña?"
  - Botón "Iniciar Sesión"
- ✅ Divider "o continúa con"
- ✅ Botones de login social:
  - Google (con logo SVG)
  - Facebook (con logo SVG)
- ✅ Link a registro: "¿No tienes una cuenta? Regístrate aquí"
- ✅ Nuevos estilos en `layout.css`:
  - `.auth-section` - Sección centrada verticalmente
  - `.auth-container`, `.auth-card` - Contenedor con glassmorphism
  - `.auth-card__title`, `.auth-card__subtitle` - Títulos
  - `.auth-form` - Formulario
  - `.auth-options` - Recordarme y olvidaste contraseña
  - `.auth-link` - Links con hover
  - `.auth-divider` - Separador con línea
  - `.social-login`, `.social-btn` - Botones sociales
  - `.auth-footer` - Footer con link a registro

**Componentes utilizados**:
- Auth card con glassmorphism
- Form inputs (email, password)
- Checkbox
- Social buttons con SVG icons
- Links con hover effects

**Archivos creados**:
- `login.html` ✅

**Archivos modificados**:
- `css/layout.css` - Estilos de autenticación (+137 líneas)

**Progreso**:
- **Fase 1**: 5/5 vistas completadas (100%) ✅
- **Fase 2**: 1/7 vistas completadas (14.3%)
- **Total general**: 6/17 vistas completadas (35.3%)

**Próximos pasos** (pendiente de aprobación del usuario):
1. Vista 7: Registro (`registro.html`)
2. Vista 8: Solicitar Prótesis (`beneficiario-solicitar.html`)
3. Vista 9: Gestionar Solicitudes (`admin-solicitudes.html`)

---

### 2025-11-23 - Sesión 9: Vista 7 - Registro

**Actividades realizadas**:
- ✅ Creación de `registro.html`
- ✅ Selector de tipo de usuario:
  - Card "Donante" con icono de corazón
  - Card "Beneficiario" con icono de persona
  - Estado seleccionado con fondo azul y texto blanco
  - Hover effects con elevación
- ✅ Formulario de registro completo:
  - Nombre y Apellido (2 columnas)
  - Correo electrónico
  - Contraseña y Confirmar contraseña (2 columnas)
  - Checkbox términos y condiciones con links
  - Botón "Crear Cuenta"
- ✅ Divider "o regístrate con"
- ✅ Botones de registro social (Google, Facebook)
- ✅ Link a login: "¿Ya tienes una cuenta? Inicia sesión aquí"
- ✅ Nuevos estilos en `components.css`:
  - `.user-type-selector` - Grid 2 columnas
  - `.user-type-option` - Label clickeable
  - `.user-type-card` - Card con glassmorphism
  - Estados: hover (elevación), checked (fondo azul)
  - Transiciones en SVG icons

**Componentes utilizados**:
- User type selector (nuevo componente)
- Form inputs (text, email, password)
- Checkbox con links inline
- Social buttons
- Auth card (max-width: 650px)

**Archivos creados**:
- `registro.html` ✅

**Archivos modificados**:
- `css/components.css` - User type selector (+76 líneas)

**Progreso**:
- **Fase 1**: 5/5 vistas completadas (100%) ✅
- **Fase 2**: 2/7 vistas completadas (28.6%)
- **Total general**: 7/17 vistas completadas (41.2%)

**Próximos pasos** (pendiente de aprobación del usuario):
1. Vista 8: Solicitar Prótesis (`beneficiario-solicitar.html`)
2. Vista 9: Gestionar Solicitudes (`admin-solicitudes.html`)
3. Vista 10: Gestionar Inventario (`admin-inventario.html`)

---

### 2025-11-23 - Sesión 10: Vista 8 - Solicitar Prótesis

**Actividades realizadas**:
- ✅ Creación de `beneficiario-solicitar.html`
- ✅ Navegación de beneficiario (3 items)
- ✅ Formulario extenso dividido en 5 secciones:
  
  **1. Información Personal:**
  - Nombre completo, Fecha de nacimiento
  - Teléfono, Correo electrónico
  - Dirección completa
  
  **2. Información Médica:**
  - Tipo de prótesis (select: pierna, brazo, mano, pie, rodilla, otra)
  - Lado afectado (izquierdo, derecho, ambos)
  - Causa de amputación (accidente, enfermedad, congénito, otra)
  - Fecha de amputación
  - Descripción médica detallada (textarea)
  
  **3. Tu Historia:**
  - Cuéntanos tu historia (textarea 6 filas)
  - ¿Cómo mejoraría tu vida? (textarea 4 filas)
  
  **4. Información Económica:**
  - Situación laboral (select)
  - Ingresos mensuales (select con rangos)
  - Seguro médico (radio: sí, no, parcial)
  
  **5. Documentación:**
  - Informe médico (PDF, máx. 5MB)
  - Fotografía personal (JPG/PNG, máx. 2MB)
  - Documentación adicional (opcional, múltiple)
  - 2 Checkboxes de aceptación

- ✅ Nuevos estilos en `components.css`:
  - `.request-form-container`, `.request-form`
  - `.form-help` - Texto de ayuda
  - `.input-file` - Input de archivo con botón estilizado
  - `.input-file::file-selector-button` - Botón personalizado
  - `.radio-group`, `.radio-label` - Grupo de radios

- ✅ Nuevos estilos en `layout.css`:
  - `.dashboard__subtitle` - Subtítulo del dashboard

**Componentes utilizados**:
- Form sections (5 secciones)
- Inputs (text, email, tel, date)
- Selects (múltiples opciones)
- Textareas (3 diferentes)
- File inputs (3, con estilos personalizados)
- Radio buttons group
- Checkboxes (2 de aceptación)
- Botón submit con icono

**Archivos creados**:
- `beneficiario-solicitar.html` ✅

**Archivos modificados**:
- `css/components.css` - Request form (+81 líneas)
- `css/layout.css` - Dashboard subtitle (+9 líneas)

**Progreso**:
- **Fase 1**: 5/5 vistas completadas (100%) ✅
- **Fase 2**: 3/7 vistas completadas (42.9%)
- **Total general**: 8/17 vistas completadas (47.1%)

**Próximos pasos** (pendiente de aprobación del usuario):
1. Vista 10: Gestionar Inventario (`admin-inventario.html`)
2. Vista 11: Publicar Actualización (`admin-actualizar-caso.html`)
3. Vista 12: Detalle de Campaña + Comentarios (`campana-detalle.html`)

---

### 2025-11-23 - Sesión 11: Vista 9 - Gestionar Solicitudes (Admin)

**Actividades realizadas**:
- ✅ Creación de `admin-solicitudes.html`
- ✅ Filtros de solicitudes (3 selects): Estado, Tipo de prótesis, Ordenar por
- ✅ Tabla de solicitudes con 7 columnas:
  - ID, Beneficiario (avatar + nombre + email), Tipo de Prótesis, Fecha, Estado, Urgencia, Acciones
- ✅ 5 solicitudes de ejemplo con diferentes estados
- ✅ Componente table-user con avatar circular
- ✅ Badges de urgencia: Alta (rojo), Media (naranja), Baja (verde)
- ✅ Botones de acción: Ver detalles, Aprobar (verde), Rechazar (rojo)
- ✅ Nuevos estilos en `components.css` (+97 líneas):
  - `.request-filters` - Filtros de solicitudes
  - `.table-user`, `.table-user__avatar`, `.table-user__info` - Usuario en tabla
  - `.table-actions` - Acciones de tabla
  - `.badge--urgente`, `.badge--media`, `.badge--baja` - Badges de urgencia
  - `.btn-icon--success`, `.btn-icon--danger` - Variantes de botones

**Archivos creados**:
- `admin-solicitudes.html` ✅

**Archivos modificados**:
- `css/components.css` - Request filters y table user (+97 líneas)

**Progreso**:
- **Fase 1**: 5/5 vistas (100%) ✅
- **Fase 2**: 4/7 vistas (57.1%)
- **Total general**: 9/17 vistas (52.9%) 🎉 **¡Más del 50%!**

**Próximos pasos**:
1. Vista 11: Publicar Actualización
2. Vista 12: Detalle de Campaña + Comentarios

---

### 2025-11-23 - Sesión 12: Vista 10 - Gestionar Inventario (Admin)

**Actividades realizadas**:
- ✅ Creación de `admin-inventario.html`
- ✅ Dashboard header con botón "Agregar Prótesis"
- ✅ 4 Stat cards con iconos:
  - Total Prótesis: 48 (azul)
  - Disponibles: 32 (verde)
  - En Proceso: 12 (naranja)
  - Stock Bajo: 4 (rojo)
- ✅ Filtros: Tipo, Estado, Proveedor
- ✅ Tabla de inventario (8 columnas): ID, Tipo, Modelo, Proveedor, Stock, Estado, Precio, Acciones
- ✅ 3 productos de ejemplo con stock badges
- ✅ Botones: Ver, Editar, Eliminar
- ✅ Nuevos estilos (+120 líneas):
  - `.inventory-stats`, `.stat-card` - Cards de estadísticas
  - `.stat-card__icon` con variantes de color
  - `.stock-badge` con variantes (high, medium, low)
  - `.dashboard-header` - Header con botón

**Archivos creados**:
- `admin-inventario.html` ✅

**Archivos modificados**:
- `css/components.css` (+113 líneas)
- `css/layout.css` (+6 líneas)

**Progreso**:
- **Fase 1**: 5/5 (100%) ✅
- **Fase 2**: 5/7 (71.4%)
- **Total**: 10/17 (58.8%)

---

### 2025-11-23 - Sesión 13: Vista 11 - Publicar Actualización (Admin)

**Actividades realizadas**:
- ✅ Creación de `admin-actualizar-caso.html`
- ✅ 4 secciones de formulario:
  1. Selección de campaña (select)
  2. Contenido: Título, Tipo, Mensaje (textarea)
  3. Multimedia: Imágenes (múltiple), Video
  4. Visibilidad: Radio group, Checkboxes de notificación
- ✅ Vista previa de actualización:
  - Avatar + Autor + Fecha + Badge
  - Título y texto de ejemplo
  - Botones: Me gusta, Comentar
- ✅ Botones de acción: Guardar borrador, Publicar
- ✅ Nuevos estilos (+120 líneas):
  - `.update-form-container`, `.update-form`
  - `.form-actions` - Botones alineados a la derecha
  - `.update-preview` - Card de vista previa
  - `.update-preview__header/avatar/info/content/footer`
  - `.update-preview__action` - Botones con hover

**Archivos creados**:
- `admin-actualizar-caso.html` ✅

**Archivos modificados**:
- `css/components.css` (+120 líneas)

**Progreso**:
- **Fase 1**: 5/5 (100%) ✅
- **Fase 2**: 6/7 (85.7%)
- **Total**: 11/17 (64.7%)

---

### 2025-11-23 - Sesión 14: Vista 12 - Detalle de Campaña + Comentarios ✅ FASE 2 COMPLETADA

**Actividades realizadas**:
- ✅ Creación de `campana-detalle.html`
- ✅ Hero de campaña con imagen (400px height)
- ✅ Layout 2 columnas: Main content + Sidebar
- ✅ Sección Historia con 3 párrafos
- ✅ Actualizaciones (2 cards)
- ✅ Sección de Comentarios:
  - Formulario de comentario con avatar
  - 3 comentarios con avatar, autor, fecha
  - Botones: Me gusta (con contador), Responder
- ✅ Sidebar:
  - Donation card: Monto, progreso, stats, botón
  - Beneficiary card: Avatar, info, detalles
  - Top donors card: 3 donantes con avatares
- ✅ Nuevo archivo CSS: `campaign-detail.css` (+390 líneas)
- ✅ Estilos en `layout.css` (+104 líneas)

**Archivos creados**:
- `campana-detalle.html` ✅
- `css/campaign-detail.css` ✅

**Archivos modificados**:
- `css/layout.css` (+104 líneas)

**Progreso**:
- **Fase 1**: 5/5 (100%) ✅ COMPLETADA
- **Fase 2**: 7/7 (100%) ✅ COMPLETADA
- **Total**: 12/17 (70.6%)

**🎉 FASE 2 COMPLETADA - Todas las vistas críticas implementadas**

---

## 🎓 ENTREGABLES PARA ACTIVIDAD 3

### Prototipo
- [ ] Archivos HTML de todas las vistas
- [ ] Archivos CSS organizados
- [ ] Assets (imágenes, iconos)
- [ ] Prototipo navegable (enlaces entre páginas)
- [ ] Archivo .zip para entrega

### Informe
- [ ] Introducción (máx 100 palabras)
- [ ] Justificación del tipo de prototipo
- [ ] Mapa de navegación (gráfico)
- [ ] Diseño de menús
- [ ] Conclusiones sobre resultados de aprendizaje
- [ ] Bibliografía (formato APA)

### Exportación a Figma
- [ ] Importar diseños HTML a Figma
- [ ] Crear enlaces de navegación en Figma
- [ ] Generar enlace compartible

---

## 📚 REFERENCIAS

- Actividad 2: Requisitos y Modelos Conceptuales
- Benyon, D. (2014). Designing Interactive Systems
- Garrett, J.J. (2011). The Elements of User Experience
- Material de apoyo de la asignatura

---

**Última actualización**: 23/11/2025 - 11:45 AM  
**Responsable**: Grupo 7 - Actividad 3
