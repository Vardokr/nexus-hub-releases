# NEXUS HUB

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

Die verfügbaren Bearbeitungsfunktionen richten sich nach der bestätigten Clan-Rolle und den Datenbankberechtigungen.

## Download & Installation

1. Öffne die [Releases](https://github.com/Vardokr/nexus-hub-releases/releases).
2. Lade die Setup-Datei der gewünschten Version herunter.
3. Starte den Installer und folge den Anweisungen.

Dieses Repository dient der Bereitstellung von Installationsdateien und Updates.

## Ersteinrichtung

Der Einrichtungsassistent führt dich durch die Konfiguration:

1. Eigene Firebase-Realtime-Database verbinden.
2. Wargaming-API-Zugang eintragen.
3. Den gewünschten Clan auswählen.
4. Optional Discord-Webhooks hinterlegen.

Jeder Clan verwendet seine eigene Firebase-Instanz. Es besteht keine automatische Verbindung zur Datenbank eines anderen Clans.

Die Firebase-Zugriffsregeln müssen passend eingerichtet werden; die Einrichtung der App ersetzt diese Absicherung nicht.

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

Bitte entferne Zugangsdaten, Webhook-Adressen und persönliche Informationen vor der Veröffentlichung.

[Fehler melden oder Verbesserung vorschlagen](https://github.com/Vardokr/nexus-hub-releases/issues)

## Entwicklung unterstützen

Wenn dir NEXUS HUB hilft, kannst du die Weiterentwicklung freiwillig unterstützen:

[Buy me a coffee](https://buymeacoffee.com/vardokr)

## Hinweis

NEXUS HUB ist ein unabhängiges Community-Projekt und kein offizielles Produkt von Wargaming. World of Tanks und zugehörige Marken gehören ihren jeweiligen Rechteinhabern.
