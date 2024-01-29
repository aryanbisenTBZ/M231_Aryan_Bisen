Anzeigen, Bearbeiten und Löschen von Cookies:
Verwenden Sie den Bereich Cookies des Anwendungstools , um die HTTP-Cookies für eine Webseite anzuzeigen, zu bearbeiten und zu löschen.

1. Öffnen Sie DevTools, indem Sie F12 oder STRG+UMSCHALT+I
2. Wählen Sie in DevTools Anwendung(Application) aus. Wenn diese Registerkarte nicht angezeigt wird, klicken Sie auf die Schaltfläche Weitere Tools (Symbol weitere Tools) und dann auf Anwendung. Der Bereich Manifest wird in der Regel standardmässig geöffnet:
{Bild}
3. Wählen sie unter Speicher "Cookies" aus.
Dieser Bereich enthält folgende Felder:
(Quelle: https://learn.microsoft.com/de-de/microsoft-edge/devtools-guide-chromium/storage/cookies)
Name. Der Name des Cookies.

Wert. Der Wert des Cookies.

Domäne. Die Hosts, die das Cookie empfangen dürfen. Weitere Informationen finden Sie unter Umfang der Cookies.

Pfad. Die URL, die in der angeforderten URL vorhanden sein muss, um den Cookie Header zu senden. Weitere Informationen finden Sie unter Umfang der Cookies.

Läuft ab/Max-Age. Das Ablaufdatum oder das maximale Alter des Cookies. Siehe Permanente Cookies. Bei Sitzungscookies ist dieser Wert immer Session.

Größe. Die Größe des Cookies in Bytes.

HttpOnly. Wenn true, gibt dieses Feld an, dass das Cookie nur über HTTP verwendet werden soll und keine JavaScript-Änderung zulässig ist. Weitere Informationen finden Sie unter HttpOnly-Cookies.

Sicher. Gibt truedieses Feld an, dass das Cookie nur über eine sichere HTTPS-Verbindung an den Server gesendet werden muss. Weitere Informationen finden Sie unter Sichere Cookies.

SameSite. Enthält strict oder lax , wenn das Cookie das experimentelle Samesite-Attribut verwendet.

SameParty. Dieses Attribut bietet Webentwicklern eine Möglichkeit, Cookies zu kommentieren, die in websiteübergreifenden Kontexten derselben Partei festgelegt oder gesendet werden dürfen.

Partitionsschlüssel. Der Partitionsschlüssel eines Cookies ist nur vorhanden, wenn das Cookie im partitionierten Speicher festgelegt wird und der Website der obersten Ebene entspricht, auf der das Cookie ursprünglich erstellt wurde. Weitere Informationen finden Sie unter Cookies mit einem chips-Ursprung (Independent Partitioned State).

Priorität. Enthält low, medium (Standard) oder high , wenn das Cookie das veraltete Attribut Cookiepriorität verwendet.

Bearbeiten von Cookies:
Die Felder Name, Wert, Domäne, Pfad und Ablauf/Max-Age können bearbeitet werden. Doppelklicken Sie auf ein Feld, um es zu bearbeiten
