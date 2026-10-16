Upload-Ordner fuer das Handy
============================

Diesen ganzen Ordner "handy" bei einem Webhost hochladen, zum Beispiel
bei app.netlify.com/drop per Drag and drop.

Danach im Browser erreichbar:

   https://<deine-adresse>/           -> Fragenkatalog (index.html)
   https://<deine-adresse>/skript.html
   https://<deine-adresse>/vde-normen.html

Auf dem iPhone in Safari oeffnen und ueber Teilen ->
"Zum Home-Bildschirm" ablegen. Dann startet es wie eine App.

Hinweis: Diese Adresse ist oeffentlich erreichbar. Wer die Adresse kennt,
kann die Seiten lesen. Es werden keine Daten gesendet und nichts gespeichert.

Nach Aenderungen an den Quellen: die Dateien hier neu erzeugen mit
   python3 build.py && python3 build_skript.py
und anschliessend erneut kopieren.
