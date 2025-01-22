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
    - [Adressen verwalten](#adressen-verwalten)
    - Richternummer
    - Richterliste drucken

## Adressen verwalten

> [!NOTE]
> - man muss bei WordPress angemeldet sein
> - um Adressen bearbeiten zu können, muss der Benutzer die entsprechenden Rechte haben (siehe Admin-Bereich)
> - um Richternummern bearbeiten zu können, muss der Benutzer die entsprechenden Rechte haben (siehe Admin-Bereich)

Wenn die Seite mit dem Terminkalender aufgerufen wird, steht über der Zeile mit der Jahresauswahl der Verweis zur Richterverwaltung.
Alternativ kann natürlich auch über ein eigenes Menü zur Seite der Richterverwaltung verlinkt werden.<br>
Auf der Seite der Richterverwaltung werden die Richter alphabetisch in einer Tabelle aufgelistet. Am Ende einer jeden Zeile 
ist eine Makierung, welches Fach gerichtet werden darf.
> [!Note]
> Diese Makierung ist wichtig, da z.Bsp. bei der Richterzuordnung zu einer Prüfung nur die Richter ausgewählt werden können, die auch das richtige Fach richten dürfen (Baurichter bei JP z.Bsp.)
Jeder vorhandene Eintrag kann über den Button "EDIT" bearbeitet werden.

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
