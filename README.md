# 🎭 Tanzverein Kassei - Website

Schöne, responsive Website mit 6 Farbvariationen für Feedback-Sammlung.

## 📁 Datei-Struktur

```
/
├── theme-selector.html      # Startseite - Farbauswahl
├── index.html              # Original Grün/Schwarz
├── index-blue.html         # Version Blau
├── index-orange.html       # Version Orange
├── index-purple.html       # Version Violett
├── index-red.html          # Version Rot
├── index-teal.html         # Version Türkis
├── styles.css              # Original-Styling
├── styles-blue.css         # Blau-Styling
├── styles-orange.css       # Orange-Styling
├── styles-purple.css       # Violett-Styling
├── styles-red.css          # Rot-Styling
├── styles-teal.css         # Türkis-Styling
├── script.js               # JavaScript (alle Versionen)
├── netlify.toml            # Netlify-Konfiguration
└── README.md               # Diese Datei
```

## 🚀 Deployment auf Netlify (KOSTENLOS)

### Option 1: Mit Drag & Drop (einfachste Methode)

1. **Gehe zu** https://app.netlify.com/drop
2. **Ziehe** den ganzen `/kassei` Ordner ins Fenster
3. **Warte** ~30 Sekunden
4. **Fertig!** Die Website ist live 🎉

Die URL sieht dann so aus: `https://[zufälliger-name].netlify.app`

### Option 2: Mit GitHub (für regelmäßige Updates)

1. **GitHub Account erstellen** (falls noch nicht vorhanden)
2. **Repository erstellen** mit Namen `tanzverein-kassei`
3. **Dateien hochladen** (alle .html, .css, .js, netlify.toml)
4. **Netlify verbinden**: 
   - https://app.netlify.com → "Connect a git repository"
   - GitHub auswählen
   - Repository wählen
5. **Deploy!** Netlify macht den Rest automatisch

### Option 3: Netlify CLI (für Profis)

```bash
npm install -g netlify-cli
netlify login
netlify deploy --prod
```

## 🎨 Die 6 Farbvariationen

| Version | Farben | Vibe |
|---------|--------|------|
| **Original** | Grün/Schwarz | Natürlich, erdend |
| **Blau** | Blau/Weiß | Klassisch, vertrauenswürdig |
| **Orange** | Orange/Braun | Warm, einladend |
| **Violett** | Violett/Weiß | Kreativ, künstlerisch |
| **Rot** | Rot/Schwarz | Dynamisch, dramatisch |
| **Türkis** | Türkis/Dunkelgrün | Erfrischend, beruhigend |

## ✨ Features

- ✅ Dunkelmodus (speichert Preference)
- ✅ Animierter Theme-Toggle Button
- ✅ Particles.js Background-Animation
- ✅ Dynamische Musik-Quotes
- ✅ Custom Cursor
- ✅ Responsive Design (Mobile, Tablet, Desktop)
- ✅ Smooth Transitions & Animations
- ✅ Lazy-Loading Images

## 📝 Feedback-Sammlung

**Schreib der Klientin einen Link:**

```
Hallo Daniela,

hier sind 6 verschiedene Farbschemen für deine Website:
👉 [DEIN-NETLIFY-LINK]

Schau dir alle Versionen an und sag uns, welche dir am besten gefällt!
Du kannst auch Dark Mode testen (Moon-Icon oben rechts).

Schreib uns dein Feedback! 💌
```

## 🛠 Lokale Entwicklung

```bash
# Server starten
python3 -m http.server 8000

# Browser öffnen
http://localhost:8000/theme-selector.html
```

## 📱 Responsive Breakpoints

- **Desktop**: 1200px+
- **Tablet**: 980px - 1199px
- **Mobile**: 860px - 979px
- **Kleine Mobile**: < 760px

## 🔐 Hinweise

- Keine Abhängigkeiten - pure HTML/CSS/JS
- Alle Assets von CDN (Google Fonts, Particles.js, picsum.photos)
- Funktioniert offline (nach dem ersten Load)
- Kein Build-Prozess nötig

---

**Viel Spaß mit der Website! 🎭✨**
