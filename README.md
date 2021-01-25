# Soest Hackathon

In diesem Hackathon werden folgende Themen erklärt und gemeinsam ausprobiert:

- Einführung in [Markdown](https://de.wikipedia.org/wiki/Markdown) als weiter verbreitete, leicht lesbare Auszeichnungssprache
- Einführung in [Jupyter Notebooks](https://jupyter-tutorial.readthedocs.io/de/latest/intro.html) und warum  sie hilfreich bei der Datenanalyse sind
- Einführung in die häufig von Datenwissenschaftlern genutzte [Python Programmiersprache](https://www.python.org/)
- Einführun in die häufig für die Datenverwaltung und -analyse genutzte [Python Bibliothek Pandas](https://de.wikipedia.org/wiki/Pandas_(Software))
- Programmatisches abrufen von (Regional-)Statistiken mit Beispielen von [Datenguide](https://datengui.de/)
- Einführung in die Datenvisualisierung mit Beispielen von [Datawrapper](https://www.datawrapper.de/)

## Markdown

Markdown ist eine weit verbreitete und häufig von Programmierern und Datenwissenschaftlern genutzte vereinfachte Auszeichnungssprache.

Diese *README.md* Datei ist eine Markdown Datei, welche sowohl den Text als auch eine Beschreibung der formatierung des Textes enthält.

Es wird empfohlen ein [Markdown Tutorial](https://drdanielappel.de/tipps-tools/markdown-eine-einfach-zu-erlernende-auszeichnungssprache/) durchzugehen.

## Jupyter Notebooks

Jupyter Notebooks ermöglichen es, Informationen mit Markdown zu beschreiben sowie Programmiercode zu schreiben, auszuführen und Daten zu visualisieren. Jupyter Notebooks können jederzeit mit neuen Daten ausgeführt werden und bieten somit eine interaktive Dokumentation, lassen sich gut in einer Versionsverwaltung speichern und können einfach mit anderen geteilt werden.

Es wird empfohlen das [Jupyter Tutorial](https://jupyter-tutorial.readthedocs.io/de/latest/intro.html) durchzugehen.

Jupyter Notebooks können in verschiedenen Umgebungen genutzt werden. Für diesen Hackathon werden wir Binder verwenden, da es komplett kostenlos ist und keinen Account benötigt.

Binder hat folgende Einschränkungen, die beachtet werden sollten:
  - Sessions werden nach 10 Minuten inaktivität beendet
  - Sessions bleiben aktiv, solange das Browser Tab aktiv und im Vordergrund ist
  - Modifikationen können nur manuell im Browser gespeichert werden

### Nutzung von Binder

Ein leeres Jupyter Notebook für diesen Hackathon kann einfach über folgenden Link gestartet werden: 

[`notebook.ipynb` in Binder öffnen](https://mybinder.org/v2/gh/ffeldhaus/soest-hackathon/HEAD?filepath=notebook.ipynb)

#### Aufgaben

- Öffne das Jupyter Notebook über den oben stehenden Binder Link
- Ändere den *Cell Type* der angezeigten *Cell* auf *Markdown*
- Schreibe ein *Hallo Welt* Beispiel in Markdown
- Führe das Beispiel mit *Run* aus und verifiziere, dass die Markdown Formatierung korrekt angezeigt wird
- Speichere das Resultat im Browser Storage dann ändere etwas und lade dann die vorherige Version aus dem Browser Storage

Im Unterverzeichnis [`beispiele`](beispiele) gibt es ein [`markdown.ipynb`](beispiele/markdown.ipynb) Jupyter Notebook als Beispiel für diese Aufgabe. Es kann über folgenden Link in Binder geöffnet werden:

[`markdown.ipynb` in Binder öffnen](https://mybinder.org/v2/gh/ffeldhaus/soest-hackathon/HEAD?filepath=beispiele/markdown.ipynb)

## Python

Python ist eine weit verbreitete, einfach zu erlernden Programmiersprache welche insbesondere in der Datenanalyse weit verbreitet ist. Es gibt viele Einführungen und Tutorials wir werden uns jedoch auf die wesentlichen Informationen beschränken um Daten analysieren und visualisieren zu können. Für weitergehende Informationen wird das offizielle (englischsprachige) [The Python Tutorial](https://docs.python.org/3/tutorial/) empfohlen.

Das Python Tutorial für diesen Hackathon findet sich im [`python_tutorial.ipynb`](beispiele/python_tutiral.ipynb) Jupyter Notebook und kann über folgenden Link in Binder geöffnet werden:

[`python_tutorial.ipynb` in Binder öffnen](https://mybinder.org/v2/gh/ffeldhaus/soest-hackathon/HEAD?filepath=beispiele/python_tutorial.ipynb)