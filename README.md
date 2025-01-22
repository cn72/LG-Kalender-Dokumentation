# PRTCD-LG-Kalender
WordPress Plugin LG-Kalender des PRTCD

## Inhaltsverzeichnis
1. Übersicht
    - Einführung
    - Lizenz
2. Installation
    - Download
    - Plugin Upload WP
    - wichtige WorPress Einstellungen
    - weitere Plugins
    - Updates
3. Shortcodes
    - Verwendung von Shortcodes
4. Admin Bereich
    - Einstellungen
    - Formulare
    - Design
    - Rechte verwalten
5. Richterverwaltung
    - [Tabelle Adressen](#tabelle-adressen)
    - [Adresse bearbeiten](#tabelle-adressen)
    - [Adresse neu anlegen / löschen](#adresse-neu-anlegen--löschen)
    - Richternummer

## Tabelle Adressen

> [!NOTE]
> - man muss bei WordPress angemeldet sein
> - um Adressen bearbeiten zu können, muss der Benutzer die entsprechenden Rechte haben (siehe Admin-Bereich)
> - um Richternummern bearbeiten zu können, muss der Benutzer die entsprechenden Rechte haben (siehe Admin-Bereich)

Wenn die Seite mit dem Terminkalender aufgerufen wird, steht über der Zeile mit der Jahresauswahl der Verweis zur Richterverwaltung.
Alternativ kann natürlich über ein eigenes Menü zur Seite der Richterverwaltung verlinkt werden.<br>
Auf der Seite der Richterverwaltung werden die Richter alphabetisch in einer Tabelle aufgelistet. Am Ende einer jeden Zeile 
ist eine Makierung, welches Fach gerichtet werden darf.
> [!Note]
> Diese Makierung ist wichtig, da z.Bsp. bei der Richterzuordnung zu einer Prüfung nur die Richter ausgewählt werden können, die auch das richtige Fach richten dürfen (Baurichter bei JP z.Bsp.)

Jeder vorhandene Eintrag kann über den Button "EDIT" bearbeitet werden. Am Ende der Tabelle gibt es die Möglichkeit, eine neue Adresse anzulegen (Button "NEU ANLEGEN") oder die Tabelle als PDF herunterzuladen (Button "DRUCKEN").

[Top](#inhaltsverzeichnis)

## Adresse bearbeiten

> [!NOTE]
> - man muss bei WordPress angemeldet sein
> - um Adressen bearbeiten zu können, muss der Benutzer die entsprechenden Rechte haben (siehe Admin-Bereich)

[Top](#inhaltsverzeichnis)

## Adresse neu anlegen / löschen

> [!NOTE]
> - man muss bei WordPress angemeldet sein
> - um Adressen anlegen/löschen zu können, muss der Benutzer die entsprechenden Rechte haben (siehe Admin-Bereich)

[Top](#inhaltsverzeichnis)


## Anhang Beispiele
- [Meldung per PDF-Formular einer Prüfung zufügen](#meldung-hinzufügen)

### Meldung hinzufügen

> [!NOTE]
> Die Übernahme der Meldedaten aus einem Formular funktioniert nur, wenn das Meldeformular vom Terminkalender heruntergeladen wird. Wird das Meldeformular aus einer anderen Quelle heruntergeladen und ausgefüllt, können diese Daten nicht übernommen werden !!!

Wird ein Meldeformular ausgefüllt und per E-mail zugesandt, dann kann dieses wie folgt einer Prüfung zugeordnet werden.

Zuerst wird der Anhang der Mail (das Meldeformular) lokal auf dem Rechner gespeichert. Nach dem Anmelden bei WordPress ruft man die Seite des Terminkalenders
auf. Bei der Prüfung, für den das Meldeformular zugesandt wurde, wählt man den Link "Meldungen" aus. Auf der kommenden Seite wird nun der Button "neue Meldung importieren" aufgerufen. Danach fügt man den zuvor gespeicherten Meldeschein ein (Button "Datei auswählen") und klickt auf "UPLOAD".

Der ausgewählte Meldeschein wird ausgelesen und die Daten werden eingetragen. Sollte der Meldeschein nicht zu dieser Prüfung gehören, werden trotzdem die Daten übernommen, man erhält jedoch einen Hinweis darauf, dass dieser Meldeschein nicht zu dieser Prüfung gehört.

[Top](#inhaltsverzeichnis)
