# Auswander-Check

Interaktiver Wizard für deutsche Familien, die strukturiert auswandern wollen.

→ Live: https://tabularasalife.github.io/auswander-check/

## Was es macht

Geführter Fragebogen mit 17 Profil-Fragen und 30+ themenspezifischen Vertiefungs-Fragen
(Pässe, Kinder/Schule, Wohnen, Banking, Steuern, Versicherungen, Haustier u.v.m.).

Auf Basis der Antworten wird per Zapier ein individuelles Ergebnis-Dokument bei
[Gamma](https://gamma.app) erzeugt und per E-Mail mit Link an den Nutzer geschickt
— inklusive Checkliste aller Todos und Hinweisen auf TRL-Beratungsthemen.

## Stack

- Single-File HTML (Vanilla JS, kein Build, keine Dependencies)
- Webhook: Zapier Catch Hook → Gamma Generate API → Gmail Send
- Hosting: GitHub Pages

## Maintained by

[Tabula Rasa Life](https://tabula-rasa.life) | Kirstin und Martin
