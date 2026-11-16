# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Überblick

Reines Dokumentations-Repository für die **KI-Lab Livecalls der Developer Akademie** (Schwerpunkt Agentic Software Development). Es gibt keinen Build, keine Tests und keinen Linter. Alle Inhalte sind Markdown auf **Deutsch**.

## Struktur

- `README.md`: Einstieg und Navigation (Tabelle "Wo finde ich was?"). Beim Anlegen neuer Ordner hier verlinken.
- `docs/YYYY-MM-DD.md`: Eine Zusammenfassung pro Call, Dateiname ist das Call-Datum.
- `docs/images/`: Alle Bilder der Zusammenfassungen. Einbindung relativ als `images/<datei>.png`.
- `projects/`: Geplant für Projekte aus den Calls (ein Ordner pro Projekt mit eigener README), existiert noch nicht.

## Neue Call-Zusammenfassung

Dafür gibt es den Skill `call-zusammenfassung` (`.claude/skills/call-zusammenfassung/`). Er legt Aufbau, Ton und Länge fest. Referenz für den Stil ist `docs/2026-11-02.md`.
