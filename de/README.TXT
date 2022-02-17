
Aktuelle Infos und �nderungen
---------------------------------------------------------


DIE SIEDLER III (r) - GOLD-EDITION (tm)
===============================================

TECHNISCHE PROBLEME UND IHRE BEHEBUNG
=====================================

Probleme mit Debuggern und System�berwachungstools
==================================================

Bitte beachten Sie, dass ein einwandfreies Spielen von "Die Siedler 3 - Gold-Edition" nicht gew�hrleistet werden kann, wenn parallel zum Spiel Programme aktiviert sind, die weitreichenden Einfluss auf Windowsprozesse haben. Zu diesen Programmen z�hlen u. a. Debugger und System�berwachungstools wie z. B. McAfee FirstAid. Sollten Sie Probleme haben, "Die Siedler 3 - Gold-Edition" zu spielen, beenden Sie bitte alle solche parallel laufenden Programme. In Einzelf�llen kann es sogar notwendig sein, ein solches Programm komplett zu deinstallieren, so z.B. bei McAfee FirstAid.


Voodoo 3-Graphikkarten
======================

Um einen einwandfreien Betrieb mit Voodoo 3-Graphikkarten (2000, 3000 und 3500) zu erm�glichen, sollten Besitzer solcher Karten immer die aktuellsten Treiber verwenden. Die verwendeten Treiber sollten nicht �lter als die Voodoo 3 Windows 9x Retail-Treiber Version 1.02.11 bzw. Voodoo 3 Windows NT Retail-Treiber Version 1.02.10 sein. Die neuesten Voodoo 3-Treiber erhalten Sie unter folgender URL: 
http://www.3dfxgamers.com .

Siedler 3 Level Editor V2.0 und Windows 95 A
============================================

Bitte beachten Sie, dass der Level Editor V2.0 NICHT unter Windows 95 A 
lauff�hig ist. Benutzer dieses Windows-Releases sollten auf Release B updaten.

Siedler 3 Level Editor: Freier Speicher bei "Karte im Spiel anschauen"
======================================================================
Die Funktion "Karte im Spiel anschauen" des Editors ben�tigt viel Speicher, weil Editor und Spiel gleichzeitig laufen.
Bei Rechnern mit wenig Hauptspeicher (bzw. wenn durch eine volle Festplatte wenig virtueller Speicher vorhanden ist) kann es deshalb zu Warnungen und Fehlern kommen.
In diesem Fall sollten Sie eine Karte im Spiel manuell laden, nachdem sie den Editor verlassen haben. Dies empfiehlt sich auch bei Rechner mit langsamen Prozessoren.

Siegbedingungen lassen sich im Editor nicht konfigurieren oder der entsprechende Men�punkt bleibt grau.
==========================================================================================

L�sst sich der Men�punkt "Siegbedingungen" nicht anw�hlen, so ist die zu editierende Karte als Multiplayerkarte definiert.

L�sung: Im Men� "Karteneinstellung" die Option "Singleplayer" ausw�hlen.

Sollte der Men�punkt ausw�hlbar sein, sich aber dadurch kein Fenster �ffnen lassen, liegt dies h�ufig an der Datei "Comctl32.dll", die in verschiedenen Versionen existiert und in jeder neueren Version auch eine erweiterte Funktionalit�t bereitstellt. Diese Bibliothek ist Teil der Microsoft Betriebssysteme Windows 95, 98 und NT 4, und insbesondere auch Teil des Microsoft Internet Explorers.

Der Editor verwendet bei den Siegbedingungen eine Funktionalit�t, die erst ab einer neueren Version dieser Datei vorhanden ist. Tats�chlich wird dieses Problem nur bei sehr wenigen Benutzern auftreten, die noch eine �ltere Version dieser Datei installiert haben. Sobald Sie Windows 98, den Internet Explorer 4.0, einen neuen Windows NT-Service-Pack, neuere Office-Versionen oder �hnliche Produkte der Firma Microsoft auf Ihrem System installiert haben, wird diese Datei automatisch durch eine neuere ersetzt, und dieses Problem wird nicht mehr auftreten. 

F�r alle anderen gibt es folgende L�sungen:

Die neueste Version dieser Datei kann man kostenlos von Microsofts Internet-Seiten herunterladen. Diese Version ist f�r alle Benutzer von Windows 95, 98 und NT 4 geeignet (Nicht f�r Alpha-Rechner). Man findet sie unter folgender Adresse: 
http://www.microsoft.com/msdownload/ieplatform/ie/comctrlx86.asp 

Installation des IE 4.0 oder IE 5.0 

Benutzern von Windows NT 4.0 hilft auch die Installation des Service-Packs 4. 

Level Editor-Kompatibilit�t
===========================

