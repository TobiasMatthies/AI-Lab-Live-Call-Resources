---
name: call-zusammenfassung
description: Erstellt eine neue Zusammenfassung eines KI-Lab Livecalls unter docs/ im Stil der bestehenden Zusammenfassungen. Verwenden, wenn der User Notizen, Links oder Bilder zu einem Call liefert und eine Dokumentation dazu möchte.
---

# Call-Zusammenfassung erstellen

Erstelle aus den Notizen des Users eine neue Datei `docs/YYYY-MM-DD.md` (Datum des Calls; wenn nicht genannt, heutiges Datum). Sprache: Deutsch.

## Vorgehen

1. Lies `README.md` und die neueste Datei in `docs/` als Stilvorlage (z. B. `docs/2026-11-02.md`).
2. Nutze nur Inhalte aus den Notizen des Users. Erkläre nichts dazu, was die Notizen nicht hergeben. Wenn eine Beschreibung fehlt, bleib bei den Namen oder frag nach.
3. Bilder gehören nach `docs/images/` und werden relativ eingebunden: `![Beschreibung](images/datei.png)`. Verschiebe lose Bilder dorthin.
4. Schreibe die Datei nach der Struktur unten.
5. Füge den neuen Call in der README nur hinzu, wenn dort eine Liste der Calls geführt wird. Aktuell verlinkt sie nur den Ordner `docs/`.
6. Committe nur, wenn der User es verlangt.

## Struktur

```markdown
# Livecall DD.MM.YYYY: Titel

## Worum ging es?
Zwei bis drei Sätze. Die Kurzzusammenfassung des Users sinngemäß übernehmen. Ein Bild kann hier stehen.

## Was wir gemacht haben
Nummerierte Liste, pro Punkt ein Thema in **Fett**, Details als kurze Unterpunkte oder Halbsätze.

## Links
Tabelle mit den Spalten "Thema" und "Link".

## So kannst du es nachmachen
Drei bis vier nummerierte Schritte zum Selbstausprobieren, mit den Links aus der Tabelle.
```

## Stilregeln

- Kurz und knapp. Keine Tabellen für Inhalte außer für die Links. Keine langen Erklärtexte.
- Einzelne Punkte in einem Satz oder Halbsatz.
- Fachbegriffe (Harness, Tool-Call, Slash-Commands) in **Fett** bei der ersten Nennung, Befehle und Dateinamen in `Code`.
- Ton: "wir" für den Call, "du" in "So kannst du es nachmachen".
