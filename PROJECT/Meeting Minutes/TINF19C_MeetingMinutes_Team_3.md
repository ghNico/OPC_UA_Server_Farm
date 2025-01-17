# Inhaltsverzeichnis

[Meeting 14.10.2020](#meeting-1)

[Meeting 16.10.2020](#meeting-2)

[Meeting 19.10.2020](#meeting-3)

[Meeting 23.10.2020](#meeting-4)

[Meeting 30.10.2020](#meeting-5)

[Meeting 03.11.2020](#meeting-6)

[Meeting 06.11.2020](#meeting-7)

[Meeting 09.11.2020](#meeting-8)

[Meeting 11.11.2020](#meeting-9)

[Meeting 12.11.2020](#meeting-10)

[Meeting 05.03.2021](#meeting-11)

[Meeting 12.03.2021](#meeting-12)

[Meeting 17.03.2021](#meeting-13)

[Meeting 19.03.2021](#meeting-14)

[Meeting 01.04.2021](#meeting-15)

[Meeting 16.04.2021](#meeting-16)

[Meeting 18.04.2021](#meeting-17)

[Meeting 21.04.2021](#meeting-18)

[Meeting 22.04.2021](#meeting-19)

[Meeting 23.04.2021](#meeting-20)

[Meeting 26.04.2021](#meeting-21)

[Meeting 30.04.2021](#meeting-22)

[Meeting 03.05.2021](#meeting-23)

[Meeting 07.05.2021](#meeting-24)

[Meeting 10.05.2021](#meeting-25)

[Meeting 12.05.2021](#meeting-26)

[Meeting 14.05.2021](#meeting-27)

[Meeting 17.05.2021](#meeting-28)

[Meeting 19.05.2021](#meeting-29)

[Meeting 20.05.2021](#meeting-30)




# <a name="meeting-1"></a> Meeting 14.10.2020
| **Verfasser** | Niklas Huber |
| --- | --- |
| **Team** | OPC UA Server Farm |
| **Teilnehmer** | Niclas Hörber, Niklas Huber, Nico Fischer, Kay Knoepfle, Phillip Förster, Daniel Zichler |

**Themen:**
- Vorgehensweise
  - In Thema OPC einlesen (jeder einzeln)
  - Wissen was in CRS, SRS und BC rein muss (jeder einzeln)
  - CRS aufstellen
- Teams Channel wo Infos für OPC
- Niklas soll der CRS-„Experte&quot; sein

**Status der Arbeit**: Informieren über das Thema

**Probleme**: keine

**Beschlüsse**: 
- Über CRS, SRS, BC und UPC informieren
- Teamschannel für UPC Informationen einrichten
- Alle relevanten Dateien in Teams hochladen

**Nächster vereinbarter Termin**: 16.10.2020

**Dauer**: Ca. 20 min 



# <a name="meeting-2"></a> Meeting 16.10.2020
| **Verfasser** | Niklas Huber |
| --- | --- |
| **Team** | OPC UA Server Farm |
| **Teilnehmer** | Niclas Hörber, Niklas Huber, Nico Fischer, Kay Knoepfle, Phillip Förster, Daniel Zichler |

**Themen:**
- Review zum MeetingMinutes File
- Ausfüllen des CRS (Goal)
- Weiteres Vorgehen planen (siehe Beschlüsse)

**Status der Arbeit**: Informieren über das Thema

**Probleme**: keine

**Beschlüsse**: 
- Goal in CRS einfügen
- Kay: Netzwerk multi IP Sache einlesen
- Phillip: CAEX 3.0 einlesen
- Niklas: CRS Thematik einlesen, Goal in CRS einfügen
- Niclas: Projektplan, BC einlesen
- Nico: grobe Anforderungen erarbeiten
- Daniel: OPC UA Client UA-Expert einlesen

**Nächster vereinbarter Termin**: 19.10.2020

**Dauer**: 1 Std



# <a name="meeting-3"></a> Meeting 19.10.2020
| **Verfasser** | Niklas Huber |
| --- | --- |
| **Team** | OPC UA Server Farm |
| **Teilnehmer** | Niclas Hörber, Niklas Huber, Nico Fischer, Kay Knoepfle, Phillip Förster, Daniel Zichler |

**Themen:**
- Files nach GIT umziehen
- Aktuelles CRS reviewed
- Was hat es mit dem BC auf sich
- Mehrere IP-Adressen fraglich
- CAEX
- Test Client

**Status der Arbeit**: CRS erstellen

**Probleme**:
- Projekt Ziel, Grund der Entwicklung und Zielgruppe unklar
- Mehrere IP-Adressen fraglich

**Beschlüsse**: 
- Niklas: 2 Product Environment erstellen
- Mail an Dozenten: Was muss alles in BC rein / Genauer Inhalt des BC / Projektziel, Grund der Entwicklung, Zielgruppe unklar
- Kai: Weiter mehrere IP-Adressen
- Nico: Files nach GIT umziehen

**Nächster vereinbarter Termin**: 23.10.2020

**Dauer**: 45 min



# <a name="meeting-4"></a> Meeting 23.10.2020
| **Verfasser** | Niklas Huber |
| --- | --- |
| **Team** | OPC UA Server Farm |
| **Teilnehmer** | Niclas Hörber, Niklas Huber, Nico Fischer, Kay Knoepfle, Phillip Förster, Daniel Zichler |

**Themen:**
- Neue Projektumgebung: Github
- Review zu CRS – Product Environment
- Review zum BC

**Status der Arbeit**: CRS erstellen

**Probleme**: Aktuell unbekanntes Abgabedatum für Dokumentation

**Beschlüsse**: 
- Jeder: Risiken fürs Projekt überlegen
- Niklas: CRS weitermachen
- Kay: Weiter in einarbeiten

**Nächster vereinbarter Termin**: 30.10.2020

**Dauer**: 1 Std



# <a name="meeting-5"></a> Meeting 30.10.2020
| **Verfasser** | Niklas Huber |
| --- | --- |
| **Team** | OPC UA Server Farm |
| **Teilnehmer** | Niclas Hörber, Niklas Huber, Nico Fischer, Kay Knoepfle, Phillip Förster, Daniel Zichler |

**Themen:**
- BC in Zusammenarbeit erstellen
    - Gant Chart
        - Aufgaben verteilen (Entwicklung)
            - Backend entwickeln
                - Umsetzung der Netzwerkkomponente (Mehrere Instanzen)
                - CAEX parser -> Backend muss CAEX Dateien einlesen können
                - Definieren & Implementierung der OPC UA Features
            - Definition des Konfigurationsdateiformats in CAEX 3.0
            - Definition von 10 aussagekräftigen Profilen
                - Welche Use Cases mit den Profilen abdecken
                - Basierend darauf die Profile erstellen
            - Testen
    - Risiko-Impact Analyse zusammen erstellt
- Weitere Vorgehensweise
- CRS besprochen
- Call mit Dozenten, um Fragen zu stellen

**Status der Arbeit**: Erstellen der Dokumente

**Probleme**: keine

**Beschlüsse**: 
- Jeder schreibt seinen Teil ins Wiki
- Phillipp probiert sich mal am SAS

**Nächster vereinbarter Termin**: 03.11.2020

**Dauer**: 1,5 Std



# <a name="meeting-6"></a> Meeting 03.11.2020
| **Verfasser** | Niklas Huber |
| --- | --- |
| **Team** | OPC UA Server Farm |
| **Teilnehmer** | Niclas Hörber, Niklas Huber, Nico Fischer, Kay Knoepfle, Phillip Förster, Daniel Zichler |

**Themen:**
- BC / Projektplan
    - Review im gesamten Team
    - Projektstrukturplaninhalt in CRS, SAS, SRS einarbeiten
- CRS
    - Review im gesamten Team
- SAS
    - Review im gesamten Team
- SRS
    - Review im gesamten Team
- Netzwerklayer von open62541 neu implementieren
    - Meeting mit Dozenten, um Problem zu lösen
    - Issue in open62541 Github öffnen
        - Müssen auf unterschiedlichen Ports arbeiten

**Status der Arbeit**: Erstellen der Dokumente

**Probleme**: Wie sollen wir Teile des SAS schon vor implementierung machen?

**Beschlüsse**: 
- Fragen: Muss im jetzigen Semester jedes Teammitglied ein Dokument haben?
- CRS, SRS, SAS weiter ausarbeiten
- Daniel fängt mit Präsentation an

**Nächster vereinbarter Termin**: 06.11.2020

**Dauer**: 1,5 Std



# <a name="meeting-7"></a> Meeting 06.11.2020
| **Verfasser** | Niklas Huber |
| --- | --- |
| **Team** | OPC UA Server Farm |
| **Teilnehmer** | Niclas Hörber, Niklas Huber, Nico Fischer, Kay Knoepfle, Phillip Förster, Daniel Zichler |

**Themen:**
- Weitere Vorgehensweise besprochen
    - CRS fertig machen
    - SRS fertig machen
    - SAS fertig machen
    - Präsentation erstellen
    - SRS und SAS in Wiki aufnehmen

**Status der Arbeit**: Erstellung/Überarbeitung der Dokumente

**Probleme**:

**Beschlüsse**: 
- Bis nächstes Meeting: Dokumente fertig
- Dann mit Präsentation beginnen

**Nächster vereinbarter Termin**: 09.11.2020

**Dauer**: 1 Std



# <a name="meeting-8"></a> Meeting 09.11.2020
| **Verfasser** | Niklas Huber |
| --- | --- |
| **Team** | OPC UA Server Farm |
| **Teilnehmer** | Niclas Hörber, Niklas Huber, Nico Fischer, Kay Knoepfle, Phillip Förster, Daniel Zichler |

**Themen:**
- Projektplan, BC, CRS, SRS und SAS im Team reviewed
- Präsentationstemplate erstellt
- Aufteilen der Präsentation


**Status der Arbeit**: Dokumentation abgeschlossen

**Probleme**:

**Beschlüsse**: 
- Jeder macht seinen Präsentationsteil
- Nico: SRS und SAS in Git Wiki

**Nächster vereinbarter Termin**: 11.11.2020

**Dauer**: 1,5 Std



# <a name="meeting-9"></a> Meeting 11.11.2020
| **Verfasser** | Niklas Huber |
| --- | --- |
| **Team** | OPC UA Server Farm |
| **Teilnehmer** | Niclas Hörber, Niklas Huber, Nico Fischer, Kay Knoepfle, Phillip Förster, Daniel Zichler |

**Themen:**
- Review zur Präsentation
- Review zum SRS und SAS in Git Wiki

**Status der Arbeit**: Vorbereitung auf Präsentation

**Probleme**:

**Beschlüsse**: 

**Nächster vereinbarter Termin**: 12.11.2020

**Dauer**: 1 Std



# <a name="meeting-10"></a> Meeting 12.11.2020
| **Verfasser** | Niklas Huber |
| --- | --- |
| **Team** | OPC UA Server Farm |
| **Teilnehmer** | Niclas Hörber, Niklas Huber, Nico Fischer, Kay Knoepfle, Phillip Förster, Daniel Zichler |

**Themen:**
- Nochmaliges Review zur Präsentation

**Status der Arbeit**: Vorbereitung auf Präsentation

**Probleme**:

**Beschlüsse**: SRS und SAS in Git Wiki

**Nächster vereinbarter Termin**: Präsentation in Vorlesung

**Dauer**: 1 Std

# <a name="meeting-11"></a> Meeting 05.03.2021
| **Verfasser** | Niklas Huber |
| --- | --- |
| **Team** | OPC UA Server Farm |
| **Teilnehmer** | Niclas Hörber, Niklas Huber, Nico Fischer, Phillip Förster, Daniel Zichler |

**Themen:**
- Stand des Projekts
    - Mit Coding starten
        - Bisherige Arbeit von Kay bekommen
    - CAEX 3.0 Parser
    - Open62541Stack
- Ausscheiden von Kay
    - Phillip wird zum Product Manager „befördert“

**Status der Arbeit**: Alle wieder auf aktuellen Stand bringen

**Probleme**: 
- Hauptentwickler hat Projektgruppe verlassen
- Versionsprobleme
- 
**Beschlüsse**: 
- Jeder liest alle bisherige Doku durch
- Jeder installiert WSL 2 / Linux

**Nächster vereinbarter Termin**: 12.03.2021

**Dauer**: 45 min



# <a name="meeting-12"></a> Meeting 12.03.2021
| **Verfasser** | Niklas Huber |
| --- | --- |
| **Team** | OPC UA Server Farm |
| **Teilnehmer** | Niclas Hörber, Niklas Huber, Nico Fischer, Phillip Förster, Daniel Zichler |

**Themen:** Weiteres Vorgehen (siehe Beschlüsse) / Nachbesprechung der 1. Vorlesung im 4. Semester

**Status der Arbeit**: Alle wieder auf aktuellen Stand bringen

**Probleme**:

**Beschlüsse**: 
- Niklas:
    - Git den Anforderungen des Dozenten anpassen
- Nico & Phillip:
    - Implementierung anfangen / informieren
- Daniel:
    - Vorlage seines Dokuments machen
- Niclas
    - Informieren was alles gemacht werden muss (Projektdoku, Abgabe, …)
- Projekt in aktueller Version (Alte Version verwerfen)

**Nächster vereinbarter Termin**:  17.03.2021

**Dauer**: 30 min



# <a name="meeting-13"></a> Meeting 17.03.2021
| **Verfasser** | Niklas Huber |
| --- | --- |
| **Team** | OPC UA Server Farm |
| **Teilnehmer** | Niclas Hörber, Niklas Huber, Nico Fischer, Phillip Förster, Daniel Zichler |

**Themen:** 
- Call mit Dozenten für Support beim Projekt
- Review zu allen organisatorischen Punkten von Niclas
    - GitHub
    - Noten
    - Präsentation
- Review zum Anfang der Implementierung (Nico & Phillip)
    - Wie sich jeder auf unseren Linux Server connected
    - Problem: wir verstehen den Code nicht -> Call mit Dozenten
- Review zu anpassungen auf GIT (Niklas)

**Status der Arbeit**: Anfang der Implementierung

**Probleme**: Probleme bei der Implementierung

**Beschlüsse**: Niclas nimmt Kontakt zu Dozenten weger oben genannten Call auf

**Nächster vereinbarter Termin**: 19.03.2021

**Dauer**: 30 min



# <a name="meeting-14"></a> Meeting 19.03.2021
| **Verfasser** | Niklas Huber |
| --- | --- |
| **Team** | OPC UA Server Farm |
| **Teilnehmer** | Niclas Hörber, Niklas Huber, Nico Fischer, Phillip Förster, Daniel Zichler |

**Themen:** 
- Hilfestellung von Dozenten in Vorlesung
    - AML File anstatt JSON (von Hilfestellung) Konfigurationsdatei -> AML anschauen
    - Weitere Vorgehensweise (mithilfe der Hilfestellung) besprechen

**Status der Arbeit**: Anfang der Implementierung

**Probleme**:

**Beschlüsse**: Nico, Phillip probieren mit Hilfestellung zu Arbeiten; Daniel mit Testen beschäftigen

**Nächster vereinbarter Termin**: 01.04.2021

**Dauer**: 30 min



# <a name="meeting-15"></a> Meeting 01.04.2021
| **Verfasser** | Niklas Huber |
| --- | --- |
| **Team** | OPC UA Server Farm |
| **Teilnehmer** | Niclas Hörber, Niklas Huber, Nico Fischer, Phillip Förster, Daniel Zichler |

**Themen:** 
- Alle auf gleichen Stand bringen
    - Hilfestellung grob verstanden
    - Unklare Aufgabe und Ziel des Projekts (vorallem bezüglich der 10 unterschiedlichen Server Profile)
      

**Status der Arbeit**: Anfang der Implementierung

**Probleme**: Unklares Ziel des Projekts

**Beschlüsse**: Niclas vereinbart treffen mit Dozenten

**Nächster vereinbarter Termin**: 09.04.2021

**Dauer**: 45 min 



# <a name="meeting-16"></a> Meeting 16.04.2021
| **Verfasser** | Niklas Huber |
| --- | --- |
| **Team** | OPC UA Server Farm |
| **Teilnehmer** | Niclas Hörber, Niklas Huber, Nico Fischer, Phillip Förster, Daniel Zichler |

**Themen:** 
- Weiteres Vorgehen besprochen:
  - Konfiguaration von Attributen (Temperatur. Gerätename, ...)
    - In Github wiki
- Noch zu machen (Start der Entwicklung)
  - User Inferface (Console)
  - Logger
  - Server host
  - Parser
  - OPC UA client (bereits vorhanden)

- Schwierigkeiten:
  - "Vorgaukeln" von 10 Servern 

**Status der Arbeit**: Implementierung

**Probleme**:

**Beschlüsse**: 
- "richtiger" Start implementierung
- Nico und Phillip machen Core Library
- Niclas macht Logger
- Niklas schaut wie man AML Dateien parsen/einlesen
- Daniel fängt mit Testfällen an (also unterschiedliche AML Dateien)

**Nächster vereinbarter Termin**: 18.04.2021 15 Uhr

**Dauer**: 45 min



# <a name="meeting-17"></a> Meeting 18.04.2021
| **Verfasser** | Niklas Huber |
| --- | --- |
| **Team** | OPC UA Server Farm |
| **Teilnehmer** | Niclas Hörber, Niklas Huber, Nico Fischer, Phillip Förster |

**Themen:** 
- Besprechung der Updates
  - 10 simulierte Server funktioneren
  - File einlesen ist noch zu machen
  - Überlegung zur Umsetzung des UI

**Status der Arbeit**: Implementierung

**Probleme**:

**Beschlüsse**: 
- Eventuell GUI
- Mit XML-Parser anfangen
- Schreiben des Loggers
- Test AML Files bauen

**Nächster vereinbarter Termin**: 21.04.2021 13 Uhr

**Dauer**: 30 min


# <a name="meeting-18"></a> Meeting 21.04.2021
| **Verfasser** | Niklas Huber |
| --- | --- |
| **Team** | OPC UA Server Farm |
| **Teilnehmer** | Niclas Hörber, Niklas Huber, Nico Fischer, Phillip Förster, Daniel Zichler |

**Themen:** 
- Parser:
  - Welche Daten von AML Datei auslesen -> Lassen gesamte XML File parsen
  - Get Methode damit Server geparste Daten bekommt   
- Logger:
  - Review zu bisheriger Arbeit

**Status der Arbeit**: Implementierung

**Probleme**:

**Beschlüsse**: 
- Weiterarbeiten an Parser und Logger
- Weitere AML Dateien erstellen

**Nächster vereinbarter Termin**: 22.04.2021 14 Uhr

**Dauer**: 45 min



# <a name="meeting-19"></a> Meeting 22.04.2021
| **Verfasser** | Niklas Huber |
| --- | --- |
| **Team** | OPC UA Server Farm |
| **Teilnehmer** | Niclas Hörber, Niklas Huber, Nico Fischer, Phillip Förster, Daniel Zichler |

**Themen:** 
- Review zum Parser:
  - Parser selbst
  - Überblicksdatei für Klassen in Parser
- Keine richtige Präsentation am Freitag

**Status der Arbeit**: Implementierung

**Probleme**: 

**Beschlüsse**: 
- Parser integrieren -> Attribute in Server darstellen
- Weiterhin AML File erstellen

**Nächster vereinbarter Termin**: 23.04.2021 nach Vorlesung

**Dauer**: 30 min



# <a name="meeting-20"></a> Meeting 23.04.2021
| **Verfasser** | Niklas Huber |
| --- | --- |
| **Team** | OPC UA Server Farm |
| **Teilnehmer** | Niclas Hörber, Niklas Huber, Nico Fischer, Phillip Förster, Daniel Zichler |

**Themen:** 
- Besprechung des Kundeninterfaces
  - Implementierung einer GUI
  - Anpassen des BC / Strukturprojektplan wegen wegfallen von Kay (Stundenverteilung und co.)
  - Unit Tests aus Anforderungen schreiben (auch aus Gantt-chart)
  - GitHub verbessern für Review in nächster Vorlesung am 30.04.
- Weiters Vorgehen:
  - Weiteres einbinden der AML Files in Server
  - GUI entwickeln
  - Weitere AML Files erstellen
  - GitHub verbessern


**Status der Arbeit**: Implementierung

**Probleme**:

**Beschlüsse**: 
- Implementierung eines GUI
- Wegfallen von Unit Tests (Begründung: Kay ist weggefallen)

**Nächster vereinbarter Termin**: 26.04.2021 10:30 Uhr

**Dauer**: 15 min





# <a name="meeting-21"></a> Meeting 26.04.2021
| **Verfasser** | Niklas Huber |
| --- | --- |
| **Team** | OPC UA Server Farm |
| **Teilnehmer** | Niclas Hörber, Niklas Huber, Nico Fischer, Phillip Förster, Daniel Zichler |

**Themen:** 
- Noch zu erstellende Dokumente
   - STP - System Test Plan
   - STR - System Test Report
- In GitWiki: 
    - Noch ausführliche Beschreibung zu allen Modulen
    - User Manual
- Erster Entwurf des GUI reviewed
- Nur einlesen von AML Dateien keine AMLX
- Nächste Schritte:
   - Fehlerhandling (z.B.: Fehlerhafte AML Datei abfangen)
   - GUI
   - Dokumentation
   - Nodes anzeigen (nur aus Instance Hierarchy)
   - Mehrere Files laden
   - Weitere AML-Files machen

**Status der Arbeit**: Implementierung

**Probleme**:

**Beschlüsse**: Festlegung nächster Schritte

**Nächster vereinbarter Termin**: 30.04.2021 nach Vorlesung

**Dauer**: 20 min



# <a name="meeting-22"></a> Meeting 30.04.2021
| **Verfasser** | Niklas Huber |
| --- | --- |
| **Team** | OPC UA Server Farm |
| **Teilnehmer** | Niclas Hörber, Niklas Huber, Phillip Förster |

**Themen:**
- Nächste Schritte:
   - Fehlerhandling (z.B.: Fehlerhafte AML Datei abfangen)
   - GUI
   - Dokumentation (Module und User Manual)
   - Nodes anzeigen (nur aus Instance Hierarchy)
   - Mehrere Files laden
   - Weitere AML-Files machen
   - Logger
   - Präsentation

**Status der Arbeit**: Implementierung + Anfang der Doku + Vorbereiten auf Präsentation

**Probleme**:

**Beschlüsse**: 
- Niklas: Über finale Präsentation informieren
- Niklas & Philipp: Parser Modul Doku
- Philipp: Mehrere Files einlesen
- Niclas: Gantt Chart anpassen für neuen Präsentationstermin
- Niclas: GUI einarbeiten

**Nächster vereinbarter Termin**: 03.05.2021 - 10.30 Uhr

**Dauer**: 15 min



# <a name="meeting-23"></a> Meeting 03.05.2021
| **Verfasser** | Niklas Huber |
| --- | --- |
| **Team** | OPC UA Server Farm |
| **Teilnehmer** | Niclas Hörber, Niklas Huber, Nico Fischer, Phillip Förster |

**Themen:** 
- Review zu Präsentationsentwurf und 
- Festlegen der nächsten Schritte
  - Phillip macht Logger
  - Niclas macht GUI  
**Status der Arbeit**: Implementation

**Probleme**:

**Beschlüsse**: 

**Nächster vereinbarter Termin**: 07.05.2021 nach der Vorlesung

**Dauer**: 15 min



# <a name="meeting-24"></a> Meeting 07.05.2021
| **Verfasser** | Niklas Huber |
| --- | --- |
| **Team** | OPC UA Server Farm |
| **Teilnehmer** | Niclas Hörber, Niklas Huber, Nico Fischer, Phillip Förster, Daniel Zichler |

**Themen:** 
- GUI:
    - Review zu bisheriger GUI
    - Absprache für weiteres Vorgehen
- Logging (was loggen):
    - Server started
    - Server shutdown
    - Erfolgreiches Parsen
    - Fehlgeschlagenes Parsen

**Status der Arbeit**: Implementation

**Probleme**:
- Schwierigkeiten bei Implementierung von GUI

**Beschlüsse**: 
- bis nächsten Termin
  - GUI weitermachen
  - Server Logger Kommunikaion

**Nächster vereinbarter Termin**: 10.05.2021 - 10.30 Uhr

**Dauer**: 45 min



# <a name="meeting-25"></a> Meeting 10.05.2021
| **Verfasser** | Niklas Huber |
| --- | --- |
| **Team** | OPC UA Server Farm |
| **Teilnehmer** | Niklas Huber, Nico Fischer, Daniel Zichler |

**Themen:** 
- Fragen zur Doku geklärt
- Mini Review zur GUI
- Evtl. Anpassungen an System Design in SAS

**Status der Arbeit**: Implementierung

**Probleme**:

**Beschlüsse**: 

**Nächster vereinbarter Termin**: 12.05.2021 - 19:30

**Dauer**: 30 min



# <a name="meeting-26"></a> Meeting 12.05.2021
| **Verfasser** | Niklas Huber |
| --- | --- |
| **Team** | OPC UA Server Farm |
| **Teilnehmer** | Niclas Hörber, Niklas Huber, Nico Fischer, Phillip Förster, Daniel Zichler |

**Themen:** 
- Review zur Parser Doku, um (fast) fertige Moduldoku für Projektreview zu haben
- Kleine Fragen zur Doku geklärt
- Verbindung von Server Host und User Interface

**Status der Arbeit**: Implementierung

**Probleme**: GUI für Windows entwickelt, Serverimplementierung in Linux

**Beschlüsse**: 

**Nächster vereinbarter Termin**: 14.05.2021 - nach der Vorlesung

**Dauer**: 2 Std 30 min



# <a name="meeting-27"></a> Meeting 14.05.2021
| **Verfasser** | Niklas Huber |
| --- | --- |
| **Team** | OPC UA Server Farm |
| **Teilnehmer** | Niclas Hörber, Niklas Huber, Nico Fischer, Phillip Förster, Daniel Zichler |

**Themen:** 
- Verbesserter Präsentationsentwurf
- GUI für Windows entwickelt, Serverimplementierung in Linux
  - Keine Lösung gefunden
  - Implementieren doch Command Line UI
  - Bisherige GUI geben wir als "GUI vorschlag" mit ab

**Status der Arbeit**: Implementierung

**Probleme**: GUI für Windows entwickelt, Serverimplementierung in Linux

**Beschlüsse**: 

**Nächster vereinbarter Termin**: 17.05.2021 - 19:30

**Dauer**: 1 Std



# <a name="meeting-28"></a> Meeting 17.05.2021
| **Verfasser** | Niklas Huber |
| --- | --- |
| **Team** | OPC UA Server Farm |
| **Teilnehmer** | Niclas Hörber, Niklas Huber, Nico Fischer, Phillip Förster, Daniel Zichler |

**Themen:** 
- Fehlende Doku
- 10 aussagekräftige AML Dateien
- Tests
  - nicht implementierte GUI wird nicht getested 
- Implementation, noch zu machen:
  - Logger
  - Fehlererkennung (z.b. fehlerhaftes AML file)
  - Noch keine "values" anzeigen  

**Status der Arbeit**: Ende der Implementation

**Probleme**: Zeit

**Beschlüsse**: 
- bis Mittwoch aktiv an Project arbeiten
- Was bis dahin nicht implementiert ist wird auch nicht mehr implementiert, da sonst Probleme mit der Doku und Testplan

**Nächster vereinbarter Termin**: 19.05.2021 - 14 Uhr

**Dauer**: 50 min



# <a name="meeting-29"></a> Meeting 19.05.2021
| **Verfasser** | Niklas Huber |
| --- | --- |
| **Team** | OPC UA Server Farm |
| **Teilnehmer** | Niclas Hörber, Niklas Huber, Nico Fischer, Phillip Förster, Daniel Zichler |

**Themen:** 
- OrdnerStruktur besprochen (EXECUTABLE, PROJECT and SOURCE)
- Huzzln damit fehlende Features fertig sind, damit baldmöglichst die Doku & Tests abgeschlossen ist

**Status der Arbeit**: Fertigstellung der Implementierung & erstes Testing

**Probleme**:

**Beschlüsse**: 

**Nächster vereinbarter Termin**: 20.05.2021 - 16 Uhr

**Dauer**: 15 min



# <a name="meeting-30"></a> Meeting 20.05.2021
| **Verfasser** | Niklas Huber |
| --- | --- |
| **Team** | OPC UA Server Farm |
| **Teilnehmer** | Niclas Hörber, Niklas Huber, Nico Fischer, Phillip Förster, Daniel Zichler |

**Themen:** 
- Review der Tests
- Fertigstellung der Präsentation
- Organisatorisches zur Präsentation besprochen

**Status der Arbeit**: Vorbereitung auf Präsentation

**Probleme**:

**Beschlüsse**: 

**Nächster vereinbarter Termin**: keine

**Dauer**: 1,5 Std