Bitte beachten Sie, dass der Level Editor V2.0 mit allen Karten kompatibel ist, die mit dem Level Editor V1.0 (auf der Siedler III Mission-CD mitgeliefert) erstellt wurden.
Der Level Editor V1.0 kann umgekehrt alle Karten verarbeiten, die mit dem Level Editor V2.0 erzeugt wurden, solange diese KEINE Amazonen oder Amazonenobjekte enthalten!

Multiplayer-Spiele speichern
============================
1.) Pro Multiplayer-Spiel wird eine Speicher-Datei auf der Festplatte der beteiligten Spieler abgelegt. W�hrend dieses Spiels wird immer wieder diese Datei �berschrieben. Wenn Sie ein anderes Spiel beginnen, wird eine neue Datei erzeugt. 
Wenn Sie sehr gro�e Karten spielen (z.B. gro�e Zufallskarten), k�nnen diese Dateien sehr gro� (maximal ca. 13MB) werden. Bitte sorgen Sie f�r gen�gend freien Festplattenspeicher.

2.) Wenn im Spiel bei einem der Rechner w�hrend des Speicherns 
Probleme auftreten, und der Rechner aussteigt, wird das Speichern bei den anderen Spielern (eventuell nach einer l�ngeren Pause) fortgesetzt. Bis auf den Spieler mit dem fehlgeschlagenen Speicher-Versuch k�nnen alle weiterspielen und auch den Spielstand laden.
M�gliche Ursachen f�r Probleme beim Speichern sind z.B. 
- mangelnder Festplattenspeicher (sowohl f�r die Spielst�nde selbst, als auch f�r virtuellen Speicher von Windows)
- eine defekte oder fehlerhafte Festplatte

3.) Ein Spiel, das z.B. im LAN begonnen wurde, kann problemlos im Internet fortgesetzt werden, und umgekehrt.


Meldung "out of memory"
=======================
Sollten Sie eine derartige Fehlermeldung erhalten, pr�fen Sie bitte, ob gen�gend freier Speicher auf der Festplatte f�r virtuellen Speicher (meist C:) vorhanden ist.


Intellimouse(r)
===============
Auf manchen Rechnern kann es zu einer Fehlermeldung vom Windows Explorer kommen, wenn Sie eine Microsoft(r) Intellimouse(r) benutzen. Siedler 3 l�uft jedoch einwandfrei. Nach unserem Kenntnisstand handelt es sich um eine Inkompatibilit�t zwischen Intellipoint 2.2 (der Maustreiber-Software) und DirectX 6.0.
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

- Neuer Spielmodus "leicht" f�r alle Kampagnen-Spiele.
- Ausbau des Wirtschaftsmodus: Spieldauer kann vor dem Spiel festgelegt werden.
- Beseitigung des Desyncs, der nach dem Laden der Spielst�nde aufgetreten ist.
- Beseitigung des Marktplatzfehlers.

1.52

- Keine Desyncs mehr beim Zauber "Waren senden" oder "Waren herbeirufen". 
- Alle Umwandlungszauber funktionieren nun wieder mit bis zu 40 Wareneinheiten. 
- Der Zauber "Gold zu Stein" der Amazonen wirkt nun auch auf Edelsteine. 
- Edelsteine der �gypter werden wieder in der Endstatistik unter Gold mitgez�hlt. 
- Fehler beim Login in die Lobby sind behoben. 
- Baustatistiken k�nnen mit "STRG-B" an und abgeschaltet werden. 
- Belieferung von Gongwerkst�tten sichergestellt. 
- Essensverteilungsmen� Edelsteinminen korrigiert. 
- LAN-Spiele erzeugen keine DirectPlay Fehler mehr. 
- Warenduplikation bei "Waren herbeirufen" ist behoben. 
- Bienensound sollte keine Abst�rze mehr verursachen. 
- Alle Amazonen Multiplayerkarten sind nun auch in Ranglistenspielen verwendbar. 


1.51

- F�r alle die DAS GEHEIMNIS DER AMAZONEN noch nicht erworben haben, wurde durch das Update auf die Version 1.51 die Kompatibilit�t f�r Multiplayer-Spiele sichergestellt

1.50

- Release-Version der Erweiterungs-CD "Die Siedler III - Das Geheimnis der Amazonen".

1.38

- Die schnelle Produktion vieler Soldaten durch den Abri� einer Kaserne kurz vor der Rekrutierung ist nicht mehr m�glich.

1.37

- Korrektur der Mana-Produktion. 
- Die Wirkung des Zauberspruchs "Samuraischwert" ist abgeschw�cht. 

1.36

- In Weltranglistenspielen ist die Meldung "Sie haben seit xx Minuten nicht mehr gespeichert" deaktiviert. 
- Mana-Anzeige korrigiert. 

