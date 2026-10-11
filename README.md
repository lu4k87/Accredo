# ACCREDO · Reakkreditierungs- & PO-Novellierungsprozess

Interaktive Scrollytelling-Webseite zur schrittweisen Visualisierung eines Hochschul-Reakkreditierungs- und Prüfungsordnungsprozesses (SPO).

## Highlights & Features
- **Scrollytelling & Step-by-Step Motion (soft-motion):**
  - Beim Scrollen wird der Prozess Schritt für Schritt animiert und visualisiert.
  - Sticky Visualizer links mit synchron mitwachsender Progress-Rail (`--ease-out`, einmaliger Ring beim Phasenwechsel, keine Hektik).
  - Karten-Inhalte blenden beim ersten Erscheinen gestaffelt ein, Übergabe-Gates mit einmaligem Lichtstreif; `prefers-reduced-motion` zeigt sofort den Endzustand.
  - Klick auf Meilensteine scrollt sanft zur jeweiligen Phase.
- **Rollen & Zuständigkeiten (RACI):**
  - Live-Radar im Sticky-Panel zeigt für jeden Schritt die verantwortlichen Akteure (Responsible, Accountable, Consulted, Informed) mit Avataren und Positionen.
  - Rollen-Karten der Phasen nennen die RACI-Rolle im Klartext (Durchführung, Verantwortung, Beratung, Information).
  - Filterbare Perspektiven: Studiengangsleitung, Qualitätsmanagement, Prüfungsausschuss, Fakultätsrat, Gutachtergruppe.
- **Übergabedokumente (.pdf) & Handover-Gates:**
  - 14 realistische Artefakte (Evaluationsberichte, Satzungsentwurf SPO v2.0, Modulhandbuch, Rechtsgutachten, Fakultätsratsbeschluss, Akkreditierungsdossier, Peer-Gutachten, Akkreditierungsurkunde).
  - Jedes Dokument kann per Klick geöffnet werden: Zeigt Metadaten, Versionsstand, SHA-256 Hash, Freigabekette und formatierte Inhaltsauszüge.
- **Zentrale Deliverables-Matrix:**
  - Umschaltung zwischen Scrollytelling-Ablauf und tabellarischer Übergabe-Matrix mit Volltext-Suche.
- **Theme-Support:**
  - Light Mode (Default, Look „Klar“: Navy-Tinte + Königsblau, Status/RACI/Gates vollflächig) & Dark Mode, Texte mit Kontrast ≥ 7:1.
  - Zero-Dependency: Funktioniert lokal vollständig offline ohne externe CDNs oder Internetzugang.

## Starten & Betrachten
Einfach die Datei direkt im Browser öffnen:
```bash
# Direkt im Standard-Browser:
xdg-open __Project_accredo/index.html

# Oder per lokalem Webserver:
python3 -m http.server 8090 --directory __Project_accredo/
# Dann aufrufen: http://localhost:8090
```
