# MongoDB-Rest
## Restheart Anleitung
1. Herunterladen von restheart-1.1.3.zip unter folgender Seite 
https://github.com/SoftInstigate/RESTHeart/releases
2. Entsparken der ZIP-Datei und Speichern dieser Datei in restheart-1.1.3 Ordner
3. Kopieren des dist Ordners, der sich unter https://github.com/Data-City/client befindet, und hinzufügen des Ordners in restheart-1.1.3 Ordner
4. Kopieren der Konfigurationsdaten restheart.yml und security.yml, die sich unter https://github.com/Data-City/MongoDB-Rest/tree/master/etc befinden, und ersetzen der Konfigurationsdaten in restheart-1.1.3\etc Ordner
5. Laufen des Restheart unter JAVA 8 
```
mongod.exe
java -server -jar restheart.jar etc/restheart.yml
```

   Aufrufen des Clients
```
localhost:8080/datacity
```
