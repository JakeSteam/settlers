
Aktuelle Infos und Änderungen
---------------------------------------------------------


DIE SIEDLER III (r) - GOLD-EDITION (tm)
===============================================

TECHNISCHE PROBLEME UND IHRE BEHEBUNG
=====================================

Probleme mit Debuggern und Systemüberwachungstools
==================================================

Bitte beachten Sie, dass ein einwandfreies Spielen von "Die Siedler 3 - Gold-Edition" nicht gewährleistet werden kann, wenn parallel zum Spiel Programme aktiviert sind, die weitreichenden Einfluss auf Windowsprozesse haben. Zu diesen Programmen zählen u. a. Debugger und Systemüberwachungstools wie z. B. McAfee FirstAid. Sollten Sie Probleme haben, "Die Siedler 3 - Gold-Edition" zu spielen, beenden Sie bitte alle solche parallel laufenden Programme. In Einzelfällen kann es sogar notwendig sein, ein solches Programm komplett zu deinstallieren, so z.B. bei McAfee FirstAid.


Voodoo 3-Graphikkarten
======================

Um einen einwandfreien Betrieb mit Voodoo 3-Graphikkarten (2000, 3000 und 3500) zu ermöglichen, sollten Besitzer solcher Karten immer die aktuellsten Treiber verwenden. Die verwendeten Treiber sollten nicht älter als die Voodoo 3 Windows 9x Retail-Treiber Version 1.02.11 bzw. Voodoo 3 Windows NT Retail-Treiber Version 1.02.10 sein. Die neuesten Voodoo 3-Treiber erhalten Sie unter folgender URL: 
http://www.3dfxgamers.com .

Siedler 3 Level Editor V2.0 und Windows 95 A
============================================

Bitte beachten Sie, dass der Level Editor V2.0 NICHT unter Windows 95 A 
lauffähig ist. Benutzer dieses Windows-Releases sollten auf Release B updaten.

Siedler 3 Level Editor: Freier Speicher bei "Karte im Spiel anschauen"
======================================================================
Die Funktion "Karte im Spiel anschauen" des Editors benötigt viel Speicher, weil Editor und Spiel gleichzeitig laufen.
Bei Rechnern mit wenig Hauptspeicher (bzw. wenn durch eine volle Festplatte wenig virtueller Speicher vorhanden ist) kann es deshalb zu Warnungen und Fehlern kommen.
In diesem Fall sollten Sie eine Karte im Spiel manuell laden, nachdem sie den Editor verlassen haben. Dies empfiehlt sich auch bei Rechner mit langsamen Prozessoren.

Siegbedingungen lassen sich im Editor nicht konfigurieren oder der entsprechende Menüpunkt bleibt grau.
==========================================================================================

Lässt sich der Menüpunkt "Siegbedingungen" nicht anwählen, so ist die zu editierende Karte als Multiplayerkarte definiert.

Lösung: Im Menü "Karteneinstellung" die Option "Singleplayer" auswählen.

Sollte der Menüpunkt auswählbar sein, sich aber dadurch kein Fenster öffnen lassen, liegt dies häufig an der Datei "Comctl32.dll", die in verschiedenen Versionen existiert und in jeder neueren Version auch eine erweiterte Funktionalität bereitstellt. Diese Bibliothek ist Teil der Microsoft Betriebssysteme Windows 95, 98 und NT 4, und insbesondere auch Teil des Microsoft Internet Explorers.

Der Editor verwendet bei den Siegbedingungen eine Funktionalität, die erst ab einer neueren Version dieser Datei vorhanden ist. Tatsächlich wird dieses Problem nur bei sehr wenigen Benutzern auftreten, die noch eine ältere Version dieser Datei installiert haben. Sobald Sie Windows 98, den Internet Explorer 4.0, einen neuen Windows NT-Service-Pack, neuere Office-Versionen oder ähnliche Produkte der Firma Microsoft auf Ihrem System installiert haben, wird diese Datei automatisch durch eine neuere ersetzt, und dieses Problem wird nicht mehr auftreten. 

Für alle anderen gibt es folgende Lösungen:

Die neueste Version dieser Datei kann man kostenlos von Microsofts Internet-Seiten herunterladen. Diese Version ist für alle Benutzer von Windows 95, 98 und NT 4 geeignet (Nicht für Alpha-Rechner). Man findet sie unter folgender Adresse: 
http://www.microsoft.com/msdownload/ieplatform/ie/comctrlx86.asp 

Installation des IE 4.0 oder IE 5.0 

Benutzern von Windows NT 4.0 hilft auch die Installation des Service-Packs 4. 

Level Editor-Kompatibilität
===========================

