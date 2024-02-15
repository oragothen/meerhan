---
layout: post
title:  "Technisches Setup"
date:   2024-02-15 14:45:00 +0100
imgs: 
  - path: assets/img/pedro.jpg
    desc: "Image of a grumpy cat"
---
Entgegen meiner gestrigen Ansage jetzt doch schon ein weiterer Post. 
<br> 
Da mein Indonesienaufenthalt ohne Laptop stattfinden wird, brauche ich eine gute Möglichkeit, um vom Handy aus zu posten. Die ganze Website ist ja über Github gehosted und funktioniert wie eine Maschine, in die Git Commits rein gehen, und aus der Website raus kommt. Das bedeutet aber auch, dass ich die Commits (Text und Bild) von meinem Mobilfunkendgerät irgendwie erstellen und nach Github bekommen muss. 
<br> 
Die Möglichkeiten dafür (zumindest die, an die ich gedacht habe) sind: 
<ul> 
<li> Github Web Interface: kann mehr oder weniger alles, aber sehr clunky - gerade der Upload von mehreren Bildern ist sehr Pain</li>
<li> Github App: Weniger clunky, kann aber keine Dateien hoch laden - nur inline erstellen. Damit könnte ich die Posts schreiben, aber keine Bilder hoch laden </li>
<li> SSH auf meinen Pi: erlaubt einfaches Scripten in einer angenehmen Umgebung, aber Bilder dahin bekommen ist etwas tricky</li>
<li> Termux und Git CLI: Pain. Theoretisch vermutlich möglich, aber erfordert manuelles Registrieren/Erstellen eines RSA Keys, Navigation durch das Android Filesystem per Handytastatur und CLI-basiertes Committen und Pushen - Nein danke </li>
<li> MGit: Erlaubt einfaches Interfacen mit einem Git-Repo. Bilder kann ich manuell in den lokalen Ordner kopieren, Text per Texteditor schreiben und dann per App pushen. Problem: die App "braucht" vollen Dateisystemzugriff oder funktioniert nicht. Das sind Rechte, die Google nicht mal <a href="https://i.kym-cdn.com/entries/icons/facebook/000/017/046/BptVE1JIEAAA3dT.jpg">mir selbst</a> anvertraut und so weit ist unsere Beziehung noch nicht fortgeschritten, dass ich dieser App das anvertraue.</li>
<li> SPCK Code Editor: Naja, es funktioniert. Ich kann Dateien von extern importieren, zusammen committen, und pushen. Etwas weniger praktisch als MGit (wenn "es funktioniert" als Vorraussetzung ignoriert wird). Bonus: es gibt einen eingebauten Code Editor </li>
</ul> 
Ich habe mich für die letzte Variante entschieden - die scheint mir im Moment einfach die Robusteste. Falls Sie, werte Lesende Person, diesen Post lesen, dann funktioniert die Methode auch. 
Angehängt habe ich ein Bild das mit all dem nichts zu tun hat - das ist Pedro/Leo, unsere Nachbarskatze. 