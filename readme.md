# LB 324

## Aufgabe 2
Schritt 1: Installation von pre-commit

pip install pre-commit

Schritt 2: Überprüfung der Installation

pre-commit --version

Schritt 3: Konfigurationsdatei

.pre-commit-config.yaml Datei muss erstellt werden im Ordner

Schritt 4: Hooks installieren

pre-commit install

Schritt 5: Hooks manuell ausführen

pre-commit run --all-files

## Aufgabe 4
https://ilicvuklb-324.azurewebsites.net

Schritt 1: Auf Azure bei Ressourcengruppe erstellen dann auf App Services klicken.
Schritt 2: Gehe zu App Service und klicke auf "Konfiguration".
Unter "Anwendungs-Einstellungen" kann man Schlüssel-Wert-Paare hinzufügen. Füge das geheime Passwort aus .env Datei hinzu.
Schritt 3: Automatische Auslieferung konfigurieren
Gehe zu App Service und klicke auf "Deployment Center".
Wähle GitHub als Quelle und verbinde das Repository.
Konfiguriere die Build-Pipeline so, dass sie auf erfolgreiche Merges in den main Branch reagiert.
