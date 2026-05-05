# 💚 VITA-IMC — Tu Salud Inteligente

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/es/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/es/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/es/docs/Web/JavaScript)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=for-the-badge&logo=github&logoColor=white)](https://pages.github.com/)
[![GDPR Compliant](https://img.shields.io/badge/GDPR-Compliant-00C853?style=for-the-badge&logo=shield&logoColor=white)](https://gdpr.eu/)
[![No Backend](https://img.shields.io/badge/Backend-None%20Required-5856D6?style=for-the-badge&logo=serverless&logoColor=white)]()
[![License](https://img.shields.io/badge/License-MIT-AF52DE?style=for-the-badge)](LICENSE)
[![Version](https://img.shields.io/badge/Version-1.0.0-007AFF?style=for-the-badge)]()

> **VITA-IMC** es una aplicación web progresiva de salud personal que permite calcular el Índice de Masa Corporal (IMC), realizar seguimiento de metas, programar sesiones y ganar logros — todo sin backend, sin servidores y con privacidad total. Los datos se almacenan exclusivamente en el dispositivo del usuario.

---

## 📋 Tabla de Contenidos

- [✨ Características](#-características)
- [🎨 Diseño y UI](#-diseño-y-ui)
- [🏗️ Arquitectura](#️-arquitectura)
- [📁 Estructura del Proyecto](#-estructura-del-proyecto)
- [🚀 Instalación y Despliegue](#-instalación-y-despliegue)
- [📱 Secciones de la App](#-secciones-de-la-app)
- [🏆 Sistema de Logros](#-sistema-de-logros)
- [⭐ Sistema de Puntos](#-sistema-de-puntos)
- [🔒 Privacidad y Seguridad](#-privacidad-y-seguridad)
- [⚖️ Cumplimiento Legal](#️-cumplimiento-legal)
- [🧩 Tecnologías](#-tecnologías)
- [🌐 Compatibilidad](#-compatibilidad)
- [🗺️ Roadmap](#️-roadmap)
- [🤝 Contribuciones](#-contribuciones)
- [📄 Licencia](#-licencia)

---

## ✨ Características

| Característica | Descripción |
|---|---|
| 📏 **Cálculo de IMC** | Cálculo automático con clasificación según estándares OMS |
| 🎯 **Metas personalizadas** | Define tu peso objetivo y fecha límite con seguimiento visual |
| 📅 **Agenda de sesiones** | Programa sesiones de seguimiento con nombre, fecha y notas |
| 📊 **Historial completo** | Registro de cada medición con estado de ánimo, variación y puntos |
| 🏆 **Sistema de logros** | 9 logros desbloqueables con puntos acumulativos |
| ⭐ **Gamificación** | Sistema de puntos, niveles y recompensas por constancia |
| 😊 **Avatares personalizables** | 12 avatares de emoji para personalizar el perfil |
| ⚙️ **Editor de perfil** | Edita todos tus datos, avatar y meta en cualquier momento |
| 🔄 **Reinicio seguro** | Opciones de borrado parcial o total con confirmación doble |
| 🔒 **Privacidad total** | Sin backend, sin tracking, sin cookies de terceros |
| 📱 **Responsive** | Optimizado para móvil, tablet y escritorio |
| 🌙 **Tema oscuro** | Diseño oscuro premium con orbes de luz ambiental |

---

## 🎨 Diseño y UI

VITA-IMC sigue el lenguaje de diseño del ecosistema **Apple** — oscuro, vibrante y con profundidad visual real.

### Paleta de colores del sistema

| Token | Color | Hex | Uso |
|---|---|---|---|
| `--v-blue` | 🔵 Azul sistema | `#007AFF` | Acciones primarias, IMC card |
| `--v-indigo` | 🟣 Índigo | `#5856D6` | Gradientes, énfasis |
| `--v-purple` | 💜 Púrpura | `#AF52DE` | Gradientes hero, acentos |
| `--v-green` | 🟢 Verde | `#34C759` | Éxito, sesiones completadas, IMC normal |
| `--v-yellow` | 🟡 Amarillo | `#FFCC00` | Puntos, logros, sesiones pendientes |
| `--v-orange` | 🟠 Naranja | `#FF9500` | Próxima sesión, advertencias leves |
| `--v-red` | 🔴 Rojo | `#FF3B30` | Errores de validación, zona de reinicio |
| `--v-pink` | 🩷 Rosa | `#FF2D55` | Gradiente destructivo |
| `--v-teal` | 🩵 Teal | `#5AC8FA` | IMC bajo peso |
| `--surface` | ⬛ Superficie | `#1C1C1E` | Cards principales |
| `--surface2` | ⬛ Superficie 2 | `#2C2C2E` | Inputs, filas secundarias |

### Efectos visuales

- **Glassmorphism** — `backdrop-filter: blur(40px) saturate(180%)` en header y nav
- **Ambient orbs** — 3 orbes de luz difusa animados en el fondo (azul, púrpura, rosa)
- **Gradiente hero** — `linear-gradient(135deg, #007AFF → #5856D6 → #AF52DE)` en elementos clave
- **Shimmer dorado** — animación de brillo en la tarjeta de puntos/logros
- **Sombras de color** — box-shadow con color temático en botones y cards principales

### Tipografía

| Familia | Uso | Pesos |
|---|---|---|
| `Plus Jakarta Sans` | Cuerpo, labels, botones | 300, 400, 600, 700, 800 |
| `-apple-system` | Fallback nativo iOS/macOS | Sistema |

### Iconografía

Todos los íconos son **emoji nativos** del sistema operativo — sin dependencias externas, cero requests adicionales y compatibilidad universal.

| Emoji | Contexto |
|---|---|
| 💚 | Logo / ícono de la app |
| 🏠 | Navegación — Inicio |
| 📏 | Navegación — Medir |
| 📊 | Navegación — Historial |
| 📅 | Navegación — Sesiones |
| 🏆 | Navegación — Logros |
| ⚙️ | Navegación — Perfil |
| ⭐ | Puntos acumulados |
| 🎯 | Meta de peso |
| 🔥 | Racha de mediciones |
| 🌱 🚶 💪 🏃 🏆 | Niveles de usuario |

---

## 🏗️ Arquitectura

```
VITA-IMC
│
├── Single HTML File (SPA)
│   ├── <head>         → Meta, fonts (Google Fonts CDN), title
│   ├── <style>        → CSS con variables, glassmorphism, animaciones
│   ├── <body>
│   │   ├── .ambient   → Orbes de fondo animados
│   │   ├── .cookie-bar → Banner RGPD
│   │   ├── <header>   → Logo + puntos + avatar (sticky top)
│   │   ├── <nav>      → Bottom navigation (sticky bottom)
│   │   ├── <main>     → Páginas (setup, dashboard, medir, historial, sesiones, logros, perfil)
│   │   ├── #sessModal → Sheet modal para nueva sesión
│   │   └── #confirmModal → Sheet modal de confirmación de reinicio
│   └── <script>       → Lógica de app (vanilla JS, sin frameworks)
│
└── localStorage
    ├── vi2_p  → Perfil del usuario (JSON)
    ├── vi2_m  → Array de mediciones (JSON)
    ├── vi2_s  → Array de sesiones (JSON)
    └── vi2_ck → Aceptación de cookies (flag)
```

### Flujo de datos

```
Usuario abre la app
        │
        ▼
  ¿localStorage tiene vi2_p?
        │
   NO ──┤──► Pantalla de Setup → doSetup() → guarda perfil + 1ª medición
        │
   SÍ ──┤──► bootApp() → carga datos → muestra Dashboard
        │
        ▼
  Ciclo de uso:
  Medir → doMeasure() → push a measurements[] → save() → refreshAll()
  Sesión → saveSession() → push a sessions[] → save() → renderSess()
  Perfil → saveProfile() → update profile{} → save() → refreshAll()
  Reinicio → doReset() → limpia localStorage → reload()
```

---

## 📁 Estructura del Proyecto

```
vita-imc/
│
├── index.html          ← Aplicación completa (single file)
├── README.md           ← Este archivo
└── LICENSE             ← Licencia MIT
```

> La aplicación es intencionalmente **monolítica** (un solo archivo HTML). Esto permite desplegarla en GitHub Pages sin configuración de build, bundlers ni dependencias de Node.js.

---

## 🚀 Instalación y Despliegue

### Opción 1 — GitHub Pages (recomendado, gratis)

```bash
# 1. Crear repositorio en GitHub
#    Nombre sugerido: vita-imc

# 2. Subir el archivo
#    Renombrar vita-imc.html → index.html
#    Subir a la rama main

# 3. Activar GitHub Pages
#    Settings → Pages → Branch: main → / (root) → Save

# 4. Tu app estará en:
#    https://[tu-usuario].github.io/vita-imc
```

### Opción 2 — Local (sin instalación)

```bash
# Simplemente abrir el archivo en el navegador
open index.html          # macOS
start index.html         # Windows
xdg-open index.html      # Linux
```

### Opción 3 — Servidor local simple

```bash
# Con Python (viene preinstalado en macOS/Linux)
python3 -m http.server 8080

# Con Node.js
npx serve .

# Luego abrir: http://localhost:8080
```

> ⚠️ **No se requiere** Node.js, npm, build process, ni ninguna dependencia externa para ejecutar la app.

---

## 📱 Secciones de la App

### 🏠 Inicio (Dashboard)
Vista principal con resumen completo del estado de salud:
- **Tarjeta IMC** con gradiente azul-índigo-púrpura, valor actual, categoría y barra de escala
- **Stats** — total de mediciones, racha de días, puntos acumulados
- **Tarjeta de meta** — barra de progreso con % completado y días restantes
- **Próxima sesión** — muestra la siguiente sesión pendiente

### 📏 Medir
Registro de nuevas mediciones:
- Input de peso con validación en tiempo real
- Selector de estado de ánimo (8 emojis)
- Campo de nota opcional
- Resultado visual con IMC, categoría en color y mensaje personalizado
- Puntos otorgados automáticamente (+20 base, +15 bonus por progreso hacia la meta)

### 📊 Historial
Registro cronológico de todas las mediciones:
- Emoji de estado de ánimo del día
- IMC calculado + peso registrado
- Categoría con color temático según clasificación OMS
- Delta de peso respecto a la medición anterior (↑ rojo / ↓ verde)
- Puntos ganados en cada sesión
- Nota personal si fue registrada

### 📅 Sesiones
Agenda de seguimiento personal:
- Programar sesiones con nombre, fecha y nota
- Estados: `Pendiente` 🟡 / `Completada` 🟢 / `Vencida` 🔴
- Marcar sesiones como hechas desde la misma vista
- La próxima sesión se muestra también en el Dashboard

### 🏆 Logros
Sistema de gamificación:
- Tarjeta de puntos con animación shimmer dorada
- Nivel actual del usuario
- Grilla de 9 logros con estado desbloqueado/bloqueado
- Toast de notificación al desbloquear un nuevo logro

### ⚙️ Perfil
Configuración y gestión de datos:
- Tarjeta resumen del perfil (avatar, nombre, estadísticas)
- Formulario completo de edición con validaciones
- Cambio de avatar entre 12 opciones
- **Zona de reinicio** con confirmación doble:
  - 🗑 Borrar solo historial y sesiones (conserva perfil)
  - 💥 Reiniciar todo desde cero

---

## 🏆 Sistema de Logros

| ID | Ícono | Nombre | Condición | Puntos |
|---|---|---|---|---|
| `first` | 🌱 | Primer Paso | 1 medición registrada | +50 pts |
| `five` | 💎 | Consistente | 5 mediciones registradas | +120 pts |
| `ten` | 🔟 | Decena | 10 mediciones registradas | +200 pts |
| `month` | 🗓️ | Un Mes | 30 mediciones registradas | +400 pts |
| `goal10` | 🎯 | 10% Logrado | 10% del progreso hacia la meta | +150 pts |
| `goal50` | 🏅 | A Mitad | 50% del progreso hacia la meta | +300 pts |
| `goal100` | 🏆 | ¡Meta! | Meta de peso alcanzada (100%) | +1000 pts |
| `sessions3` | 🔥 | 3 Sesiones | 3 sesiones programadas | +75 pts |
| `imcdrop` | 📉 | IMC Mejor | IMC mejoró 2+ puntos | +200 pts |

---

## ⭐ Sistema de Puntos

### Cómo se ganan puntos

| Acción | Puntos base | Bonus |
|---|---|---|
| Primera medición | +50 | — |
| Cada medición siguiente | +20 | +15 si hay progreso hacia la meta |
| Sesión marcada como completada | +30 | — |
| Logro desbloqueado | Variable | Ver tabla de logros |

### Niveles

| Nivel | Puntos requeridos | Ícono |
|---|---|---|
| Principiante | 0 – 99 pts | 🌱 |
| Explorador | 100 – 299 pts | 🚶 |
| Comprometido | 300 – 599 pts | 💪 |
| Atleta | 600 – 999 pts | 🏃 |
| Campeón | 1000+ pts | 🏆 |

---

## 🔒 Privacidad y Seguridad

VITA-IMC fue diseñada con **Privacy by Design** como principio fundamental.

```
✅ Sin servidor backend
✅ Sin base de datos externa
✅ Sin cookies de rastreo de terceros
✅ Sin analytics ni telemetría
✅ Sin APIs externas que reciban datos del usuario
✅ HTTPS automático en GitHub Pages
✅ Datos almacenados únicamente en localStorage del navegador
✅ Banner de consentimiento de cookies incluido
✅ El usuario puede borrar todos sus datos en cualquier momento
```

### Datos almacenados localmente

```json
// vi2_p — Perfil
{
  "name": "string",
  "emoji": "string",
  "height": "number (cm)",
  "goalWeight": "number (kg)",
  "goalDate": "string (ISO date)",
  "startWeight": "number (kg)",
  "created": "number (timestamp)"
}

// vi2_m — Mediciones (array)
{
  "weight": "number (kg)",
  "imc": "number",
  "mood": "string (emoji)",
  "note": "string",
  "date": "string (ISO datetime)",
  "pts": "number"
}

// vi2_s — Sesiones (array)
{
  "id": "number (timestamp)",
  "name": "string",
  "date": "string (ISO date)",
  "note": "string",
  "status": "pending | done | missed"
}
```

---

## ⚖️ Cumplimiento Legal

| Regulación | Estado | Detalle |
|---|---|---|
| **RGPD** (UE) | ✅ Cumple | Sin datos personales en servidores. Consentimiento explícito. Derecho al olvido implementado. |
| **Ley 25.326** (Argentina) | ✅ Cumple | Sin tratamiento de datos personales fuera del dispositivo. |
| **LFPDPPP** (México) | ✅ Cumple | Sin transferencia de datos a terceros. |
| **LGPD** (Brasil) | ✅ Cumple | Sin base de datos externa. Datos bajo control exclusivo del usuario. |
| **CAN-SPAM** | ✅ N/A | La app no envía emails. Substack gestiona suscripciones con doble opt-in. |
| **OWASP** | ✅ Cumple | Sin inputs que ejecuten código. Sin eval(). Sin XSS posible. |
| **PCI-DSS** | ✅ N/A | Sin procesamiento de pagos en la app. |

> 📌 **Nota:** Al desplegar en GitHub Pages, el procesamiento de HTTPS y headers de seguridad es gestionado por GitHub. Se recomienda revisar la [política de privacidad de GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages#data-collection).

---

## 🧩 Tecnologías

| Tecnología | Versión | Uso |
|---|---|---|
| **HTML5** | Living Standard | Estructura semántica, localStorage API |
| **CSS3** | Living Standard | Variables, glassmorphism, animaciones, grid, flexbox |
| **Vanilla JavaScript** | ES2020+ | Lógica de app, DOM manipulation, localStorage |
| **Google Fonts** | CDN | `Plus Jakarta Sans` — tipografía principal |
| **GitHub Pages** | — | Hosting estático gratuito con HTTPS |
| **localStorage API** | Web Standard | Persistencia de datos en el dispositivo |

> **Sin frameworks. Sin dependencias npm. Sin build process.** El archivo `index.html` es el único artefacto de despliegue.

---

## 🌐 Compatibilidad

| Navegador | Soporte | Notas |
|---|---|---|
| Chrome 90+ | ✅ Completo | Recomendado |
| Firefox 88+ | ✅ Completo | |
| Safari 14+ | ✅ Completo | Prefijo `-webkit-` incluido para backdrop-filter |
| Edge 90+ | ✅ Completo | |
| Samsung Internet 14+ | ✅ Completo | |
| IE 11 | ❌ No soportado | CSS Variables y ES2020 no compatibles |

### Dispositivos probados

| Dispositivo | Resolución | Estado |
|---|---|---|
| iPhone SE | 375px | ✅ |
| iPhone 14 Pro | 393px | ✅ |
| Samsung Galaxy S21 | 360px | ✅ |
| iPad Air | 820px | ✅ |
| MacBook 13" | 1280px | ✅ |
| Desktop FHD | 1920px | ✅ |

---

## 🗺️ Roadmap

### v1.0.0 — Actual ✅
- [x] Cálculo de IMC con clasificación OMS
- [x] Perfil personalizable con avatares emoji
- [x] Historial de mediciones con estado de ánimo
- [x] Sistema de metas con progreso visual
- [x] Agenda de sesiones
- [x] 9 logros desbloqueables
- [x] Sistema de puntos y niveles
- [x] Editor de perfil completo
- [x] Zona de reinicio con confirmación
- [x] Banner de cookies RGPD
- [x] Diseño glassmorphism estilo Apple

### v1.1.0 — Próximas funciones 🔄
- [ ] Exportar historial como CSV o PDF
- [ ] Gráfico de evolución del IMC en el tiempo
- [ ] Notificaciones de sesiones (Web Notifications API)
- [ ] Modo PWA (Progressive Web App) con instalación en pantalla de inicio
- [ ] Soporte para múltiples perfiles en el mismo dispositivo
- [ ] Internacionalización (EN, PT)

### v2.0.0 — Visión futura 🔮
- [ ] Sincronización opcional en la nube (opt-in)
- [ ] Integración con Google Fit / Apple Health
- [ ] API de recomendaciones nutricionales
- [ ] Modo coach / seguimiento de terceros con código QR

---

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor sigue este proceso:

```bash
# 1. Fork del repositorio
# 2. Crea una rama para tu feature
git checkout -b feature/nombre-del-feature

# 3. Realiza tus cambios en index.html
# 4. Verifica que funciona abriendo en el navegador
# 5. Commit con mensaje descriptivo
git commit -m "feat: descripción del cambio"

# 6. Push y abre un Pull Request
git push origin feature/nombre-del-feature
```

### Convenciones de commit

| Prefijo | Uso |
|---|---|
| `feat:` | Nueva funcionalidad |
| `fix:` | Corrección de bug |
| `style:` | Cambios de diseño/CSS |
| `docs:` | Cambios en documentación |
| `refactor:` | Refactorización sin cambio de funcionalidad |

---

## 📄 Licencia

```
MIT License

Copyright (c) 2026 FlowSolutions

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
```

---

<div align="center">

**VITA-IMC** · Hecho con 💚 por [FlowSolutions](https://github.com/flowsolutions01-dev)

*Tu salud, tu datos, tu control.*

[![GitHub](https://img.shields.io/badge/GitHub-flowsolutions01--dev-222222?style=flat-square&logo=github)](https://github.com/flowsolutions01-dev)
[![AdSense](https://img.shields.io/badge/Monetizado%20con-Google%20AdSense-4285F4?style=flat-square&logo=google)](https://adsense.google.com)

</div>