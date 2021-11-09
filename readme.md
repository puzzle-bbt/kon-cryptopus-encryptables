# Cryptopus Encryptables

## Ausgangslage

In Cryptopus können heute Accounts mit Benutzer/Passwort, Dateien welche an Accounts angehängt sind, sowie Openshift Secrets gespeichert werden. All diese Elemente werden mithilfe eines komplexen Passworts welches auf dem Team (Teammember) gespeichert ist ver- und entschlüsselt. 

## Motivation Encryptables

Neben Zugangsdaten mit Benutzer/Passwort werden auch Tokens, PINs, Zertifikate, E-Mail usw. in Cryptopus gespeichert. Mit Encryptables soll ein neues Konzept eingeführt werden, das die Datenstruktur flexibler macht und alle Elemente direkt einem Ordner anhängt. Dateien werden künftig nicht mehr den Accounts sondern direkt einem Folder bzw. dadurch an ein Team angehängt.

## Ziele

1. Die Sicherheit der sensitiven Daten soll durch die Verwendung eines IV (initialization Vectors) Werts bei der Verschlüsselung erhöht werden.
2. Mithilfe anderer Speichermöglichkeiten soll die Flexibilität zum Abspeichern von Daten und die Übersichtlichkeit in der Applikation für Benutzer verbessert werden.

## Konzeption

* 1.0 Konzept
  * 1.1 [Encryptables Model](1_konzeption/1.1_encryptables_model.md)
  * 1.2 [UI Anpassungen](1_konzeption/1.2_ui_changes.md)
  * 1.3 [API änderungen](1_konzeption/1.3_api.md)
  * 1.4 [Migration](1_konzeption/1.4_migration.md)
  * 1.5 [Umsetzung](1_konzeption/1.5_implementation.md)
  * 1.6 [Verschlüsselung](1_konzeption/1.6_encryption.md)
