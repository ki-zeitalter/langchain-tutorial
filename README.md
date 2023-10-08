# LangChain Tutorials

Willkommen zu meinem LangChain Tutorial von KI Zeitalter. Diese Notebooks bilden die Anschaungsmateralien und Experimente für die YouTube Tutorial-Reihe dar, die in Kürze auf dem KI Zeitalter YT-Kanal https://www.youtube.com/channel/UCuYeTFVuY9lxNGc_eCqeC6w erscheinen.

# Vorbereitungen

Die allermeisten Teile des Tutorials greifen auf die OpenAI-API zu (ChatGPT) zu. Hierfür benötigt man einen API-Key. Bitte beachte, dass die Verwendung der API kostenpflichtig ist. D.h. du must dir ein Kundenkonto anlegen und Zahlungsinformationen hinterlegen.
Die Kosten halten sich, sofern man nichts "Blödes" anstellt in Grenzen. Beim Ausprobieren der Codebeispiele in diesem Tutorial, sollten sich die Kosten im Bereich von wenigen Cents bis wenige Dollar bewegen.
Auf der Kontoverwaltungsseite von OpenAI kannst du dir jederzeit ein Limit einrichten. Damit kannst du auf jeden Fall vermeiden, dass du aus Versehen zu hohe Kosten verursachst.

Gehe auf https://platform.openai.com/signup um ein Konto zu erstellen.
Anschliessend kannst du unter https://platform.openai.com/account/api-keys dir einen API-Key erzeugen lassen. 
Meine Empfehlung: erstelle dir so viele Keys wie du brauchst. Z.B. einen für dieses Tutorial, einen für etwas anderes, usw. Nachdem du mit diesem Tutorial fertig bist, wiederrufe den Key einfach.

Den Key füge bitte in eine .env Datei im Hauptverzeichnis von diesem Projekt ein. Wie die Datei aussehen soll, siehst du in der Datei .env.template. Am Ende sollte es wie folgt aussehen:

```console
OPENAI_API_KEY=sk-NdsQ5.......................................9HM
```

Diese Datei wird nicht in Git eingecheckt!
