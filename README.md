QISCheck
========

Fork der Original-App von Christian Caspers für die HS Rhein-Main https://github.com/ccaspers/qischeck

Einfache Android-App zum Anzeigen des Notenspiegels aus dem QIS-System
der Uni Kiel. Da keine API vorhanden ist wird die Internetseite mit JSoup
geparsed. Aktuell wird nur der Studiengang Physik unterstützt.


##Features
* Übserichtliche Darstellung
* automatische Synchronisierung
* Sync-Intervall einstellbar
* Benachrichtigungen bei neuen Noten

![Screenshot][1]

##Download
* Dropbox: https://dl.dropbox.com/u/6910770/QISCheck.apk

##Hinweis
Die Zugangsdaten zum QIS-System werden in den SharedPreferences im Klartext gespeichert.
Auf Geräten mit Root-Zugriff stellt das ein Sicherheitsrisiko dar, da andere Anwendungen
dadurch Zugriff auf die Privaten Daten der App erhalten könnten. 

[1]: http://www.pixeltronics.net/qischeck-screenshot.png
