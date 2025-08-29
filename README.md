# 🏋️‍♂️ Calculadora Olímpica — PWA

Aplicación **Progressive Web App (PWA)** para calcular el peso total levantado en **levantamientos olímpicos**.  
Funciona en iPhone, Android y navegadores modernos. Se puede instalar como **app de pantalla completa** y usar **sin conexión**.

---

## 🚀 Funcionalidades

- Selección de **barra olímpica**: 45 lb o 35 lb.  
- Agregar **discos por un solo lado** (la app duplica automáticamente al otro).  
- Cambio de unidades **libras ↔ kilos**.  
- **Resumen total**:  
  - Conteo de discos por pares  
  - Total por lado  
  - Total general en lb y kg  
- Cálculo por **% del RM (1 Rep Max)**:  
  - Campo para RM  
  - Porcentaje manual o con **preajustes (50–95%)**  
  - Opción de redondeo **hacia abajo, hacia arriba o al plato más cercano**  
  - Desglose exacto de discos por lado  
- **Exportación de resultados** a **CSV** y **PDF**.  
- **PWA lista**: instalación en iPhone/Android, soporte **offline** con Service Worker.  

---

## 📱 Instalación en tu Teléfono

### iPhone / iPad (iOS 16+)
1. Abre la app en **Safari**:  
   👉 [https://TU-USUARIO.github.io/olympic-weight-pwa](https://TU-USUARIO.github.io/olympic-weight-pwa)  
2. Pulsa **Compartir → Añadir a pantalla de inicio**.  
3. La app aparecerá como ícono en tu Home Screen.  

### Android
1. Abre la app en **Chrome/Edge**:  
   👉 [https://TU-USUARIO.github.io/olympic-weight-pwa](https://TU-USUARIO.github.io/olympic-weight-pwa)  
2. Toca los **⋮** (menú) → **Instalar app**.  
3. La app se añadirá a tu launcher.  

> Una vez instalada, funciona **offline**.

---

## 🛠️ Cómo desplegar (GitHub Pages)

1. Descarga o clona el proyecto.  
2. Sube los archivos (`index.html`, `manifest.webmanifest`, `sw.js`, carpeta `icons/`) a tu repositorio.  
3. En GitHub:  
   - Ve a **Settings → Pages**  
   - Source: `main` → carpeta `/ (root)`  
4. Tu app estará disponible en:  
   `https://TU-USUARIO.github.io/olympic-weight-pwa/`

---

## 📂 Estructura del proyecto

olympic-weight-pwa/
├── index.html # Aplicación principal
├── manifest.webmanifest # Configuración de la PWA
├── sw.js # Service Worker (offline cache)
├── icons/
│ ├── icon-192.png
│ ├── icon-512.png
│ └── apple-touch-icon.png
└── README.md


---

## 📋 To-Do / Ideas futuras
- Inventario de discos (límite de pares disponibles).  
- Guardar configuraciones del usuario en localStorage.  
- Modo **competencia** (solo mostrar pesos a cargar).  
- Multilenguaje (Español / Inglés).  

---

## 📜 Licencia
Este proyecto es de uso libre bajo la licencia **MIT**.  
Si lo usas, ¡no olvides dejarme una ⭐ en GitHub!
