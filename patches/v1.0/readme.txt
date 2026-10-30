================================================================================

  PHANTASY STAR (Sega Master System)
  German Translation / Deutsche Uebersetzung

  Version 1.0
  Release: 2026-10-30

  Author / Autor: Karlhungus
  https://github.com/Karlhungus79/Phantasy-Star-SMS-German-Translation-QOL-Updates

================================================================================

  1. ENGLISH
  2. DEUTSCH


################################################################################
  1. ENGLISH
################################################################################

Unofficial fan project, not affiliated with SEGA. No ROM is included, only
this patch. You need your own copy of the game.


--------------------------------------------------------------------------------
  1.1 CONTENTS
--------------------------------------------------------------------------------

  Dialogue, narration ........... German, proofread
  System and battle messages .... German
  Menus, status window, shops ... German (windows rebuilt)
  Title screen, name entry ...... German (FORTSETZEN)
  Credits headings .............. German
  Items, weapons, armour ........ original English names
  Enemies ....................... original English names
  Spells ........................ original English names (HEAL, FIRE, ...)
  Characters and places ......... original names (Alis, Myau, Odin, Noah,
                                  Lutz, Palma, Motavia, Dezoris)

  The umlauts Ae, Oe, Ue are displayed correctly in the game. The game only
  has capital letters, so the eszett is written as SS.
  The ROM is expanded from 512 KB to 1 MB.


--------------------------------------------------------------------------------
  1.2 QUALITY-OF-LIFE FEATURES
--------------------------------------------------------------------------------

  OPTIONEN (new entry in the main menu below SPEICHERN / save)
    ERF. UND MESETA ... 1X / 2X / 4X (experience and meseta)
    SCHNELLER LAUFEN .. JA / NEIN (faster walking: overworld, towns,
                        dungeons)
    ZUFALLSKAEMPFE .... AN / AUS (random encounters on/off)
    MAKROS ............ macro editor

  MAKRO (new battle command)
    4 macros, one command per character: ANGRIFF (attack), MAGIE (spell)
    or WARE (item). One selection plays the whole round. If MP or the item
    are missing, the character attacks instead.

  BATTLE TURBO
    Hold button 1 during a battle round.

  Options and macros are stored in battery RAM and apply to all save slots.


--------------------------------------------------------------------------------
  1.3 HOW TO PATCH
--------------------------------------------------------------------------------

  Required: English ROM, 524,288 bytes
    CRC32  00BEF1D7
    SHA-1  07fcf297be4f4c9d92cd3f119a7ac48467e06838

  Tool: Floating IPS (Flips) or Rom Patcher JS
    https://www.smwcentral.net/?p=section&a=details&id=11474
    https://www.marcrobledo.com/RomPatcher.js/

  flips.exe --apply PS1_SMS_German_v1.0.bps "Phantasy Star (USA, Europe).sms" "Phantasy Star (DE) v1.0.sms"

  Result: 1,048,576 bytes
    CRC32  AFC0AEE6
    SHA-1  e2854eb06a6488795f9d6a02cdc7ecebc3a72228

  All checksums: checksums_v1.0.txt


--------------------------------------------------------------------------------
  1.4 NOTES
--------------------------------------------------------------------------------

  - Please start a new game.
  - Tested in emulators, not yet on real hardware (EverDrive).
  - Please report mistakes as an issue on GitHub, with a screenshot.


--------------------------------------------------------------------------------
  1.5 CREDITS
--------------------------------------------------------------------------------

  Karlhungus (Marcel) ... project lead, translation, testing
  Claude (Anthropic) .... technical support
  Phantasy Star SMS disassembly (SMS Examine / WLA-DX)
  Tools: WLA-DX, Floating IPS (Alcaro), Genesis Plus GX, ares
  Macro idea: Phantasy Star IV (SEGA, 1993)

  YouTube: https://www.youtube.com/@rgbretrogaming

  Phantasy Star is a trademark of SEGA.


################################################################################
  2. DEUTSCH
################################################################################