Bitte beachten Sie, dass der Level Editor V2.0 mit allen Karten kompatibel ist, die mit dem Level Editor V1.0 (auf der Siedler III Mission-CD mitgeliefert) erstellt wurden.
Der Level Editor V1.0 kann umgekehrt alle Karten verarbeiten, die mit dem Level Editor V2.0 erzeugt wurden, solange diese KEINE Amazonen oder Amazonenobjekte enthalten!

Multiplayer-Spiele speichern
============================
1.) Pro Multiplayer-Spiel wird eine Speicher-Datei auf der Festplatte der beteiligten Spieler abgelegt. Während dieses Spiels wird immer wieder diese Datei überschrieben. Wenn Sie ein anderes Spiel beginnen, wird eine neue Datei erzeugt. 
Wenn Sie sehr große Karten spielen (z.B. große Zufallskarten), können diese Dateien sehr groß (maximal ca. 13MB) werden. Bitte sorgen Sie für genügend freien Festplattenspeicher.

2.) Wenn im Spiel bei einem der Rechner während des Speicherns 
Probleme auftreten, und der Rechner aussteigt, wird das Speichern bei den anderen Spielern (eventuell nach einer längeren Pause) fortgesetzt. Bis auf den Spieler mit dem fehlgeschlagenen Speicher-Versuch können alle weiterspielen und auch den Spielstand laden.
Mögliche Ursachen für Probleme beim Speichern sind z.B. 
- mangelnder Festplattenspeicher (sowohl für die Spielstände selbst, als auch für virtuellen Speicher von Windows)
- eine defekte oder fehlerhafte Festplatte

3.) Ein Spiel, das z.B. im LAN begonnen wurde, kann problemlos im Internet fortgesetzt werden, und umgekehrt.


Meldung "out of memory"
=======================
Sollten Sie eine derartige Fehlermeldung erhalten, prüfen Sie bitte, ob genügend freier Speicher auf der Festplatte für virtuellen Speicher (meist C:) vorhanden ist.


Intellimouse(r)
===============
Auf manchen Rechnern kann es zu einer Fehlermeldung vom Windows Explorer kommen, wenn Sie eine Microsoft(r) Intellimouse(r) benutzen. Siedler 3 läuft jedoch einwandfrei. Nach unserem Kenntnisstand handelt es sich um eine Inkompatibilität zwischen Intellipoint 2.2 (der Maustreiber-Software) und DirectX 6.0.
Die Fehlermeldung verschwindet, wenn Sie den Intellipoint 2.2 Maustreiber deinstallieren (und somit die erweiterten Features der Intellimouse verlieren).

Historie der enthaltenen Updates
================================

1.57

- Release-Version von "Die Siedler III - Gold-Edition"

1.56

- Der Fehler mit den Dieben wurde entfernt. 
- Der Unsichtbare Knopf im Tempel wurde entfernt. 
- Der Fehler, der beim verschieben von Schiffen auftrat, wurde entfernt. 
- Chat Admins, die Mitglieder des Blue Byte Clans sind, werden im Chat blau gekennzeichnet 


1.54

- Neuer Spielmodus "leicht" für alle Kampagnen-Spiele.
- Ausbau des Wirtschaftsmodus: Spieldauer kann vor dem Spiel festgelegt werden.
- Beseitigung des Desyncs, der nach dem Laden der Spielstände aufgetreten ist.
- Beseitigung des Marktplatzfehlers.

1.52

- Keine Desyncs mehr beim Zauber "Waren senden" oder "Waren herbeirufen". 
- Alle Umwandlungszauber funktionieren nun wieder mit bis zu 40 Wareneinheiten. 
- Der Zauber "Gold zu Stein" der Amazonen wirkt nun auch auf Edelsteine. 
- Edelsteine der Ägypter werden wieder in der Endstatistik unter Gold mitgezählt. 
- Fehler beim Login in die Lobby sind behoben. 
- Baustatistiken können mit "STRG-B" an und abgeschaltet werden. 
- Belieferung von Gongwerkstätten sichergestellt. 
- Essensverteilungsmenü Edelsteinminen korrigiert. 
- LAN-Spiele erzeugen keine DirectPlay Fehler mehr. 
- Warenduplikation bei "Waren herbeirufen" ist behoben. 
- Bienensound sollte keine Abstürze mehr verursachen. 
- Alle Amazonen Multiplayerkarten sind nun auch in Ranglistenspielen verwendbar. 


1.51

- Für alle die DAS GEHEIMNIS DER AMAZONEN noch nicht erworben haben, wurde durch das Update auf die Version 1.51 die Kompatibilität für Multiplayer-Spiele sichergestellt

1.50

- Release-Version der Erweiterungs-CD "Die Siedler III - Das Geheimnis der Amazonen".

1.38

- Die schnelle Produktion vieler Soldaten durch den Abriß einer Kaserne kurz vor der Rekrutierung ist nicht mehr möglich.

1.37

