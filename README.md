# Jass-Tafel (Coiffeur & Schieber)

Schreibtafel für Coiffeur und Schieber als eine einzige HTML-Datei (`index.html`). Läuft offline, die Schriften sind eingebettet.

## Benutzung

`index.html` im Browser öffnen (Chrome/Firefox). Der Spielstand wird im Browser gespeichert (localStorage), getrennt pro Gerät und Browser.

## Coiffeur – Wertung

- Pro Jassart tragen beide Teams ihre gemachten Punkte ein (0–157).
- Gewinn erst, wenn beide gespielt haben: Das bessere Team erhält **Differenz × Multiplikator**, das andere einen Strich.
- 157 Punkte → beim anderen Team sofort ein Strich.
- Misère: Gemachte Punkte eintragen, weniger gewinnt; 0 Punkte → beim anderen Team sofort ein Strich.
- Multiplikator = Position der Jassart (oberste ×1, …).

## Standard-Jassarten

Herz, Ecke, Kreuz, Schaufel, Misère, Obenabe, Undenufe, Slalom, 9-fach, 10-fach (×1–×10). Umschaltbar auf deutsche Karten (Rose, Schelle, Eichel, Schilte).

## Schieber

- Oben zwischen **Coiffeur** und **Schieber** umschalten. Jeder Modus hat seinen eigenen Spielstand; Teams und Design gelten für beide.
- Pro Runde: Trumpf wählen, Stichpunkte **eines** Teams eintippen – das andere erhält 157 minus diese Punkte. **Match**: 257 zu 0.
- Weis (Feld pro Team) und Stöck (20, Knopf pro Team).
- Trumpf-Multiplikator einstellbar (Standard: Herz/Ecke ×1, Kreuz/Schaufel ×2, Obenabe/Undenufe ×3). Weis und Stöck werden wahlweise mitmultipliziert.
- Zielpunkte frei einstellbar (Standard 2500). Sieger ist, wer das Ziel zuerst erreicht – innerhalb einer Runde in der Reihenfolge **Stöck, Weis, Stich**.
- Runden antippen zum Bearbeiten oder Löschen.

## Einstellungen

- Teams mit je zwei Spielern («Anna + Beat»)
- Jassarten hinzufügen, umbenennen, als Misère markieren, löschen, per Griff ⋮⋮ verschieben
- Designs: Teppich grün, hellgrün, rot, blau, schwarz, braun, creme, hellblau, hellgrau, hellrot, Schiefer
- Rückgängig ↶ / Wiederholen ↷
