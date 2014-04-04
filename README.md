Filmsoziologie
==============

Der Grund für das Scheitern der Filmsoziologie ist das Fehlen eines gemeinsamen Erkenntnis-Interesse. Wenn Film in der Soziologie vorkommt, dann als Artefakt, der mit der Gesellschaft in Beziehung gesetzt wird. Film ist entweder sozial verursacht oder hat soziale Auswirkungen. Jedoch ist der Film selbst nicht sozial, und kann somit nicht im Erkenntnisinteresse der Soziologie stehen. Eine Film-Soziologie in dessen Mittelpunkt der Film steht, benötigt eine soziologische Definiton von Film. Film selbst muss soziologisch verstanden werden. So eine Film-Soziologie zeigt, wie aus Gesellschaft Film und dann wieder Gesellschaft wird und verbindet somit die zwei Enden der Filmsoziologie.


Infos
-----

Bachelaureatsarbeit für Soziologie an der Universtität Graz.


Technisch
---------


Ich schreibe die Arbeit in *einer* Textdatei. Um die Textdatei in ein Druckfertiges Format umzuwandeln verwende ich *pandoc* das mir via *LaTeX* eine PDF-Datei setzt.

    pandoc -i draft.md -o draft.pdf --filter pandoc-citeproc --csl=kzfss.csl

Vorausetzung sind die die Programme *pandoc* und eine *LaTeX* Distribution.
Die Bibliographie ist am Ende des Dokuments in Form einer YAML-Liste notiert und wird mit pandoc und einer Vorlage für den Zitierstil der Köllner Zeitschrift für Soziologie und Sozialpsychologie gesetzt.

### Links

- <http://johnmacfarlane.net/pandoc/README.html#citations>
- <https://www.tug.org/texlive/>
- <https://github.com/citation-style-language/styles/blob/master/kolner-zeitschrift-fur-soziologie-und-sozialpsychologie.csl>
