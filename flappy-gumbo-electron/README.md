# Flappy Gumbo – Desktop-App bauen

## Voraussetzungen
- **Node.js** (https://nodejs.org) – Version 18 oder neuer
- **Windows** (für die .exe) oder macOS/Linux für andere Plattformen

## Schritte

### 1. Abhängigkeiten installieren
```
npm install
```

### 2. Optional: Testen (ohne zu bauen)
```
npm start
```

### 3. Windows-Installer bauen
```
npm run dist
```

Der fertige Installer landet in: `dist/Flappy Gumbo Setup 1.0.0.exe`

---

## Icon anpassen (optional)
- Lege eine `app/icon.ico`-Datei (256×256 px) ab, damit die App ein eigenes Icon bekommt.
- Falls keine `icon.ico` vorhanden ist, verwendet Electron das Standard-Icon.

## Projektstruktur
```
flappy-gumbo-electron/
├── main.js          ← Electron Hauptprozess
├── package.json     ← Build-Konfiguration
└── app/
    ├── index.html   ← Das Spiel
    └── assets/
        ├── index-B2YXOzq8.js
        ├── badge.js
        └── index-BDXTVpS5.css
```
