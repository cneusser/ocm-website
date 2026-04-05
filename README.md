# Dr. Christian Neusser, DBA – Organisation & Change Management

Persönliche Akademiker-Website für die FH-Professur an der Fachhochschule Kärnten.

**Live-URL nach Deployment:** `https://DEIN-GITHUB-BENUTZERNAME.github.io/REPO-NAME/`

---

## Dateien in diesem Repository

| Datei | Zweck |
|-------|-------|
| `index.html` | Die gesamte Website (eine einzige Datei, kein Build-Schritt nötig) |
| `.nojekyll` | Verhindert, dass GitHub Jekyll-Verarbeitung ausführt |
| `README.md` | Diese Datei |

---

## Deployment auf GitHub Pages – Schritt für Schritt

### 1. Repository erstellen

1. Gehe zu [github.com](https://github.com) und melde dich an (oder registriere dich)
2. Klicke oben rechts auf **+** → **New repository**
3. Wähle einen Repository-Namen, z. B. `ocm-website` oder `christian-neusser`
4. Stelle auf **Public** (GitHub Pages funktioniert nur bei öffentlichen Repos im Free-Plan)
5. Klicke **Create repository**

### 2. Dateien hochladen

**Option A – Direkt im Browser (einfachste Methode):**
1. Im neu erstellten Repository auf **Add file** → **Upload files** klicken
2. Alle drei Dateien hochladen: `index.html`, `.nojekyll`, `README.md`
3. Unten auf **Commit changes** klicken

**Option B – Per Git (für Entwickler):**
```bash
git init
git add index.html .nojekyll README.md
git commit -m "Initial website deployment"
git branch -M main
git remote add origin https://github.com/DEIN-BENUTZERNAME/REPO-NAME.git
git push -u origin main
```

### 3. GitHub Pages aktivieren

1. Im Repository auf **Settings** (Zahnrad oben) klicken
2. Im linken Menü auf **Pages** klicken
3. Unter **Branch** → `main` auswählen, Ordner `/ (root)` belassen
4. Auf **Save** klicken
5. Nach ca. 1–2 Minuten ist die Seite live unter:
   `https://DEIN-BENUTZERNAME.github.io/REPO-NAME/`

---

## Inhalt der Website

- **Profil** – Drei Identitäten: Transformationsforscher · Organisationsgestalter · Hochschuldozent
- **Lehrbegleitung** – Modul Change Management & Konfliktmanagement (5 Themenblöcke mit Akkordeon)
- **Wissensportal** – 5 Theorie-Deep-Dives mit Quellen (Strukturelle Trägheit, Ambidexterität, Dynamic Capabilities, Org. Routinen, HRO)
- **Drei-Säulen-Modell** – Eigenes Forschungsmodell (MSTM) + Paradigmenwechsel CM
- **Forschungsprojekte** – 4 laufende/geplante Projekte mit Methode und Förderhinweisen
- **Publikationen** – Vollständige Publikationsliste
- **Kontakt** – Kontaktdaten, ORCID, Google Scholar

---

## Anpassungen

Die gesamte Website besteht aus einer einzigen `index.html`-Datei. Zum Bearbeiten:
- Öffne `index.html` in einem Texteditor (z. B. VS Code, Notepad++)
- Farben, Texte, Links können direkt angepasst werden
- Nach Änderungen: Datei erneut auf GitHub hochladen (Upload files → bestehende Datei ersetzen)

---

© Dr. Christian Neusser, DBA · Organisation & Change Management · Fachhochschule Kärnten
