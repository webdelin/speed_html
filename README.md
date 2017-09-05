<h1>Hauptressource:</h1>
	<p>Node.js: https://nodejs.org/de/</p>
	<p>Gulp: http://gulpjs.com/</p>
	<p>Bower: http://bower.io/</p>
	<p>Browsersync: https://browsersync.io/</p>
	<p>Github: https://github.com/</p>
	<p>Autor: https://www.webdelin.de</p>
---
SPEED HTML Entwicklungsumgebung von webdelin.de<br>
<a target="_blank" href="http://www.youtube.com/watch?v=SzEjbi9h7KU">Anleitungsvideo</a>
---
<strong>Entwicklungsumgebung der Routineaufgaben für Webentwicklung zu automatisieren hilft.</strong><br>
Aufgaben wie zum Beispiel:
<ol>
	<li>Erstellung einen Automatisierten WebServer auf nodejs und automatische Neuladen der Seite im Browser nach speichern;</li>
	<li>Unterstützt einer vielzahl von Scripte wie JavaScript, CSS und HTML Preprocessoren (Coffeescript, Less, Sass, Stylus, Jade, etc.);</li>
	<li>Minifizierung von CSS und JS Scripten, sowie die Optimierung und die Verkettung der einzelnen Projektdateien in ein Datei;</li>
	<li>Automatische erstellt von CSS Präfixe (Vorsilben auf den Namen von CSS-Eigenschaften, die den Browser-Hersteller für benutzerdefinierte Eigenschaften hinzugefügt werden "-moz-,-ie-,-o-,-webkit-") für CSS;</li>
	<li>Verwaltung von Dateien und Ordnern in dem Projekt - Erstellen, Löschen, Umbenennen;</li>
	<li>Steuerung mit der Betriebssystembefehle (Konsole);</li>
	<li>Automatische komprimierung von Bildern (png, jpg, svg, und andere.)</li>
	<li>Mit deploy (Fertige Projekt senden an einen externen WebServer) Projekt im ordner dist per FTP, SFTP, Git, usw. hochladen</li>
	<li>Verwendung von unendlich vielen Node.js und Gulp Utilities, Programme und Plug-Ins.</li>
</ol>
<p>Ich kann mit Sicherheit sagen, dass diese Entwicklungsumgebung mit viele Werkzeuge für jede Aufgabe in der Webentwicklung geeignet ist, von kleine bis ganz große Komplexe Webprojekte.</p>
<p>Entwicklungsumgebung mit Gulp hat gulpfile.js Datei die eine Reihe von Anweisungen(task) enthält die für das Projektmanagement und ablauf wichtig sind. Gulp Anweisungen werden geschrieben in JavaScript, im Grunde alle Anweisungen(task) haben des gleichen Typs und gemeinsame Merkmale.</p>
---
<h2>Anleitung:</h2>
<strong>Die Daten mit HTML/PHP, IMG, SASS, JS und Fonts befindet sich im ordner "/app/" rohdaten</strong>
<ol>
	<li>Installiere Node.js: https://nodejs.org/de/</li>
	<li>Öffne konsole im projekt und installiere alle Packette <code>npm i</code> // Alle benötigte packette werde aus der package.json Installiert</li>
	<li>Mit <code>gulp</code> starte Entwicklungsumgebung</li>
	<li>Mit <code>build</code> wird fertige projekt im ordner /dist/ erstellt "alle scripte alle bilder werden komprimiert"</li>
	<li>Mit <code>deploy</code> wird fertige projekt von ordner /dist/ per FTP übertragen</li>
</ol>
---
<h3>mögliche Fehler:</h3>
"bower ENOGIT git is not installed or not in the PATH"
Dann diese befehl in der konsole von Projektordner ausführen.<br>
<code>git init</code> oder <code>set PATH=%PATH%;C:\Program Files\Git\bin;</code>
---