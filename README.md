# ACCREDO · Reakkreditierungs- & PO-Novellierungsprozess

Interaktive Scrollytelling-Webseite zur schrittweisen Visualisierung eines Hochschul-Reakkreditierungs- und Prüfungsordnungsprozesses (SPO).

## Highlights & Features
- **Scrollytelling & Step-by-Step Motion (soft-motion):**
  - Beim Scrollen wird der Prozess Schritt für Schritt animiert und visualisiert.
  - Sticky Visualizer links mit synchron mitwachsender Progress-Rail (`--ease-out`, dezenter Glow, keine Hektik).
  - Klick auf Meilensteine scrollt sanft zur jeweiligen Phase.
- **Rollen & Zuständigkeiten (RACI):**
  - Live-Radar im Sticky-Panel zeigt für jeden Schritt die verantwortlichen Akteure (Responsible, Accountable, Consulted, Informed) mit Avataren und Positionen.
  - Filterbare Perspektiven: Studiengangsleitung, Qualitätsmanagement, Prüfungsausschuss, Fakultätsrat, Gutachtergruppe.
- **Übergabedokumente (.pdf) & Handover-Gates:**
  - 14 realistische Artefakte (Evaluationsberichte, Satzungsentwurf SPO v2.0, Modulhandbuch, Rechtsgutachten, Fakultätsratsbeschluss, Akkreditierungsdossier, Peer-Gutachten, Akkreditierungsurkunde).
  - Jedes Dokument kann per Klick geöffnet werden: Zeigt Metadaten, Versionsstand, SHA-256 Hash, Freigabekette und formatierte Inhaltsauszüge.
- **Zentrale Deliverables-Matrix:**
  - Umschaltung zwischen Scrollytelling-Ablauf und tabellarischer Übergabe-Matrix mit Volltext-Suche.
- **Theme-Support:**
  - Dark Mode (Default) & Light Mode, optimiert für Lesbarkeit und Kontraste.
  - Zero-Dependency: Funktioniert lokal vollständig offline ohne externe CDNs oder Internetzugang.

## Starten & Betrachten
Einfach die Datei direkt im Browser öffnen:
```bash
# Direkt im Standard-Browser:
xdg-open __Project_akkreditierung_prozess/index.html

# Oder per lokalem Webserver:
python3 -m http.server 8090 --directory __Project_akkreditierung_prozess/
# Dann aufrufen: http://localhost:8090
```
