<!--
language: de
color: <span style="display:inline-block;width:1.5rem;height:1.5rem;background-color:@0;border:1px solid #ccc;border-radius:2px;vertical-align:middle;"></span> `@0`

import: ./specs/dashboard/README.md
import: https://raw.githubusercontent.com/LiaTemplates/virtual-speaker/0.1.1/README.md
import: https://raw.githubusercontent.com/LiaTemplates/Wictionary/0.0.2/README.md
import: https://raw.githubusercontent.com/LiaTemplates/Wikimedia/0.0.2/README.md
import: https://raw.githubusercontent.com/LiaTemplates/mermaid_template/0.1.4/README.md
import: https://raw.githubusercontent.com/LiaTemplates/BeforeAndAfter/main/README.md
import: https://raw.githubusercontent.com/LiaTemplates/three.js/0.1.0/README.md
import: https://raw.githubusercontent.com/herbigm/ChemmacrosJS/main/README.md
import: https://raw.githubusercontent.com/LiaTemplates/JSXGraph/0.0.3/README.md
import: https://raw.githubusercontent.com/LiaTemplates/PeriodicTable/main/README.md
import: https://raw.githubusercontent.com/LiaTemplates/BlocklyCode/0.1.0/README.md
import: https://raw.githubusercontent.com/LiaTemplates/AVR8js/main/README.md
import: https://raw.githubusercontent.com/LiaTemplates/Chat-Simulation/main/README.md
import: https://raw.githubusercontent.com/LiaTemplates/Comunica/0.0.3/README.md
-->

# Finde Deinen Weg – Ein Rundgang durch den Rohstoffkreislauf

Hier wächst dein Kursplan. Du bringst deine Idee mit; der Assistent im Chat hilft dir, daraus Lernziele, Aufgaben und fertiges Material zu entwickeln. Du prüfst jeden Vorschlag und entscheidest, was bleibt. **Ohne deine Bestätigung wird nichts gespeichert.**

