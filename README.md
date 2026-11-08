# Bilder für Pull Requests von Haben

Vorher-/Nachher-Bilder für die Beschreibung von Pull Requests in [firsttris/haben](https://github.com/firsttris/haben), je Pull Request ein Ordner `pr-<n>/`. Ein eigenes Repository, damit die Bilder nicht in jedem Klon von Haben landen; Ablauf im Skill `pr-screenshots` dort.

- Nur Testdaten, nie echte Belege, Steuernummern, IBANs oder Zugangsdaten: Das Repository ist öffentlich.
- Nur neue Commits, kein Force-Push: Die Beschreibungen verlinken die Bilder über den Commit-SHA (`https://raw.githubusercontent.com/firsttris/haben-bilder/<sha>/pr-<n>/<datei>.png`).
- Dateinamen: `<ansicht>-<hell|dunkel>-<desktop|handy>-<vorher|nachher>.png`.
