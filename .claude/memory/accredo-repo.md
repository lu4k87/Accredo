---
name: accredo-repo
description: Accredo (Akkreditierungs-Scrollytelling) = eigenes Repo ~/__project_accredo (lu4k87/Accredo) neben dev_ws; subtree-Spiegelung überholt
metadata:
  type: reference
---

Projekt **Accredo** (Reakkreditierungs-/PO-Prozess, Scrollytelling-Seite) = eigenes Repo `git@github.com:lu4k87/Accredo.git`, lokal `~/__project_accredo/` neben dev_ws (seit 2026-10-12, Liste `config/projects.yaml`).
- Ändern: direkt dort committen + pushen; pre-push-Hook (`tools/pages_hook.sh`) veröffentlicht die Seite `https://lu4k87.github.io/accredo` (`tools/publish_pages.py` liest HEAD des Repos).
- Überholt: `git subtree split`/`commit-tree` aus `dev_ws/__project_accredo` (bis 2026-10-11).
- Ordner-Konvention: [[project-folder-prefix]].
