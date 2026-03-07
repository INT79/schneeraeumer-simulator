# 🚛 Schneeräum-Simulator Berlin Hermsdorf

> Browser-basierter 3D-Schneeräum-Simulator für die Einarbeitung von IM NORDEN Fahrern im Revier Berlin Hermsdorf.

## 🎮 Über das Projekt

Ein interaktiver Simulator im GTA5-Stil, der neue Fahrer mit dem Winterdienstrevier Berlin Hermsdorf vertraut macht. Das Fahrzeug: der T1150 Ladog — realistisch simuliert im Browser, ohne Installation.

**Ziel:** Neue Mitarbeiter können das Revier, die Routen und typische Situationen virtuell kennenlernen, bevor sie das erste Mal real ausrücken.

## 🗺️ Features (geplant)

- [ ] 3D-Karte des Reviers Berlin Hermsdorf (basierend auf OpenStreetMap)
- [ ] T1150 Ladog Fahrzeugmodell mit Räumschild & Streugerät
- [ ] Routenplanung mit Prioritätsstufen
- [ ] Wetter-Simulation (Schneefall, Glätte)
- [ ] Aufgaben-System (Räumaufträge, Salz nachfüllen)
- [ ] Score & Zeiterfassung
- [ ] Mobile-kompatibel

## 🛠️ Tech Stack

- **Frontend:** Three.js / Babylon.js (3D-Rendering)
- **Karte:** OpenStreetMap + Mapbox GL
- **Physik:** Cannon.js / Rapier
- **Build:** Vite

## 📁 Projektstruktur

```
schneeraeumer-simulator/
├── src/
│   ├── assets/          # 3D-Modelle, Texturen, Sounds
│   ├── components/      # UI-Komponenten
│   ├── game/            # Spiellogik
│   │   ├── vehicle/     # Fahrzeugsteuerung
│   │   ├── map/         # Karten-Rendering
│   │   └── weather/     # Wetter-Simulation
│   └── main.js          # Einstiegspunkt
├── public/              # Statische Assets
├── docs/                # Dokumentation, Routen-PDFs
└── tests/               # Tests
```

## 🌿 Branch-Strategie

| Branch | Zweck |
|--------|-------|
| `main` | Stabile, produktionsreife Version |
| `develop` | Aktiver Entwicklungszweig |
| `feature/*` | Neue Features (Merge → develop) |
| `fix/*` | Bugfixes (Merge → develop) |
| `release/*` | Release-Vorbereitung (Merge → main) |

## 🚀 Quickstart

```bash
# Abhängigkeiten installieren
npm install

# Entwicklungsserver starten
npm run dev

# Build für Produktion
npm run build
```

## 👷 Entwicklung

Entwickelt von **KI Agent (IM NORDEN)** im Auftrag von Tobias.

---

*IM NORDEN Winterdienst — Berlin Hermsdorf*
