# 🐷 Porqueriza App

Aplicación web completa para gestionar una porqueriza/granja porcina desde iPhone, iPad o cualquier dispositivo con navegador.

## ✨ Características

- **📊 Dashboard** - KPIs en tiempo real: cerdas activas, barracos, gestantes, lechones destetados
- **🐷 Registro de Animales** - Control completo de cerdas y barracos (arete, raza, peso, estado)
- **🐣 Control Reproductivo** - Seguimiento de servicios, gestaciones, partos y destetes
- **💰 Gestión Financiera** - Registro de gastos y ventas, cálculo de rentabilidad
- **📈 Análisis y Gráficos** - Visualización de ingresos, gastos, producción mensual
- **💾 Copias de Seguridad** - Exporta/importa tus datos en JSON
- **📊 Exportar a Excel** - Todos tus registros en hojas de cálculo
- **🔔 Alertas Automáticas** - Recordatorios de próximos partos y destetes

## 🚀 Cómo usar (Acceso rápido)

### En tu iPhone/iPad:
```
https://[TU_USUARIO].github.io/porqueriza-app
```

Luego:
1. Abre Safari en iPhone
2. Ve a la URL arriba
3. Toca el botón **Compartir** (↗️)
4. Selecciona **"Agregar a pantalla de inicio"**
5. ¡Listo! Ya tienes la app en tu pantalla

### En Desktop:
```
https://[TU_USUARIO].github.io/porqueriza-app
```

## 📋 Requisitos

- Navegador web moderno (Safari, Chrome, Firefox, Edge)
- Conexión internet (solo la primera vez)
- Después funciona **sin internet**

## 💾 Datos

Todos los datos se guardan **localmente** en tu dispositivo. No se suben a ningún servidor.

### Hacer copia de seguridad:
1. Ve a **⚙️ Más**
2. Toca **⬇️ Crear copia de seguridad**
3. El archivo se descarga automáticamente

### Restaurar desde copia:
1. Ve a **⚙️ Más**
2. Toca **⬆️ Restaurar copia de seguridad**
3. Selecciona tu archivo .json

## 📊 Exportar datos

- **Excel (.xlsx)** - Todos tus registros en hojas de cálculo
- **PDF** - Imprime los reportes (imprime a PDF en tu iPhone)

## 🔧 Desarrollo

### Estructura:
```
porqueriza-app/
├── index.html       # App completa (todo en un archivo)
├── README.md        # Este archivo
└── .gitignore       # Archivos ignorados
```

### Tecnologías:
- React 18 (desde CDN)
- Recharts (gráficos)
- XLSX (exportar Excel)
- Storage API (almacenamiento local)

### Para modificar la app:
1. Edita `index.html` directamente
2. Haz commit: `git add . && git commit -m "descripción"`
3. Push: `git push`
4. Los cambios aparecen automáticamente en tu URL (después de 1-2 minutos)

## 🎨 Personalización

En el archivo `index.html`, busca esta sección para cambiar colores:

```javascript
const DEFAULT_SET = { farmName:"Mi Porqueriza", owner:"", currency:"₡" };
```

Cambiar:
- `farmName` - Nombre de tu granja
- `owner` - Tu nombre
- `currency` - Moneda (₡ = CRC, $ = USD, Q = GTQ, L = HNL)

## 📱 Instalar en múltiples dispositivos

Si tienes iPhone, iPad, etc:

1. En cada dispositivo, abre Safari
2. Ve a: `https://[TU_USUARIO].github.io/porqueriza-app`
3. Toca **Compartir** → **Agregar a pantalla de inicio**

**Los datos se sincronizan automáticamente** si creas copias de seguridad regulares y las restauras en cada dispositivo.

## 🐛 Problemas comunes

**P: La app no abre en Safari**
R: Asegúrate que el repositorio sea **público**. Espera 2-3 minutos después de hacer push.

**P: Los datos se perdieron**
R: Los datos se guardan en almacenamiento local del navegador. Si limpias el caché, se pierden. Usa copias de seguridad.

**P: No me carga en iPhone**
R: Asegúrate que sea HTTPS (debe decir `https://` no `http://`)

## 📝 Licencia

Libre para usar y modificar.

## 👨‍💻 Autor

Creado con ❤️ para granjas porcinas en Costa Rica.

---

**¿Necesitas ayuda?** Revisa los datos guardados en **⚙️ Configuración**.
