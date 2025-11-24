# 🗺️ Flujo de Navegación del Prototipo

**Fecha**: 2025-11-23  
**Propósito**: Documentar cómo acceder a todas las secciones del prototipo

---

## 📍 Punto de Entrada Principal

### index.html
**URL**: `http://127.0.0.1:5500/index.html`

Desde aquí puedes:
- ✅ Ver la página de inicio pública
- ✅ Ir a **Login** (botón en el header)
- ✅ Ir a **Registro** (botón en el header)

---

## 🔐 Acceso a las Diferentes Áreas

### Desde index.html → login.html

**Flujo**:
```
index.html
    ↓ Click en "Login"
login.html
    ↓ Sección "Acceso Rápido - Prototipo"
    ├─→ 👤 Acceder como Donante → donante-dashboard.html
    ├─→ 🙏 Acceder como Beneficiario → beneficiario-dashboard.html
    └─→ ⚙️ Acceder como Administrador → admin-dashboard.html
```

---

## 👥 Roles y Páginas

### 1. 👤 DONANTE (Donor)

**Dashboard**: `donante-dashboard.html`

**Navegación del Donante**:
```
donante-dashboard.html (Dashboard)
    ├─→ donante-campanas.html (Campañas)
    ├─→ donante-favoritos.html (Favoritos)
    └─→ donante-donacion.html (Realizar Donación)
```

**Páginas**:
- ✅ `donante-dashboard.html` - Panel principal del donante
- ✅ `donante-campanas.html` - Explorar campañas
- ✅ `donante-favoritos.html` - Campañas guardadas
- ✅ `donante-donacion.html` - Formulario de donación
- ✅ `campana-detalle.html` - Detalle de una campaña

---

### 2. 🙏 BENEFICIARIO (Beneficiary)

**Dashboard**: `beneficiario-dashboard.html`

**Navegación del Beneficiario**:
```
beneficiario-dashboard.html (Dashboard)
    ├─→ beneficiario-solicitar.html (Solicitar Prótesis)
    └─→ beneficiario-mis-solicitudes.html (Mis Solicitudes)
```

**Páginas**:
- ✅ `beneficiario-dashboard.html` - Panel principal del beneficiario
- ✅ `beneficiario-solicitar.html` - Formulario para solicitar prótesis
- ✅ `beneficiario-mis-solicitudes.html` - Ver estado de solicitudes

---

### 3. ⚙️ ADMINISTRADOR (Admin)

**Dashboard**: `admin-dashboard.html`

**Navegación del Admin**:
```
admin-dashboard.html (Dashboard)
    ├─→ admin-solicitudes.html (Solicitudes)
    ├─→ admin-inventario.html (Inventario)
    ├─→ admin-reportes.html (Reportes)
    ├─→ admin-moderacion.html (Moderación)
    └─→ admin-actualizar-caso.html (Actualizar Caso)
```

**Páginas**:
- ✅ `admin-dashboard.html` - Panel principal del admin
- ✅ `admin-solicitudes.html` - Gestionar solicitudes de beneficiarios
- ✅ `admin-inventario.html` - Gestionar inventario de prótesis
- ✅ `admin-reportes.html` - Ver reportes y estadísticas
- ✅ `admin-moderacion.html` - Moderar contenido
- ✅ `admin-actualizar-caso.html` - Actualizar estado de casos

---

## 🗺️ Mapa Completo del Sitio

```
📁 PACO EL MORLACO - PROTOTIPO
│
├─ 🌐 PÁGINAS PÚBLICAS
│  ├─ index.html (Inicio)
│  ├─ login.html (Iniciar Sesión)
│  └─ registro.html (Registrarse)
│
├─ 👤 ÁREA DONANTE
│  ├─ donante-dashboard.html
│  ├─ donante-campanas.html
│  ├─ donante-favoritos.html
│  ├─ donante-donacion.html
│  └─ campana-detalle.html
│
├─ 🙏 ÁREA BENEFICIARIO
│  ├─ beneficiario-dashboard.html
│  ├─ beneficiario-solicitar.html
│  └─ beneficiario-mis-solicitudes.html
│
└─ ⚙️ ÁREA ADMINISTRADOR
   ├─ admin-dashboard.html
   ├─ admin-solicitudes.html
   ├─ admin-inventario.html
   ├─ admin-reportes.html
   ├─ admin-moderacion.html
   └─ admin-actualizar-caso.html
```

**Total de páginas**: 17

---

## 🚀 Cómo Acceder a las Páginas de Admin

### Opción 1: Desde Login (Recomendado para Prototipo)

1. ✅ Abrir `index.html`
2. ✅ Click en botón **"Login"** en el header
3. ✅ Scroll hacia abajo hasta **"Acceso Rápido - Prototipo"**
4. ✅ Click en **"⚙️ Acceder como Administrador"**
5. ✅ Llegarás a `admin-dashboard.html`

### Opción 2: URL Directa

Simplemente abre en el navegador:
```
http://127.0.0.1:5500/admin-dashboard.html
```

### Opción 3: Desde el Dashboard de Admin

Una vez en `admin-dashboard.html`, usa el menú de navegación:
- Dashboard
- Solicitudes
- Inventario
- Reportes
- Moderación

---

## 🔄 Navegación entre Páginas de Admin

### Desde admin-dashboard.html

**Menú de navegación superior**:
```
┌─────────────────────────────────────────────────────────┐
│ [Logo] [Dashboard] [Solicitudes] [Inventario] [Reportes] [Moderación] [User] │
└─────────────────────────────────────────────────────────┘
```

