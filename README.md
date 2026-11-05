<p align="center">
  <img src="docs/assets/logo-512.png" alt="NEXUS HUB" width="140">
</p>

<h1 align="center">NEXUS HUB</h1>

<p align="center">
  <b>Dein Clan. Eine Zentrale.</b><br>
  Das Clan Operations Center für World of Tanks
</p>

<p align="center">
  <a href="https://github.com/Vardokr/nexus-hub-releases/releases/latest"><b>Download</b></a> ·
  <a href="#ersteinrichtung">Ersteinrichtung</a> ·
  <a href="https://github.com/Vardokr/nexus-hub-releases/issues">Fehler melden</a>
</p>

<p align="center">
  <img src="docs/assets/dashboard.webp" alt="Dashboard von NEXUS HUB" width="900"><br>
  <sub>Beispielansicht mit Demodaten</sub>
</p>

---

NEXUS HUB ist eine Windows-Anwendung zur Verwaltung und Organisation von World-of-Tanks-Clans. Mitgliederverwaltung, Recruiting und Einsatzplanung kommen in einer gemeinsamen Oberfläche zusammen.

## Funktionen

- **Dashboard:** Die wichtigsten Clan-Informationen auf einen Blick.
- **Mitglieder & Personalakten:** Spielerwerte, Clan-Ränge, Notizen, Abwesenheiten und Discord-Kontaktdaten.
- **Clan-Wächter:** Beobachtung von Clans und Erfassung von Austritten für das Recruiting.
- **Recruiting:** Bewerbungen in Listen- und Board-Ansicht verwalten.
- **Spielersuche & Talent Scout:** Spieler finden und ihre Werte vergleichen.
- **Anforderungschecker:** Spieler anhand konfigurierbarer Kriterien prüfen.
- **Organisation:** Kalender, Teams, Ausbildung und Dienstgrade.
- **Operationen:** Manöver, Turniere, Kampagnen und Bollwerk.
- **Statistiken:** Auswertungen zu Mitgliederwerten und Aktivität.
- **Discord-Anbindung:** Benachrichtigungen über konfigurierbare Webhooks.
- **Lokaler Cache:** Bereits geladene Daten schneller bereitstellen.

Die verfügbaren Bearbeitungsfunktionen richten sich nach der bestätigten Clan-Rolle und den Berechtigungen.

## Download & Installation

1. Öffne die [Releases](https://github.com/Vardokr/nexus-hub-releases/releases).
2. Lade die Setup-Datei der gewünschten Version herunter.
3. Starte den Installer und folge den Anweisungen.

Dieses Repository dient der Bereitstellung von Installationsdateien und Updates.

## Ersteinrichtung

Alle Clans laufen auf einem zentralen NEXUS-Server. Du brauchst keine eigene Datenbank und keine eigenen Schlüssel. Jeder Clan ist über seinen Wargaming-Clan-Tag getrennt und sieht nur seine eigenen Daten.

Der Einrichtungsassistent fragt, was du bist:

1. **Ich leite den Clan** (Kommandant oder Stellvertreter): Mit Wargaming anmelden. Der Clan wird einmalig aktiviert, danach zeigt dir NEXUS HUB deinen **Clan-Code** im Format `XXXX-XXXX-XXXX`. Gib ihn an deine Mitglieder weiter.
2. **Ich bin Mitglied:** Clan-Code eintragen und mit Wargaming anmelden.
3. **Ich war schon dabei:** Deine vorhandenen Daten bleiben erhalten.

Optional kannst du Discord-Webhooks hinterlegen.

Der Server prüft bei jeder Anfrage, ob dein Wargaming-Account zum Clan gehört. Die Clan-Leitung kann unter **Einstellungen → Datenbank** jederzeit einen neuen Clan-Code erzeugen und die Verbindung testen.

## Updates

Die installierte Windows-Version kann nach veröffentlichten Updates suchen. Eine manuelle Prüfung findest du unter:

**Einstellungen → App Info → Nach Updates suchen**

Download und Installation werden in der Anwendung angeboten. Vor dem Neustart solltest du offene Eingaben speichern.

Wer bisher eine portable Version verwendet, muss einmal die Setup-Version installieren, um die integrierte Update-Funktion zu nutzen.

## Hilfe & Fehlerberichte

Die integrierte Hilfe erklärt die wichtigsten Funktionen.

Mit **Strg + Umschalt + L** öffnest du das Diagnoseprotokoll. Bei einem Fehlerbericht helfen:

- Verwendete NEXUS-HUB-Version
- Kurze Beschreibung und Schritte zum Nachstellen
- Screenshot oder relevanter Diagnoseauszug


[Fehler melden oder Verbesserung vorschlagen](https://github.com/Vardokr/nexus-hub-releases/issues)

## Entwicklung unterstützen

Wenn dir NEXUS HUB hilft, kannst du die Weiterentwicklung freiwillig unterstützen:

[Buy me a coffee](https://buymeacoffee.com/vardokr)

## Hinweis

NEXUS HUB ist ein unabhängiges Community-Projekt und kein offizielles Produkt von Wargaming. World of Tanks und zugehörige Marken gehören ihren jeweiligen Rechteinhabern.
