# Soest Hackathon

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ffeldhaus/soest-hackathon/HEAD?urlpath=lab/tree/README.md)

In diesem Hackathon werden folgende Themen erklärt und gemeinsam ausprobiert:

- Einführung in [Jupyter Notebooks](https://jupyter-tutorial.readthedocs.io/de/latest/intro.html) und warum  sie hilfreich bei der Datenanalyse sind
- Einführung in [Markdown](https://de.wikipedia.org/wiki/Markdown) als weiter verbreitete, leicht lesbare Auszeichnungssprache
- Einführung in die häufig von Datenwissenschaftlern genutzte [Python Programmiersprache](https://www.python.org/)
- Einführun in die häufig für die Datenverwaltung und -analyse genutzte [Python Bibliothek Pandas](https://de.wikipedia.org/wiki/Pandas_(Software))
- Programmatisches abrufen von (Regional-)Statistiken mit Beispielen von [Datenguide](https://datengui.de/)
- Einführung in die Datenvisualisierung mit Beispielen von [Datawrapper](https://www.datawrapper.de/)

## Jupyter Notebooks

Jupyter Notebooks ermöglichen es, Informationen mit Markdown zu beschreiben sowie Programmiercode zu schreiben, auszuführen und Daten zu visualisieren. Jupyter Notebooks können jederzeit mit neuen Daten ausgeführt werden und bieten somit eine interaktive Dokumentation, lassen sich gut in einer Versionsverwaltung speichern und können einfach mit anderen geteilt werden.

Es wird empfohlen das [Jupyter Tutorial](https://jupyter-tutorial.readthedocs.io/de/latest/intro.html) durchzugehen.

### Jupyter Notebooks mit Binder ausführen

Jupyter Notebooks können in verschiedenen Umgebungen genutzt werden. Für diesen Hackathon werden wir Binder verwenden, da es komplett kostenlos ist und keinen Account benötigt.

Binder hat folgende Einschränkungen, die beachtet werden sollten:
  - Sessions werden nach 10 Minuten inaktivität beendet
  - Sessions bleiben aktiv, solange das Browser Tab aktiv und im Vordergrund ist
  - Modifikationen können nur manuell im Browser gespeichert werden

Ein leeres Jupyter Notebook für diesen Hackathon kann einfach über folgenden Link gestartet werden: 

[`notebook.ipynb` in Binder öffnen](https://mybinder.org/v2/gh/ffeldhaus/soest-hackathon/HEAD?filepath=notebook.ipynb)

## Markdown

Markdown ist eine weit verbreitete und häufig von Programmierern und Datenwissenschaftlern genutzte vereinfachte Auszeichnungssprache.

Diese *README.md* Datei ist eine Markdown Datei, welche sowohl den Text als auch eine Beschreibung der Formatierung des Textes enthält.

Es wird empfohlen ein [Markdown Tutorial](https://drdanielappel.de/tipps-tools/markdown-eine-einfach-zu-erlernende-auszeichnungssprache/) durchzugehen.

Im Unterverzeichnis [`beispiele`](beispiele) befindet sich [`markdown.ipynb`](beispiele/markdown.ipynb), eine Markdown Referenz in einem Jupyter Notebook. Diese kann über folgenden Link in Binder geöffnet werden:

[`markdown.ipynb` in Binder öffnen](https://mybinder.org/v2/gh/ffeldhaus/soest-hackathon/HEAD?filepath=beispiele/markdown.ipynb)

### Aufgaben

- Öffne ein [leeres Jupyter Notebook](https://mybinder.org/v2/gh/ffeldhaus/soest-hackathon/HEAD?filepath=notebook.ipynb)
- Ändere den *Cell Type* der angezeigten *Cell* auf *Markdown*
- Schreibe ein *Hallo Welt* Beispiel in Markdown
- Führe das Beispiel mit *Run* aus und verifiziere, dass die Markdown Formatierung korrekt angezeigt wird
- Speichere das Resultat im Browser Storage, dann ändere etwas und lade dann die vorherige Version aus dem Browser Storage

[`hallo_welt.ipynb` in Binder öffnen](https://mybinder.org/v2/gh/ffeldhaus/soest-hackathon/HEAD?filepath=beispiele/hallo_welt.ipynb)

## Python

Python ist eine weit verbreitete, einfach zu erlernende Programmiersprache welche insbesondere für die Datenanalyse genutzt wird. Es gibt viele Einführungen und Tutorials, wir werden uns jedoch auf die wesentlichen Informationen beschränken um Daten analysieren und visualisieren zu können. Für weitergehende Informationen wird das offizielle (englischsprachige) [The Python Tutorial](https://docs.python.org/3/tutorial/) empfohlen.

Das Python Tutorial für diesen Hackathon findet sich im [`python_tutorial.ipynb`](beispiele/python_tutiral.ipynb) Jupyter Notebook und kann über folgenden Link in Binder geöffnet werden:

[`python_tutorial.ipynb` in Binder öffnen](https://mybinder.org/v2/gh/ffeldhaus/soest-hackathon/HEAD?filepath=beispiele/python_tutorial.ipynb)

### Aufgaben

- Öffne ein [leeres Jupyter Notebook](https://mybinder.org/v2/gh/ffeldhaus/soest-hackathon/HEAD?filepath=notebook.ipynb)
- Schreibe eine Funktion für den *Satz des Pythagoras* mit Parametern für die beiden Katheten `a` und `b`. Die Funktion soll die Hypotenuse `c` ausgeben
- **Tipp:** Binde das Modul `math` ein um mit `math.sqrt()` die Wurzel ziehen zu können