1.35

- Der Fortschritt beim Planieren einer Baustelle wird nun durch einen 
Prozentwert angezeigt. 
 Waren, die frei auf dem eigenen Gel�nde liegen, werden nun auch in neu gebaute 
Lager gebracht. 
- Vor dem Abriss des letzten Turms gibt es nun eine Warnmeldung. 
- Im Falle von Verbindungsverlusten, die auf eine schlechte Verbindungsqualit�t 
zur�ckzuf�hren sind, weist das Programm die fehlerhafte Verbindung durch eine
Meldung eindeutig aus! 

1.32

- Zeitanzeige: Jeder Spieler bekommt die M�glichkeit sich �ber die Spieldauer zu 
informieren durch eine zuschaltbare Zeitanzeige mittels der Taste "t".
- Speichern im Mehrspielerspiel: Jeder Mitspieler kann ein Spiel speichern,
indem er im Spiel einfach auf das Computersymbol links unten und dann auf 
Speichern klickt. Der Spielstand wird dann auf ALLEN beteiligten Computer 
gespeichert, so dass, falls das Spiel beendet wird, ohne dass es einen Sieger gab, das Spiel von jedem der Beteiligten auch wieder in der SIEDLER III Lobby 
angelegt werden kann. Falls dann einer der Beteiligten keine Lust mehr darauf 
hat, das Spiel zu Ende zu bringen, kann dieser durch einen Computerspieler 
ersetzt werden. Ein gespeichertes Spiel wird wie ein normales Netzwerkspiel 
angelegt, z.B. also indem Sie via Lobby auf "Create Game" klicken. Im 
Kartenauswahldialog werden dann auch gespeicherte Mehrspielerspielst�nde 
angeboten. W�hlen Sie dort den gew�nschten aus. 
- Automatisches Speichern in der Kampagne: Das Programm merkt sich 
Kampagnenkarten, die Sie erfolgreich abgeschlossen haben. Laden k�nnen Sie diese 
Spielst�nde, wenn Sie im Hauptmen� den Schalter "Spielstand laden" anklicken und 
im dann erscheinenden Lademen� rechts auf den Schalter "Kampagne" klicken. Eine 
Liste erscheint, in der alle von Ihnen schon begonnenen Kampagnenmissionen 
eingetragen sind. Klicken Sie auf die Mission, die Sie als letztes abgebrochen 
haben. 
- Verbesserte Aufbau-KI: Die Computer-KI baut zu Spielbeginn nun effektiver. 
Dadurch kann Sie schneller als vorher einen funktionierenden Warenkreislauf 
aufbauen. 
- Desync Problem beseitigt: Wenn ein Multiplayer-Spiel mit weniger Spielern als 
vorgesehen, also mit geschlossenen Slots, gestartet wurde kam es meist 
fr�her oder sp�ter zu einer Desynchronisation des Spiels. Dieses Problem ist nun 
behoben.

1.27

- Korrektur seltener Probleme beim Beitritt eines Spieles in der Lobby. 

1.26

- Verbesserung des Multiplayer-Modus im Zusammenhang mit Desyncs. 
- Korrektur einer unrichtigen Meldung am Ende der achten asiatischen Mission. 

1.25

- Anzeige aktiver Einheiten im Menu. 
- Men�s zur Warenverteilung jetzt von jedem aktuellen Geb�ude aus direkt 
anw�hlbar. 
- Neue Meldungen des Lobby Servers informieren besser �ber Logon-Ereignisse. 
- Der Multiplayer-Modus ist um "Tooltips" erg�nzt worden. Sie informieren �ber
die Funktion der Buttons in der Lobby. 
- Die erstmalige Anmeldung am Lobby-Server startet automatisch den "Spieler 
erzeugen"-Dialog. 
- Zus�tzliche Meldungen informieren �ber eine eventuell unzureichende Gr��e der 
Swap-Datei. 
- Verbessertes Scrolling unter Windows NT. 
- Korrektur der Katapultmunitionsanzeige. 
- Auf Systemen ohne WININET.DLL kann jetzt auch SIEDLER III gespielt werden.
Updates k�nnen manuell gestartet werden. 

1.23

- Einige Desync-Probleme im Multiplayerspiel sind beseitigt. 
- Abbruch des Spieles wenn ein Mitspieler das Spiel verl�sst kommt nun nicht mehr vor. 
- DIE SIEDLER III wird bei Spielstart auf Virenbefall �berpr�ft und
gegebenenfalls nicht gestartet. 
- Die Unstimmigkeit des Briefing in der 3. R�mermission ist beseitigt. 


---------------------------------------------------------
Blue Byte Software
