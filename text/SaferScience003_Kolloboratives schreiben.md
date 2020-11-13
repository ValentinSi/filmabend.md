## Kollaboratives Schreiben - Wie diese Anleitung entsteht

Autor*innen: David Kirschenheuter `(https://gitlab.com/davidki)`{=latex}

### Markdown

Markdown ist eine Textauszeichnungssprache, ähnlich, aber deutlich einfacher wie HTML. Markdown hat den Zweck, dass Text schnell geschrieben werden kann, ohne viel Zeit für die Formatierung zu verlieren.

Auf Grund der Einfachheit kann allein mit Markdown jedoch kein komplexes Dokument erstellt werden. Allerdings können Markdown-Dateien sehr gut in unterschiedlich Formate konvertiert werden (Latex, DOCX, PDF, HTML u.v.m.)

Markdown-Texte bestehen aus zwei Elementen: dem eigentliche Text und Formatierungsangaben. Beide Elemente können in eine einfache Textdatei geschrieben werden und mit der Endung .md abgespeichert werden. 

Es gibt einige Markdown-Editoren, die das schreiben mit Markdown noch einfacher und intuitiver gestalten. Ein Beispiel ist z.B. [Typora](www.tpyor.io)

Hilfestellung findet sich im Internet z.B. beim [Markdownguide](https://www.markdownguide.org/cheat-sheet)

Die wichtigsten Syntaxelemente (die Formatierungsangaben) sollen im folgenden genannt werden:

#### Überschriften

Aus `## Überschrift 2` wird eine Überschrift der zweiten Ebene angelegt

#### Hervorhebungen

`** Fetter Text **` wird zu **Fetter Text** und `*kursiver Text*` wird zu *kursiver Text*

#### Links

`[Linktext](https://www.example.com` wird zu [Linktext](https://www.example.com

#### Quellen

Quellen Angaben können in einer extra Bibtex-Datei (Literaturverzeichnis, kann z.B. mit Zotero erstellt) aufgelistet werden. Dort hat jede Quelle eine eindeutige ID. Mit dieser ID kann im Markdown-Text zitiert werden: `[quellen-id]`

#### Listen

Nummerierte Listen können wie folgt erstellt werden

````markdown
1. Element
2. Element
````

1. Element
2. Element

Nicht nummerierte Listen können wie folgt erstellt werden:

```markdown
- Erstes Element
  - Kindelement
- Zweites Element
```

- Erstes Element
  - Kindelement
- Zweites Element

### Versionskontrolle und gemeinsames Schreiben mit Git und Gitlab

#### Git

 Ursprünglich für die Entwicklung von Software in großen Teams konzipiert, kann Git auch für das gemeinsame Verfassen von Texten (statt Programmcode) genutzt werden.

#### Gitlab

www.gitlab.com ist eine Online-Plattform zum kollaborativen Arbeiten und stellt eine graphische Weboberfläche für Git dar.

### Konvertieren mit Pandoc

Pandoc ist ein Kommandozeilenprogramm, das verschiedenste Textdateien verarbeiten kann. Dieses Projekt nutzt Pandoc, um aus den einzelen Markdown-Dateien ein PDF-Dokument zu erstellen. Dieser Prozess läuft automatisiert im Gitlab-Repository ab. Mehr Informationen zu Pandoc gibt es hier https://pandoc.org/ Zahlreiche Beispielanwendungen sind hier zu finden: https://pandoc.org/demos.html
