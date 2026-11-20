# xTTier — eXtended Technical Training for Infrastructure, Engineering & Reliability

[![Latest Release](https://img.shields.io/github/v/release/netssv/xttier-releases?style=flat-square&color=7c6bb0&label=Release)](https://github.com/netssv/xttier-releases/releases/latest)
[![Tracks](https://img.shields.io/badge/Tracks-Tier%201%20%7C%20Tier%202%20%7C%20Tier%203%20%7C%20SysAdmin%20%7C%20DevOps-7c6bb0?style=flat-square)](https://xttier.rop-martel.workers.dev)
[![Stack](https://img.shields.io/badge/Stack-Linux%20CLI%20%7C%20Apache%20%7C%20PHP--FPM%20%7C%20MariaDB%20%7C%20DNS%20%7C%20Exim-5fa882?style=flat-square)](https://xttier.rop-martel.workers.dev)
[![Simulation](https://img.shields.io/badge/Simulation-40%2B%20Real--World%20Incidents-181622?style=flat-square)](https://xttier.rop-martel.workers.dev)
[![Platforms](https://img.shields.io/badge/Platforms-Android%20%7C%20iOS%20%7C%20Web%20PWA-5fa882?style=flat-square)](https://xttier.rop-martel.workers.dev)
[![Offline](https://img.shields.io/badge/PWA-100%25%20Offline%20Capable-524973?style=flat-square)](https://xttier.rop-martel.workers.dev)

> **xTTier** (*eXtended Technical Training for Infrastructure, Engineering & Reliability* / *eXtended Troubleshooting & Triage for Incident Escalation & Resolution*) es la plataforma interactiva multiplataforma de simulación técnica y entrenamiento en terminal (CLI). 
> 
> Diseñada para capacitar, auditar y acelerar habilidades reales sin poner en riesgo entornos de producción: desde soporte frontline y DNS (Tier 1), diagnóstico y administración en servidores (Tier 2 y Tier 3), hasta ingeniería Linux de sistemas (SysAdmin) y operaciones modernas en la nube (DevOps / SRE).

---

## 🎯 Especialidades y Rutas de Formación

```
┌───────────────────────────────────────────────────────────────────────────┐
│                          RUTAS DE ENTRENAMIENTO                           │
├──────────────┬──────────────┬──────────────┬──────────────┬───────────────┤
│    TIER 1    │    TIER 2    │    TIER 3    │   SYSADMIN   │    DEVOPS     │
│   Frontline  │ Server Admin │ Deep Triage  │  Linux Core  │  Cloud & SRE  │
├──────────────┼──────────────┼──────────────┼──────────────┼───────────────┤
│ • DNS & MX   │ • SSH & nano │ • Kernel log │ • cPanel/WHM │ • CI/CD & Git │
│ • HTTP 4xx   │ • Apache/Nginx│ • MySQL dump │ • iptables   │ • 12-Factor   │
│ • Mail ports │ • PHP-FPM    │ • Memory OOM │ • Exim MTA   │ • Docker/Sync │
│ • WHOIS check│ • .htaccess  │ • Disk inode │ • SSL / TLS  │ • Reliability │
└──────────────┴──────────────┴──────────────┴──────────────┴───────────────┘
```

---

## 📲 Descarga Directa de Instaladores Nativos

| Plataforma | Binario | Método de Instalación | Enlace Directo |
| :--- | :--- | :--- | :--- |
| **Android** | `xTTier.apk` | Sideload (Habilitar fuentes desconocidas) | [⬇️ **Descargar APK**](https://github.com/netssv/xttier-releases/releases/latest/download/xTTier.apk) |
| **iOS / iPad** | `xTTier.ipa` | TrollStore (Permanente) / Sideloadly USB | [⬇️ **Descargar IPA**](https://github.com/netssv/xttier-releases/releases/latest/download/xTTier.ipa) |
| **Web PWA** | Web App | Safari > *Compartir > Agregar a pantalla de inicio* | [🌐 **Abrir Web App**](https://xttier.rop-martel.workers.dev) |

---

## 🛠️ Guía Rápida de Instalación

### 1. Android (Teléfonos y Tablets)
1. Descarga [xTTier.apk](https://github.com/netssv/xttier-releases/releases/latest/download/xTTier.apk).
2. Toca el archivo descargado para iniciar la instalación.
3. Si el sistema lo pide, autoriza la instalación de aplicaciones desde el navegador.
4. Presiona **Instalar**. Funciona 100% offline con base de datos local y sincronización en la nube opcional.

### 2. Apple iPad & iPhone (iOS)

#### A. Con TrollStore (Recomendado — Permanente y Sin Revokes)
*Compatible con iOS 14.0 hasta 17.0:*
1. Descarga [xTTier.ipa](https://github.com/netssv/xttier-releases/releases/latest/download/xTTier.ipa) en Safari.
2. Abre la app **Archivos (Files)**.
3. Mantén presionado `xTTier.ipa` > **Compartir** > Selecciona **TrollStore**.
4. Pulsa **Install**. No caduca a los 7 días ni requiere cuenta de Apple Developer.

#### B. Con Sideloadly / AltStore (Cualquier versión de iOS)
1. Conecta tu dispositivo por cable USB a la computadora.
2. Arrastra `xTTier.ipa` dentro de **Sideloadly**, ingresa tu Apple ID gratuito y presiona **Start**.
3. En el dispositivo, ve a **Ajustes > General > Gestión de dispositivos y VPN** y autoriza tu perfil.

#### C. Standalone PWA en iPad (Sin descargas de archivos)
1. Abre [https://xttier.rop-martel.workers.dev](https://xttier.rop-martel.workers.dev) en Safari en tu iPad.
2. Toca el icono de **Compartir** y pulsa **Agregar a pantalla de inicio**.
3. Queda instalada a pantalla completa con navegación táctil fluida y almacenamiento offline.

---

## 🔒 Privacidad del Código Fuente
Este repositorio público distribuye exclusivamente los artefactos compilados mediante CI/CD automatizado en **GitHub Actions**. El código fuente completo, banco de reactivos pedagógicos, migraciones SQL y lógica del tutor socrático residen de forma segura en el repositorio privado central.
