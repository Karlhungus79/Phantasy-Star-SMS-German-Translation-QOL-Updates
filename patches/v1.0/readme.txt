================================================================================

  PHANTASY STAR (Sega Master System)
  Deutsche Uebersetzung / German Translation

  Version 1.0
  Release: 30.10.2026

  Autor: Karlhungus
  https://github.com/Karlhungus79/Phantasy-Star-SMS-German-Translation-QOL-Updates

================================================================================

Inoffizielles Fan-Projekt, keine Verbindung zu SEGA. Es wird kein ROM
mitgeliefert, nur dieser Patch. Du brauchst deine eigene Kopie des Spiels.


--------------------------------------------------------------------------------
  1. INHALT
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
  2. KOMFORTFUNKTIONEN
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
  3. PATCHEN
--------------------------------------------------------------------------------

  Benoetigt: englisches ROM, 524.288 Bytes
    CRC32  00BEF1D7
    SHA-1  07fcf297be4f4c9d92cd3f119a7ac48467e06838

  Werkzeug: Floating IPS (Flips) oder Rom Patcher JS
    https://www.smwcentral.net/?p=section&a=details&id=11474
    https://www.marcrobledo.com/RomPatcher.js/

  flips.exe --apply PS1_SMS_German_v1.0.bps "Phantasy Star (USA, Europe).sms" "Phantasy Star (DE) v1.0.sms"

  Ergebnis: 1.048.576 Bytes
    CRC32  7A3870F2
    SHA-1  dfe64058479f0e9c49a7aeeac409f610ec06d3df

  Alle Pruefsummen: checksums_v1.0.txt


--------------------------------------------------------------------------------
  4. HINWEISE
--------------------------------------------------------------------------------

  - Bitte ein neues Spiel beginnen.
  - Getestet in Emulatoren, noch nicht auf echter Hardware (EverDrive).
  - Fehler bitte mit Screenshot als Issue auf GitHub melden.


--------------------------------------------------------------------------------
  5. CREDITS
--------------------------------------------------------------------------------

  Karlhungus (Marcel) ... Projektleitung, Uebersetzung, Tests
  Claude (Anthropic) .... technische Unterstuetzung
  Phantasy-Star-SMS-Disassembly (SMS Examine / WLA-DX)
  Werkzeuge: WLA-DX, Floating IPS (Alcaro), Genesis Plus GX, ares
  Makro-Idee: Phantasy Star IV (SEGA, 1993)

  YouTube: https://www.youtube.com/@rgbretrogaming

  Phantasy Star ist eine Marke von SEGA.

================================================================================