- Korrektur der Mana-Produktion. 
- Die Wirkung des Zauberspruchs "Samuraischwert" ist abgeschwächt. 

1.36

- In Weltranglistenspielen ist die Meldung "Sie haben seit xx Minuten nicht mehr gespeichert" deaktiviert. 
- Mana-Anzeige korrigiert. 

1.35

- Der Fortschritt beim Planieren einer Baustelle wird nun durch einen 
Prozentwert angezeigt. 
 Waren, die frei auf dem eigenen Gelände liegen, werden nun auch in neu gebaute 
Lager gebracht. 
- Vor dem Abriss des letzten Turms gibt es nun eine Warnmeldung. 
- Im Falle von Verbindungsverlusten, die auf eine schlechte Verbindungsqualität 
zurückzuführen sind, weist das Programm die fehlerhafte Verbindung durch eine
Meldung eindeutig aus! 

1.32

- Zeitanzeige: Jeder Spieler bekommt die Möglichkeit sich über die Spieldauer zu 
informieren durch eine zuschaltbare Zeitanzeige mittels der Taste "t".
- Speichern im Mehrspielerspiel: Jeder Mitspieler kann ein Spiel speichern,
indem er im Spiel einfach auf das Computersymbol links unten und dann auf 
Speichern klickt. Der Spielstand wird dann auf ALLEN beteiligten Computer 
gespeichert, so dass, falls das Spiel beendet wird, ohne dass es einen Sieger gab, das Spiel von jedem der Beteiligten auch wieder in der SIEDLER III Lobby 
angelegt werden kann. Falls dann einer der Beteiligten keine Lust mehr darauf 
hat, das Spiel zu Ende zu bringen, kann dieser durch einen Computerspieler 
ersetzt werden. Ein gespeichertes Spiel wird wie ein normales Netzwerkspiel 
angelegt, z.B. also indem Sie via Lobby auf "Create Game" klicken. Im 
Kartenauswahldialog werden dann auch gespeicherte Mehrspielerspielstände 
angeboten. Wählen Sie dort den gewünschten aus. 
- Automatisches Speichern in der Kampagne: Das Programm merkt sich 
Kampagnenkarten, die Sie erfolgreich abgeschlossen haben. Laden können Sie diese 
Spielstände, wenn Sie im Hauptmenü den Schalter "Spielstand laden" anklicken und 
im dann erscheinenden Lademenü rechts auf den Schalter "Kampagne" klicken. Eine 
Liste erscheint, in der alle von Ihnen schon begonnenen Kampagnenmissionen 
eingetragen sind. Klicken Sie auf die Mission, die Sie als letztes abgebrochen 
haben. 
- Verbesserte Aufbau-KI: Die Computer-KI baut zu Spielbeginn nun effektiver. 
Dadurch kann Sie schneller als vorher einen funktionierenden Warenkreislauf 
aufbauen. 
- Desync Problem beseitigt: Wenn ein Multiplayer-Spiel mit weniger Spielern als 
vorgesehen, also mit geschlossenen Slots, gestartet wurde kam es meist 
früher oder später zu einer Desynchronisation des Spiels. Dieses Problem ist nun 
behoben.

1.27

- Korrektur seltener Probleme beim Beitritt eines Spieles in der Lobby. 

1.26

- Verbesserung des Multiplayer-Modus im Zusammenhang mit Desyncs. 
- Korrektur einer unrichtigen Meldung am Ende der achten asiatischen Mission. 

1.25

- Anzeige aktiver Einheiten im Menu. 
- Menüs zur Warenverteilung jetzt von jedem aktuellen Gebäude aus direkt 
anwählbar. 
- Neue Meldungen des Lobby Servers informieren besser über Logon-Ereignisse. 
- Der Multiplayer-Modus ist um "Tooltips" ergänzt worden. Sie informieren über
die Funktion der Buttons in der Lobby. 
- Die erstmalige Anmeldung am Lobby-Server startet automatisch den "Spieler 
erzeugen"-Dialog. 
- Zusätzliche Meldungen informieren über eine eventuell unzureichende Größe der 
Swap-Datei. 
- Verbessertes Scrolling unter Windows NT. 
- Korrektur der Katapultmunitionsanzeige. 
- Auf Systemen ohne WININET.DLL kann jetzt auch SIEDLER III gespielt werden.
Updates können manuell gestartet werden. 

1.23

- Einige Desync-Probleme im Multiplayerspiel sind beseitigt. 
- Abbruch des Spieles wenn ein Mitspieler das Spiel verlässt kommt nun nicht mehr vor. 
- DIE SIEDLER III wird bei Spielstart auf Virenbefall überprüft und
gegebenenfalls nicht gestartet. 
- Die Unstimmigkeit des Briefing in der 3. Römermission ist beseitigt. 


---------------------------------------------------------
Blue Byte Software
