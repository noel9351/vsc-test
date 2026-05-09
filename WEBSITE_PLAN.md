# Website Plan — Noel Gafner Portfolio

## Anforderungen

| Kategorie   | Entscheidung                                      |
|-------------|---------------------------------------------------|
| Typ         | Persönliches Developer-Portfolio                  |
| Design      | Dark & Tech — "Terminal Prime" Ästhetik           |
| Seiten      | Home, About, Projects, Contact                    |
| Rolle       | Developer / Entwickler                            |
| Projekte    | Web-Projekte + GitHub Repos (Karten-Layout)       |
| Kontakt     | E-Mail + LinkedIn + GitHub                        |
| Framework   | Kein Framework — reines HTML / CSS / JS           |

---

## Design-Token

| Variable     | Wert        | Verwendung             |
|--------------|-------------|------------------------|
| `--bg`       | `#030305`   | Haupt-Hintergrund      |
| `--bg2`      | `#080810`   | Terminal-Blöcke        |
| `--surface`  | `#0d0d18`   | Karten, Flächen        |
| `--border`   | `#1a1a2e`   | Rahmen, Trennlinien    |
| `--green`    | `#00ff88`   | Neon-Primärfarbe       |
| `--blue`     | `#00b4ff`   | Sekundäre Akzentfarbe  |
| `--text`     | `#c8d8e8`   | Fliesstext             |
| `--muted`    | `#3a4a5a`   | Gedämpfter Text        |

**Typografie:** Chakra Petch (Headings) + JetBrains Mono (Body)

---

## Dateistruktur

```
vsc-test/
├── index.html
├── about.html
├── projects.html
├── contact.html
├── css/
│   └── style.css
├── js/
│   └── main.js
├── assets/
│   └── images/
├── WEBSITE_PLAN.md
└── README.md
```

---

## Seiten

| Seite            | Inhalt                                          |
|------------------|-------------------------------------------------|
| `index.html`     | Hero, Tagline, 3 Feature-Karten                |
| `about.html`     | Bio, Skill-Tags, Terminal-Block                |
| `projects.html`  | Web-Projekte + GitHub Repos als Karten         |
| `contact.html`   | E-Mail, LinkedIn, GitHub Links                 |

---

*Erstellt: 2026-05-09 | Skill: creative-design/frontend-design*
