---
{"dg-publish":true,"permalink":"/0-meta/2-markdown/","dg-note-properties":{}}
---

## Navigation mit der Tastatur
Cursor mit Pfeiltasten bewegen.
Mit gedrückter Strg-Taste bewegt man den Cursor um ganze Wörter.
Mit gedrückter Shift-Taste und Pfeiltasten markiert man mit dem Cursor.
## Wichtige Tastenkombinationen
Strg+Z macht die letzte Aktion rückgängig
Strg+A markiert alles
Strg+X schneidet den markierten Text aus und kopiert ihn
Strg+C kopiert den markierten Text
Strg+V fügt den kopierten Text ein
Windows ⊞+L zum Sperren des Computers
## Ebene 2
hat zwei Hashtags vor dem Leerzeichen
### Formatierungen
Heute schreibe **ich** einen **fetten** Text über das *tolle* und _einfache_ Markdown.
Man kann auch Text ~~durchstreichen~~ oder ==hervorheben==.
## Links
Ich gehe ans [[GRg3\|GRg3]] in der [Hagenmüllergasse](https://www.grg3.at).
```
[[interner Link]]
[Bildschirmanzeigetext](externe URL)
```
**Interne** Links macht man mit ==doppelten eckigen== Klammern.
**Externe** Links mit dem Anzeigetext in ==einfacher eckiger== Klammer und anschließend die Ziel-URL in ==runder== Klammer. Man erkennt diese am Pfeil-aus-Box-Symbol danach.
## Zitate
mit einem > Zeichen einleiten
> "Ich weiß, dass ich nichts weiß" - Sokrates
## Escape-Charakter
wenn ich Markdown-==Sonderzeichen== anzeigen lassen will
z.B. Schüler\*innen
~~~
Schüler\*innen
~~~
dafür einen ==Backslash \\== (Alt Gr + ß) vorher einfügen
## Codeblock
~~~
```
Codeblock wird nicht formatiert braucht keinen Escape-Charakter
```
~~~
```
~~~
startet und endet entweder mit 3 Backticks ` oder Tilden ~ 
~~~
```
## Bilder einbetten
### externe Bilder
werden live eingebettet
mit ==Rufzeichen !== davor wird es eingebettet
mit der ==Pipe |== (Alt Gr + <) kann man die Bildbreite in Pixel bestimmen
```
![optionaler Anzeigetext|Pixelbreite](Link zur Bilddatei) 

![200](https://www.grg3.at/wp-content/uploads/2018/11/cropped-GRg3_5x5_transparent_positiv.png)
```
![200](https://www.grg3.at/wp-content/uploads/2018/11/cropped-GRg3_5x5_transparent_positiv.png)
![300](https://www.grg3.at/wp-content/uploads/2026/10/PXL_20261001_110759541.MP_-1024x576.jpg)
### Copy/Paste lokal
ein Bild aus dem Zwischenspeicher wird mit Strg+V eingefügt, dabei wird das Bild im Vault gespeichert, die Datei heißt zB **Pasted image 1.png** und erscheint links in der Navigation
~~~
![[Pasted image 20261021152753.png|400]]
|400 für bestimmte Pixelbreite
~~~
![[Pasted image 20261021152753.png\|400]]
## Listen
Enter: nächstes Listenelement beginnen
Shift + Enter: für eine neue Zeile beim aktuellen Listenelement
### ungeordnete Listen
starten mit -, * oder + und danach ein Leerzeichen
- M
- D
- E
- je nach Schultyp:
	- RG: L oder F
	- G: L und F
### geordnete Listen
starten mit Zahl und dann . oder )
1. Aufstehen
2. Frühstücken
3. Anziehen
4. Zähne putzen
	1. Bürste befeuchten
	2. Zahnpasta auftragen
	3. 2 Minuten lang putzen
	4. spülen
5. Jause packen
### ToDo-Listen
Abstand jeweils nach ==-== , ==\[== und  ==\]==
Unteraufgaben mit Tabulator einrücken
~~~
- [ ]   unerledigte Aufgabe
- [X]     erledigte Aufgabe
- [ ]   unerledigte Hauptaufgabe     
	- [x] erledigte Unteraufgabe
~~~
- [ ] Markdown lernen
	- [x] Navigation mit der Tastatur
	- [x] Wichtige Tastenkombinationen
	- [x] Formatierung-Basics
	- [x] Ebene 2
	- [x] Links
	- [x] Zitate
	- [x] Escape
	- [x] Code
	- [x] Bilder
	- [x] Listen
		- [x] ungeordnete Listen
		- [x] geordnete Listen
		- [x] ToDo-Listen
	- [x] Code
	- [x] Tabellen
	- [x] Ablaufdiagramme
	- [ ] Dataview

# Tabellen
```
| Fach | Lehrkraft   |
| ---- | ---------   |
| M    | Reisner     |
| D    | Vit-Eckert  |
| E    | Wunder      |
```
über Rechtsklick > Einfügen > Tabelle
erstellt eine leere 2x2-Tabelle
==Enter== in der letzten Zeile erzeugt neue Tabellenzeile

| Fach | Lehrkraft          |
| ---- | ------------------ |
| M    | Reisner            |
| D    | Vit-Eckert         |
| E    | Wunderl            |
| F    | Steinhauser-Talbot |
| L    | Sachatonicsek      |
# Ablaufdiagramme
### Syntax für Mermaid-Flowchart-Diagramme:
```
~~~mermaid
--- 
title: Titel 
---
flowchart TD (für Top-Down) oder flowchart LR (für von links nachs rechts)
Kürzel[Bezeichnung im Diagramm]
Kürzel["❤ Unicode in Anführungszeichen"]
Quellkürzel --> Zielkürzel
Quellkürzel --> Zielkürzel 1 & Zielkürzel 2
~~~
```
### Code:
```
~~~mermaid
--- 
title: Schultypwahl 
---
flowchart TD

5 --> 6
6 --> 7K & 7M
7K --> 8K
7M --> 8M
8M & 8K--> M

5[5. Klasse]
6[6. Klasse]
7M[7. Klasse mit Musik]
7K[7. Klasse mit Kunst]
8M[8. Klasse mit Musik]
8K[8. Klasse mit Kunst]
M[Matura]   
~~~
```
### gerendert:
~~~mermaid
--- 
title: Schultypwahl 
---
flowchart TD

5 --> 6
6 --> 7K & 7M
7K --> 8K
7M --> 8M
8M & 8K--> M

5[5. Klasse]
6[6. Klasse]
7M[7. Klasse mit Musik]
7K[7. Klasse mit Kunst]
8M[8. Klasse mit Musik]
8K[8. Klasse mit Kunst]
M[Matura]   


~~~
