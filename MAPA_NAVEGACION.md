# 🗺️ Mapa de Navegación - Paco el Morlaco

## 📋 Estructura de Navegación por Rol

### 🌐 Navegación Pública (No autenticado)
**Páginas**: `index.html`, `login.html`, `registro.html`

**Header Navigation:**
- Inicio → `index.html`
- Campañas → `donante-campanas.html`
- Contacto → `index.html#contacto`

**Header Actions:**
- Login → `login.html`
- Sign Up → `registro.html`

---

### 💙 Navegación Donante (Autenticado como Donante)
**Páginas**: `donante-dashboard.html`, `donante-campanas.html`, `donante-donacion.html`, `campana-detalle.html`

**Header Navigation:**
- Dashboard → `donante-dashboard.html`
- Campañas → `donante-campanas.html`
- Favoritos → `donante-favoritos.html` ⚠️ (Fase 3)
- Historial → `donante-historial.html` ⚠️ (No planificado - opcional)
- Fondo General → `donante-donacion.html`

**Links Internos:**
- Desde `donante-campanas.html` → `campana-detalle.html` (click en campaña)
- Desde `campana-detalle.html` → `donante-donacion.html` (botón "Donar Ahora")

---

### 🤝 Navegación Beneficiario (Autenticado como Beneficiario)
**Páginas**: `beneficiario-dashboard.html`, `beneficiario-solicitar.html`, `beneficiario-mis-solicitudes.html`

**Header Navigation:**
- Dashboard → `beneficiario-dashboard.html` ⚠️ (Fase 3)
- Solicitar Prótesis → `beneficiario-solicitar.html` ✅
- Mis Solicitudes → `beneficiario-mis-solicitudes.html` ⚠️ (Fase 3)

---

### 👨‍💼 Navegación Admin (Autenticado como Admin)
**Páginas**: `admin-dashboard.html`, `admin-solicitudes.html`, `admin-inventario.html`, `admin-reportes.html`, `admin-moderacion.html`, `admin-actualizar-caso.html`

**Header Navigation:**
- Dashboard → `admin-dashboard.html` ⚠️ (Fase 3)
- Solicitudes → `admin-solicitudes.html` ✅
- Inventario → `admin-inventario.html` ✅
- Reportes → `admin-reportes.html` ✅
- Moderación → `admin-moderacion.html` ⚠️ (Fase 3)

**Links Internos:**
- Desde `admin-solicitudes.html` → `admin-actualizar-caso.html` (botón "Publicar campaña")

---

## ✅ Estado de Implementación

### Fase 1 - Completada ✅
- ✅ `index.html` - Home
- ✅ `donante-dashboard.html` - Dashboard Donante
- ✅ `donante-campanas.html` - Listado Campañas
- ✅ `donante-donacion.html` - Formulario Donación
- ✅ `admin-reportes.html` - Panel Reportes

### Fase 2 - Completada ✅
- ✅ `login.html` - Iniciar Sesión
- ✅ `registro.html` - Registrarse
- ✅ `beneficiario-solicitar.html` - Solicitar Prótesis
- ✅ `admin-solicitudes.html` - Gestionar Solicitudes
- ✅ `admin-inventario.html` - Gestionar Inventario
- ✅ `admin-actualizar-caso.html` - Publicar Actualización
- ✅ `campana-detalle.html` - Detalle Campaña + Comentarios

### Fase 3 - Pendiente ⏳
- ⏳ `beneficiario-dashboard.html` - Dashboard Beneficiario
- ⏳ `beneficiario-mis-solicitudes.html` - Mis Solicitudes
- ⏳ `admin-dashboard.html` - Dashboard Admin
- ⏳ `admin-moderacion.html` - Moderación Comentarios
- ⏳ `donante-favoritos.html` - Mis Favoritos

### No Planificadas (Opcionales)
- ❌ `donante-historial.html` - Historial de Donaciones

---

## 🔗 Links que Necesitan Verificación

### Links en Navegación Donante
- ✅ `donante-dashboard.html` → Existe
- ✅ `donante-campanas.html` → Existe
- ⚠️ `donante-favoritos.html` → Fase 3 (pendiente)
- ⚠️ `donante-historial.html` → No planificado (se puede remover del nav)
- ✅ `donante-donacion.html` → Existe

### Links en Navegación Beneficiario
- ⚠️ `beneficiario-dashboard.html` → Fase 3 (pendiente)
- ✅ `beneficiario-solicitar.html` → Existe
- ⚠️ `beneficiario-mis-solicitudes.html` → Fase 3 (pendiente)

### Links en Navegación Admin
- ⚠️ `admin-dashboard.html` → Fase 3 (pendiente)
- ✅ `admin-solicitudes.html` → Existe
- ✅ `admin-inventario.html` → Existe
- ✅ `admin-reportes.html` → Existe
- ⚠️ `admin-moderacion.html` → Fase 3 (pendiente)

---

## 📝 Acciones Recomendadas

### 1. Remover "Historial" de navegación Donante
El item "Historial" no está planificado en ninguna fase. Se recomienda:
- **Opción A**: Removerlo de la navegación
- **Opción B**: Dejarlo pero que apunte a `donante-dashboard.html` temporalmente

### 2. Completar Fase 3
Desarrollar las 5 vistas pendientes para completar todos los links de navegación.

### 3. Agregar Breadcrumbs (Opcional)
Para mejorar la navegación, considerar agregar breadcrumbs en vistas de detalle:
- `campana-detalle.html`: Inicio > Campañas > [Nombre Campaña]

---

## 🎯 Flujos de Usuario Principales

### Flujo 1: Donante hace una donación
1. `index.html` (público)
2. Click "Sign Up" → `registro.html`
3. Registro como Donante
4. Redirect → `donante-dashboard.html`
5. Click "Campañas" → `donante-campanas.html`
6. Click en campaña → `campana-detalle.html`
7. Click "Donar Ahora" → `donante-donacion.html`
8. Completar donación → Redirect `donante-dashboard.html`

### Flujo 2: Beneficiario solicita prótesis
1. `index.html` (público)
2. Click "Sign Up" → `registro.html`
3. Registro como Beneficiario
4. Redirect → `beneficiario-dashboard.html` (Fase 3)
5. Click "Solicitar Prótesis" → `beneficiario-solicitar.html`
6. Completar formulario → Redirect `beneficiario-mis-solicitudes.html` (Fase 3)

### Flujo 3: Admin gestiona solicitudes
1. `login.html`
2. Login como Admin
3. Redirect → `admin-dashboard.html` (Fase 3)
4. Click "Solicitudes" → `admin-solicitudes.html`
5. Click "Aprobar" → Solicitud aprobada
6. Click "Publicar campaña" → `admin-actualizar-caso.html`
7. Publicar actualización → Redirect `admin-solicitudes.html`

---

## ✅ Verificación Completada

**Fecha**: 2025-11-23
**Estado**: Navegación verificada y documentada
**Próximo paso**: Completar Fase 3 para cerrar todos los links pendientes
