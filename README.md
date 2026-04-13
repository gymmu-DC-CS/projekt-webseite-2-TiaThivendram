[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/pAqJXfzR)

05.03 
Grundgerüst von HTML und angefangen ein paar infos zu sammeln.

12.03 
Tabelle gemacht. Infos und Bilder hinzugefügt.

quelle für Geschihte:https://travel-eat-love.de/sri-lanka/die-geschichte-sri-lankas/
quelle für Geographische Lage: https://de.wikipedia.org/wiki/Sri_Lanka#Geographie

 table {
        border-collapse: collapse;
    }
--> Raster für Tabelle (Chatgpt)

td, th {
    border: 1px solid black;
    padding: 4px 20px;
}
--> Raster grösse und padding -- abstand von den Wörter (Chatgpt)

#StrandmitPalme {
    width: 700px;
    height: 200px;
    object-fit: cover;
    object-position: center;
}
--> damit das bild geschnitten wird anstatt es zu dehnen (Chatgpt)

13.03
Javascrip nachgeschaut und ausprobier, aber nicht funktioniert. 
https://www.w3schools.com/js/js_output.asp

Infos zu Bevölkerung gesammelt.
Bevölkerung Quellen: 
https://colombo.embassy.qa/en/sri-lanka/info
https://ceylon.anilau.com/de

19.03
Infos zur Religion:
https://en.wikipedia.org/wiki/Religion_in_Sri_Lanka
HAbe versuch das Bild rechts neben den Text zu machen, aber hat irgndwie nich funktionier, werde vielleicht zu Hause das noch mal anschauen.
Bildung:https://www.lankahelp.org/blog/wissenswertes-ueber-sri-lanka/schulsystem/
Ich habe versuch den abstand zwischen der Überschrift und dem Text zu verkleinern.

26.03
position: fixed;
Element bleibt immer an derselben Stelle
auch wenn mann scrollt bleibt es sichtbar (wie bei Wikipedia)

body {
    margin: 0;
    margin-left: 250px;
}
Das verschiebt den ganzen Inhalt nach rechts und kein abstand zu oben

#inhalt a:hover {
    text-decoration: underline;
}
Es seht so aus als würde man einen link klicken. Macht linie unter dem Wort wenn man mit der Maus drauf geht.
Sehenswrdigkeiten Quelle
https://www.22places.de/sri-lanka-sehenswuerdigkeiten/
und auch noch von zu Hause
Habe Bilder neben dem Text hinzugefügt

27.03.26
Küche Quelle: https://reisehappen.de/essen-in-sri-lanka/
Ich habe heute den Hintergrund geändert und noch eine Einleitung und über die Küche geschrieben.
Ich habe so ein Slide Bilder Ding mit dem Essen gemacht.

10.04.26
Ich habe versucht die Bilder beim essen näher zu machen aber hat nicht funktioniert, aber so ist es auch gut. Ich habe den Javascrip hinzugefügt. Wenn man den Pfeil drückt bringt es einem von unten bis wieder nach oben.

JavaScript:
.onclick
Bedeutung: Wenn man drauf klickt. (sogenanntes Event)

= function () { ... }
Bedeutung: Das ist eine Funktion (eine Aktion)

window
Bedeutung: Das ist das Browser-Fenster

.scrollTo()
Bedeutung: Scrolle zu einer bestimmten Position.

{ top: 0 }
Bedeutung:
top = wie weit nach oben
0 = ganz oben

behavior: "smooth"
Bedeutung:
smooth = sanft / langsam scrollen
ohne das → würde es sofort springen

Für manche Dinge für HTML, CSS und JavaScript habe ich von KahnAcademy, dieser einten Seite wo wir benutzt haben als KahnAcedemy abgstürzt ist und habe auch sonst wo noch im Internet geschaut. Ich habe auch ein paar YouTube Videos angeschaut.

