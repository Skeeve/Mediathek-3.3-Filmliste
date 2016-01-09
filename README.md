# Mediathek-3.3-Filmliste
Diese Scriptsammlung soll MediathekView 3.3 unterstützen. Am 01.01.2016 wurde der Support für Filmlisten im alten Format eingestellt. Diese Scripte laden die neue Filmliste und schreiben sie ins alte Format um.

# Voraussetzung
MediathekView Version 3.3 muß installiert und lauffähig sein.

Die filmliste wird in ~/.mediathek3/ als filme.xml abgelegt.

# Installation
Die Dateien
    filmliste_laden
    filmliste_konvertieren
im selben Verzeichnis als ausführbare Dateien speichern.

Die XZ-Tools von http://tukaani.org/xz/ installieren.

Zum Update der Filmliste (~/.mediathek3/filme.xml) wird einfach das Script "filmliste_laden" gestartet, während MediathekView nicht läuft.