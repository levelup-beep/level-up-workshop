# Level Up Workshop

Workshop-Seite für **Level Up, Ladies!** — KI-Power für Frauen in Job, Business und Alltag.

**Live:** https://levelupladies.de/level-up-workshop/

Die Seite begleitet den Workshop und lässt sich danach selbstständig durcharbeiten. Sie führt
durch drei Levels, alle Prompts sind direkt kopierbar.

| Level | Inhalt | Dauer |
|-------|--------|-------|
| 01 · Setup | Persönliche Präferenzen einrichten, damit Claude dich kennt | ca. 20 Min |
| 02 · Workflow | Masterprompt für eine wiederkehrende Aufgabe bauen und als Projekt anlegen | ca. 25 Min |
| 03 · Superpower | Artefakte nutzen und ein eigenes Tool bauen | ca. 20–35 Min |

Dazu FAQ und ein Handout zum Download.

## Inhalt des Repos

| Datei | Zweck |
|-------|-------|
| `index.html` | Die komplette Workshop-Seite, eine einzelne Datei ohne Abhängigkeiten außer Google Fonts |
| `handout-level-up-ladies_2.pdf` | Handout zum Ausdrucken, 7 Seiten, verlinkt unter „Downloads" |
| `.nojekyll` | Schaltet die Jekyll-Verarbeitung von GitHub Pages ab |

## Ändern

`index.html` ist eine einzelne statische Datei: HTML, CSS und JavaScript in einem Stück.
Bearbeiten, committen, pushen — GitHub Pages veröffentlicht die Änderung automatisch.

Das Handout wird nicht von Hand gebaut, sondern von `handout_2_build.py` erzeugt
(liegt im Arbeitsordner, nicht in diesem Repo). Dort stehen alle Texte und die URL,
die im Hinweis-Kasten auf Seite 2 erscheint.

## Verwandt

- Workshop-Seite für den Bildungsbereich: https://levelupladies.de/level_up_ladies/
- Landingpage: https://github.com/levelup-beep/levelup-beep.github.io

## Kontakt

Insa Riese und Mareike Kirch · riesekirch@gmail.com
