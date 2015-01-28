#Die Struktur der Quellenverzeichnisse

Zunächst braucht man natürlich einen passenden Verzeichnisbaum für die Quelldateien. Man kann diesen in der Datei /etc/rpmrc festlegen, üblicherweise wird hier einfach /usr/src verwendet.

Eventuell müssen die folgenden Verzeichnisse angelegt werden, um einen Verzeichnisbaum für das Übersetzen zu erstellen:
~~~
    BUILD ist das Verzeichnis, in dem die Übersetzung durch den RPM stattfindet. Man muß seine Testübersetzungen nicht in diesem speziellen Verzeichnis durchführen, aber hier ist es, wo der RPM seine Übersetzungen durchführt.
    SOURCES hier sollten alle tar-Archive der originalen Quellen und die Patches stehen. Hier sucht der RPM per Default nach den Quelldateien.
    SPECS hier gehören die Spec-Dateien hin.
    RPMS das Verzeichnis für die fertig übersetzten rpm's.
    SRPMS das Verzeichnis für die Quell-rpm's.
~~~
