# FFM-Radio Transkriptionen

Diese Ordner enthalten automatische Transkriptionen aller FFM-Radio-Teile, die per whisper erzeugt wurden.

Es wurde folgender Befehl verwendet:
whisper ffm1.mp3 --model medium --language German

Das Model medium hat bessere Ergebnisse als small und large produziert.
Ausnahme: FFM-Radio Vol. 2 musste mit small erzeugt werden, medium hat nur Unsinn erzeugt. Daher ist die Qualität der Erkennung hier etwas schlechter.

Die Dateien wurden am 17.08.2024 erstellt.

Der Branch original enthält die Dateien genau so, wie sie von Whisper erzeugt wurden.
Die txt-Dateien im main-Branch wurden teilweise manuell verbessert.
