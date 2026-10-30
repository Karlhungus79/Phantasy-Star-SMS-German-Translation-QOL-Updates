# Phantasy Star (Sega Master System) – German Translation / Deutsche Übersetzung

**Version 1.0** · Release: 30.10.2026 · Author: **Karlhungus**
Platform: Sega Master System

**English** | [Deutsch](#deutsch)

> Unofficial fan translation, not affiliated with or endorsed by SEGA.
> No ROM is included – you need your own copy of the game. This project distributes a patch file only, never a patched ROM.

---

# English

A complete German fan translation of the original **Phantasy Star** (SEGA, 1987/88) for the Sega Master System, based on the English export version – plus a set of quality-of-life extensions in the spirit of the later Phantasy Star games.

## Download

[`patches/v1.0/PS1_SMS_German_v1.0.bps`](patches/v1.0/PS1_SMS_German_v1.0.bps) – checksums in [`patches/v1.0/checksums_v1.0.txt`](patches/v1.0/checksums_v1.0.txt).

## The translation

| | |
|---|---|
| Dialogue (341 sections), narration (23 pages), system and battle messages (174) | translated, proofread |
| Menus, battle commands, status window, shops | translated (windows rebuilt for longer German words) |
| Title screen (CONTINUE → FORTSETZEN), name entry, credits headings | translated |
| Item, weapon and armour names | **original English** (also when named inside a German sentence) |
| Enemy names | **original English** |
| Spell names | **original English** (HEAL, FIRE, THUN, …) |
| Character and place names | original: Alis, Myau, Odin, Noah, Lutz – Palma, Motavia, Dezoris |

- Umlauts Ä, Ö and Ü are displayed correctly (new tile in the font). The game only has capital letters, so ß is written as SS.
- Keeping item, enemy and spell names in English was a deliberate decision: they are part of the series' identity and fans know them in this form.
- To make room for the German text, the ROM was expanded from 512 KB to 1 MB. Text, dictionary, menus and the new code live in the new banks.

## Quality-of-life features

All extras are built into the patch.

- **OPTIONEN** – a new 6th entry in the field menu below SPEICHERN (save):
  - **ERF. UND MESETA 1X / 2X / 4X** – multiplies experience and meseta from battles.
  - **SCHNELLER LAUFEN JA / NEIN** – walk at vehicle speed on the overworld, in towns and in dungeons; the party follows correctly.
  - **ZUFALLSKÄMPFE AN / AUS** – random encounters on/off (overworld and dungeons). Boss and story battles are not affected.
  - **MAKROS** – macro editor (see below).
- **Battle macros** (inspired by Phantasy Star IV): set up four macros, each with one command per party member – ANGRIFF (attack), MAGIE (spell) or WARE (item). In battle, the new command **MAKRO** executes a whole round with one selection. If a spell lacks MP or an item is used up, that member attacks instead. Healing spells automatically target the party member with the biggest HP loss.
- **Battle turbo:** hold **button 1** during a battle round to play it at roughly double speed.
- The options and macros are stored once in battery RAM and apply to all save slots.

## Required ROM

| | |
|---|---|
| Game | Phantasy Star (USA/Europe, English export version) |
| Size | 524,288 bytes (512 KB) |
| CRC32 | `00BEF1D7` |
| MD5 | `1110938df80f4e44c8213d7f85cfb5e6` |
| SHA-1 | `07fcf297be4f4c9d92cd3f119a7ac48467e06838` |

The BPS patch checks the source ROM and refuses any other file.

## How to patch

1. Download [Floating IPS (Flips)](https://www.smwcentral.net/?p=section&a=details&id=11474) or use the browser tool [Rom Patcher JS](https://www.marcrobledo.com/RomPatcher.js/).
2. Apply `PS1_SMS_German_v1.0.bps` to your English ROM.
3. Save the result as e.g. `Phantasy Star (DE) v1.0.sms`.

Command line: `flips.exe --apply PS1_SMS_German_v1.0.bps "Phantasy Star (USA, Europe).sms" "Phantasy Star (DE) v1.0.sms"`

Expected result: 1,048,576 bytes, CRC32 `7A3870F2`, SHA-1 `dfe64058479f0e9c49a7aeeac409f610ec06d3df`.

## Notes

- **Start a new game.** Saves from the English version or other builds are not guaranteed to work.
- Tested in emulators. Real hardware (e.g. EverDrive) has not been tested yet – feedback is welcome.
- Found a mistake? Please open an [issue](../../issues) with a screenshot and, if possible, the place in the game.

## Credits

- **Karlhungus (Marcel)** – project lead, translation, testing
- **Claude (Anthropic)** – technical support (text system, ROM expansion, Z80 code, build tools)
- Phantasy Star SMS disassembly (created with SMS Examine, assembled with WLA-DX) – basis for the analysis
- Tools: WLA-DX, Floating IPS by Alcaro, Genesis Plus GX (automated tests), ares
- Macro idea: *Phantasy Star IV* (SEGA, 1993)

YouTube: https://www.youtube.com/@rgbretrogaming

## Legal

This is an unofficial fan project and not affiliated with SEGA. The patch contains no complete game data; you need your own legally obtained copy of the game. Phantasy Star is a trademark of SEGA.

---

<a id="deutsch"></a>

# Deutsch

Eine vollständige deutsche Fan-Übersetzung des ersten **Phantasy Star** (SEGA, 1987/88) für das Sega Master System, auf Basis der englischen Export-Version – dazu Komfortfunktionen im Stil der späteren Phantasy-Star-Teile.

## Download

[`patches/v1.0/PS1_SMS_German_v1.0.bps`](patches/v1.0/PS1_SMS_German_v1.0.bps) – Prüfsummen in [`patches/v1.0/checksums_v1.0.txt`](patches/v1.0/checksums_v1.0.txt).

## Die Übersetzung

| | |
|---|---|
| Dialoge (341 Abschnitte), Erzähltexte (23 Seiten), System- und Kampfmeldungen (174) | übersetzt, gegengelesen |
| Menüs, Kampfbefehle, Statusfenster, Läden | übersetzt (Fenster für längere deutsche Wörter neu aufgebaut) |
| Titelbild (CONTINUE → FORTSETZEN), Namenseingabe, Abspann-Überschriften | übersetzt |
| Gegenstände, Waffen, Rüstungen | **englische Originalnamen** (auch wenn sie im deutschen Text vorkommen) |
| Gegnernamen | **englische Originalnamen** |
| Zaubernamen | **englische Originalnamen** (HEAL, FIRE, THUN, …) |
| Figuren und Orte | Originalnamen: Alis, Myau, Odin, Noah, Lutz – Palma, Motavia, Dezoris |

- Die Umlaute Ä, Ö und Ü werden korrekt dargestellt (neues Tile im Zeichensatz). Das Spiel kennt nur Großbuchstaben, ß wird deshalb als SS geschrieben.
- Gegenstands-, Gegner- und Zaubernamen bleiben bewusst englisch: Sie gehören zur Identität der Reihe und sind Fans in dieser Form bekannt.
- Für den deutschen Text wurde das ROM von 512 KB auf 1 MB erweitert. Texte, Wörterbuch, Menüs und der neue Code liegen in den neuen Bänken.

## Komfortfunktionen (QOL)

Alle Extras sind fest im Patch eingebaut.

- **OPTIONEN** – neuer 6. Punkt im Hauptmenü unter SPEICHERN:
  - **ERF. UND MESETA 1X / 2X / 4X** – vervielfacht Erfahrung und Meseta aus Kämpfen.
  - **SCHNELLER LAUFEN JA / NEIN** – Laufen in Fahrzeug-Geschwindigkeit auf der Oberwelt, in Städten und in Dungeons; die Gruppe folgt korrekt.
  - **ZUFALLSKÄMPFE AN / AUS** – Zufallskämpfe an/aus (Oberwelt und Dungeons). Boss- und Story-Kämpfe bleiben unberührt.
  - **MAKROS** – Makro-Editor (siehe unten).
- **Kampf-Makros** (nach dem Vorbild von Phantasy Star IV): vier Makros mit je einem Befehl pro Figur – ANGRIFF, MAGIE oder WARE. Im Kampf führt der neue Befehl **MAKRO** eine ganze Runde mit einer Auswahl aus. Fehlen MP oder ist ein Gegenstand aufgebraucht, greift die Figur stattdessen an. Heilzauber treffen automatisch das Mitglied mit dem größten HP-Verlust.
- **Kampf-Turbo:** **Taste 1** während einer Kampfrunde gedrückt halten – die Runde läuft etwa doppelt so schnell.
- Optionen und Makros werden einmal im Batterie-RAM gespeichert und gelten für alle Spielstände.

## Benötigtes ROM

| | |
|---|---|
| Spiel | Phantasy Star (USA/Europa, englische Export-Version) |
| Größe | 524.288 Byte (512 KB) |
| CRC32 | `00BEF1D7` |
| MD5 | `1110938df80f4e44c8213d7f85cfb5e6` |
| SHA-1 | `07fcf297be4f4c9d92cd3f119a7ac48467e06838` |

Der BPS-Patch prüft das Ausgangs-ROM und lehnt andere Dateien ab.

## Patch anwenden

1. [Floating IPS (Flips)](https://www.smwcentral.net/?p=section&a=details&id=11474) herunterladen oder das Browser-Tool [Rom Patcher JS](https://www.marcrobledo.com/RomPatcher.js/) nutzen.
2. `PS1_SMS_German_v1.0.bps` auf das englische ROM anwenden.
3. Ergebnis z. B. als `Phantasy Star (DE) v1.0.sms` speichern.

Kommandozeile: `flips.exe --apply PS1_SMS_German_v1.0.bps "Phantasy Star (USA, Europe).sms" "Phantasy Star (DE) v1.0.sms"`

Erwartetes Ergebnis: 1.048.576 Byte, CRC32 `7A3870F2`, SHA-1 `dfe64058479f0e9c49a7aeeac409f610ec06d3df`.

## Hinweise

- **Bitte ein neues Spiel beginnen.** Spielstände der englischen Version oder anderer Builds funktionieren nicht zuverlässig.
- Getestet in Emulatoren. Auf echter Hardware (z. B. EverDrive) wurde noch nicht getestet – Rückmeldungen sind willkommen.
- Fehler gefunden? Bitte ein [Issue](../../issues) mit Screenshot und möglichst der Stelle im Spiel anlegen.

## Credits

- **Karlhungus (Marcel)** – Projektleitung, Übersetzung, Tests
- **Claude (Anthropic)** – technische Unterstützung (Textsystem, ROM-Erweiterung, Z80-Code, Build-Werkzeuge)
- Phantasy-Star-SMS-Disassembly (erstellt mit SMS Examine, assembliert mit WLA-DX) – Grundlage der Analyse
- Werkzeuge: WLA-DX, Floating IPS von Alcaro, Genesis Plus GX (automatische Tests), ares
- Makro-Idee: *Phantasy Star IV* (SEGA, 1993)

YouTube: https://www.youtube.com/@rgbretrogaming

## Rechtliches

Dies ist ein inoffizielles Fan-Projekt und steht in keiner Verbindung zu SEGA. Der Patch enthält kein vollständiges Spiel; du brauchst deine eigene, legal erworbene Kopie. Phantasy Star ist eine Marke von SEGA.
