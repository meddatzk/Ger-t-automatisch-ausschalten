# Gerät automatisch ausschalten

Dieser Home Assistant Blueprint ermöglicht es dir, ein beliebiges Gerät automatisch auszuschalten, nachdem es für eine bestimmte Zeit eingeschaltet war. Du kannst die Zeitdauer zwischen 1 und 90 Minuten wählen und die Entität des Geräts auswählen.

## Konfiguration

Um diesen Blueprint zu verwenden, gehe wie folgt vor:

1. Klicke auf den Button **Automatisierung hinzufügen** unten.
[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://raw.githubusercontent.com/meddatzk/Ger-t-automatisch-ausschalten/main/geraet_auto_aus.yaml)
3. Wähle den gewünschten Trigger und fülle die erforderlichen Felder aus.
4. Klicke auf **Blauenprint importieren**.
5. Wähle den "Gerät automatisch ausschalten"-Blueprint und fülle die erforderlichen Felder aus.

Nachdem der Blueprint importiert wurde, kannst du ihn in deinem Home Assistant Dashboard verwenden und die folgenden Einstellungen vornehmen:

- **Gerät Entität**: Wähle die Entität des Geräts aus, das automatisch ausgeschaltet werden soll.
- **Minuten bis zum Ausschalten**: Wähle die Anzahl der Minuten, nach denen das Gerät ausgeschaltet werden soll (zwischen 1 und 90 Minuten).

## Anwendung

Nachdem du den Blueprint konfiguriert hast, wird er automatisch aktiviert, wenn das ausgewählte Gerät eingeschaltet wird. Das Gerät wird dann nach der ausgewählten Zeit automatisch ausgeschaltet.

