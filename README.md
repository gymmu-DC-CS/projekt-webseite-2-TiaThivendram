[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/pAqJXfzR)


05.03 
Was wollte ich machen?
Ich wollte das Gründgerüst vom HTML machen und erste Informationen zu Sri Lanka sammeln.

Hilfe:
Sie haben es vor gezeigt.

Was ich gelernt habe:
Ich habe gelernt, wie ein HTML-Grundgerüst auf Visual Studio aufbaut. 

Umsetzung im Projekt:
Ich habe die Grundstruktur für meine Website erstellt und erste Inhalte eingefügt.



12.03 
Was wollte ich machen?
Ich wollte eine Tabelle erstellen und Inhalte übersichtlich darstellen. Dazu wollte ich noch ein Bild hinzzufügen.

Hilfe:
KahnAcademy
Chatgpt

quelle für Geschihte:https://travel-eat-love.de/sri-lanka/die-geschichte-sri-lankas/
quelle für Geographische Lage: https://de.wikipedia.org/wiki/Sri_Lanka#Geographie

Was ich gelent habe:
was padding ist (Abstand innerhalb der Zelle)
wie man Bilder zuschneidet mit object-fit

Umsetzung im Projekt:
Ich habe eine Tabelle erstellt und Bilder eingefügt. Ausserdem habe ich das Design mit CSS verbessert.

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
Was wollte ich machen?
Ich wollte JavaScript ausprobieren. --> hat nicht funktioniert und noch Informationen zur Bevölkerung finden.

Hilfe:
https://www.w3schools.com/js/js_output.asp

Was ich gelernt habe:
Ich habe erste Grundlagen zu JavaScript angeschaut, aber noch nicht alles verstanden.

Umsetzung im Projekt:
Der Code hat noch nicht funktioniert, aber ich habe erste Erfahrungen gesammelt.

Bevölkerung Quellen: 
https://colombo.embassy.qa/en/sri-lanka/info
https://ceylon.anilau.com/de



19.03
Was wollte ich machen?
Ich wollte mehr Inhalte hinzufügen und das Layout verbessern.

Infos zur Religion:
https://en.wikipedia.org/wiki/Religion_in_Sri_Lanka

Bildung:https://www.lankahelp.org/blog/wissenswertes-ueber-sri-lanka/schulsystem/

Was ich gelernt habe:
Ich habe gelernt wie man Inhalte strukturiert und wie man den abstand zwischen der Überschrift und dem Text zu verkleinern.

Umsetzung im Projekt:
Ich habe Informationen zu Religion und Bildung hinzugefügt.
Ich habe versucht, ein Bild neben den Text zu setzen, was noch nicht ganz funktioniert hat.



26.03
Was wollte ich machen?
Ich wollte auf der linken Seite wie ein Inhaltsverzeichnis machen.

Hilfe:
Chatgpt 

Was ich gelernt habe:

position: fixed → Element bleibt beim Scrollen sichtbar
margin → Abstand aussen
hover → Effekt bei Mausbewegung

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
Was wollte ich machen?
Ich wollte den Hintergrund ändern und noch eine Einleitung über Sri Lanka und über die Küche geschrieben. Ich wollte noch so ein Slide für Essenbider machen.

Hilfe:
YouTube
Chatgpt

Küche Quelle: https://reisehappen.de/essen-in-sri-lanka/

Was ich gelernt habe:
Ich habe gelernt wie ein einfacher Bild-Slider funktioniert.

Umsetzung im Projekt:
Ich habe eine Einleitung geschrieben, den Hintergrund geändert und einen Slider für Essensbilder erstellt.



10.04.26
Was wollte ich machen?
Ich wollte versuchen die Bilder beim Essen näher zu machen, aber hat nicht funktioniert, aber so ist es auch gut. Ich wollte den Javascrip hinzufügen. Wenn man den Pfeil drückt bringt es einem von unten bis wieder nach oben.

Hilfe:
W3Schools
Chatgpt
YouTube

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

Was ich gelernt habe:

onclick → reagiert auf Klick
function() → führt Code aus
window.scrollTo() → scrollt im Browser
behavior: "smooth" → weiches Scrollen

Umsetzung im Projekt:
Ich habe einen Button erstellt, der beim Klicken die Seite sanft nach oben scrollt.

Nicht alles funktioniert sofort, aber durch Ausprobieren habe ich es am Ende fast alles geschafft.

Für manche Dinge für HTML, CSS und JavaScript habe ich von KahnAcademy, W3Schools und habe auch sonst wo noch im Internet geschaut. Ich habe auch ein paar YouTube Videos angeschaut.

14.04.26
Ich habe mein Readme besser strukturiert.

