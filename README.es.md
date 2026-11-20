# xTTier — eXtended Technical Training for Infrastructure, Engineering & Reliability

<p align="center">
  <b>Idiomas:</b> <a href="README.md"><b>English</b></a> | <b>Español</b>
</p>

<p align="center">
  <a href="https://github.com/netssv/xttier-releases/releases/latest"><img src="https://img.shields.io/github/v/release/netssv/xttier-releases?style=flat-square&color=7c6bb0&label=Última%20Versión" alt="Última Versión"></a>
  <a href="https://xttier.rop-martel.workers.dev"><img src="https://img.shields.io/badge/Tracks-Tier%201%20%7C%20Tier%202%20%7C%20Tier%203%20%7C%20SysAdmin%20%7C%20DevOps-7c6bb0?style=flat-square" alt="Rutas"></a>
  <a href="https://xttier.rop-martel.workers.dev"><img src="https://img.shields.io/badge/Stack-Linux%20CLI%20%7C%20Apache%20%7C%20PHP--FPM%20%7C%20MariaDB%20%7C%20DNS%20%7C%20Exim-5fa882?style=flat-square" alt="Stack"></a>
  <a href="https://xttier.rop-martel.workers.dev"><img src="https://img.shields.io/badge/Simulación-40%2B%20Casos%20Reales-181622?style=flat-square" alt="Simulación"></a>
  <a href="https://xttier.rop-martel.workers.dev"><img src="https://img.shields.io/badge/Plataformas-Android%20%7C%20iOS%20%7C%20Web%20PWA-5fa882?style=flat-square" alt="Plataformas"></a>
  <a href="https://xttier.rop-martel.workers.dev"><img src="https://img.shields.io/badge/PWA-100%25%20Offline-524973?style=flat-square" alt="Offline PWA"></a>
</p>

> **xTTier** (*eXtended Technical Training for Infrastructure, Engineering & Reliability* / *eXtended Troubleshooting & Triage for Incident Escalation & Resolution*) es la plataforma interactiva multiplataforma de simulación técnica y entrenamiento en terminal Linux (CLI).
> 
> Guiado por **`xBooty`**, el sistema capacita y entrena habilidades reales sin poner en riesgo entornos de producción a través de 5 rutas especializadas: desde soporte frontline y DNS (Tier 1), administración y diagnóstico en servidores (Tier 2 y Tier 3), hasta ingeniería Linux de sistemas (SysAdmin) y operaciones modernas en la nube (DevOps / SRE).

---

## Especialidades y Matriz de Formación

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

## Descarga Directa de Instaladores Nativos

Compilados automáticamente mediante pipelines verificados de GitHub Actions y distribuidos mediante la CDN global de GitHub:

| Plataforma | Binario | Método Recomendado de Instalación | Enlace Directo |
| :--- | :--- | :--- | :--- |
| **Android** | `xTTier.apk` | Sideload (Habilitar fuentes desconocidas) | [Descargar APK](https://github.com/netssv/xttier-releases/releases/latest/download/xTTier.apk) |
| **iOS / iPad** | `xTTier.ipa` | TrollStore (Permanente sin revokes) o Sideloadly / AltStore | [Descargar IPA](https://github.com/netssv/xttier-releases/releases/latest/download/xTTier.ipa) |
| **Web PWA** | Web App | Safari > *Compartir > Agregar a pantalla de inicio* | [Abrir Web App](https://xttier.rop-martel.workers.dev) |

---

## Guía de Instalación

### Android (Instalación Directa)
1. Descarga el instalador [`xTTier.apk`](https://github.com/netssv/xttier-releases/releases/latest/download/xTTier.apk) en tu dispositivo.
2. Abre el archivo descargado desde tu navegador o explorador de archivos.
3. Si el sistema te lo solicita, activa **Permitir desde esta fuente** en los ajustes de seguridad.
4. Pulsa **Instalar** y disfruta del laboratorio con soporte offline.

### Apple iOS y iPadOS

#### Opción A: TrollStore (Recomendado para iOS 14.0 – 17.0)
* Instalación permanente sin límite de 7 días y sin depender de una PC.
1. Descarga [`xTTier.ipa`](https://github.com/netssv/xttier-releases/releases/latest/download/xTTier.ipa) en tu dispositivo.
2. Abre el archivo dentro de TrollStore y selecciona **Install**.
3. xTTier quedará instalado de forma permanente.

#### Opción B: Sideloadly / AltStore (Cualquier versión de iOS)
1. Descarga [`xTTier.ipa`](https://github.com/netssv/xttier-releases/releases/latest/download/xTTier.ipa) en tu computadora (Windows / macOS).
2. Conecta tu iPhone o iPad por cable USB o red local.
3. Arrastra el archivo `xTTier.ipa` a Sideloadly o AltServer e introduce tu Apple ID.
4. En tu dispositivo iOS, ve a **Ajustes > General > Administración de dispositivos y VPN** y confía en el certificado.

#### Opción C: PWA Standalone (Sin computadora ni IPA)
1. Abre [xttier.rop-martel.workers.dev](https://xttier.rop-martel.workers.dev) en Safari.
2. Pulsa el botón **Compartir** (`[+]`).
3. Elige **Agregar a pantalla de inicio**.
4. La app funcionará en pantalla completa con soporte 100% offline.

---

## Actualizaciones Automáticas In-App

* **Web / PWA:** Al publicar una nueva versión, se despliega un banner flotante. Al pulsar **Actualizar**, se recarga la caché del Service Worker de inmediato.
* **App Nativa (Android / iOS):** El motor `VersionUpdater` consulta la versión en producción. Al detectar una actualización, ofrece el botón **Descargar** que abre el navegador del sistema para instalar el nuevo binario.
* **Historial de Cambios:** Pulsa el badge **`v2.1`** en la barra superior o escribe `version` / `changelog` en la consola para consultar las notas detalladas de cada versión.

---

## Verificación de Integridad y Privacidad

Para comprobar que el archivo no ha sufrido alteraciones:

```bash
# Verificar Android APK
sha256sum xTTier.apk

# Verificar iOS IPA
sha256sum xTTier.ipa
```

Compara el hash con el publicado en el [Último Release en GitHub](https://github.com/netssv/xttier-releases/releases/latest).

> **Aviso de Privacidad:** Este repositorio satélite solo aloja binarios y documentación pública. El código fuente principal, reactivos de examen y esquemas de base de datos se conservan en repositorios privados.