**Click en cada item para navegar**:
- ✅ **Dashboard** → `admin-dashboard.html`
- ✅ **Solicitudes** → `admin-solicitudes.html`
- ✅ **Inventario** → `admin-inventario.html`
- ✅ **Reportes** → `admin-reportes.html`
- ✅ **Moderación** → `admin-moderacion.html`

**Acciones en las páginas**:
- ✅ Desde `admin-solicitudes.html` → Click en "Actualizar" → `admin-actualizar-caso.html`

---

## 📋 Resumen de Acceso Rápido

### Para Probar el Prototipo

| Rol | Acceso Directo | Desde Login |
|-----|----------------|-------------|
| **Donante** | `donante-dashboard.html` | 👤 Acceder como Donante |
| **Beneficiario** | `beneficiario-dashboard.html` | 🙏 Acceder como Beneficiario |
| **Admin** | `admin-dashboard.html` | ⚙️ Acceder como Administrador |

---

## 🎯 Flujo de Usuario Típico

### Donante
```
1. index.html (Ver campañas destacadas)
2. login.html → Acceder como Donante
3. donante-dashboard.html (Ver resumen)
4. donante-campanas.html (Explorar campañas)
5. campana-detalle.html (Ver detalle)
6. donante-donacion.html (Realizar donación)
7. donante-favoritos.html (Ver favoritos)
```

### Beneficiario
```
1. index.html (Conocer la plataforma)
2. registro.html (Registrarse)
3. login.html → Acceder como Beneficiario
4. beneficiario-dashboard.html (Ver estado)
5. beneficiario-solicitar.html (Solicitar prótesis)
6. beneficiario-mis-solicitudes.html (Ver solicitudes)
```

### Administrador
```
1. login.html → Acceder como Administrador
2. admin-dashboard.html (Ver KPIs)
3. admin-solicitudes.html (Revisar solicitudes)
4. admin-actualizar-caso.html (Actualizar estado)
5. admin-inventario.html (Gestionar stock)
6. admin-moderacion.html (Moderar contenido)
7. admin-reportes.html (Ver estadísticas)
```

---

## 🔧 Modificaciones Realizadas

### login.html

**Agregado**: Sección "Acceso Rápido - Prototipo"

```html
<!-- Acceso Rápido Prototipo -->
<div style="margin-top: 48px; padding-top: 32px; border-top: 1px solid rgba(255, 255, 255, 0.1);">
    <p style="color: var(--text-dark); font-size: var(--font-size-sm); font-weight: var(--font-bold); margin-bottom: 16px; text-align: center;">
        🔧 Acceso Rápido - Prototipo
    </p>
    <div style="display: flex; flex-direction: column; gap: 12px;">
        <a href="donante-dashboard.html" class="btn-secondary" style="width: 100%; text-align: center;">
            👤 Acceder como Donante
        </a>
        <a href="beneficiario-dashboard.html" class="btn-secondary" style="width: 100%; text-align: center;">
            🙏 Acceder como Beneficiario
        </a>
        <a href="admin-dashboard.html" class="btn-secondary" style="width: 100%; text-align: center;">
            ⚙️ Acceder como Administrador
        </a>
    </div>
</div>
```

**Ubicación**: Después del formulario de login, antes del cierre de `.auth-card`

---

## 📱 Navegación Responsive

### Desktop
- ✅ Menú de navegación horizontal en el header
- ✅ Todos los items visibles

### Tablet/Mobile
- ✅ Puede requerir menú hamburguesa (no implementado)
- ✅ Actualmente mantiene navegación horizontal

---

## 🎨 Indicadores Visuales

### Página Activa
El item del menú de la página actual tiene:
- ✅ Fondo con sombreado blanco (`nav__item--active`)
- ✅ Ejemplo: En `admin-inventario.html`, "Inventario" está resaltado

### Logo Clickable
- ✅ Click en el logo → Regresa a `index.html`
- ✅ Funciona en todas las páginas

---

## 📝 Notas para Desarrollo Futuro

### Autenticación Real
En producción, el flujo sería:
```
1. Usuario ingresa credenciales en login.html
2. Backend valida y determina el rol
3. Redirige según el rol:
   - Donante → donante-dashboard.html
   - Beneficiario → beneficiario-dashboard.html
   - Admin → admin-dashboard.html
```

### Protección de Rutas
- ✅ Las páginas de admin deberían requerir autenticación
- ✅ Middleware para verificar permisos
- ✅ Redirección a login si no está autenticado

---

## ✅ Checklist de Navegación

### Páginas Públicas
- [x] index.html accesible
- [x] login.html accesible desde index
- [x] registro.html accesible desde index
- [x] Acceso rápido en login.html

### Área Donante
- [x] Acceso desde login.html
- [x] Navegación entre páginas de donante
- [x] Logo regresa a index.html

### Área Beneficiario
- [x] Acceso desde login.html
- [x] Navegación entre páginas de beneficiario
- [x] Logo regresa a index.html

### Área Admin
- [x] Acceso desde login.html ✅ **NUEVO**
- [x] Navegación entre páginas de admin
- [x] Logo regresa a index.html

---

## 🎯 Resultado Final

### ✅ Ahora puedes acceder a todas las páginas de admin

**Ruta recomendada**:
```
index.html
    ↓ Click "Login"
login.html
    ↓ Scroll down → "Acceso Rápido - Prototipo"
    ↓ Click "⚙️ Acceder como Administrador"
admin-dashboard.html
    ↓ Usa el menú de navegación
Todas las páginas de admin disponibles
```

---

**Estado**: ✅ COMPLETADO  
**Acceso a Admin**: Disponible desde login.html  
**Documentación**: `FLUJO_NAVEGACION_PROTOTIPO.md`
