# Emel's Event Solution - React Website

## Beschreibung
Professionelle Event-Planning und Dekoration Website für "Emel's Event Solution", erstellt mit React und TypeScript.

## Features
- **Responsive Design**: Optimiert für alle Geräte
- **Navigation**: Sticky Header mit Smooth Scrolling
- **Service-Showcase**: 6 professionelle Event-Services
- **Galerie**: Hochwertige Event-Bilder
- **Booking-System**: Interaktives Buchungsformular mit Validierung
- **AI-Integration**: Google Gemini AI Chat-Widget (optional)

## Projektstruktur
```
src/
├── components/
│   ├── Navigation.tsx      - Header mit Navigation
│   ├── Hero.tsx            - Hero-Sektion
│   ├── Services.tsx        - Service-Showcase
│   ├── Gallery.tsx         - Bild-Galerie
│   ├── BookingForm.tsx     - Buchungsformular
│   ├── Button.tsx          - Button-Komponente
│   ├── Footer.tsx          - Footer
│   └── ChatWidget.tsx      - AI-Chat (optional)
├── services/
│   └── geminiService.ts    - Google Gemini AI Service
├── App.tsx                 - Hauptkomponente
├── constants.ts            - Konstanten
├── types.ts                - TypeScript-Typen
├── index.tsx               - Entry Point
├── index.html              - HTML-Datei
└── metadata.json           - App-Metadaten
```

## Installation & Setup

### 1. Repository clonen
```bash
git clone https://github.com/ibrahimhtiti-alt/emels-event-solution.git
cd emels-event-solution
```

### 2. Dependencies installieren
```bash
npm install
```

### 3. Entwicklungs-Server starten
```bash
npm start
```
Die App läuft unter http://localhost:3000

### 4. Für Production bauen
```bash
npm run build
```

## GitHub Pages Deployment

Wie bereits konfiguriert, wird die App automatisch auf GitHub Pages deployed:
- **Live URL**: https://ibrahimhtiti-alt.github.io/emels-event-solution/
- **Deploy-Quelle**: main branch, / (root) Ordner

## Konfiguration

### Google Gemini API (Optional)
Wenn Sie den AI-Chat aktivieren möchten:

1. Erstellen Sie einen API Key bei [Google AI Studio](https://aistudio.google.com)
2. Setzen Sie die Umgebungsvariable:
```bash
RESP_APP_GEMINI_API_KEY=YOUR_API_KEY_HERE
```

## Technologies
- **React 18** - UI Framework
- **TypeScript** - Type Safety
- **React DOM** - Browser Rendering
- **CSS3** - Styling & Animations
- **Google Gemini AI** - Optional AI Features

## Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Package.json Scripts
```json
"start": "react-scripts start"        - Entwicklungs-Server
"build": "react-scripts build"        - Production Build
"predeploy": "npm run build"          - Pre-deployment Hook
"deploy": "gh-pages -d build"         - GitHub Pages Deploy
```

## Contact
- **Email**: info@emels-event.com
- **Phone**: +1 234 567 8900
- **Instagram**: @emels_eventsolution

## License
Proprietary © 2024 Emel's Event Solution. All rights reserved.

## Author
Gemini AI (Google AI Studio)

---

**Hinweis**: Für die vollständige React-Implementierung mit allen Komponenten, bitte folgen Sie der Anleitung unter: [GitHub Repository](https://github.com/ibrahimhtiti-alt/emels-event-solution)
