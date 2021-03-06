# Mediathek-3.3-Filmliste
Diese Scriptsammlung soll MediathekView 3.3 unterstützen. Am 01.01.2016 wurde der Support für Filmlisten im alten Format eingestellt. Diese Scripte laden die neue Filmliste und schreiben sie ins alte Format um.

# Voraussetzung
MediathekView Version 3.3 muß installiert und lauffähig sein.

Die XZ-Tools von http://tukaani.org/xz/ oder das fertige Mac Paket (XZ.pkg) von http://macpkg.sourceforge.net/ ist installiert.

Zur Info: Die Filmliste wird in ~/.mediathek3/ als filme.xml abgelegt. Dies ist der Normalfall und es muß nichts weiter getan werden, wenn man nicht aktiv am Verhalten von MediathekView etwas geändert hat.

# Installation als Programm
Die Datei "Filmliste laden.zip" entpacken und das enthaltene Programm ins Programmverzeichnis kopieren.

MediathekView kann nach dem Download der Filmliste automatisch gestartet werden. Dazu einfach einmal MediathekView_Mac_Start.command auf "Filmliste laden" ziehen und den folgenden Dialog mit "Ja" beantworten.

Danach erscheint die Frage "Soll das Terminal Fenster offen bleiben um alle Meldungen von MediathekView anzuzeigen, oder soll es geschlossen werden?". 

"Offen" bedeutet, daß das Terminal Fenster, in dem der Download Fortschritt angezeigt wird, offen bleibt solange MediathekView läuft. Hier erscheinen dann auch die Log-Meldungen von MediathekView.

"Schließen" bedeutet, daß dieses Fenster nur bis ca. 10 Sekunden nach dem Start von MediathekView zu sehen bleibt und danach geschlossen wird.

# Archivierte Filmlisten

Archivierte Filmlisten sind, wie in der FAQ von MediathekView beschrieben, erhältlich.

https://sourceforge.net/p/zdfmediathk/wiki/FAQ/#in-der-mediathek-des-senders-xyz-ist-die-sendung-vorhanden-in-der-filmliste-jedoch-nicht

So eine Liste kann einfach auf "Filmliste laden" gezogen werden, um sie zu aktivieren.

# Installation als Kommandozeilen Tools
Die Dateien
    filmliste_laden
    filmliste_konvertieren
im selben Verzeichnis als ausführbare Dateien speichern.

Zum Update der Filmliste (~/.mediathek3/filme.xml) wird einfach das Script "filmliste_laden" gestartet, während MediathekView nicht läuft.

Geladene archivierte Filmlisten können einfach als Parameter für "filmliste_laden" angegeben werden.