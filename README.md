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

Die App fragt nach einem **Riot-API-Key**. Den bekommst du von der Person, die
dir die App gegeben hat — einmal eintragen, neu starten, fertig.

Der Key steckt bewusst nicht im Installer: alles, was hier zum Download liegt,
kann jeder öffnen. So bleibt er bei dir auf dem Rechner, landet nur in der
lokalen Datenbank und wird an niemanden außer Riot geschickt.

## Updates

Nichts zu tun. Die App sucht beim Start selbst nach einer neuen Version, lädt sie
im Hintergrund und meldet sich erst, wenn sie bereit ist. Ein Klick auf **Jetzt
neu starten** installiert sie in wenigen Sekunden; wer die App stattdessen
einfach schließt, hat das Update beim nächsten Start.

Accounts, Matches, Einstellungen und der Key bleiben dabei erhalten.

---

Privates Projekt. Nicht mit Riot Games verbunden.
