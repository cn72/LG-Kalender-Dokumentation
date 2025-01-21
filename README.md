# PRTCD-LG-Kalender
WordPress Plugin LG-Kalender des PRTCD

## Inhaltsverzeichnis

Anhang Beispiele
- [Meldung per PDF-Formular einer Prüfung zufügen](#meldung-hinzufügen)

## Meldung hinzufügen

> [!NOTE]
> Die Übernahme der Meldedaten aus einem Formular funktioniert nur, wenn das Meldeformular vom Terminkalender heruntergeladen wird. Wird das Meldeformular aus einer anderen Quelle heruntergeladen und ausgefüllt, können diese Daten nicht übernommen werden !!!

Wird ein Meldeformular ausgefüllt und per E-mail zugesandt, dann kann dieses wie folgt einer Prüfung zugeordnet werden.

Zuerst wird der Anhang der Mail (das Meldeformular) lokal auf dem Rechner gespeichert. Nach dem Anmelden bei WordPress ruft man die Seite des Terminkalenders
auf. Bei der Prüfung, für den das Meldeformular zugesandt wurde, wählt man den Link "Meldungen" aus. Auf der kommenden Seite wird nun der Button "neue Meldung importieren" aufgerufen. Danach fügt man den zuvor gespeicherten Meldeschein ein (Button "Datei auswählen") und klickt auf "UPLOAD".

Der ausgewählte Meldeschein wird ausgelesen und die Daten werden eingetragen. Sollte der Meldeschein nicht zu dieser Prüfung gehören, werden trotzdem die Daten übernommen, man erhält jedoch einen Hinweis darauf, dass dieser Meldeschein nicht zu dieser Prüfung gehört.

[Top](#inhaltsverzeichnis)
