# Sensennacht: Update-Paket

Hier liegt nur die fertige Spieldatei für die Update-Funktion der Exe.

- `version.json`: aktuelle Version, Build-Nummer und Prüfsumme
- `index.html`: das Spiel

Die Exe fragt beim Start `version.json` ab. Ist die Build-Nummer höher als ihre eigene, lädt sie `index.html`, prüft die Prüfsumme und startet damit.
