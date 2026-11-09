# Private Home-Assistant-Anbindung

Diese privat genutzte Anwendung verbindet Home Assistant mit
Google Calendar und sichert eigene Frigate-Kameraaufnahmen
über rclone in Google Drive. Sie ist kein öffentlich angebotener
Dienst und kein offizielles Google- oder Home-Assistant-Angebot.

## Datenschutzhinweise

Die Kalenderintegration verarbeitet die vom Kontoinhaber
freigegebenen Kalenderdaten für die eingerichteten Funktionen
in Home Assistant.

Für die Kamerasicherung werden Aufnahmen und zugehörige
Dateiinformationen in den dafür eingerichteten Ordner des
Google-Drive-Kontos übertragen. Lokal werden relevante
Aufnahmen derzeit etwa einen Tag, in Google Drive 31 Tage
aufbewahrt und anschließend automatisch bereinigt.

Zugangstoken werden auf den privaten Systemen gespeichert.
Das Google-Passwort wird bei Google eingegeben und nicht von
dieser Anwendung gespeichert. Die Daten werden nicht verkauft
oder für Werbung genutzt.

Der Kontoinhaber kann den Google-Zugriff in seinen
Google-Kontoeinstellungen widerrufen und vorhandene
Drive-Dateien selbst löschen. Kontakt: die im Google-
Einwilligungsdialog angegebene Support-Adresse.

Die Nutzung der Google-Daten erfolgt entsprechend der
[Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy),
einschließlich der Limited-Use-Anforderungen.
