# BotC Scripts – Public Assets

Öffentliches Bild-Repository für Lyx' Blood-on-the-Clocktower-Homebrew-Scripts. Hier liegen Hintergrundbilder und Charakter-Icons, damit sie beim Import eines Scripts ins [Script Tool](https://script.bloodontheclocktower.com/) bzw. in Townsquare/Bloodstar per öffentlicher URL (`raw.githubusercontent.com`) geladen werden können.

## Struktur

Pro Script ein Ordner (kebab-case-Slug):

```
<script-slug>/
  background.jpg          # Hintergrundbild des Scripts (_meta.background)
  icons/
    <rolle>.png           # reguläres Alignment (Townsfolk/Outsider: gut · Minion/Demon: böse)
    <rolle>-b.png          # invertiertes Alignment "böse" (nur bei gutem Grundteam)
    <rolle>-g.png          # invertiertes Alignment "gut" (nur bei bösem Grundteam)
```

Jede Rolle hat also genau zwei Bild-Varianten (regulär + invertiert), referenziert im Script-JSON als `"image": [regulär, invertiert]`.

## Scripts

- **sprawl-requiem** – Shadowrun-Setting (Sixth World), Homebrew