<div align="center">

  <h1>🔮 Vengeance Utilities • Spatial HUD & Dev Hub</h1>
  <p><strong>Interactive 3D glassmorphism music HUD, synced lyrics engine, live telemetry & developer portfolio.</strong></p>

  <p>
    <a href="https://vengeanceutilities.de">
      <img src="https://img.shields.io/badge/Live_Site-vengeanceutilities.de-a855f7?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Live Site">
    </a>
    <img src="https://img.shields.io/badge/UI-3D_Spatial_Glass-ec4899?style=for-the-badge" alt="3D Spatial Glass">
    <img src="https://img.shields.io/badge/Stack-HTML5%20%7C%20CSS3%20%7C%20ES6+-3b82f6?style=for-the-badge" alt="Tech Stack">
    <img src="https://img.shields.io/badge/Database-Supabase_REST-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase">
  </p>

  <p>
    <img src="https://img.shields.io/badge/Lyrics-LRCLIB_Synced-22c55e?style=flat-square" alt="LRCLIB">
    <img src="https://img.shields.io/badge/Presence-Lanyard_API-5865F2?style=flat-square&logo=discord&logoColor=white" alt="Discord Presence">
    <img src="https://img.shields.io/badge/Server-Fabric_Modded-f59e0b?style=flat-square" alt="Minecraft Fabric">
    <img src="https://img.shields.io/badge/App-Vengeance_Player_5.1-a855f7?style=flat-square&logo=android&logoColor=white" alt="Vengeance Player">
  </p>

</div>

---

### ✨ Overview

**Vengeance Utilities** kombiniert ein schwebendes 3D-Glassmorphism-Musik-HUD mit Live-System-Telemetrie, App-Releases und einem direkt gekoppelten Supabase-Control-Center — inspiriert von modernen Spatial-Desktop-Skins.

- **🧊 Spatial 3D Floating HUD:** Schwerelos schwebende Glass-Panels (`Continue Playing`, `Album Card`, `Control Dock`) mit interaktivem Maus-Tilt, iOS-Lockscreen-Uhr und dynamischem **Screen-Edge Ambient Glow** passend zur Song-Palette.
- **🔍 7-Platform Universal Search:** Direkte Live-Suche über *YouTube Music, Spotify, Spotify Web Player, Apple Music, SoundCloud, Amazon Music* und *Automatic* — inklusive Support für unveröffentlichte Tracks & Leaks.
- **🎤 Kinetic Synced Lyrics (LRCLIB):** Echtzeit-synchronisierte Lyrics mit Glow-Fokus, Click-to-Seek, verschiedenen Layout-Modi (*Left Flow*, *Centered Glow*, *Focus Line*) und **Other Lyrics**-Versionsauswahl.
- **🎬 Smart Video / Cover Backdrop:** Vollbild-Musikvideo im Hintergrund mit automatischer Erkennung gesperrter Embeds — wechselt bei Bedarf nahtlos in den geblurrten **Cover Mode**.
- **📡 Live Ecosystem Telemetry:**
  - **Discord Presence:** Echtzeit-Status & Spotify-Activity über die Lanyard REST API.
  - **Minecraft Fabric Server:** Live-Ping, Spieleranzahl und One-Click-IP-Copy (`vengeanceutilities.de`).
  - **Vengeance Apps Hub:** Direkte GitHub-Release-Anbindung inkl. Download-Counter für die **Vengeance Player 5.1 APK**.
- **🎛️ Vengeance OS Control Center (`dashboard.html`):** Echtzeit-Verwaltung für Profil, Akzentfarben, Fonts, CRT-Scanlines, Drag-&-Drop-Playlist-Sortierung, YouTube-Auto-Fill und JSON-Backups.

---

### 🛠️ Tech Stack & APIs

| Bereich | Technologien & Schnittstellen |
| :--- | :--- |
| **Frontend** | Vanilla HTML5, Modern CSS3 (`backdrop-filter`, 3D CSS Transforms, Keyframe Floating), ES6+ JavaScript |
| **Backend & BaaS** | [Supabase](https://supabase.com/) (PostgreSQL & Direct REST API) |
| **Audio & Video** | Hybrid YouTube Embed + `postMessage` Engine mit Browser-resilienter Hybrid-Timeline |
| **Search & Lyrics** | [LRCLIB API](https://lrclib.net/) (Synced & Plain LRC) & iTunes JSONP Search API |
| **Live Telemetry** | [Lanyard API](https://github.com/Phineas/lanyard) (Discord), [McStatus.io v2](https://mcstatus.io/) (Minecraft), GitHub Releases API |
| **Icons & Fonts** | FontAwesome 6.5, Google Fonts (`Outfit`, `Inter`, `Fira Code`, `Roboto Mono`) |

---

### 📂 Repository Structure

```text
├── index.html          # Öffentliches Spatial 3D Music HUD & Developer Showcase
├── dashboard.html      # Vengeance OS Control Center (Supabase Live-Editor & Backup)
├── schema.sql          # Supabase Tabellenstruktur & Open-Access Policies
└── README.md           # Projektdokumentation
```

---

### ⌨️ Hotkeys & Shortcuts

| Taste / Shortcut | Kontext | Aktion |
| :--- | :--- | :--- |
| `Space` | HUD (`index.html`) | Play / Pause |
| `→` / `←` | HUD (`index.html`) | Nächster / Vorheriger Track |
| `H` | HUD (`index.html`) | **Zen Mode** umschalten (UI aus-/einblenden) |
| `Esc` | HUD (`index.html`) | Aktive Modals, Such-Overlay & Popover schließen |
| `Strg + S` | Dashboard (`dashboard.html`) | Aktiven Einstellungs-Tab sofort in Supabase speichern |

---

### 💻 Developer Rig Specs

| Komponente | Spezifikation |
| :--- | :--- |
| **OS** | Windows 11 Pro (AtlasOS) |
| **CPU** | AMD Ryzen 7 5800X |
| **GPU** | AMD Radeon RX 6750 XT |
| **RAM** | 32 GB DDR4 @ 3600 MHz |
| **Mainboard** | ASUS ROG Strix B550-A Gaming |

---

<div align="center">
  <sub>Built with 💜 by <strong>UpperEchelon</strong> • <a href="https://vengeanceutilities.de">vengeanceutilities.de</a></sub>
</div>