<!-- class="journal-start" -->
[Zur Übersicht →](#dashboard-–-übersicht)

## Dashboard – Übersicht

```json @Dashboard.View
{
  "title": "Finde Deinen Weg – Ein Rundgang durch den Rohstoffkreislauf",
  "context": "Schülerinnen von 16–25 Jahren · Selbstlernkurs, 5 Etappen × 10 Minuten · Demo für die Partner von MINT meets MONTAN",
  "subtitle": "Alle fünf Etappen und die Kursprüfung sind bestanden, und der Kurs ist seit dem 28.10.2026 unter LiaPlayground veröffentlicht. Es fehlt nur noch dein Blick auf das Material – Ziel: fertig vor dem 06.11.2026.",
  "notice": "Messwerte, Remote-Angebote, Mia und die Chat-Figuren sind Beispiele bzw. Ideen und im Kurs so gekennzeichnet. Die Demo braucht eine Internetverbindung.",
  "next": {
    "title": "Material erstellen",
    "why": "Alles ist geprüft, aber erst dein Blick macht das Material fertig. Klick dich einmal als Schülerin durch die fünf Etappen und gib frei, was so bleiben soll.",
    "label": "Material ansehen und freigeben",
    "href": "agent:teaching/preview?file=README.md",
    "command": ":preview README.md",
    "icon": "👁"
  },
  "unitLabel": {
    "one": "Etappe",
    "many": "Etappen"
  },
  "unitsTitle": "Etappen",
  "labels": {
    "decide": "Noch zu entscheiden",
    "prepare": "Vor dem Einsatz vorbereiten",
    "viewMaterial": "So sehen es die Schülerinnen"
  },
  "selected": "2",
  "units": [
    {
      "id": "1",
      "title": "Die Landkarte: Woher kommt dein Akku?",
      "state": "current",
      "statusLabel": "bestanden – wartet auf deine Freigabe",
      "usable": {
        "state": "yes"
      },
      "summary": "Kreislauf-SVG, 360°-Stollen, Zuordnung, Umfrage und Vorher/Nachher – alles im Browser ausprobiert.",
      "href": "#1.-die-landkarte:-woher-kommt-dein-akku?",
      "view": {
        "href": "agent:teaching/preview?file=1",
        "command": ":preview 1",
        "label": "So sehen es die Schülerinnen"
      },
      "process": {
        "title": "Die Landkarte: Woher kommt dein Akku?",
        "steps": [
          {
            "title": "Etappe planen",
            "state": "done",
            "why": "Die Skizze legt Ziel, Aufgaben und Selbstkontrolle fest.",
            "result": "Planungsskizze mit Zuordnung und Umfrage"
          },
          {
            "title": "Material ausarbeiten",
            "state": "draft",
            "why": "Aus der Skizze entsteht die Seite, die die Schülerinnen sehen.",
            "result": "8 Folien im Kurs, dazu die Seite „Quellen“",
            "next": "Ansehen und freigeben."
          },
          {
            "title": "Bilder einfügen",
            "state": "optional",
            "why": "Die Fotos kommen direkt von Wikimedia, der Stollen ist eine eigene Grafik."
          },
          {
            "title": "Prüfen und überarbeiten",
            "state": "done",
            "why": "Verständlichkeit, Passung zum Lernziel und Sachaussagen werden geprüft, bevor die Demo rausgeht.",
            "result": "Bedenken am 28.10.2026 geklärt: 2 bestätigt, 2 geändert"
          }
        ]
      }
    },
    {
      "id": "2",
      "title": "Erkunden: Ein Stein voller Lithium",
      "state": "current",
      "statusLabel": "bestanden – wartet auf deine Freigabe",
      "usable": {
        "state": "yes"
      },
      "summary": "Mineralfotos, Bestimmungsquiz, Dünnschliff-Foto und 3D-Modell – im Browser ausprobiert.",
      "href": "#2.-erkunden:-ein-stein-voller-lithium",
      "view": {
        "href": "agent:teaching/preview?file=2",
        "command": ":preview 2",
        "label": "So sehen es die Schülerinnen"
      },
      "process": {
        "title": "Erkunden: Ein Stein voller Lithium",
        "steps": [
          {
            "title": "Etappe planen",
            "state": "done",
            "why": "Die Skizze legt Ziel, Aufgaben und Selbstkontrolle fest.",
            "result": "Planungsskizze mit Bestimmungsquiz und Freitextfrage"
          },
          {
            "title": "Material ausarbeiten",
            "state": "draft",
            "why": "Aus der Skizze entsteht die Seite, die die Schülerinnen sehen.",
            "result": "8 Folien im Kurs",
            "next": "Ansehen und freigeben."
          },
          {
            "title": "Bilder einfügen",
            "state": "optional",
            "why": "Die Fotos kommen direkt von Wikimedia mit Bildnachweis."
          },
          {
            "title": "Prüfen und überarbeiten",
            "state": "done",
            "why": "Verständlichkeit, Passung zum Lernziel und Sachaussagen werden geprüft, bevor die Demo rausgeht.",
            "result": "Bedenken am 28.10.2026 geklärt: Steckbriefe und Härte nach Wikipedia angepasst, Zinnwald-Bezug ergänzt"
          }
        ]
      }
    },
    {
      "id": "3",
      "title": "Umwandeln: Lithium aus Erz und Altbatterie",
      "state": "current",
      "statusLabel": "bestanden – wartet auf deine Freigabe",
      "usable": {
        "state": "yes"
      },
      "summary": "Periodensystem, Reaktionsgleichung, Laugungs-Simulation, Tabelle mit Formeln und Recycling-Rechner – im Browser ausprobiert.",
      "href": "#3.-umwandeln:-lithium-aus-erz-und-altbatterie",
      "view": {
        "href": "agent:teaching/preview?file=3",
        "command": ":preview 3",
        "label": "So sehen es die Schülerinnen"
      },
      "process": {
        "title": "Umwandeln: Lithium aus Erz und Altbatterie",
        "steps": [
          {
            "title": "Etappe planen",
            "state": "done",
            "why": "Die Skizze legt Ziel, Aufgaben und Selbstkontrolle fest.",
            "result": "Planungsskizze mit Simulation, Quiz und Kurzantwort"
          },
          {
            "title": "Material ausarbeiten",
            "state": "draft",
            "why": "Aus der Skizze entsteht die Seite, die die Schülerinnen sehen.",
            "result": "9 Folien im Kurs",
            "next": "Ansehen und freigeben."
          },
          {
            "title": "Bilder einfügen",
            "state": "optional",
            "why": "Diese Etappe kommt ohne Fotos aus."
          },
          {
            "title": "Prüfen und überarbeiten",
            "state": "done",
            "why": "Verständlichkeit, Passung zum Lernziel und Sachaussagen werden geprüft, bevor die Demo rausgeht.",
            "result": "Bedenken am 28.10.2026 geklärt: Verfahren, Gleichung, Faustregel und Rechner nach Wikipedia angepasst"
          }
        ]
      }
    },
    {
      "id": "4",
      "title": "Sortieren: Ein Roboter lernt trennen",
      "state": "current",
      "statusLabel": "bestanden – wartet auf deine Freigabe",
      "usable": {
        "state": "yes"
      },
      "summary": "Blockly-Sortierweiche mit Förderband und automatischer Prüfung, Streudiagramm und Arduino – im Browser ausprobiert.",
      "href": "#4.-sortieren:-ein-roboter-lernt-trennen",
      "view": {
        "href": "agent:teaching/preview?file=4",
        "command": ":preview 4",
        "label": "So sehen es die Schülerinnen"
      },
      "process": {
        "title": "Sortieren: Ein Roboter lernt trennen",
        "steps": [
          {
            "title": "Etappe planen",
            "state": "done",
            "why": "Die Skizze legt Ziel, Aufgaben und Selbstkontrolle fest.",
            "result": "Planungsskizze mit Code-Aufgabe und Quiz"
          },
          {
            "title": "Material ausarbeiten",
            "state": "draft",
            "why": "Aus der Skizze entsteht die Seite, die die Schülerinnen sehen.",
            "result": "7 Folien im Kurs",
            "next": "Ansehen und freigeben."
          },
          {
            "title": "Bilder einfügen",
            "state": "optional",
            "why": "Diese Etappe kommt ohne Fotos aus."
          },
          {
            "title": "Prüfen und überarbeiten",
            "state": "done",
            "why": "Verständlichkeit, Passung zum Lernziel und Sachaussagen werden geprüft, bevor die Demo rausgeht.",
            "result": "Bedenken am 28.10.2026 geklärt: Brandgefahr belegt, Stahlgehäuse als Annahme, Sortieranlagen nach Beleg"
          }
        ]
      }
    },
    {
      "id": "5",
      "title": "Dein Weg",
      "state": "current",
      "statusLabel": "bestanden – wartet auf deine Freigabe",
      "usable": {
        "state": "yes"
      },
      "summary": "Gruppenchat, Netz-Diagramm, Zuordnung, Umfrage, Flussdiagramm und Wissensgraph – im Browser ausprobiert.",
      "href": "#5.-dein-weg",
      "view": {
        "href": "agent:teaching/preview?file=5",
        "command": ":preview 5",
        "label": "So sehen es die Schülerinnen"
      },
      "process": {
        "title": "Dein Weg",
        "steps": [
          {
            "title": "Etappe planen",
            "state": "done",
            "why": "Die Skizze legt Ziel, Aufgaben und Selbstkontrolle fest.",
            "result": "Planungsskizze mit Zuordnung, Umfrage und Reflexion"
          },
          {
            "title": "Material ausarbeiten",
            "state": "draft",
            "why": "Aus der Skizze entsteht die Seite, die die Schülerinnen sehen.",
            "result": "9 Folien im Kurs",
            "next": "Ansehen und freigeben."
          },
          {
            "title": "Bilder einfügen",
            "state": "optional",
            "why": "Diese Etappe kommt ohne Fotos aus."
          },
          {
            "title": "Prüfen und überarbeiten",
            "state": "done",
            "why": "Verständlichkeit und Passung zum Lernziel werden geprüft, bevor die Demo rausgeht.",
            "result": "Prüfung vom 28.10.2026"
          }
        ]
      }
    }
  ],
  "process": {
    "title": "So entsteht dein Kurs",
    "description": "Die Schritte vom Thema bis zum geprüften Material. Diese Übersicht zeigt immer, wo wir gerade stehen.",
    "steps": [
      {
        "title": "Den Rahmen festlegen",
        "state": "done",
        "why": "Thema, Zielgruppe, Format und Sprache prägen alles, was folgt.",
        "result": "Selbstlernkurs, 5 Etappen × 10 Minuten, ein Link, lockeres Du"
      },
      {
        "title": "Gliederung und Lernziele",
        "state": "done",
        "why": "Klare Lernziele sagen, was die Schülerinnen am Ende können.",
        "result": "5 Lernziele, je eines pro Etappe"
      },
      {
        "title": "Didaktik",
        "state": "done",
        "why": "Methoden, Aufgabenformen und Unterstützung, die zu den Lernzielen passen.",
        "result": "Muster Orientierung und Kostprobe, Begleitfigur Mia"
      },
      {
        "title": "Vorlagen für Aktivitäten",
        "state": "done",
        "why": "Fertige Bausteine für Simulation, Code, Mineralbild und Landkarte – oder ein eigener, wenn nichts passt.",
        "result": "virtual-speaker, Wictionary, Wikimedia, Mermaid, BeforeAndAfter, three.js, ChemmacrosJS, JSXGraph, PeriodicTable, BlocklyCode, AVR8js, Chat-Simulation, Comunica"
      },
      {
        "title": "Material erstellen",
        "state": "draft",
        "why": "Erklärungen, Aufgaben und Selbstkontrollen entstehen aus den Planungsskizzen.",
        "result": "42 Folien in einer Kursdatei, mit Quellen und Bildnachweisen",
        "next": "Ansehen und freigeben."
      },
      {
        "title": "Prüfen und überarbeiten",
        "state": "done",
        "why": "Verständlichkeit und Passung zu den Lernzielen werden geprüft, bevor die Demo an die Partner geht.",
        "result": "Kursprüfung vom 28.10.2026 bestanden"
      },
      {
        "title": "Veröffentlichen",
        "state": "done",
        "why": "Den geprüften Kurs als Link teilen – zum Beispiel mit den Projektpartnern.",
        "result": "Veröffentlicht am 28.10.2026 in LiaPlayground/mint-meets-montan-demo"
      }
    ],
    "note": "Kein Ablaufplan – mit dem Kursrahmen entschieden, daher fehlt dieser Schritt. Fertig ist eine Etappe erst, wenn ihre Prüfung bestanden ist und du sie freigegeben hast."
  },
  "decisions": [
    {
      "key": "preparation-fachpruefung",
      "kind": "prepare",
      "title": "Gegenlesen durch Mineralogie und Chemie",
      "why": "Die Etappen 2 und 3 sind mit Wikipedia belegt; ein Blick der Fachleute bleibt sinnvoll, bevor die Partner die Demo sehen.",
      "how": "Etappe 2 der Mineralogie und Etappe 3 der Technischen Chemie zum Gegenlesen schicken; Rückmeldung vor dem 06.11.2026 einplanen. Die geänderten Aussagen stehen in den Entscheidungen der Etappen.",
      "href": "#prüfbericht-–-etappe-3",
      "label": "Prüfbericht Etappe 3",
      "source": {
        "check": 3,
        "date": "2026-10-28"
      }
    },
    {
      "key": "preparation-avatar",
      "kind": "prepare",
      "title": "Mia als Avatar vor der Vorführung ausprobieren",
      "why": "Der sprechende Avatar braucht eine LiaScript-Schnittstelle, die erst mit der nächsten Version kommt, und erscheint nur im Folienmodus mit Ton. Im Testbrowser gab es keine Stimmen, daher ist er nicht ausprobiert.",
      "how": "Den Kurs im Folienmodus mit Ton in Chrome öffnen; klappt der Avatar nicht, liest Mia ohne Gesicht vor."
    },
    {
      "key": "preparation-internet",
      "kind": "prepare",
      "title": "Internet und Ladezeit am Vorführort prüfen",
      "why": "Der Kurs lädt 13 Vorlagen und Bilder aus dem Netz; ohne Verbindung fehlen Bausteine.",
      "how": "Vor dem Termin den Link am Vorführrechner einmal ganz öffnen."
    },
    {
      "key": "decide-offline",
      "kind": "decide",
      "title": "Offline-Versprechen im Antrag",
      "why": "Das Ideenpapier verspricht Kurse, die offline laufen; diese Demo braucht Internet. Der Partner-Kasten in Etappe 5 sagt das offen.",
      "how": "Entscheiden, ob der Satz im Partner-Kasten so bleibt oder ob der Antrag das Offline-Versprechen genauer fasst."
    }
  ],
  "explore": [
    {
      "icon": "🛠️",
      "title": "Veröffentlichung aktualisieren",
      "description": "Nach weiteren Änderungen den Kurs im Repository auf den neuen Stand bringen.",
      "label": "Veröffentlichung aktualisieren",
      "href": "agent:development/update-project",
      "command": ":update-project"
    },
    {
      "icon": "🧑‍🎓",
      "title": "Als Schülerin ausprobieren",
      "description": "Eine Etappe mit einer Lernbegleitung durchspielen.",
      "label": "Etappe 1 ausprobieren",
      "href": "agent:teaching/try-as-learner?number=1",
      "command": ":try-as-learner 1"
    },
    {
      "icon": "🎨",
      "title": "Gestaltung",
      "description": "Einheitlicher Look für Kreislauf, Bilder und Farben.",
      "label": "Gestaltung festlegen",
      "href": "agent:artist/switch",
      "command": ":agent artist"
    }
  ],
  "links": [
    {
      "label": "Kursrahmen",
      "href": "#course-context-–-kursrahmen"
    },
    {
      "label": "Gliederung",
      "href": "#outline-–-gliederung"
    },
    {
      "label": "Didaktik",
      "href": "#didactics-–-didaktik"
    },
    {
      "label": "Etappen",
      "href": "#sessions-–-etappen"
    },
    {
      "label": "Notizen",
      "href": "#notes-backup-–-notizen"
    }
  ],
  "footer": "abgeleiteter Stand · 28.10.2026"
}
```

---

## Course Context – Kursrahmen

<!-- class="journal-actions" -->
[✏️ Kursrahmen überarbeiten](agent:teaching/init-course) `:init-course`

<!--- Filled by :scaffold from templates/course-context.yaml (layout: summary table + <details>). --->

**Kursrahmen:** bestätigt am 28.10.2026.

<!-- data-type="none" -->
| Punkt | Entschieden |
|---|---|
| Titel | Finde Deinen Weg – Ein Rundgang durch den Rohstoffkreislauf |
| Für wen | Schülerinnen von 16–25 Jahren, ländliche Region; die Demo zeigt den Kurs den Partnern im Projekt |
| Wie gelernt wird | Allein, im eigenen Tempo, ohne gemeinsame Stunde |
| Umfang | 5 Etappen × 10 Minuten |
| Verteilung | Ein Link für alle Etappen |
| Sprache und Anrede | Deutsch, lockeres Du |
| Autor | MINT meets MONTAN – TU Bergakademie Freiberg |
| Zeitplan pro Etappe | Nein |

<details><summary>Einstellungen für den Assistenten – hier gibt es nichts zu lesen</summary>

* __Course Type:__
  1. Type: self-paced
  2. Working Title: Finde Deinen Weg – Ein Rundgang durch den Rohstoffkreislauf
  3. Target Group: Schülerinnen von 16–25 Jahren aus ländlichen Regionen Südwestsachsens, oft ohne Elternhaus mit Studium; die Demo wird den Projektpartnern (Professuren) von MINT meets MONTAN live gezeigt und als Link verschickt

* __Terminology:__
  1. sessions-called: Etappe

* __Course Profile:__
  1. Persona type: coach
  2. Agenda required: no
  3. Pacing: learner-driven
  4. Assessment defaults: self-check quizzes, reflection
  5. Units: 5 × 10 min

* __File Structure:__
  1. Mode: single-file
  2. Session folder naming: n/a for single-file

* __Conventions & Standards:__
  1. Language: de
  2. Tone: informal
  3. Person: Du
  4. Instructor Address: Du
  5. Author: MINT meets MONTAN – TU Bergakademie Freiberg
  6. Contact:

* __LiaScript conventions:__
  - keine besonderen Vorgaben; Vorlagen werden nach dem Gerüst mit `:suggest-templates` ausgewählt

* __Additional Notes:__
  - Demo-Ziele für die Partner: das Netz-Prinzip mit Verweisen erkennen, die eigene Station wiederfinden, sehen, was LiaScript kann (Simulation, ausführbarer Code, Quiz, Umfrage, Zwilling).
  - Frist: fertig vor dem 06.11.2026; Vorführung live und als Link.
  - Quelle: Ideenpapier „MINT meets MONTAN“ v2 vom 28.10.2026 (vertraulich) – angefragte Partner, Zusagen und TODOs kommen nicht in den Kurs.
  - Für :suggest-templates: Laugungs-Simulation (Etappe 3), ausführbarer Code (Etappe 4), zoombares Mineralbild (Etappe 2), klickbare Kreislauf-Landkarte (Etappe 1).
  - Fachliche Prüfung: Etappe 2 durch die Mineralogie, Etappe 3 durch die Chemie, bevor die Demo rausgeht.
  - Kursdatei: Die vorhandene `README.md` im Hauptordner (Anleitung des Teaching-Agents) darf mit dem ersten Material überschrieben werden (Entscheidung vom 28.10.2026).
  - Veröffentlichung (28.10.2026): bewusst keine Kontaktadresse im Kurskopf; Kurstext und Planung unter CC BY 4.0; das Repository enthält Kurs, Journal und `specs/dashboard/`, nicht das Ideenpapier und nicht die übrigen Assistenten-Dateien.

</details>

---

## Outline – Gliederung

<!-- class="journal-actions" -->
[✏️ Gliederung überarbeiten](agent:teaching/create-outline) `:create-outline`

<!--- Filled by :scaffold from templates/course-outline.yaml. --->

<!-- data-key="title" -->
* __Titel:__
  Finde Deinen Weg – Ein Rundgang durch den Rohstoffkreislauf (Projekt MINT meets MONTAN)

<!-- data-key="target-audience" -->
* __Zielgruppe:__
  Schülerinnen von 16–25 Jahren aus ländlichen Regionen Südwestsachsens, oft ohne Elternhaus mit Studium, ohne fachliche Vorkenntnisse über das Schulwissen hinaus. Der Kurs dient als Demo: Er wird den Projektpartnern im Vorhaben MINT meets MONTAN gezeigt, die ihn mit den Augen der Schülerinnen ausprobieren.

<!-- data-key="time-commitment" -->
* __Zeitaufwand:__
  50 Minuten – 5 Etappen × 10 Minuten, im eigenen Tempo

<!-- data-key="abstract" -->
* __Kurzbeschreibung:__
  Woher kommt das Lithium in deinem Handy-Akku – und was passiert damit, wenn der Akku kaputt ist? Der Rundgang folgt dem Lithium durch den Rohstoffkreislauf: Du bestimmst ein Mineral, gewinnst Lithium in einem simulierten Laborversuch aus Erz und Altbatterie und bringst einem Roboter bei, Wertstoffe zu sortieren. An jeder Station siehst du, welche Studiengänge dahinterstehen und wie es weitergeht – digital, im Remote-Labor oder vor Ort in Freiberg.

<!-- data-key="learning-goals" -->
* __Lernziele:__ Die Schülerinnen können …
  1. die Stationen des Rohstoffkreislaufs beschreiben und Lithium darin verorten
  2. ein Lithium-Mineral anhand von Fotos und beschriebenen Merkmalen bestimmen
  3. aus Beispiel-Messwerten einer Laugung ablesen, wie gut Lithium gelöst wird, und eine Einflussgröße begründen
  4. eine vorgegebene Sortierregel für einen Roboter ergänzen und testen
  5. Stationen und Studiengänge benennen, die zu ihren eigenen Interessen passen

<!-- data-key="session-overview" -->
* __Übersicht der Etappen:__
  - 1 · Die Landkarte → Lernziel 1 → Zuordnungsquiz
  - 2 · Erkunden → Lernziel 2 → Bestimmungsquiz
  - 3 · Umwandeln → Lernziel 3 → Quiz zur Kurve
  - 4 · Sortieren → Lernziel 4 → Code läuft fehlerfrei + Quiz
  - 5 · Dein Weg → Lernziel 5 → Zuordnung Studiengang zu Station

---

## Didactics – Didaktik

<!-- class="journal-actions" -->
[✏️ Didaktik überarbeiten](agent:teaching/create-didactics) `:create-didactics` · [🎨 Gestaltung](agent:artist/create-visuals) `:agent artist` → `:create-visuals`

<!--- Filled by :scaffold from templates/course-didactics.yaml. --->

**Gestaltung der Etappen:** bestätigt am 28.10.2026.

<!-- data-key="didactic-concept" -->
* __Ablauf einer Etappe:__
  Wo sind wir im Kreislauf? → Frage mit Alltagsbezug („Sinn statt Technik“) → kurze Erklärung → Ausprobieren → Selbstkontrolle → Verweis auf Lernort, Remote-Labor und Studiengänge → „Was kommt danach?“ → Hinweiskasten für die Projektpartner. Über die Landkarte kann man frei zwischen den Etappen springen – wie im Netz des Antrags.

<!-- data-key="guiding-figure" -->
* __Begleitfigur:__
  Mia, eine fiktive Studentin der Angewandten Naturwissenschaft in Freiberg. Sie ist neugierig, ehrlich und gibt zu, dass sie früher selbst keine Ahnung hatte. Im Kurs ist sie einmal sichtbar als ausgedachte Figur gekennzeichnet; im Projekt begleiten echte Studentinnen.

<!-- data-key="language-style" -->
* __Sprache:__
  Lockeres Du, kurze Sätze, jedes Fachwort mit einem Alltagsbild eingeführt, keine „Mädchen“-Etiketten.

<!-- data-key="lesson-patterns" -->
* __Wiederkehrende Muster:__
  - __Orientierung__ – Etappen 1 und 5, Überblick und Einordnung – muss enthalten: klickbare Kreislauf-Landkarte, eine Umfrage oder Reflexion, einen Hinweiskasten für die Partner.
  - __Kostprobe__ – Etappen 2–4, eine Kreislauf-Station zum Ausprobieren – muss enthalten: Verortung am Anfang und Ende, eine interaktive Aufgabe mit Rückmeldung, einen Verweis auf ein hybrides oder reales Angebot und die Studiengänge, einen Hinweiskasten für die Partner.
  - Durchgängig: Jede Etappe nutzt mindestens zwei Darstellungsformen (Text plus Bild oder Interaktion) und bietet eine zweite Möglichkeit, Verständnis zu zeigen, die über das Quiz hinausgeht.

<!-- data-key="difficulty" -->
* __Schwierigkeit:__
  Für Einsteigerinnen – nur Schulwissen nötig.

<!-- data-key="voice-sample" -->
* __Stimmprobe:__
  „Hey, ich bin Mia. Ehrlich gesagt hab ich mich früher nie gefragt, wo das Lithium in meinem Handy-Akku herkommt. Heute weiß ich: Bevor es in deinem Akku landet, steckte es in einem Stein – und wenn der Akku kaputt ist, kann es zurück in den Kreislauf. Genau diesen Weg gehen wir jetzt zusammen. Du musst nichts vorher wissen, probier einfach aus.“

<details><summary>Einstellungen für den Assistenten – hier gibt es nichts zu lesen</summary>

* __Teaching Style:__
  conversational – lockeres Du, kurze Sätze, Alltagsbilder vor Fachbegriffen

* __Course Type:__
  self-paced – learner-driven, freier Einstieg über die Landkarte, jede Etappe endet mit einer Selbstkontrolle

* __Didactic Framework:__ ADDIE
  Klare, wiederholbare Phasen passen zu einem Selbstlernkurs, der in kurzer Zeit entsteht und geprüft wird.

* __Default Session Method:__ UDL Format Variety (slug: `udl`)
  Ohne Lehrkraft im Raum brauchen die Schülerinnen mehrere Zugänge: Text, Bild, Simulation, Code.

* __Session Types:__
  1. __Orientierung__ (slug: `orientierung`) — Überblick und Einordnung im Kreislauf (Etappen 1 und 5).
     Required: klickbare Kreislauf-Landkarte; Umfrage oder Reflexionsaufgabe; Hinweiskasten für die Projektpartner.
  2. __Kostprobe__ (slug: `kostprobe`) — eine Kreislauf-Station zum Ausprobieren (Etappen 2–4).
     Required: Kreislauf-Verortung am Anfang und Ende; mindestens eine interaktive Aufgabe mit Rückmeldung (Quiz, Simulation oder Code); Verweis auf ein hybrides oder reales Angebot und die zugehörigen Studiengänge; Hinweiskasten für die Projektpartner.

* __Difficulty Level:__
  beginner – keine Vorkenntnisse über das Schulwissen hinaus; jedes Fachwort wird eingeführt, Code wird nur ergänzt.

</details>

---

## Visual Identity – Gestaltung

<!-- class="journal-actions" -->
[🎨 Gestaltung](agent:artist/create-visuals) `:agent artist` → `:create-visuals` · [🎨 Logo](agent:artist/create-logo) `:agent artist` → `:create-logo`

<!--- Filled by :create-visuals (optional) from templates/visuals.yaml. --->

_Freiwillig – der Gestaltungsassistent füllt das aus, wenn Bilder und Farben einheitlich aussehen sollen._

---

## Templates – Vorlagen

<!-- class="journal-actions" -->
[▶️ Vorlagen vorschlagen](agent:teaching/suggest-templates) `:suggest-templates` · [👁 Vorlagenkatalog](agent:teaching/preview?file=specs/catalog/README.md) `:preview specs/catalog/README.md` · [▶️ Vorlagen verwalten](agent:teaching/manage-templates) `:manage-templates`

<!--- Managed from templates/course-templates.yaml: adopted templates by :manage-templates, the briefs of templates in development by :suggest-templates, the selection line by both, removals included (ownership: agents/teaching-agent.yaml → journal_formatting_rules). --->

Die LiaScript-Vorlagen dieses Projekts werden im Kopf ganz oben in `journal.md` eingebunden und auch in jeder Materialdatei, die sie nutzt.

Geprüfte Vorlagen stehen im Vorlagenkatalog (`specs/catalog/README.md`); weitere Vorlagen der Gemeinschaft gibt es unter [topics/liascript-template](https://github.com/topics/liascript-template). Eine ausgewählte Vorlage wird mit ihrer `import:`-Zeile in den Projektkopf eingetragen, hier beschrieben und im Material genauso eingebunden. Eine Vorlage, die noch entwickelt wird, steht hier mit einem Steckbrief, bis sie übernommen ist.

* __Template selection:__ done – virtual-speaker, wictionary, wikimedia, mermaid, before-and-after, threejs, chemmacros-js, jsxgraph, periodic-table, blockly-code, avr8js, chat-simulation, comunica

<section>

### Dashboard

* __Import:__
  `./specs/dashboard/README.md`

* __Header entry:__
  `import: ./specs/dashboard/README.md`

* __Purpose:__
  Zeigt die Übersicht des Projekts (nächster Schritt, Einheiten, Arbeitsstand, offene Punkte) aus einem einzigen Datenblock.

* __Use when:__
  1. Den Planungsstand unter `## Dashboard` in `journal.md` anzeigen

* __How to use:__
  1. Die Einbindung im Kopf von `journal.md` stehen lassen.
  2. Den Datenblock mit `:update-dashboard` neu erzeugen, nie von Hand ändern.

* __Special usage notes:__
  1. Beschreibung und Beispiele: `specs/dashboard/README.md`; Prüfung mit `node specs/dashboard/validate-journal.mjs`.

### virtual-speaker

* __Catalog id:__ virtual-speaker

* __Source:__ found

* __Import:__
  `https://raw.githubusercontent.com/LiaTemplates/virtual-speaker/0.1.1/README.md`

* __Header entry:__
  `import: https://raw.githubusercontent.com/LiaTemplates/virtual-speaker/0.1.1/README.md`

* __Purpose:__
  Mia (und weitere fiktive Figuren) als animierter Avatar, der beim Vorlesen der Erzählkommentare die Lippen bewegt.

* __Use when:__
  1. Etappen 1–5: Erzählkommentare von Mia

* __Basic example:__

  ```markdown
      @VirtualSpeaker.speaker(mia)
      --{{1}}--
  Hey, ich bin Mia.
  ```

* __How to use:__
  1. Figur einmal registrieren: `VirtualSpeaker.define('mia', { style: 'micah', seed: 'Mia', name: 'Mia' })` (Stil und Seed bestimmen das Gesicht).
  2. Vor jedem Kommentar `@VirtualSpeaker.speaker(id)` setzen; mehrere Figuren sind möglich.

* __Special usage notes:__
  1. Braucht `window.LIA.narrator`, laut README im Entwicklungszweig von LiaScript, „mit der nächsten Version“ – vor der Vorführung ausprobieren.
  2. Der Avatar erscheint nur im Präsentations- oder Folienmodus mit Ton, nicht im Lehrbuchmodus.

### Wictionary

* __Catalog id:__ wictionary

* __Source:__ found

* __Import:__
  `https://raw.githubusercontent.com/LiaTemplates/Wictionary/0.0.2/README.md`

* __Header entry:__
  `import: https://raw.githubusercontent.com/LiaTemplates/Wictionary/0.0.2/README.md`

* __Purpose:__
  Fachwörter anklickbar machen: ein Klick zeigt die Bedeutung aus dem deutschen Wiktionary.

* __Use when:__
  1. Etappen 1–5: jedes neue Fachwort (z. B. Laugung, Mineral, Sensor)

* __Basic example:__

  ```markdown
  Beim Recycling hilft die @wik(Laugung, de).
  ```

* __How to use:__
  1. `@wik(Wort, de)` für das deutsche Wiktionary, `@wikd(Begriff, de, Anzeigetext)` für einen eigenen Anzeigetext.

* __Special usage notes:__
  1. Braucht Internet; die Abfrage läuft erst beim Klick.
  2. Ob jedes Fachwort einen Eintrag hat, beim Ausarbeiten prüfen; Inhalte stehen unter CC BY-SA.

### Wikimedia

* __Catalog id:__ wikimedia

* __Source:__ found

* __Import:__
  `https://raw.githubusercontent.com/LiaTemplates/Wikimedia/0.0.2/README.md`

* __Header entry:__
  `import: https://raw.githubusercontent.com/LiaTemplates/Wikimedia/0.0.2/README.md`

* __Purpose:__
  Fotos von Wikimedia Commons mit Titel, Urheber und Lizenz einbinden – wichtig, weil der Kurs als OER erscheinen soll.

* __Use when:__
  1. Etappe 2: Mineralfotos
  2. Etappen 1, 3–5: Fotos von Lernorten, Bergbau und Recycling

* __Basic example:__

  ```markdown
  @Wikimedia.embed(File:Hoverfly_May_2008-8.jpg)
  ```

* __How to use:__
  1. `@Wikimedia.embed(Datei)` für ein Bild, `@Wikimedia.gallery(Datei1|Datei2)` für mehrere.
  2. Einzelne Angaben mit `@Wikimedia.credit(Datei)`, `@Wikimedia.license(Datei)` usw.

* __Special usage notes:__
  1. Braucht Internet (Commons-Abfrage); Fehler erscheinen nur in der Browser-Konsole.

### Mermaid

* __Catalog id:__ mermaid

* __Source:__ found

* __Import:__
  `https://raw.githubusercontent.com/LiaTemplates/mermaid_template/0.1.4/README.md`

* __Header entry:__
  `import: https://raw.githubusercontent.com/LiaTemplates/mermaid_template/0.1.4/README.md`

* __Purpose:__
  Das Netz der Angebote als Diagramm.

* __Use when:__
  1. Etappe 1: Überblick über die Angebotsformen
  2. Etappe 5: das Netz der Angebote

* __Basic example:__

  ````markdown
  ```mermaid @mermaid
  flowchart LR
    Erkunden --> Gewinnen --> Umwandeln --> Nutzen --> Sortieren
  ```
  ````

* __How to use:__
  1. Codeblock ` ```mermaid @mermaid ` für mehrzeilige Diagramme; `@mermaid_eval` für ein bearbeitbares Diagramm.

* __Special usage notes:__
  1. Lädt Mermaid 10.5.0 von jsDelivr; klickbare Knoten sind in der README nicht dokumentiert.

### BeforeAndAfter

* __Catalog id:__ before-and-after

* __Source:__ found

* __Import:__
  `https://raw.githubusercontent.com/LiaTemplates/BeforeAndAfter/main/README.md`

* __Header entry:__
  `import: https://raw.githubusercontent.com/LiaTemplates/BeforeAndAfter/main/README.md`

* __Purpose:__
  Zwei Bilder mit einem Schieberegler vergleichen.

* __Use when:__
  1. Etappe 1: Tagebau und renaturierte Landschaft
  2. Etappe 2: Dünnschliff in normalem und polarisiertem Licht
  3. Etappe 3: Altbatterie und Schwarzmasse

* __Basic example:__

  ```markdown
  @beforeAndAfter(img/glacier-1883.jpg,img/glacier-2015.jpg)
  ```

* __How to use:__
  1. `@beforeAndAfter(bild1,bild2)` – die beiden Adressen ohne Leerzeichen dazwischen.

* __Special usage notes:__
  1. Freie Bildpaare müssen noch gefunden werden; ohne Versionsangabe.

### three.js

* __Catalog id:__ threejs

* __Source:__ found

* __Import:__
  `https://raw.githubusercontent.com/LiaTemplates/three.js/0.1.0/README.md`

* __Header entry:__
  `import: https://raw.githubusercontent.com/LiaTemplates/three.js/0.1.0/README.md`

* __Purpose:__
  Ein drehbares 3D-Modell als Objektzwilling eines Minerals.

* __Use when:__
  1. Etappe 2 (Extra): 3D-Mineral

* __Basic example:__

  ```markdown
  @THREE.gltf(assets/models/mineral.glb)
  ```

* __How to use:__
  1. `@THREE.gltf(url)` lädt ein glTF/GLB-Modell; drehen mit links ziehen, zoomen mit dem Mausrad.

* __Special usage notes:__
  1. Ein frei lizenziertes 3D-Modell muss noch gefunden werden; laut README nur glTF/GLB.

### ChemmacrosJS

* __Catalog id:__ chemmacros-js

* __Source:__ catalog

* __Import:__
  `https://raw.githubusercontent.com/herbigm/ChemmacrosJS/main/README.md`

* __Header entry:__
  `import: https://raw.githubusercontent.com/herbigm/ChemmacrosJS/main/README.md`

* __Purpose:__
  Chemische Formeln, Reaktionsgleichungen und Gefahrensymbole im Text.

* __Use when:__
  1. Etappe 3: Reaktionsgleichung der Laugung und Gefahrensymbol der Säure

* __Basic example:__

  ```markdown
  @reaction(2 H2 + O2 -> 2 H2O)
  ```

* __How to use:__
  1. `@ch(Formel)`, `@reaction(Gleichung)`, `@ghspic(Piktogramme)`.

* __Special usage notes:__
  1. Enthält die Formel Klammern oder Kommas, muss sie in Backticks stehen.
  2. Ohne Versionsangabe (Hauptzweig); die Gefahrensymbole kommen von Wikimedia Commons. Die Gleichung prüft die Chemie.

### JSXGraph

* __Catalog id:__ jsxgraph

* __Source:__ found

* __Import:__
  `https://raw.githubusercontent.com/LiaTemplates/JSXGraph/0.0.3/README.md`

* __Header entry:__
  `import: https://raw.githubusercontent.com/LiaTemplates/JSXGraph/0.0.3/README.md`

* __Purpose:__
  Laugungs-Simulation: ein Schieberegler für die Temperatur verändert die Kurve live.

* __Use when:__
  1. Etappe 3: Simulation mit Beispiel-Messwerten

* __Basic example:__

  ````markdown
  ```javascript @JSX.Graph
  var a = board.create('slider', [[-4, 4], [0, 4], [-3, 1, 3]], { name: 'a' });
  var f = board.create('functiongraph', [(x) => a.Value() * x * x]);
  ```
  ````

* __How to use:__
  1. Codeblock mit `@JSX.Graph`; eigene Grenzen mit `@JSX.Graph.withParams(...)`.

* __Special usage notes:__
  1. Die Kurve beruht auf Beispieldaten und wird so gekennzeichnet.

### PeriodicTable

* __Catalog id:__ periodic-table

* __Source:__ found

* __Import:__
  `https://raw.githubusercontent.com/LiaTemplates/PeriodicTable/main/README.md`

* __Header entry:__
  `import: https://raw.githubusercontent.com/LiaTemplates/PeriodicTable/main/README.md`

* __Purpose:__
  Das Periodensystem: Wo steht Lithium?

* __Use when:__
  1. Etappe 3: Einstieg

* __Basic example:__

  ```markdown
  @PeriodicTable.withStyle("width: 50%; height: 600px;")
  ```

* __How to use:__
  1. `@PeriodicTable` oder `@PeriodicTable.withStyle("…")` für Größe und Breite.

* __Special usage notes:__
  1. Die README nennt als Import die GitHub-Seite; hier steht die Rohdatei. Ohne Version, letzte Änderung 2021.

### BlocklyCode

* __Catalog id:__ blockly-code

* __Source:__ catalog

* __Import:__
  `https://raw.githubusercontent.com/LiaTemplates/BlocklyCode/0.1.0/README.md`

* __Header entry:__
  `import: https://raw.githubusercontent.com/LiaTemplates/BlocklyCode/0.1.0/README.md`

* __Purpose:__
  Programmieren mit Blöcken über JavaScript – mit eigenen Roboter-Blöcken und automatisch geprüfter Aufgabe.

* __Use when:__
  1. Etappe 4: Sortierregel ergänzen

* __Basic example:__

  ````markdown
  ```js
  roboter.greife()
  ```
  @Blockly.js(level4)
  ````

* __How to use:__
  1. Eigene Befehle mit `window.LiaBlockly.defineModule(name, functions)`, eigene Blöcke mit `defineBlock(spec)`.
  2. Geprüfte Aufgabe: ein versteckter Block ` ```js -Check ` mit `await run()` und `expect(...)`, dazu `@Blockly.js.check(level4)`.

* __Special usage notes:__
  1. Stufe `level4` (ab Klasse 8) passt zur Zielgruppe; ein Lauf stoppt nach höchstens 5 s.

### AVR8js

* __Catalog id:__ avr8js

* __Source:__ found

* __Import:__
  `https://raw.githubusercontent.com/LiaTemplates/AVR8js/main/README.md`

* __Header entry:__
  `import: https://raw.githubusercontent.com/LiaTemplates/AVR8js/main/README.md`

* __Purpose:__
  Ein simuliertes Arduino mit Sensor und Servo – so sieht Roboter-Code im echten Labor aus.

* __Use when:__
  1. Etappe 4 (Extra): Arduino mit Sensor und Servo

* __Basic example:__

  ````markdown
  <div id="example"><wokwi-led color="red" pin="13"></wokwi-led></div>

  ```cpp
  void setup() { pinMode(13, OUTPUT); }
  void loop() { digitalWrite(13, HIGH); delay(500); digitalWrite(13, LOW); delay(500); }
  ```
  @AVR8js.sketch(example)
  ````

* __How to use:__
  1. Bauteile als `wokwi-…`-Elemente in einen Container, darunter der Code mit `@AVR8js.sketch(id)`.

* __Special usage notes:__
  1. Der Code wird online bei hexi.wokwi.com übersetzt – braucht Internet; ohne Versionsangabe.

### Chat-Simulation

* __Catalog id:__ chat-simulation

* __Source:__ found

* __Import:__
  `https://raw.githubusercontent.com/LiaTemplates/Chat-Simulation/main/README.md`

* __Header entry:__
  `import: https://raw.githubusercontent.com/LiaTemplates/Chat-Simulation/main/README.md`

* __Purpose:__
  Ein Gruppenchat fiktiver Studentinnen aus Mineralogie, Chemie und Robotik, die von ihrem Weg ins Studium erzählen.

* __Use when:__
  1. Etappe 5: statt der noch fehlenden Vorbild-Videos

* __Basic example:__

  ````markdown
  ```javascript @CHAT
  [
    {name: "Mia", message: "Wie seid ihr eigentlich zum Studium gekommen?"},
    {name: "Lea", message: "Ehrlich? Über einen Schulbesuch."}
  ]
  ```
  ````

* __How to use:__
  1. Nachrichten als JSON-Liste mit `name` und `message`; Markdown und LiaScript-Elemente in `message` sind erlaubt.

* __Special usage notes:__
  1. Die erste Person steht links, alle anderen rechts; keine Avatare pro Person.
  2. Lädt eine Tipp-Animation von tenor.com – für den Schuleinsatz wegen Datenschutz prüfen. Alle Figuren sind fiktiv und so gekennzeichnet.

### Comunica

* __Catalog id:__ comunica

* __Source:__ found

* __Import:__
  `https://raw.githubusercontent.com/LiaTemplates/Comunica/0.0.3/README.md`

* __Header entry:__
  `import: https://raw.githubusercontent.com/LiaTemplates/Comunica/0.0.3/README.md`

* __Purpose:__
  „Frag die Landkarte“: vorbereitete Abfragen an einen kleinen Wissensgraphen aus Stationen, Angeboten und Studiengängen – Brücke zu InWiVis.

* __Use when:__
  1. Etappe 5 (Extra, vor allem für die Partner)

* __Basic example:__

  ````markdown
  ```turtle
  @prefix ex: <http://example.org/> .
  ex:Chemie ex:station ex:Umwandeln .
  ```
  ```sparql
  PREFIX ex: <http://example.org/>
  SELECT ?fach WHERE { ?fach ex:station ex:Umwandeln }
  ```
  @Comunica.RDF_SPARQL
  ````

* __How to use:__
  1. `@Comunica.RDF_SPARQL`: Turtle-Block mit den Daten, dann der SPARQL-Block; das Ergebnis erscheint als Tabelle.

* __Special usage notes:__
  1. Nur ein Teil der Ausgabeformate wird unterstützt; Wissensgraph als Grafik ist nicht dokumentiert.

</section>

---

## Agenda – Ablaufplan

<!-- class="journal-actions" -->
[▶️ Ablaufplan erstellen](agent:teaching/create-agenda) `:create-agenda`

<!--- Filled by :create-agenda from templates/course-agenda.yaml (skip if the course profile says agenda: no). --->

Kein Zeitplan – mit dem Kursrahmen entschieden.

---

## Sessions – Etappen

<!-- class="journal-actions" -->
[▶️ Neue Etappe planen](agent:teaching/create-session) `:create-session`

<!--- Managed by :create-session, :promote-session, :coauthor-materials and :validate-course. Overview first — status list, then the technical table in <details> (templates/session-skeleton.yaml → section_layout.overview) — then one `### {n}. {title}` subsection per session. --->

<!--- 28.10.2026: :suggest-templates hat in jeder Etappe unter „Inhalt“ die Zeile „Bausteine“ (Kern / Extra für Neugierige) ergänzt. --->

<!--- 28.10.2026: Material aller fünf Etappen von :build-session erzeugt und geprüft; Inhalt und Bausteine-Zeilen an das fertige Material angepasst. --->

1. Die Landkarte: Woher kommt dein Akku? – bestanden – wartet auf deine Freigabe
2. Erkunden: Ein Stein voller Lithium – bestanden – wartet auf deine Freigabe
3. Umwandeln: Lithium aus Erz und Altbatterie – bestanden – wartet auf deine Freigabe
4. Sortieren: Ein Roboter lernt trennen – bestanden – wartet auf deine Freigabe
5. Dein Weg – bestanden – wartet auf deine Freigabe

<!--- One subsection per session, structured like this:

`### {n}. {Session Title}` (the heading line of each subsection)

{{action line: `class="journal-actions"` attribute comment + state-dependent links, see `data/agent-links.md`}}

{{<details> "Technical settings and more actions": **Type:** slug, **Method:** slug, further commands</details>}}

{{visible kind line: display names of type and method}}

Each bold label is in the course language and carries its key comment on the line above it (data-key = summary, content, activities, decisions, references — templates/session-skeleton.yaml); the comment is left out here only because it would end this note.

**{{"Summary", translated}}:**

{{2–4 sentences: focus, didactic intent, known stumbling blocks}}

**{{"Content", translated}}:**

{{topic list / content skeleton per templates/session-skeleton.yaml}}

**{{"Activities", translated}}:**

1. {{activity}}

**{{"Decisions", translated}}:**

- **{{date}}:** {{instructor decision about this unit — added during :coauthor-materials; a bullet with the date in bold, never a numbered item that starts with the date}}

**{{"References", translated}}:**

1. {{reference}}

The block order is fixed in `templates/session-skeleton.yaml` → `section_layout.entry_order`: action line, technical
details, then the skeleton fields; after them the validation report (after :validate-course; a heading in the course
language, "Validation report – {unit} {n}", above `<section data-key="validation-report">`), `#### Images` (created with
the first image entry, by :coauthor-materials or :create-image) and `#### Persona Reviews` (after :review-as-persona),
in this order. Never use `#####` headings inside a session.
--->

<details><summary>Technische Übersicht</summary>

<!-- data-type="none" -->
| # | Title | Type | Method | Skeleton | Material | Done | Notes |
|---|-------|------|--------|----------|----------|------|-------|
| 1 | Die Landkarte: Woher kommt dein Akku? | orientierung | udl | ✅ | ✅ | ✅ | bestanden – wartet auf deine Freigabe |
| 2 | Erkunden: Ein Stein voller Lithium | kostprobe | udl | ✅ | ✅ | ✅ | bestanden – wartet auf deine Freigabe |
| 3 | Umwandeln: Lithium aus Erz und Altbatterie | kostprobe | udl | ✅ | ✅ | ✅ | bestanden – wartet auf deine Freigabe |
| 4 | Sortieren: Ein Roboter lernt trennen | kostprobe | udl | ✅ | ✅ | ✅ | bestanden – wartet auf deine Freigabe |
| 5 | Dein Weg | orientierung | udl | ✅ | ✅ | ✅ | bestanden – wartet auf deine Freigabe |

</details>

### 1. Die Landkarte: Woher kommt dein Akku?

<!-- class="journal-actions" -->
[👁 So sehen es die Schülerinnen](agent:teaching/preview?file=1) `:preview 1`

<details>
<summary>Technische Einstellungen und weitere Aktionen</summary>

**Type:** orientierung

**Method:** udl

[✏️ Gemeinsam überarbeiten](agent:teaching/coauthor-materials?number=1) `:coauthor-materials 1` · [✏️ Kleine Korrektur](agent:teaching/quick-fix?number=1) `:quick-fix 1 <was?>`

</details>

<!-- data-key="kind" -->
**Art:** Orientierung

<!-- data-key="summary" -->
**Zusammenfassung:**

Einstieg über die Frage nach dem eigenen Akku. Mia stellt sich vor und wird als fiktive Figur gekennzeichnet. Der Kreislauf mit seinen sieben Stationen erscheint als klickbare Karte, Lithium ist der rote Faden.

Stolperstein: Sieben Stationen sind viel. Nur vier werden im Rundgang besucht, die anderen bleiben sichtbar auf der Karte.

<!-- data-key="content" -->
**Inhalt:**

- Die Stationen Erkunden, Gewinnen, Umwandeln, Nutzen, Sortieren, Zurückführen, Renaturieren
- Die drei Angebotsformen real, hybrid und digital
- Die Karte als Sprungbrett zu den Etappen 2–4
- Hinweiskasten für die Projektpartner
- Bausteine: Kern – Kreislauf als SVG mit Auswahlfeld (ein Skript färbt die gewählte Station ein), 360°-Rundblick in einen gezeichneten Stollen (eigene Grafik) als Einstieg · Extra für Neugierige – Vorher/Nachher: Tagebau Cottbus-Nord und Cottbuser Ostsee (Station Renaturieren)

<!-- data-key="activities" -->
**Aktivitäten:**

1. Zuordnung neuer Situationen: „Ein Bagger holt Gestein aus der Grube“ → Gewinnen · „Im Labor wird aus Gesteinspulver ein weißes Salz“ → Umwandeln · „Du lädst dein Handy über Nacht auf“ → Nutzen · „Eine Anlage trennt Akkus von Dosen und Schrauben“ → Sortieren
2. Umfrage: Welche Station interessiert dich am meisten?

<!-- data-key="decisions" -->
**Entscheidungen:**

- **28.10.2026:** „Lithium wird auch aus salzhaltigem Wasser gewonnen“ bestätigt – belegt durch Wikipedia „Lithium“ (Abschnitt Gewinnung).
- **28.10.2026:** Bildunterschrift „hier entsteht der Cottbuser Ostsee“ bestätigt – belegt durch Wikipedia „Cottbuser Ostsee“.
- **28.10.2026:** Quellenseite „Quellen“ vor den Bildnachweisen angelegt; jede Etappe trägt dort ihre Belege ein.
- **28.10.2026:** „Ordne zu“ fragt neue Situationen statt der Erklärtexte der Karte ab, damit Verständnis statt Wiedererkennen geprüft wird.

<!-- data-key="references" -->
**Quellen:**

1. Ideenpapier „MINT meets MONTAN“ v2, Abschnitt 2 und Abb. 1
2. Wikipedia: [Lithium](https://de.wikipedia.org/wiki/Lithium) und [Cottbuser Ostsee](https://de.wikipedia.org/wiki/Cottbuser_Ostsee) – im Kurs auf der Seite „Quellen“
3. Fotos: Wikimedia Commons, Nachweise im Kapitel „Bildnachweise“ des Kurses

#### Prüfbericht – Etappe 1

<section data-key="validation-report">

**Ergebnis:** bestanden – wartet auf deine Freigabe (28.10.2026)

**Jetzt mit den Schülerinnen nutzbar:** ja

**Was funktioniert:**

- „Der Rohstoffkreislauf“: Auswahl einer Station färbt sie im SVG ein und verlinkt zur passenden Etappe – im Browser ausprobiert
- „Ein Blick in den Stollen“: 360°-Rundblick lädt und lässt sich drehen – im Browser angesehen
- „Ordne zu“ und „Was interessiert dich?“: Drag & Drop und Umfrage ohne Fehler; Kreislauf-Verortung am Anfang und Ende, Partner-Kasten vorhanden
- „Extra: Vom Tagebau zum See“: Regler zwischen beiden Fotos funktioniert – im Browser angesehen
- Beide Sachaussagen von dir bestätigt, mit Wikipedia belegt
- Bei der Prüfung geändert: „Ordne zu“ fragt neue Situationen statt der Erklärtexte ab; neue Seite „Quellen“ vor den Bildnachweisen mit den Belegen für Etappe 1 – danach gerenderte Prüfung ohne neue Befunde

**Noch offen:**

- nichts – die Etappe wartet nur auf deinen Blick in die Ansicht der Schülerinnen
- Hinweis: Auf „Ordne zu“ muss man bei 1024×768 einmal scrollen, um die Tabelle zu sehen

<details>
<summary>Technischer Bericht</summary>

- __Date:__ 2026-10-28
- __Material:__ README.md → ## Die Landkarte: Woher kommt dein Akku?
- __Result:__ PASS
- __Mode:__ course

**Content:**
- Lernziel 1 (Stationen beschreiben, Lithium verorten) durch Kreislauf-SVG, Stollen und Zuordnung abgedeckt
- Sachaussagen Lithium aus Salzwasser und Cottbuser Ostsee: bestätigt (Entscheidungen vom 28.10.2026), belegt auf der Seite „Quellen“ ✅
- Zuordnung prüft neue Situationen statt Wiedererkennen ✅

**Type Consistency:**
- Session Type: orientierung — Required: klickbare Kreislauf-Landkarte ✅; Umfrage oder Reflexion ✅; Hinweiskasten für die Projektpartner ✅

**Method Consistency:**
- Session Method: udl — Required: zwei Darstellungsformen (Text, SVG, 360°-Bild) ✅; zweite Form, Verständnis zu zeigen (Zuordnung und Umfrage) ✅; Alternativtexte, einfache Sprache ✅

**Persona & Style:**
- Mia spricht in lockerem Du, als ausgedachte Figur gekennzeichnet; keine „Mädchen“-Etiketten ✅

**LiaScript Syntax:**
- check-material: keine fehlenden Bilder, keine Antwortmuster; „Ordne zu“ passt bei 1024×768 erst nach dem Scrollen (gemessen bei 1024×768, 810×1080, 1080×810)
- Ein JavaScript-Fehler („Cannot read properties of null (reading 'addEventListener')“) ohne Folienzuordnung, im Browser ohne sichtbare Folge; Quelle vermutlich eine der Vorlagen

**Unit entry (journal):**
- Inhalt und Bausteine-Zeile an das Material angepasst (gezeichneter Stollen statt Foto)

**Duration (advisory):** Schätzung 10 min vs. 10 min – im Rahmen (Extra zusätzlich etwa 2 min)

**Reference Check:** nicht mit reference-checker geprüft; die zwei Wikipedia-Quellen als Auszug gelesen und passend zu den Aussagen

**Templates:** virtual-speaker, Wictionary, BeforeAndAfter im Kopf eingebunden ✅; Pannellum nicht als Vorlage, sondern direkt über jsDelivr mit eigenem Makro `@panorama` (die Vorlage blockierte das Laden etwa 30 s)

**Recommended Actions:**
1. Die Etappe in der Ansicht der Schülerinnen ansehen und freigeben (`:preview 1`)

</details>

</section>

### 2. Erkunden: Ein Stein voller Lithium

<!-- class="journal-actions" -->
[👁 So sehen es die Schülerinnen](agent:teaching/preview?file=2) `:preview 2`

<details>
<summary>Technische Einstellungen und weitere Aktionen</summary>

**Type:** kostprobe

**Method:** udl

[✏️ Gemeinsam überarbeiten](agent:teaching/coauthor-materials?number=2) `:coauthor-materials 2` · [✏️ Kleine Korrektur](agent:teaching/quick-fix?number=2) `:quick-fix 2 <was?>`

</details>

<!-- data-key="kind" -->
**Art:** Kostprobe

<!-- data-key="summary" -->
**Zusammenfassung:**

Wie erkennt man ein Mineral? An Fotos und beschriebenen Merkmalen (Farbe, Glanz, Spaltbarkeit) werden Lithium-Minerale unterschieden.

Stolperstein: Die Härte kann man am Bildschirm nicht testen, deshalb wird sie nur beschrieben.

<!-- data-key="content" -->
**Inhalt:**

- Verortung: Start des Kreislaufs, danach Gewinnen
- Drei Lithium-Minerale – Lepidolith, Zinnwaldit, Spodumen –, jedes mit eigenem Foto und eigenem Steckbrief (Farbe, Glanz, Form, Härte-Spanne)
- Regionaler Bezug: Zinnwaldit ist nach Zinnwald im Erzgebirge benannt
- Härte nach Mohs als Balkendiagramm (typische, gerundete Werte)
- Ein Dünnschliff mit Glimmer unter dem Polarisationsmikroskop als Kostprobe für „Mikroskop aus der Ferne“
- Studiengang Geologie/Mineralogie
- Verweis auf „Mikroskop aus der Ferne“ (Idee) und terra mineralia (Lernort)
- Bausteine: Kern – Mineralfotos von Wikimedia, Bestimmungsquiz mit zwei anderen Fotos, Dünnschliff-Foto · Extra für Neugierige – drehbares 3D-Modell (vereinfachter Glimmer-Stapel und Spodumen-Kristall) als Vorstufe eines Objektzwillings

<!-- data-key="activities" -->
**Aktivitäten:**

1. Bestimmungsquiz mit zwei Fotos: Welches Mineral ist das?
2. Kurze Freitext-Frage: Welches Merkmal hat dir geholfen?

<!-- data-key="decisions" -->
**Entscheidungen:**

- **28.10.2026:** Steckbriefe an Wikipedia angepasst: Lepidolith „rosa bis grauviolett“, Zinnwaldit „graubraun bis grünlich, fächer- oder rosettenförmig“, Spodumen „meist hell, selten rosa“; Härte-Spannen im Text.
- **28.10.2026:** Härte-Diagramm: Zinnwaldit 3 statt 3,5 (Spanne 2,5 bis 4); die übrigen Werte bestätigt.
- **28.10.2026:** Regionaler Bezug ergänzt: Zinnwaldit ist nach Zinnwald im Erzgebirge benannt (belegt durch Wikipedia „Zinnwaldit“).
- **28.10.2026:** Tipp zu Foto B nennt Farbe und Form, weil Spodumen auch rosa bis violett sein kann.

<!-- data-key="references" -->
**Quellen:**

1. Ideenpapier „MINT meets MONTAN“ v2, Abschnitt 5
2. Wikipedia: [Lepidolith](https://de.wikipedia.org/wiki/Lepidolith), [Lepidolite (englisch)](https://en.wikipedia.org/wiki/Lepidolite), [Zinnwaldit](https://de.wikipedia.org/wiki/Zinnwaldit), [Spodumen](https://de.wikipedia.org/wiki/Spodumen), [Mohs-Skala](https://de.wikipedia.org/wiki/Mohs-Skala), [Muskovit](https://de.wikipedia.org/wiki/Muskovit) – im Kurs auf der Seite „Quellen“
3. Fotos: Wikimedia Commons, Nachweise im Kapitel „Bildnachweise“ des Kurses

#### Prüfbericht – Etappe 2

<section data-key="validation-report">

**Ergebnis:** bestanden – wartet auf deine Freigabe (28.10.2026)

**Jetzt mit den Schülerinnen nutzbar:** ja

**Was funktioniert:**

- „Drei Lithium-Minerale“: Fotos mit Urheber und Lizenz über Wikimedia, anklickbares Fachwort „Glimmer“ – im Browser angesehen
- „Bestimme selbst“: zwei Quizfragen mit anderen Fotos als auf der Lernseite, Tipp nach dem ersten Fehlversuch, vorgelesen; die Fotos geben die Lösung nicht im Bildtext preis
- „Extra: Ein Modellkristall zum Drehen“: 3D-Modell lädt, Teile sind anklickbar – im Browser angesehen
- Kreislauf-Verortung am Anfang und Ende, Verweis auf terra mineralia und Studiengang, Partner-Kasten
- Bei der Kursprüfung korrigiert: Links zu den Dateiseiten von Foto A und Foto B im Kapitel „Bildnachweise“; im Journal-Eintrag eine Aufgabe zum Zinnwald-Bezug gestrichen
- Bei der Prüfung geändert: Steckbriefe, Härte-Diagramm und Tipp zu Foto B nach Wikipedia; Zinnwald-Bezug ergänzt; Belege für Etappe 2 auf der Seite „Quellen“ – danach gerenderte Prüfung ohne neue Befunde

**Noch offen:**

- nichts – die Etappe wartet nur auf deinen Blick in die Ansicht der Schülerinnen
- Hinweis: Die Belege stammen aus Wikipedia; eine Durchsicht durch die Mineralogie bleibt sinnvoll, bevor die Demo rausgeht
- Hinweis: „Bestimme selbst“, Foto B passt bei 1024×768 und 1080×810 erst nach dem Scrollen

<details>
<summary>Technischer Bericht</summary>

- __Date:__ 2026-10-28
- __Material:__ README.md → ## Erkunden: Ein Stein voller Lithium
- __Result:__ PASS
- __Mode:__ course

**Content:**
- Lernziel 2 (Lithium-Mineral anhand von Fotos und Merkmalen bestimmen) durch Steckbrief, drei Minerale und Bestimmungsquiz abgedeckt
- Sachaussagen zu Mineralmerkmalen und Härte mit Wikipedia abgeglichen (als Auszug gelesen) und angepasst; Entscheidungen vom 28.10.2026 ✅
- Geplantes Vorher/Nachher-Bildpaar eines Dünnschliffs (normales und polarisiertes Licht): kein freies Bildpaar gefunden; stattdessen ein Einzelbild in polarisiertem Licht

**Type Consistency:**
- Session Type: kostprobe — Required: Verortung am Anfang und Ende ✅; interaktive Aufgabe mit Rückmeldung (Bestimmungsquiz) ✅; Verweis auf hybrides/reales Angebot und Studiengang ✅; Partner-Kasten ✅

**Method Consistency:**
- Session Method: udl — Required: zwei Darstellungsformen (Text, Fotos, Diagramm, 3D) ✅; zweite Form, Verständnis zu zeigen (Freitext) ✅; Alternativtexte, einfache Sprache ✅

**Persona & Style:**
- lockeres Du, jedes Fachwort erklärt (Mineral, Glimmer, Mohs-Skala) ✅

**LiaScript Syntax:**
- check-material: keine Antwortmuster, Tipps vorgelesen; Hinweis auf große Wikimedia-Bilder (die Vorlage lädt 1280 px breite Vorschauen)

**Unit entry (journal):**
- Inhalt und Bausteine-Zeile an das Material angepasst (kein Dünnschliff-Bildpaar, 3D-Modell statt zoombarem Bild)

**Duration (advisory):** Schätzung 11 min vs. 10 min – im Rahmen (Extra zusätzlich etwa 2 min)

**Reference Check:** nicht mit reference-checker geprüft; sechs Wikipedia-Artikel als Auszug gelesen, Aussagen daran angepasst

**Templates:** Wikimedia, Wictionary, three.js im Kopf eingebunden ✅

**Recommended Actions:**
1. Die Etappe in der Ansicht der Schülerinnen ansehen und freigeben (`:preview 2`)
2. Optional: die Steckbriefe von der Mineralogie gegenlesen lassen

</details>

</section>

### 3. Umwandeln: Lithium aus Erz und Altbatterie

<!-- class="journal-actions" -->
[👁 So sehen es die Schülerinnen](agent:teaching/preview?file=3) `:preview 3`

<details>
<summary>Technische Einstellungen und weitere Aktionen</summary>

**Type:** kostprobe

**Method:** udl

[✏️ Gemeinsam überarbeiten](agent:teaching/coauthor-materials?number=3) `:coauthor-materials 3` · [✏️ Kleine Korrektur](agent:teaching/quick-fix?number=3) `:quick-fix 3 <was?>`

</details>

<!-- data-key="kind" -->
**Art:** Kostprobe

<!-- data-key="summary" -->
**Zusammenfassung:**

Wie wird aus Erz oder Altbatterie wieder ein Wertstoff? Die Laugung wird mit einem Alltagsbild eingeführt („wie Tee ziehen lassen“). Danach bedienen die Schülerinnen eine Simulation mit Beispiel-Messwerten.

Stolperstein: Die Daten sind keine echten Messungen und werden so gekennzeichnet.

<!-- data-key="content" -->
**Inhalt:**

- Verortung: davor Gewinnen bzw. Sortieren, danach Nutzen
- Laugung: Erz zerkleinern und rösten, mit Schwefelsäure aufschließen, Lithiumcarbonat mit Soda ausfällen (Ionen-Gleichung); Schwarzmasse aus alten Akkus
- Einflussgrößen Temperatur und Zeit; Faustregel der RGT-Regel (doppelt bis viermal so schnell, das Modell rechnet mit doppelt)
- Studiengänge Chemie und Angewandte Naturwissenschaft
- Verweis auf „Laugung live mit Messwerten“ (Idee) und das Chemielabor (Lernort)
- Bausteine: Kern – Periodensystem als Einstieg, Reaktionsgleichung mit Gefahrensymbol, Laugungs-Simulation mit Schieberegler · Extra für Neugierige – Messwerte-Tabelle mit Formeln zum Selbstrechnen, Recycling-Rechner (Schieberegler → Diagramm, gekennzeichnete Beispielrechnung)

<!-- data-key="activities" -->
**Aktivitäten:**

1. Simulation: Temperatur per Schieberegler ändern und die Kurve beobachten
2. Quiz: Welche Aussage passt zur Kurve?
3. Mia fragt: Warum lohnt sich das Recycling von Altbatterien? (kurze Antwort)

<!-- data-key="decisions" -->
**Entscheidungen:**

- **28.10.2026:** Verfahrensschritte an Wikipedia angeglichen: zerkleinert, geröstet, mit Schwefelsäure aufgeschlossen, Lithium geht als Salz in Lösung; „weißer Feststoff“; bei der Schwarzmasse wird Lithium als Lithiumcarbonat zurückgewonnen.
- **28.10.2026:** Reaktionsgleichung in der belegten Ionen-Form 2 Li⁺ + Na₂CO₃ → Li₂CO₃ + 2 Na⁺ statt der Lithiumsulfat-Form.
- **28.10.2026:** Faustregel nach der RGT-Regel: „doppelt bis viermal so schnell – unser Modell rechnet mit doppelt“.
- **28.10.2026:** Schlusssatz des Recycling-Rechners beschreibt nur noch, was das Beispiel zeigt.

<!-- data-key="references" -->
**Quellen:**

1. Ideenpapier „MINT meets MONTAN“ v2, Abschnitt 5
2. Wikipedia: [Lithium](https://de.wikipedia.org/wiki/Lithium), [Lithiumcarbonat](https://de.wikipedia.org/wiki/Lithiumcarbonat), [Batterierecycling](https://de.wikipedia.org/wiki/Batterierecycling), [Schwefelsäure](https://de.wikipedia.org/wiki/Schwefels%C3%A4ure), [RGT-Regel](https://de.wikipedia.org/wiki/RGT-Regel) – im Kurs auf der Seite „Quellen“
3. Beispieldaten: ausgedacht, im Kurs als Beispiel gekennzeichnet

#### Prüfbericht – Etappe 3

<section data-key="validation-report">

**Ergebnis:** bestanden – wartet auf deine Freigabe (28.10.2026)

**Jetzt mit den Schülerinnen nutzbar:** ja

**Was funktioniert:**

- „Simulation: Mach es wärmer!“: Schieberegler verändert die Kurve live – im Browser ausprobiert
- „Laugung – wie Tee ziehen lassen“: Reaktionsgleichung mit tiefgestellten Zahlen, Gefahrensymbol, anklickbares Fachwort „Säure“ – im Browser angesehen
- „Extra: Messwerte selbst auswerten“: Tabelle rechnet die Ausbeute mit Formeln – im Browser ausprobiert
- „Extra: Der Recycling-Rechner“: Regler und Diagramm reagieren – im Browser ausprobiert
- Quizfragen ohne Antwortmuster, Tipps vorgelesen; Verortung, Verweise und Partner-Kasten vorhanden
- Bei der Kursprüfung korrigiert: Der Tipp auf „Was zeigt die Kurve?“ nennt jetzt die Seite „Simulation: Mach es wärmer!“; im Journal-Eintrag die Quelle „Beispieldaten“ ohne Aufgabe formuliert
- Bei der Prüfung geändert: Verfahrensschritte, Ionen-Gleichung (im Browser angesehen: Ladungen hoch-, Zahlen tiefgestellt), Faustregel und Schlusssatz des Rechners nach Wikipedia; Belege für Etappe 3 auf der Seite „Quellen“ – danach gerenderte Prüfung ohne neue Befunde

**Noch offen:**

- nichts – die Etappe wartet nur auf deinen Blick in die Ansicht der Schülerinnen
- Hinweis: Die Belege stammen aus Wikipedia; eine Durchsicht durch die Technische Chemie bleibt sinnvoll, bevor die Demo rausgeht

<details>
<summary>Technischer Bericht</summary>

- __Date:__ 2026-10-28
- __Material:__ README.md → ## Umwandeln: Lithium aus Erz und Altbatterie
- __Result:__ PASS
- __Mode:__ course

**Content:**
- Lernziel 3 (Beispiel-Messwerte ablesen, Einflussgröße begründen) durch Simulation und zwei Quizfragen abgedeckt
- Sachaussagen zur Chemie mit Wikipedia abgeglichen (als Auszug gelesen) und angepasst; Entscheidungen vom 28.10.2026 ✅
- Geplantes Vorher/Nachher von Altbatterie und Schwarzmasse entfallen: kein passendes freies Bildpaar gefunden

**Type Consistency:**
- Session Type: kostprobe — Required: Verortung am Anfang und Ende ✅; interaktive Aufgabe mit Rückmeldung (Simulation und Quiz) ✅; Verweis auf hybrides/reales Angebot und Studiengänge ✅; Partner-Kasten ✅

**Method Consistency:**
- Session Method: udl — Required: zwei Darstellungsformen (Text, Gleichung, Simulation) ✅; zweite Form, Verständnis zu zeigen (Freitext „Mia fragt“) ✅; Alternativtexte, einfache Sprache ✅

**Persona & Style:**
- Alltagsbild „Tee ziehen lassen“ vor dem Fachbegriff, lockeres Du ✅

**LiaScript Syntax:**
- check-material: keine Fehler auf diesen Folien

**Unit entry (journal):**
- Bausteine-Zeile angepasst (Vorher/Nachher entfallen)

**Duration (advisory):** Schätzung 12 min vs. 10 min – im Rahmen (Extras zusätzlich etwa 5 min)

**Reference Check:** nicht mit reference-checker geprüft; fünf Wikipedia-Artikel als Auszug gelesen, Aussagen daran angepasst

**Templates:** ChemmacrosJS, JSXGraph, PeriodicTable im Kopf eingebunden ✅; SpreadSheet nicht als Vorlage, sondern jspreadsheet 4.13.4 direkt über jsDelivr mit eigenem Makro `@tabelle` (die Vorlage blockierte das Laden etwa 30 s, Version 5 rechnete keine Formeln)

**Recommended Actions:**
1. Die Etappe in der Ansicht der Schülerinnen ansehen und freigeben (`:preview 3`)
2. Optional: Verfahren und Gleichung von der Technischen Chemie gegenlesen lassen

</details>

</section>

### 4. Sortieren: Ein Roboter lernt trennen

<!-- class="journal-actions" -->
[👁 So sehen es die Schülerinnen](agent:teaching/preview?file=4) `:preview 4`

<details>
<summary>Technische Einstellungen und weitere Aktionen</summary>

**Type:** kostprobe

**Method:** udl

[✏️ Gemeinsam überarbeiten](agent:teaching/coauthor-materials?number=4) `:coauthor-materials 4` · [✏️ Kleine Korrektur](agent:teaching/quick-fix?number=4) `:quick-fix 4 <was?>`

</details>

<!-- data-key="kind" -->
**Art:** Kostprobe

<!-- data-key="summary" -->
**Zusammenfassung:**

Warum muss sortiert werden, und wie „sieht“ ein Roboter? Ein simuliertes Förderband mit Gegenständen wird über eine kleine Regel im Code sortiert.

Stolperstein: Programmieren ist für viele neu. Deshalb wird eine Regel nur ergänzt, mit Hinweis, und nicht von Grund auf geschrieben.

<!-- data-key="content" -->
**Inhalt:**

- Verortung: davor Nutzen (der Akku ist alt), danach Zurückführen bzw. Umwandeln
- Warum Akkus früh aussortiert werden müssen: Brandgefahr in Recyclinganlagen (belegtes Beispiel aus der Schweiz), wertvolles Lithium
- Wie Sortieranlagen Teile erkennen (Sensoren, maschinelles Aussortieren); der Roboter als vereinfachtes Beispiel
- Sensor-Merkmale als Daten; das Stahlgehäuse des Akkus als Annahme des Beispiels
- Eine Regel als Code
- Studiengänge Angewandte Informatik und Robotik
- Verweis auf „Sortierroboter aus der Ferne“ (Idee) und das Robotiklabor in der Reichen Zeche (Lernort)
- Bausteine: Kern – Blöcke mit Roboter-Befehlen, Förderband als animiertes SVG · Extra für Neugierige – Sensor-Streudiagramm mit Schwellwert-Regler (zeigt falsch Einsortiertes), simuliertes Arduino mit Sensor und Servo

<!-- data-key="activities" -->
**Aktivitäten:**

1. Code-Aufgabe: eine Bedingung ergänzen, ausführen und das sortierte Band sehen
2. Quiz: Welcher Gegenstand landet mit der ursprünglichen Regel falsch?

<!-- data-key="decisions" -->
**Entscheidungen:**

- **28.10.2026:** Brandgefahr mit belegtem Beispiel statt „Müllpresse“: 2023 zwölf Brände in Schweizer Recyclingbetrieben (Wikipedia „Lithium-Ionen-Akkumulator“).
- **28.10.2026:** Stahlgehäuse des Akkus als Annahme des Beispiels formuliert – für die allgemeine Aussage fand sich kein Beleg.
- **28.10.2026:** „In modernen Sortieranlagen helfen Roboter“ ersetzt durch Sensoren und maschinelles Aussortieren; der Roboter ist ausdrücklich ein vereinfachtes Beispiel.

<!-- data-key="references" -->
**Quellen:**

1. Ideenpapier „MINT meets MONTAN“ v2, Abschnitt 5
2. Wikipedia: [Lithium-Ionen-Akkumulator](https://de.wikipedia.org/wiki/Lithium-Ionen-Akkumulator), [Sensor-based sorting (englisch)](https://en.wikipedia.org/wiki/Sensor-based_sorting) – im Kurs auf der Seite „Quellen“

#### Prüfbericht – Etappe 4

<section data-key="validation-report">

**Ergebnis:** bestanden – wartet auf deine Freigabe (28.10.2026)

**Jetzt mit den Schülerinnen nutzbar:** ja

**Was funktioniert:**

- „Programmiere die Sortierweiche“: eigene Roboter-Blöcke, Förderband-Animation und automatische Prüfung – im Browser ausprobiert: mit der vorgegebenen Regel landen beide Akkus im Schrott und die Prüfung meldet den Fehler; mit der Akku-Regel ganz oben ist alles richtig sortiert („Geschafft!“)
- „Extra: Reicht ein Sensor?“: Schwellen-Regler und Streudiagramm reagieren – im Browser ausprobiert
- „Extra: Die Weiche im echten Labor“: Arduino-Code wird übersetzt und läuft – im Browser ausprobiert
- Quiz „Was ging schief?“ ohne Antwortmuster, Tipp vorgelesen; Verortung, Verweise und Partner-Kasten vorhanden
- Bei der Kursprüfung korrigiert: Der Tipp auf „Was ging schief?“ nennt jetzt die Seite „Wie ein Roboter ‚sieht‘“; Aufgabentexte nennen den Knopf mit seinem sichtbaren Symbol `</>` (Ausführen) statt „▶“; im Journal-Eintrag „Sortenreinheit“ durch den tatsächlichen Inhalt ersetzt

- Bei der Prüfung geändert: Brandgefahr mit belegtem Beispiel, Stahlgehäuse als Annahme des Beispiels, Sortieranlagen nach dem Beleg zur sensorgestützten Sortierung; Belege für Etappe 4 auf der Seite „Quellen“ – danach gerenderte Prüfung ohne neue Befunde

**Noch offen:**

- nichts – die Etappe wartet nur auf deinen Blick in die Ansicht der Schülerinnen

<details>
<summary>Technischer Bericht</summary>

- __Date:__ 2026-10-28
- __Material:__ README.md → ## Sortieren: Ein Roboter lernt trennen
- __Result:__ PASS
- __Mode:__ course

**Content:**
- Lernziel 4 (vorgegebene Sortierregel ergänzen und testen) durch die geprüfte Blockly-Aufgabe abgedeckt
- Sachaussagen mit Wikipedia abgeglichen (als Auszug gelesen); Brandgefahr belegt, Stahlgehäuse als Annahme gekennzeichnet; Entscheidungen vom 28.10.2026 ✅

**Type Consistency:**
- Session Type: kostprobe — Required: Verortung am Anfang und Ende ✅; interaktive Aufgabe mit Rückmeldung (Blockly mit Prüfung) ✅; Verweis auf hybrides/reales Angebot und Studiengänge ✅; Partner-Kasten ✅

**Method Consistency:**
- Session Method: udl — Required: zwei Darstellungsformen (Tabelle, Blöcke, Animation) ✅; zweite Form, Verständnis zu zeigen (Quiz und Freitext „Warum ganz oben?“) ✅; Alternativtexte, einfache Sprache ✅

**Persona & Style:**
- Einstieg über die Gefahr im Müll („Sinn statt Technik“), lockeres Du ✅

**LiaScript Syntax:**
- check-material: keine Fehler auf diesen Folien; der Button heißt „Ausführen“ – der Aufgabentext nennt ihn so

**Unit entry (journal):**
- beschreibt das Material wie vorhanden ✅

**Duration (advisory):** Schätzung 11 min vs. 10 min – im Rahmen (Extras zusätzlich etwa 5 min)

**Reference Check:** nicht mit reference-checker geprüft; zwei Wikipedia-Artikel (deutsch und englisch) als Auszug gelesen, Aussagen daran angepasst

**Templates:** BlocklyCode und AVR8js im Kopf eingebunden ✅; eigene Blöcke `band_regel` und `band_start` im `@onload` des Kurses

**Recommended Actions:**
1. Die Etappe in der Ansicht der Schülerinnen ansehen und freigeben (`:preview 4`)

</details>

</section>

### 5. Dein Weg

<!-- class="journal-actions" -->
[👁 So sehen es die Schülerinnen](agent:teaching/preview?file=5) `:preview 5`

<details>
<summary>Technische Einstellungen und weitere Aktionen</summary>

**Type:** orientierung

**Method:** udl

[✏️ Gemeinsam überarbeiten](agent:teaching/coauthor-materials?number=5) `:coauthor-materials 5` · [✏️ Kleine Korrektur](agent:teaching/quick-fix?number=5) `:quick-fix 5 <was?>`

</details>

<!-- data-key="kind" -->
**Art:** Orientierung

<!-- data-key="summary" -->
**Zusammenfassung:**

Rückblick auf den Weg des Lithiums. Die Karte zeigt jetzt alle Angebote im Netz, als Ideen gekennzeichnet. Mia erzählt ihren eigenen Weg ins Studium (fiktiv).

Stolperstein: Die Etappe darf nicht nach Werbung klingen. Im Mittelpunkt steht, was die Schülerin selbst gewählt hat.

<!-- data-key="content" -->
**Inhalt:**

- Netz-Karte mit Beispielangeboten real, hybrid und digital
- Studiengänge je Station
- Nächster Schritt als offene Frage: ein Kurs, ein Besuch oder eine Frage an eine Studentin
- Hinweiskasten: Im Projekt würden Wege pseudonym erfasst. In der Demo werden keine Daten gesammelt.
- Bausteine: Kern – Gruppenchat fiktiver Studentinnen, Netz der Angebote als Diagramm · Extra für Neugierige – Wege durch das Netz als Flussdiagramm, „Frag die Landkarte“ (Wissensgraph, vor allem für die Partner)

<!-- data-key="activities" -->
**Aktivitäten:**

1. Zuordnung: Geologie/Mineralogie → Erkunden · Chemie → Umwandeln · Angewandte Informatik → Sortieren
2. Umfrage: Welche Station würdest du weiter erkunden?
3. Reflexion: Was wäre dein nächster Schritt?

<!-- data-key="references" -->
**Quellen:**

1. Ideenpapier „MINT meets MONTAN“ v2, Abschnitte 2–4 und Abb. 2

#### Prüfbericht – Etappe 5

<section data-key="validation-report">

**Ergebnis:** bestanden – wartet auf deine Freigabe (28.10.2026)

**Jetzt mit den Schülerinnen nutzbar:** ja

**Was funktioniert:**

- „Im Gruppenchat“: die Nachrichten erscheinen nacheinander, alle Personen als ausgedacht gekennzeichnet – im Browser angesehen
- „Das Netz der Angebote“: Diagramm mit drei Spalten, eine pro Station – im Browser angesehen
- „Extra: Frag die Landkarte“: die Abfrage liefert die drei Angebote zur Chemie – im Browser ausprobiert
- „Extra: Wege durch das Netz“: Flussdiagramm aus einer Tabelle, als ausgedachte Zahlen gekennzeichnet
- Zuordnung, Umfrage und Reflexion; Partner-Kasten mit Hinweis, dass die Demo keine Daten sammelt und eine Internetverbindung braucht
- Bei der Kursprüfung korrigiert: „Frag die Landkarte“ nennt den Knopf mit seinem sichtbaren Symbol `</>` (Ausführen); im Journal-Eintrag die nächsten Schritte so beschrieben, wie sie im Material stehen

**Noch offen:**

- nichts – die Etappe wartet nur auf deinen Blick in die Ansicht der Schülerinnen

<details>
<summary>Technischer Bericht</summary>

- __Date:__ 2026-10-28
- __Material:__ README.md → ## Dein Weg
- __Result:__ PASS
- __Mode:__ course

**Content:**
- Lernziel 5 (passende Stationen und Studiengänge benennen) durch Zuordnung, Umfrage und Reflexion abgedeckt
- Nur Studiengänge aus dem Antrag; alle Personen und Zahlen als ausgedacht gekennzeichnet ✅

**Type Consistency:**
- Session Type: orientierung — Required: Kreislauf-Landkarte (Verortung aller Stationen, Netz-Diagramm) ✅; Umfrage oder Reflexion ✅; Partner-Kasten ✅

**Method Consistency:**
- Session Method: udl — Required: zwei Darstellungsformen (Chat, Diagramme) ✅; zweite Form, Verständnis zu zeigen (Reflexion) ✅; einfache Sprache ✅

**Persona & Style:**
- kein Werbeton; die Schülerin entscheidet selbst ✅

**LiaScript Syntax:**
- check-material: keine Fehler auf diesen Folien; Flussdiagramm nach dem Test umgedreht (`data-transpose`)

**Unit entry (journal):**
- beschreibt das Material wie vorhanden ✅

**Duration (advisory):** Schätzung 10 min vs. 10 min – im Rahmen (Extras zusätzlich etwa 5 min)

**Reference Check:** nicht geprüft – keine Literaturangaben im Material

**Templates:** Chat-Simulation, Mermaid, Comunica im Kopf eingebunden ✅

**Recommended Actions:**
1. Die Etappe in der Ansicht der Schülerinnen ansehen und freigeben (`:preview 5`)

</details>

</section>

---

## Agents – Assistenten

<!-- class="journal-actions" -->
[▶️ Assistenten anpassen](agent:teaching/configure-agent) `:configure-agent <agent>` · [▶️ Neues Lernendenprofil](agent:teaching/create-learner-persona) `:create-learner-persona`

<!--- Read-scope rule: Coauthor and specialist agents are direct ### subsections; each agent reads only its assigned subsection. --->

_Projektbezogene Einstellungen der Assistenten und Lernendenprofile._

<section>

### Coauthor

_Regeln für das Schreiben des Materials: Stimme der Begleitfigur, Hinweise, Grenzen._

* __Customization Status:__ active
* __Role / Persona:__
  Mia, fiktive Studentin der Angewandten Naturwissenschaft in Freiberg, führt als Wegbegleiterin durch den Rundgang – neugierig, ehrlich, gibt zu, dass sie früher selbst keine Ahnung hatte; einmal sichtbar als ausgedachte Figur gekennzeichnet. <!-- data-from="didactics" -->
* __Behavior Additions:__
  1. Jede Etappe beginnt und endet mit der Kreislauf-Verortung: Wo sind wir, was kommt davor, was danach? <!-- data-from="didactics" -->
  2. Einstieg über eine Frage mit Alltagsbezug („Sinn statt Technik“), erst dann Fachliches. <!-- data-from="didactics" -->
  3. Jede Etappe endet mit einem optisch abgesetzten Hinweiskasten „Für die Projektpartner“: Bezug zum Antrag und was LiaScript hier zeigt. <!-- data-from="didactics" -->
  4. Jede Etappe nutzt mindestens zwei Darstellungsformen und eine zweite Möglichkeit, Verständnis zu zeigen, die über das Quiz hinausgeht. <!-- data-from="didactics" -->
* __Preferred Interaction Style:__
  Lockeres Du, kurze Sätze, jedes Fachwort mit einem Alltagsbild eingeführt, keine „Mädchen“-Etiketten. <!-- data-from="didactics" -->
* __Project-Specific Rules:__
  1. Beispieldaten und geplante Angebote werden als „Beispiel“ bzw. „Idee“ gekennzeichnet. <!-- data-from="didactics" -->
  2. Keine erfundenen TUBAF-Angebote, Personen oder Zahlen. <!-- data-from="didactics" -->
  3. Studiengänge nur aus dem Antrag: Geologie/Mineralogie, Chemie, Angewandte Naturwissenschaft, Angewandte Informatik, Robotik. <!-- data-from="didactics" -->
  4. Nichts Vertrauliches aus dem Ideenpapier (angefragte Partner, Zusagen, TODOs). <!-- data-from="didactics" -->
  5. 10 Minuten pro Etappe, eine einzige Kursdatei. <!-- data-from="didactics" -->
* __Persona Voice Sample:__
  „Hey, ich bin Mia. Ehrlich gesagt hab ich mich früher nie gefragt, wo das Lithium in meinem Handy-Akku herkommt. Heute weiß ich: Bevor es in deinem Akku landet, steckte es in einem Stein – und wenn der Akku kaputt ist, kann es zurück in den Kreislauf. Genau diesen Weg gehen wir jetzt zusammen. Du musst nichts vorher wissen, probier einfach aus.“ <!-- data-from="didactics" -->
* __Boundaries / Never:__
  1. Die Grundregeln für Ablauf, Prüfung, Sicherheit und Quellen nicht außer Kraft setzen.

### Teaching-Agent

* __Customization Status:__ inactive
* __Behavior Additions:__
  1. keine
* __Preferred Interaction Style:__
  keine
* __Project-Specific Rules:__
  1. keine
* __Boundaries / Never:__
  1. Die Grundregeln für Ablauf, Prüfung, Sicherheit und Quellen nicht außer Kraft setzen.

### Artist-Agent

* __Customization Status:__ inactive
* __Behavior Additions:__
  1. keine
* __Preferred Visual Priorities:__
  keine
* __Project-Specific Rules:__
  1. keine
* __Boundaries / Never:__
  1. Die Grundregeln für einheitliche Gestaltung, Barrierefreiheit und Unsicherheit nicht außer Kraft setzen.

### Development-Agent

* __Customization Status:__ inactive
* __Behavior Additions:__
  1. keine
* __Preferred Publishing Workflow:__
  keine
* __Project-Specific Rules:__
  1. keine
* __Boundaries / Never:__
  1. Prüfschwellen, Git-Sicherheit und Veröffentlichungsprüfungen nicht außer Kraft setzen.

</section>

### Learner Personas – Lernendenprofile

<!--- Optional — filled by :create-learner-persona. One `#### Persona: {icon} {name}` subsection per persona (structure: tasks/create-learner-persona.md). --->

_Noch keine Lernendenprofile._

---

## Validation – Prüfung

<!--- Replaced by :validate-course (course mode). The ### Latest Validation Summary below is the authoritative publishing gate — publishing requires `Mode: course` and `Result: PASS`. Per-session reports live in ## Sessions → #### Validation Report, not here. The action line is added by update-dashboard once every unit has material. --->

### Latest Validation Summary – Letzte Kursprüfung

<!--- Filled by :validate-course (course mode), 2026-10-28. --->

- Date: 2026-10-28
- Mode: course
- Result: PASS
- Issues found: 0
- Mechanical open: 0
- Sessions checked: 5

<!-- data-key="course-findings" -->
**Befunde für den ganzen Kurs:**

- **Grundlagen:** ✅ Kursrahmen, Gliederung, Didaktik (mit Rahmenmodell und Standardmethode), Assistenten vollständig; eine Kursdatei wie angegeben
- **Vorlagen:** ✅ alle 13 Vorlagen im Kopf von Journal und Kurs eingebunden, keine Steckbriefe offen, keine Einbindung aus ausgeschlossenen Pfaden; Hinweis: Pannellum und jspreadsheet laufen direkt über jsDelivr mit eigenen Makros `@panorama` und `@tabelle` im Kurskopf
- **Zeitplan:** übersprungen – kein Zeitplan, mit dem Kursrahmen entschieden
- **Etappen-Fortschritt:** ✅ alle 5 Etappen mit Material und fertig geprüft
- **Material:** Etappe 1 – Die Landkarte: ✅ · Etappe 2 – Erkunden: ✅ · Etappe 3 – Umwandeln: ✅ · Etappe 4 – Sortieren: ✅ · Etappe 5 – Dein Weg: ✅; alle Sachaussagen mit Wikipedia belegt und auf der Seite „Quellen“ nachgewiesen (Entscheidungen vom 28.10.2026 in den Etappen)
- **Stimmigkeit:** ✅ „Etappe“ durchgehend verwendet, Mias Ton einheitlich, jedes Lernziel in seiner Etappe wiederzufinden, Nummerierung lückenlos; Hinweis: ein JavaScript-Fehler ohne Folienzuordnung (vermutlich aus einer Vorlage, ohne sichtbare Folge)

<!-- data-key="recommended-actions" -->
**Empfohlene Schritte:**
1. Die fünf Etappen in der Ansicht der Schülerinnen ansehen und freigeben (`:preview README.md`)
2. Optional: Etappe 2 der Mineralogie und Etappe 3 der Technischen Chemie zum Gegenlesen schicken
3. Zum Veröffentlichen: eine Kontaktadresse für den Kurskopf festlegen, dann `:agent development` → `:create-project`

---

## Publishing – Veröffentlichung

<!--- Maintained by the Development-Agent (:create-project, :update-project): read from the repository before anything is published. The dashboard shows it. __State:__ stays an English key. --->

* __Repository:__ https://github.com/LiaPlayground/mint-meets-montan-demo
* __Branch:__ main
* __Viewer URL:__ https://liascript.github.io/course/?https://raw.githubusercontent.com/LiaPlayground/mint-meets-montan-demo/main/README.md
* __State:__ published on 2026-10-28 (commit 8c43e1c)

---

## Analysis Status – Analysestand

<!--- Filled by :analyze-existing. --->

_Nur nötig, wenn ein bestehender Kurs überarbeitet wird._

---

## Notes Backup – Notizen

<!-- class="journal-actions" -->
[▶️ Notizen sichern](agent:teaching/save-notes) `:save-notes` · [▶️ Entscheidung festhalten](agent:teaching/save-decision) `:save-decision <title>`

<!--- Appended to by :save-notes and :save-decision from templates/note-backup.yaml. Each note is one append-only `### {Type, in the course language}: {Descriptive Title} ({YYYY-MM-DD})` subsection. --->

_Noch keine Notizen._
