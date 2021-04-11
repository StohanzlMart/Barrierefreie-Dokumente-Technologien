In x Schritten zum barrierefreien MS Word Dokument; losely based on https://webaim.org/techniques/word/

# 0 Microsoft Word Route zu PDF/UA

der gesamte Lebenszyklus des Dokuments wird betrachtet:

# 1 mit Vorlagen oder [Neues Dokument] —> [Design] > [Themes]

Hierbei ist zu beachten, dass geeignete \*.potx-Vorlagen von MircoSaft oder Dienstgeber verfügbar sind, um Anforderungen an

* Struktur (= gute Formatvorlagen um...)
  * Überschrift bzw. Logik Level 1-6
  * Formatierung
    * Zwischenräume / Whitespaces
    * einheitliche Schriftart / Font
    * ausreichend Kontrast > 4.5
    * ausreichend Schriftgröße > 10
* Metadaten
  * Dokumentdateiname
  * Dokumenttitel
  * Dokument Keywords (XML Key-Tags) [Datei] > [Info]
  * Dokumentsprache

von Anfang an zu erfüllen. Genau auf diese Anforderungen einzugehen, würde den Rahmen dieser Arbeit sprengen. Weitere Anreize hierzu: [Whitespaces](https://www.consultdmw.com/use-word-styles-to-control-white-space.html) [dotx Einführung](https://www.holgermatthes.de/diplom-reader/word/dokumentvorlage.php) [Corporate Identity Templating](http://www.soft-management.net/wp/2016/08/so-aendern-sie-die-vorlagen-ihrer-word-dokumente/)

# 2 setze Titel und sonstige Attribute

Neben dem Dokumenttitel können auch andere Attribute über [Entwicklertools] > [XML-Zuordnungsbereich] > Rechtsklick auf Titel > Einfügen Steuerfeld > "Blanker Text" im Dokument angezeigt werden. Bestenfalls wurde das schon bei der Vorlagenerstellung schon alles verknüpft, sodass nur noch im Dokument selbst gearbeitet werden muss.

# 3 schreibe das Dokument

Beachte, dass hierbei keine leeren Absatzmarken benötigt werden, denn Absatzabstand kann auch ohne leere Zeile erzeugt werden. Bilder sollten nur in Zeile mit Text eingefügt werden, um Lesereihenfolge klar zu halten.

# 4 [Überprüfen] > [Barrierefreiheit überprüfen]

Häufige Probleme können hier abgefangen werden. So können z.B. Bilder mit alternativem Text versehen oder als dekorativ markiert werden.

## Tabellen

Sollten einfach gehalten und die entsprechenden Häkchen für Kopfzeile oder -reihe richtig gesetzt werden.

# 5 Dokumentsprache richtig setzen

[STRG] + [A] > [Überprüfen] > [Sprache] > [Sprache wählen]

# 6 [Datei] > [Speichern unter]

1. .pdf-Endung auswählen.
2. Erweiterte Optionen
3. PDF/A-Kompatibilität anwählen

# 8 Viola —> 1 PDFƒ𝜶∫𝝉UA

Merke, MircoSaft Opfer 365 ist zu gut, um PDF/UA Konformität zu erreichen.
