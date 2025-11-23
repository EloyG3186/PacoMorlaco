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

### 🔄 FASE 2: Vistas Críticas Faltantes (7 vistas)

| # | Vista | Archivo | Requisitos | Estado | Prioridad |
|---|-------|---------|------------|--------|-----------|
| 6 | Iniciar Sesión | `login.html` | I2, T7-T9 | ⏳ Pendiente | 🔴 Alta |
| 7 | Registrarse | `registro.html` | I1, T1-T6 | ⏳ Pendiente | 🔴 Alta |
| 8 | Solicitar Prótesis | `beneficiario-solicitar.html` | I3, T10-T12 | ⏳ Pendiente | 🔴 Alta |
| 9 | Gestionar Solicitudes | `admin-solicitudes.html` | I4, T13-T16 | ⏳ Pendiente | 🔴 Alta |
| 10 | Gestionar Inventario | `admin-inventario.html` | I7, T23-T25 | ⏳ Pendiente | 🔴 Alta |
| 11 | Publicar Actualización | `admin-actualizar-caso.html` | I9, T26-T27 | ⏳ Pendiente | 🔴 Alta |
| 12 | Detalle de Campaña + Comentarios | `campana-detalle.html` | I6, I10, T29-T30 | ⏳ Pendiente | 🔴 Alta |

### 🟡 FASE 3: Vistas Secundarias (5 vistas)

| # | Vista | Archivo | Estado | Prioridad |
|---|-------|---------|--------|-----------|
| 13 | Dashboard Beneficiario | `beneficiario-dashboard.html` | ⏳ Pendiente | 🟡 Media |
| 14 | Mis Solicitudes (Beneficiario) | `beneficiario-mis-solicitudes.html` | ⏳ Pendiente | 🟡 Media |
| 15 | Dashboard Admin | `admin-dashboard.html` | ⏳ Pendiente | 🟡 Media |
| 16 | Moderación de Comentarios | `admin-moderacion.html` | ⏳ Pendiente | 🟡 Media |
| 17 | Mis Favoritos | `donante-favoritos.html` | ⏳ Pendiente | 🟡 Media |

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
