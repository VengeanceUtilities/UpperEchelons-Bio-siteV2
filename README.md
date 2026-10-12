<div align="center">

  <h1>🔮 Vengeance Utilities • Bio Hub</h1>
  <p><strong>Personal interactive developer bio, music engine, and system dashboard.</strong></p>

  <p>
    <a href="https://vengeanceutilities.de"><img src="https://img.shields.io/badge/Live_Site-vengeanceutilities.de-7c3aed?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Live Site"></a>
    <img src="https://img.shields.io/badge/Stack-HTML5%20%7C%20CSS3%20%7C%20JavaScript-blue?style=for-the-badge" alt="Tech Stack">
    <img src="https://img.shields.io/badge/Database-Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase">
  </p>

</div>

---

### ⚡ Overview

Ein dynamisches, interaktives Bento-Grid-Bio-Dashboard mit Glassmorphism-UI, Live-Datenbankanbindung über Supabase und integrierter Streaming-Engine.

* **Live Dynamic Backend**: Synchronisiert Profil, Statistiken, Links, Modpack-Settings und Playlists in Echtzeit via Supabase.
* **Ambient YouTube Audio Engine**: Muted Background-Video mit vollwertigen Audio-Controls, Playlist-Drawer, Scrubbing-Timeline und reaktivem Visualizer.
* **Minecraft Status Tracking**: Live-Abfrage von Server-Ping, aktiven Spielern, Version und Modpack-Informationen.
* **Interactive CLI Terminal**: Integrierte Pseudo-Shell mit Shortcut-Support (`~` / `^`) für interaktive Befehle.
* **Cyberpunk Aesthetics**: Partikel-Canvas, animierter Custom Cursor mit Physik-Trail, Spotlight-Card-Hover und optionale CRT-Scanlines.

---

### 🛠️ Tech Stack

* **Frontend:** Vanilla HTML5, Modern CSS3 (CSS Variables, Backdrop-Filter, Animations), JavaScript (ES6+)
* **Database & BaaS:** [Supabase](https://supabase.com/) (PostgreSQL & REST API)
* **APIs & Services:** YouTube IFrame Player API, McStatus API, Discord Widget API
* **Icons & Fonts:** FontAwesome 6, Google Fonts (Inter, Roboto Mono, Fira Code, Outfit)

---

### 📂 Repository Structure

```text
├── index.html          # Öffentliche Bento-Grid Bio-Seite
├── dashboard.html      # Administratives Dashboard für DB-Settings
└── README.md           # Projektdokumentation
⌨️ Hotkeys & Shortcuts
Taste    Aktion
Space    Play / Pause Audio
→ / ←    Nächster / Vorheriger Track
↑ / ↓    Lautstärke regeln (+/- 5%)
S        Zufallswiedergabe (Shuffle)
R        Track wiederholen (Loop)
M        Mute / Unmute
~        Interaktives Terminal öffnen
💻 Developer Specs
OS: Windows 11 Pro (AtlasOS)
CPU: AMD Ryzen 7 5800X
GPU: AMD Radeon RX 6750 XT
RAM: 32 GB DDR4 3600 MHz
Board: ASUS ROG Strix B550-A Gaming
