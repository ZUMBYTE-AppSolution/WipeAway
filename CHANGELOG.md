# Änderungen

## WipeAway 0.5.0 – in Vorbereitung

Noch nicht veröffentlicht. Neue Funktionen werden erst nach ihren jeweiligen Prüfungen als verfügbar ausgewiesen.

### Bereits im Entwicklungsstand enthalten

- Neue Marke WipeAway mit einem Tuch, das Dateien wegwischt, und violett-türkisem Glow.
- Neue Farbgebung für Hell- und Dunkelmodus sowie eine eigene Darstellungseinstellung.
- Einrichtungsassistent für Mitteilungen, Dateizugriff, Administrator-Helfer, App-Entfernung und Hintergrundstart.
- Update-Anbindung der direkten Ausgabe an öffentliche GitHub-Release-Dateien mit signiertem Feed und signierten Downloads.
- Automatische Updatehinweise ohne zusätzliches Fenster beim Hintergrundstart; manuelle Prüfung in der App.
- Der Anmeldestart verbindet eine bisherige Registrierung nach der Umbenennung einmal am neuen App-Ort. Unveränderte Installationen behalten ihre Zuordnung.
- Zusätzliche Grundlagen zur APFS-Erfassung und zu erklärbaren Analyse-Regeln.
- Fortsetzbare, lokal gespeicherte Laufwerksanalyse mit Größen, Dateitypen und Hinweisen auf unvollständig lesbare Bereiche.
- Automatische Cache-Vorschläge prüfen Inhalte zusätzlich auf geschützte Projekte, Chats, Schlüssel und Datenbanken. Gespeicherte Alt-Funde werden vor der Quarantäne erneut geprüft.
- Gemeinsame Website-Lizenzverwaltung mit Programmübersicht, Portfolio-Zuordnung, Geschenkcodes, Aktivierungen und programmspezifischer API-Anleitung.
- Persönliche Website-Lizenz und direkte Mac-Geschenkcodes in der App; der Einrichtungsassistent erklärt die Aktivierung vor dem Helfer-Schritt.
- Getrennter Store-Build mit Apple-Käufen und Wiederherstellung. Preise und 14-Tage-Probephase für berechtigte Abo-Neukunden sind bei Apple eingerichtet.
- Freiwillige Fehlerberichte mit Vorschau, Zugangsdaten-Filter und Anbindung an das Zumbyte-Ticketsystem.
- Direkte App und Installationspaket 0.5.0, Build 11, für Intel und Apple Silicon signiert und von Apple notarisiert.
- Native Werbe-Vorschauen für Hellmodus, Dunkelmodus, Backup-Tresor und Apple-Tarife mit gekennzeichneten Beispieldaten.
- Lokale Apple-Tests für die tatsächliche 14-Tage-Probephase, einmalige Probe-Berechtigung innerhalb der Abo-Gruppe, Lifetime-Wechsel, Ablauf und Rückerstattung bestanden.
- Zusätzliche Store-Kaufregeln verhindern weitere Pro-Käufe bei aktiver Lifetime-Lizenz und erklären vor dem Wechsel, dass ein bestehendes Apple-Abo gesondert gekündigt werden muss.
- Einlösung von Apple-Angebotscodes über Apples eigene Oberfläche auf unterstützten macOS-Versionen, mit Rückweg über den App Store auf macOS 14.
- Store-Build 12 wurde von App Store Connect erfolgreich verarbeitet und der vorbereiteten Version zugeordnet. Er ist noch nicht zur Prüfung eingereicht.
- Wiederherstellung und Dateiübertragung in der Store-Sandbox erhalten die von macOS verwalteten Sicherheitsmarkierungen. Verschlüsselte Backup-Wiederherstellung und Inhaltsprüfung wurden mit eigenen Testdateien geprüft.
- Der installierte Administrator-Helfer 5 wurde mit zwei gesperrten Testordnern für Quarantäne, Wiederherstellung und endgültiges Löschen geprüft. Das externe Symlink-Kontrollziel und beide Dauerfreigaben blieben erhalten; der Test benötigte keine erneute Administratorabfrage.

### Noch in Arbeit

- Abschließende Prüfung des korrigierten Hintergrundstarts und des Einrichtungsablaufs am installierten Mac.
- Vollständiger Updateversuch zwischen zwei öffentlich bereitgestellten Versionen.
- Weitere herstellerspezifische Speicherregeln und echte App-Verträglichkeitsprüfungen der Auslagerung.
- Die Auslagerung behält Wiederherstellungskopien am ursprünglichen Ort: deren Platz gilt noch nicht als freigegeben.
- Produktive Apple-Kaufübernahme nach der Store-Freigabe, Store-Veröffentlichung und Apples Freigabe produktiver Geschenkcodes. Käufe aus Testumgebungen schalten ausschließlich die Store-Testausgabe frei.

## SEKTOR – bisheriger Stand

WipeAway führt die bisherige SEKTOR-App weiter. Vorhandene Einstellungen, gespeicherte Scans und Quarantäne werden übernommen. Der Installer bewahrt eine vorhandene signierte SEKTOR-App getrennt für eine Wiederherstellung auf. Öffentliche Downloads werden erst nach den abschließenden Prüfungen freigegeben.
