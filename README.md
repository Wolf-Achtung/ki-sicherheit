# ki-sicherheit.jetzt

**TÜV-zertifizierte KI-Beratung & EU AI Act-Check für den Mittelstand**

---

## Über das Projekt

**ki-sicherheit.jetzt** bietet Unternehmen eine zertifizierte, rechtssichere und praxisnahe Unterstützung bei der Einführung und Nutzung von Künstlicher Intelligenz (KI) – mit Fokus auf EU AI Act, DSGVO, Risiko-Checks, Fördermittel und TÜV-Auditierbarkeit.

Die Website richtet sich an mittelständische Unternehmen und Entscheider:innen, die:
- **KI sicher & compliant einsetzen**
- Risiken und Fördermöglichkeiten schnell bewerten
- Beratung & Nachweis für KI-Förderung suchen

---

## Features & Highlights

- **KI-Schnell-Check** (Risiko-Check, anonymer Browser-Quiz)
- **Beratungsleistungen:** Strategie, Auditvorbereitung, Nachweis & Förderfähigkeit
- **Fördermittel-Formular:** Einfaches Prüf-Formular, Netlify-Integration
- **Recht & Datenschutz:** Transparente Infos zu DSGVO & EU AI Act
- **Floating Legal Icon:** Modernes „@“-Symbol rechts unten, öffnet das Datenschutz-Modal
- **Moderne Animationen:** Alle Hauptbilder mit Eye-Candy-Effekten (Pulse, Light Sweep, Micro-Move, Farbshift)
- **Responsive, mobil-optimiertes Design**
- **Kein Tracking, keine Cookies**

---

## Technischer Aufbau

- **HTML5 & CSS3 (styles.css)**
- **Vanilla JavaScript** für Animationen, Quiz, Modals
- **Bilder:** WebP-Format (optimiert für Performance)
- **Schriften:** Share Tech Mono, Inter (Google Fonts)
- **Formulare:** Netlify-Form für Fördermittel-Anfrage
- **Animationen:** Intersection Observer & CSS Keyframes

---

## Effekt-Zuordnung (Stand Juli 2025)

| Section                 | Bild              | Effekt          |
|-------------------------|-------------------|-----------------|
| Header                  | 01.webp           | Micro-Move      |
| Schnell-Check           | 04.webp           | Light Sweep     |
| Leistung & Nachweis     | 07.webp           | Pulse           |
| Förderung               | 09.webp           | Pulse           |
| Rechtliches/Transparenz | 08.webp           | Micro-Move      |
| (andere Motive möglich) | z.B. 06.webp      | Farbshift       |

**Weitere Effekte stehen als Klasse bereit:**
- img-pulse, img-light-sweep, img-micro-move, img-glow, img-farbshift

Effekte werden **nur bei Sichtbarkeit** im Viewport aktiviert.

---

## Wichtige Dateien

- `index.html` – Hauptseite, enthält alle Sections, Modals und das Floating-Icon.
- `styles.css` – Alle Layouts, Animationen und responsiven Styles.
- `/img/*.webp` – Alle verwendeten Bilder (WebP).
- `datenschutz.html` – Separate Datenschutzerklärung (wird im Modal geladen).

---

## Floating-Icon (Legal/Datenschutz-Button)

- Das **@-Symbol** rechts unten (`.legal-fab`) öffnet das Datenschutz-Modal.
- Kann einfach auf §, Schild, Waage etc. geändert werden.

---

## Formulare

- **Fördermittel-Formular:** Netlify-basiert, DSGVO-konform, Erfolgsmeldung als Popup.
- **Kontaktformular:** Im Modal, Demo-Logik (Absenden ohne Backend).

---

## Entwicklung & Anpassung

- **Effekte pro Bild**: Über das Attribut `data-img-effect` im `<img>`-Tag steuerbar.
- **Weitere Effekte** können in `styles.css` als neue Keyframes hinzugefügt werden.
- **Quiz-Logik** im Bereich „Schnell-Check“ kann über JavaScript angepasst werden.
- **Modals** lassen sich einfach über JS öffnen/schließen.

---

## Deployment

- Die Seite ist **statisch** und kann auf Netlify, Vercel oder jedem klassischen Hoster deployed werden.
- Die Formulare sind auf **Netlify** eingestellt (können aber bei Bedarf angepasst werden).
- **Keine externen Tracker, keine Cookies, DSGVO-ready.**

---

## Support & Kontakt

Wolf Hohl  
Greifswalder Str. 224a  
10405 Berlin  
E-Mail: kontakt@ki-sicherheit.jetzt

---

**Fragen, Verbesserungen, Wünsche?**  
Feedback jederzeit willkommen!

---

**Letztes Update:** Juli 2025
