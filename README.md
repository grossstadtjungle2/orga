#Organisations Repo
##Status
__aktuellster  zuerst__

[*05.05.14*] Antwort erhalten
[*03.05.14*] Proposal fertig und verschickt

##HowTo GitHub
GitHub ist eigentlich sehr einfach mit dem Comand-Line Tool zu verwenden. Dabei gibt es zwei verschiedene Standartaufgaben die zu bew�ltigen sind.
Dabei ist es wichtig sich immer im Ordner des aktuellen Repos zu befinden.

###1. Aktuellsten Stand runterladen:
1. git pull

__Fertig!__

###2. �nderungen vornehemen / Neue Dateien hinzuf�gen
1. git pull
2. �nderungen machen an den diversen Dokumenten bzw. die neuen Dateien erstellen oder auch l�schen
3. git add -A
4. git commit -m "*eure �nderung(en) beschreiben*"
5. git push
6. Nutzernamen und Passwort eingeben (Bei der Passworteingabe wird nichts angeizeigt, also sch�n sauber schreiben, sonst nochmal ab Schritt 5)

__Fertig!__

###M�glicher Fehler
Es kann passieren, dass ihr die �nderungen nach Schritt 4 nicht pushen k�nnt. Das liegt dann in den meisten F�llen daran, dass in der Zwischenzeit jemand anderes schon �nderungen get�tigt hat. Dann geht es nach Schritt 4 so weiter:
5. Auf GitHub das aktuelle Repo als Zip runterladen (ist im Orga Repo n�tig, da wir mit Dateien arbeiten, die nicht nur reinen Text enthalten und bei den nachfolgenden Schritten etwas verloren gehen k�nnte)
6. git pull
7. git merge
8. git commit -m "merged"
9. git push
10. Benutzername und PW eingeben

__Fertig!__

###Merge- und andere Konflikte
Sollte bei 'git merge' oder anderen Dingen Probleme auftauchen, dann www.gidf.com oder Marco H. fragen.
