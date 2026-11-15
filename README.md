# Angebotsfinder – Demoversion für GitHub Pages

Eine bewusst einfache Website ohne Anmeldung, Datenbank, Cookies, externe JavaScript-Bibliotheken oder Build-Prozess.

## Was Besucher tun können
- Freitextsuche über Titel, Inhalte, Schlagwörter und Fächer
- Filtern nach Klasse, Fach, Format und häufigen Themen
- Kurzbeschreibung ansehen, Details öffnen, Anbieterlink nutzen
- Stets sichtbarer Hinweis: Kostenpflichtige Buchungen laufen über den schulischen Einkauf
- Funktioniert auch auf dem Smartphone

## Wichtig vor Veröffentlichung
1. **Nur freigegebene öffentliche Daten verwenden.** Keine internen Notion-Seiten, persönlichen Daten, internen E-Mail-Adressen, Notizen oder Daten von Lernenden veröffentlichen.
2. Dies ist ein **Prototyp mit 20 ausgewählten Beispielangeboten**, nicht der vollständige Notion-Katalog mit 65 Datensätzen. Die Demodaten dienen der Funktionsprüfung. Angaben müssen vor der echten Veröffentlichung redaktionell kontrolliert werden.
3. Die generischen Buchungshinweise sind **kein Ersatz für die tatsächlichen internen Einkaufs- und Freigaberegeln**. Wortlaut mit der Schulleitung/dem Einkauf abstimmen.
4. GitHub Pages ist normalerweise öffentlich im Internet und nicht automatisch nur für Mitarbeitende zugänglich.

## Ohne Programmierkenntnisse auf GitHub veröffentlichen
1. Auf github.com mit dem eigenen Konto anmelden und ein **neues Repository** erstellen, z. B. `schul-angebotsfinder`.
2. Für GitHub Free muss es **Public** sein. Keine vertraulichen Inhalte hochladen.
3. Unter **Add file → Upload files** `index.html`, `style.css`, `app.js` und `angebote.js` hochladen. Änderungen mit **Commit changes** speichern.
4. In **Settings → Pages** unter **Build and deployment** Source **Deploy from a branch**, Branch `main`, Folder `/ (root)` auswählen und speichern.
5. Danach erscheint unter **Settings → Pages** die Adresse `https://BENUTZERNAME.github.io/schul-angebotsfinder/`. Der genaue Link wird erst nach dem Einrichten bestätigt.
6. Zum Aktualisieren die Datei `angebote.js` über GitHub bearbeiten und speichern; die Webseite wird anschließend erneut veröffentlicht.

## Dateien
- `index.html`: Aufbau und Texte
- `style.css`: Gestaltung
- `app.js`: Suche und Filter
- `angebote.js`: sichtbare Angebotsdaten (hier 20 Demoeinträge)

## Nächste Schritte für die reale Version
- Freigabe, welche Felder aus der Notion-Datenbank öffentlich erscheinen dürfen.
- Export der Notion-Angebote in eine kontrollierte, bereinigte `angebote.js` oder `angebote.json`, ohne interne Anmerkungen oder unfreigegebene Kontakte.
- Fachzuordnungen und Schlagwörter systematisch prüfen, fehlende Preise und Buchungsbedingungen kennzeichnen.
- Vom Prototyp auf eine verlässlich gepflegte Vollversion mit Verantwortlichkeit für Aktualisierungen umstellen.

Diese Demo lädt **keine Notion-Daten live**; sie ist ein statischer Abzug. Eine automatische Veröffentlichung aus Notion wäre eine spätere, gesondert zu prüfende Funktion.
