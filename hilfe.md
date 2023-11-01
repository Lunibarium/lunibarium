Hilfe
===

# Koordinaten anlegen
Die Karte mit Fundorten wird über ein `iframe` angelegt. Die genauen Koordinaten für einen Fundort können über das hierunter eingebundene Kartentool gesucht und kopiert werden.

Der benötigte Code für das `iframe` sieht wie folgt aus.

<pre>&lt;iframe src="map.html#51.651262,10.105047"&gt;</pre>

Wenn mehrere Fundorte eingetragen werden sollen, können die Koordinatensets einfach durch eine Pipe `|` getrennt werden. Für jedes Set wird ein eigener Marker in der Karte eingefügt.

<iframe src="koordinatenfinder.html" width="100%" style="border: none;" height="500px">