Inoffizielles Fan-Projekt, keine Verbindung zu SEGA. Es wird kein ROM
mitgeliefert, nur dieser Patch. Du brauchst deine eigene Kopie des Spiels.


--------------------------------------------------------------------------------
  2.1 INHALT
--------------------------------------------------------------------------------

  Dialoge, Erzaehltexte ......... deutsch, gegengelesen
  System- und Kampfmeldungen .... deutsch
  Menues, Statusfenster, Laeden . deutsch (Fenster neu aufgebaut)
  Titelbild, Namenseingabe ...... deutsch (FORTSETZEN)
  Abspann-Ueberschriften ........ deutsch
  Gegenstaende, Waffen, Ruestung  englische Originalnamen
  Gegner ........................ englische Originalnamen
  Zauber ........................ englische Originalnamen (HEAL, FIRE, ...)
  Figuren und Orte .............. Originalnamen (Alis, Myau, Odin, Noah,
                                  Lutz, Palma, Motavia, Dezoris)

  Umlaute Ae, Oe, Ue werden im Spiel korrekt dargestellt. Das Spiel kennt
  nur Grossbuchstaben, ss steht deshalb fuer Eszett.
  Das ROM wird von 512 KB auf 1 MB erweitert.


--------------------------------------------------------------------------------
  2.2 KOMFORTFUNKTIONEN
--------------------------------------------------------------------------------

  OPTIONEN (neuer Punkt im Hauptmenue unter SPEICHERN)
    ERF. UND MESETA ... 1X / 2X / 4X
    SCHNELLER LAUFEN .. JA / NEIN (Oberwelt, Staedte, Dungeons)
    ZUFALLSKAEMPFE .... AN / AUS
    MAKROS ............ Makro-Editor

  MAKRO (neuer Kampfbefehl)
    4 Makros, je Figur ANGRIFF, MAGIE oder WARE. Eine Auswahl spielt die
    ganze Runde. Fehlen MP oder Gegenstand, greift die Figur an.

  KAMPF-TURBO
    Taste 1 waehrend der Kampfrunde gedrueckt halten.

  Optionen und Makros liegen im Batterie-RAM und gelten fuer alle
  Spielstaende.


--------------------------------------------------------------------------------
  2.3 PATCHEN
--------------------------------------------------------------------------------

  Benoetigt: englisches ROM, 524.288 Bytes
    CRC32  00BEF1D7
    SHA-1  07fcf297be4f4c9d92cd3f119a7ac48467e06838

  Werkzeug: Floating IPS (Flips) oder Rom Patcher JS
    https://www.smwcentral.net/?p=section&a=details&id=11474
    https://www.marcrobledo.com/RomPatcher.js/

  flips.exe --apply PS1_SMS_German_v1.0.bps "Phantasy Star (USA, Europe).sms" "Phantasy Star (DE) v1.0.sms"

  Ergebnis: 1.048.576 Bytes
    CRC32  AFC0AEE6
    SHA-1  e2854eb06a6488795f9d6a02cdc7ecebc3a72228

  Alle Pruefsummen: checksums_v1.0.txt


--------------------------------------------------------------------------------
  2.4 HINWEISE
--------------------------------------------------------------------------------

  - Bitte ein neues Spiel beginnen.
  - Getestet in Emulatoren, noch nicht auf echter Hardware (EverDrive).
  - Fehler bitte mit Screenshot als Issue auf GitHub melden.


--------------------------------------------------------------------------------
  2.5 CREDITS
--------------------------------------------------------------------------------

  Karlhungus (Marcel) ... Projektleitung, Uebersetzung, Tests
  Claude (Anthropic) .... technische Unterstuetzung
  Phantasy-Star-SMS-Disassembly (SMS Examine / WLA-DX)
  Werkzeuge: WLA-DX, Floating IPS (Alcaro), Genesis Plus GX, ares
  Makro-Idee: Phantasy Star IV (SEGA, 1993)

  YouTube: https://www.youtube.com/@rgbretrogaming

  Phantasy Star ist eine Marke von SEGA.

================================================================================
