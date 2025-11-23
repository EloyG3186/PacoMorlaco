# 🤝 Paco el Morlaco
## Prototipo de Alta Fidelidad - Actividad 3

**Proyecto**: Plataforma web para gestión de prótesis y donaciones  
**Asignatura**: Ingeniería de Software Web (03MASW)  
**Universidad**: Universidad Internacional de Valencia (VIU)  
**Grupo**: Grupo 7  
**Periodo**: 2025/26 A

---

## 📖 Descripción

Paco el Morlaco es un proyecto colaborativo que devuelve esperanza, movilidad y dignidad a quienes perdieron una extremidad. La plataforma conecta a beneficiarios que necesitan prótesis con donantes que desean ayudar, facilitando la gestión de solicitudes, donaciones, inventario y seguimiento de casos.

---

## 🎨 Stack Tecnológico

- **HTML5**: Estructura semántica
- **CSS3**: Estilos con sistema de diseño glassmorphism
- **Fuentes**: Montserrat (Google Fonts)

---

## 📁 Estructura del Proyecto

```
/PacoMorlaco/
├── index.html                          # Home (Landing Page) ✅
├── login.html                          # Iniciar Sesión
├── registro.html                       # Registrarse
├── donante-dashboard.html              # Dashboard Donante
├── donante-campanas.html               # Listado de Campañas
├── donante-donacion.html               # Formulario de Donación
├── donante-favoritos.html              # Mis Favoritos
├── donante-historial.html              # Historial de Donaciones
├── beneficiario-dashboard.html         # Dashboard Beneficiario
├── beneficiario-solicitar.html         # Solicitar Prótesis
├── beneficiario-mis-solicitudes.html   # Mis Solicitudes
├── admin-dashboard.html                # Dashboard Admin
├── admin-solicitudes.html              # Gestionar Solicitudes
├── admin-inventario.html               # Gestionar Inventario
├── admin-reportes.html                 # Generar Reportes
├── admin-actualizar-caso.html          # Publicar Actualización
├── admin-moderacion.html               # Moderar Comentarios
├── campana-detalle.html                # Detalle de Campaña
├── css/
│   ├── reset.css                       # Reset CSS ✅
│   ├── variables.css                   # Variables CSS ✅
│   ├── components.css                  # Componentes ✅
│   └── layout.css                      # Layouts ✅
├── assets/
│   ├── images/
│   └── icons/
├── PLAN_DESARROLLO.md                  # Plan de desarrollo ✅
├── README.md                           # Este archivo ✅
└── 03MASW-Grupo7-Actividad2.pdf        # Documentación de requisitos
```

---

## 🚀 Cómo Visualizar el Proyecto

### Opción 1: Abrir directamente en el navegador

1. Navega a la carpeta del proyecto
2. Haz doble clic en `index.html`
3. El archivo se abrirá en tu navegador predeterminado

### Opción 2: Usar un servidor local (recomendado)

#### Con Python:
```bash
# Python 3
python -m http.server 8000

# Luego abre: http://localhost:8000
```

#### Con Node.js (http-server):
```bash
npx http-server -p 8000

# Luego abre: http://localhost:8000
```

#### Con VS Code (Live Server):
1. Instala la extensión "Live Server"
2. Clic derecho en `index.html`
3. Selecciona "Open with Live Server"

---

## 🎯 Progreso del Proyecto

### Fase 1: Replicación de Diseños de Figma ✅ COMPLETADA
- [x] **Vista 1**: Home (Landing Page) - `index.html` ✅
- [x] **Vista 2**: Dashboard Donante - `donante-dashboard.html` ✅
- [x] **Vista 3**: Listado de Campañas - `donante-campanas.html` ✅
- [x] **Vista 4**: Formulario de Donación - `donante-donacion.html` ✅
- [x] **Vista 5**: Panel de Reportes Admin - `admin-reportes.html` ✅

**Progreso**: 5/5 vistas (100%) 🎉

### Fase 2: Vistas Críticas Faltantes ✅ COMPLETADA
- [x] Iniciar Sesión - `login.html` ✅
- [x] Registrarse - `registro.html` ✅
- [x] Solicitar Prótesis - `beneficiario-solicitar.html` ✅
- [x] Gestionar Solicitudes - `admin-solicitudes.html` ✅
- [x] Gestionar Inventario - `admin-inventario.html` ✅
- [x] Publicar Actualización - `admin-actualizar-caso.html` ✅
- [x] Detalle de Campaña + Comentarios - `campana-detalle.html` ✅

**Progreso**: 7/7 vistas (100%) 🎉

### Fase 3: Vistas Secundarias ✅ COMPLETADA
- [x] Dashboard Admin - `admin-dashboard.html` ✅
- [x] Dashboard Beneficiario - `beneficiario-dashboard.html` ✅
- [x] Mis Solicitudes (Beneficiario) - `beneficiario-mis-solicitudes.html` ✅
- [x] Moderación de Comentarios - `admin-moderacion.html` ✅
- [x] Mis Favoritos - `donante-favoritos.html` ✅

**Progreso**: 5/5 vistas (100%) 🎉

**Total general**: 17/17 vistas (100%) 🎉🎉🎉 **¡PROYECTO COMPLETADO!**

---

## 🎨 Sistema de Diseño

### Paleta de Colores
- **Azules**: `#DDE3F7`, `#AABBEE`, `#8AA0EA`, `#829EE6`, `#C7C9F1`, `#A1CEFF`, `#6E89FD`
- **Púrpuras**: `#C6AFE3`, `#DCC3F9`, `#E8DEF6`, `#F0ECF7`, `#E5D4F5`, `#CEB2ED`
- **Rosas**: `#F3F6FA`, `#EACCD1`, `#D7CAE1`

### Tipografía
- **Fuente**: Montserrat (Google Fonts)
- **Pesos**: 300, 400, 500, 700, 800

### Efectos
- **Glassmorphism**: `backdrop-filter: blur(50px)`
- **Sombras internas**: `box-shadow: 0px 2px 8px rgba(255, 255, 255, 0.40) inset`
- **Bordes**: `outline: 1px white solid`

---

## 👥 Equipo

- **Santacruz Cesar Joel**
- **González Eloy David**
- **Skalii Tetiana**

---

## 📚 Referencias

- Actividad 2: Requisitos y Modelos Conceptuales
- Benyon, D. (2014). Designing Interactive Systems
- Garrett, J.J. (2011). The Elements of User Experience
- Material de apoyo de la asignatura

---

## 📝 Notas

- Este es un prototipo de alta fidelidad **no funcional**
- Los datos mostrados son ficticios
- El prototipo será exportado a Figma para la entrega final
- Para más detalles técnicos, consulta `PLAN_DESARROLLO.md`

---

**Última actualización**: 23/11/2025
