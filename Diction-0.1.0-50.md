## Diction 0.1.0

- Debug-Hooks workflow und format für lokale Text-Tests, kurzer Name für Standard-Sprachmodell (Closes #38)
- Lokales Sprachmodell für Workflows und Diktat-Formatierung: TextEngine, LocalText/local_text.py, Einstellung Claude/Lokal (#38)
- Lokale Transkription geprüft: Ausweichen auf ElevenLabs, Dateien über den Worker (Closes #37)
- Diktat und Dateien lokal transkribieren über den gemeinsamen Worker (#37)
- Gespräch direkt aufnehmen: Systemaudio-Tap + Mikrofon, Insel mit Zeit und Stopp, danach mit Sprechern abschreiben
- Lokal: Download-Fortschritt aus Netz-Bytes, Debug-Hooks für Einstellungen und Modelle (Closes #36)
- Lokale Laufzeit: gemeinsame uv-Umgebung, Prozess je Fähigkeit, Modellverwaltung, Einstellungen „Lokal“ (#36)
- Dateien: Sprechererkennung, Transkript-Fenster mit Namen und Markdown-Export, Anbieter Apple und lokal (#11)
- Dateien: Kurzfassung per Claude, Workflows aufs Ergebnis, Verlauf, Öffnen mit/Dienst, Warteschlange (#11)
- Audiodateien abschreiben: zur Menüleiste ziehen, Insel als Ablagefläche, Ergebnis-Karte, Einstellungen „Dateien“ (#11)
- Diktat: bei Automatisch nur Deutsch/Englisch, sonst neu mit Deutsch transkribieren (#34)
- Aufnahme-Insel nach Vorbild der Dynamic Island: Ziel-App, getönte Welle, größere Knöpfe, Stille-Hinweis (#33)
- Menüleiste: immer das Diction-Logo statt wechselnder Symbole
