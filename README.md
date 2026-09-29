# LoL Assistant — Installer & Updates

Hier liegen die fertigen Installer für **LoL Assistant**. Quellcode gibt es hier
keinen, der liegt in einem privaten Repository. Dieses Repo existiert nur, damit
die App ihre Updates ohne Anmeldung herunterladen kann.

## Installieren

1. Unter [Releases](../../releases/latest) die Datei
   `LoL-Assistant-Setup-<version>.exe` herunterladen.
2. Doppelklick. Windows SmartScreen meldet sich, weil die Datei nicht signiert
   ist — **Weitere Informationen → Trotzdem ausführen**.
3. Installiert wird nur für dein Benutzerkonto, es gibt also keine
   Administrator-Abfrage.

## Beim ersten Start

Die App fragt einmalig nach einem **Riot-API-Key** und startet danach neu.
Ohne Key funktioniert sie nicht.

Im Installer steckt bewusst kein Key: alles, was hier zum Download liegt, kann
jeder öffnen. Der eingetragene Key bleibt auf dem Rechner, landet nur in der
lokalen Datenbank und wird an niemanden außer Riot geschickt.

## Updates

Nichts zu tun. Die App sucht beim Start selbst nach einer neuen Version, lädt sie
im Hintergrund und meldet sich erst, wenn sie bereit ist. Ein Klick auf **Jetzt
neu starten** installiert sie in wenigen Sekunden; wer die App stattdessen
einfach schließt, hat das Update beim nächsten Start.

Accounts, Matches, Einstellungen und der Key bleiben dabei erhalten.

---

Privates Projekt für einen kleinen, privaten Nutzerkreis.

LoL Assistant isn't endorsed by Riot Games and doesn't reflect the views or
opinions of Riot Games or anyone officially involved in producing or managing
Riot Games properties. Riot Games, and all associated properties are trademarks
or registered trademarks of Riot Games, Inc.
