# Praxissemester-Bericht

**vorgelegt von**  
Rusilowski, Kaj Oskar  

**Hochschule Mannheim**  
Matrikelnummer: 2020804  
Studiengang: Informatik  
Semester: 6IB  

**Unternehmen**  
Turley-Straße 8 · 68167 Mannheim · DE  
Tel. +49 621 976 09140  
info@utiligence.de  
utiligence.de  

20.02.2025  

Praktikumsbeginn 15.02.2023 | Praktikumende 11.08.2023  

---

## Inhaltsverzeichnis

1 Beschreibung des Firmenumfeldes und der Zielsetzung .......................................................... 5  

2 Tätigkeitsbeschreibung ........................................................................................................... 6  
2.1 (15.02 17.02) | Einführung in das Unternehmen .............................................................. 6  
2.2 (20.02 24.02) | ABAP-Schulung ...................................................................................... 7  
2.3 (27.02 03.03) | ABAP OOP und SOAP Web Services ....................................................... 8  
2.4 (06.03 10.03) | SAP Grundlagen ..................................................................................... 9  
2.5 (13.03 17.03) | Einrichtung eines eigenen Providers/Consumers ................................. 10  
2.6 (20.03 24.03) | SAP AMI Logs ....................................................................................... 10  
2.7 (27.03 31.03) | Erste Unternehmens-Retrospektive ...................................................... 11  
2.8 (03.04 07.04) | IS-U Schulung ....................................................................................... 12  
2.9 (10.04 14.04) | IS-U Basis-Stammdaten Schulung ........................................................ 12  
2.10 (17.04 21.04) | Energiewirtschafts Schulungen .......................................................... 12  
2.11 (24.04 28.04) | Implementierung von WS-Schnittstellen ............................................ 12  
2.12 (01.05 05.05) | SAP SOA-Manager ............................................................................... 13  
2.13 (08.05 12.05) | Prozessdokument in SAP ..................................................................... 13  
2.14 (15.05 19.05) | Entwicklung von Geräteinfosätzen ..................................................... 14  
2.15 (22.05 26.05) | Konfiguration von Service Consumer ................................................. 14  
2.16 (29.05 02.06) | Neues Projekt (JAVA) ........................................................................... 15  
2.17 (05.06 09.06) | Behebung von Pdocs Fehlern .............................................................. 16  
2.18 (12.06 16.06) | Betriebausflug ..................................................................................... 17  
2.19 (19.06 23.06) | Erstellung von Webservice-Dokumentation ....................................... 17  
2.20 (26.06 30.06) | Urlaub ................................................................................................. 18  
2.21 (03.07 07.07) | Webservice-Dokumentation ............................................................... 18  
2.22 (10.07 14.07) | SAP BTP / SAP HANA Cloud ................................................................ 18  
2.23 (17.07 21.07) | Hochladen von Daten in die SAP HANA Cloud ................................... 19  
2.24 (24.07 28.07) | Verwenden von Python zum Hochladen von Daten ......................... 20  
2.25 (31.07 04.08) | Neues React-Projekt ........................................................................... 21  
2.26 (07.08 11.08) | Dokumentationserstellung .................................................................. 23  

3 Projektberich ......................................................................................................................... 24  
3.1 Überblick / Abstract .......................................................................................................... 24  
3.2 Einleitung .......................................................................................................................... 24  
3.3 Grundlagen ....................................................................................................................... 25  
3.3.1 ABAP .......................................................................................................................... 25  
3.3.2 XML & XSD ................................................................................................................. 25  
3.3.3 WSDL ......................................................................................................................... 26  
3.3.4 SOAP .......................................................................................................................... 27  
3.3.5 Enterprise Services1 ................................................................................................... 29  
3.3.6 RFC ............................................................................................................................ 30  
3.3.7 IM4G & SMG .............................................................................................................. 30  
3.3.8 Stammdaten & SAP IS-U ............................................................................................ 31  
3.3.9 S-HANA ...................................................................................................................... 34  
3.4 Lösungsmethode .............................................................................................................. 34  
3.4.1 Struttura del simulatore ............................................................................................ 34  
3.5 Ausblick ............................................................................................................................ 34  
3.6 Ergebnisse ....................................................................................................................... 35  

4 Abkürzungsverzeichnis .......................................................................................................... 37  

---

## Abbildungsverzeichnis

1 Die vier Kernkompetenzen von Utiligence (unternehmenseigene Darstellung) ..................... 6  
2 iMS-Kostenverteiler: Endergebnis ....................................................................................... 22  
3 Toplevel Element eines WSDL-Dokuments .......................................................................... 26  
4 Aufbau einer SOAP-Nachricht .............................................................................................. 28  
5 test test test ......................................................................................................................... 35  

---

## Tabellenverzeichnis

2 IM4G Komponenten ............................................................................................................. 32  

---

# 1 Beschreibung des Firmenumfeldes und der Zielsetzung

UTILIGENCE ist Partner der Energie- und Versorgungswirtschaft für effiziente, branchenspezifische Softwarelösungen und Informationstechnologie (IT). Zu den Kunden des Unternehmens zählen Stadtwerke und Regionalversorger ebenso wie international agierende Konzerne und spezialisierte Anbieter erneuerbarer Energien.

Die Rahmenbedingungen der Versorgungsbranche verändern sich ständig. Wer hier langfristig bestehen will, benötigt eine flexible, präzise auf Branche und Marktrollen zugeschnittene IT. Eine IT, die auch zukünftigen Anforderungen sicher standhält. UTILIGENCE begleitet Unternehmen auf dem Weg dahin: als verlässlicher Partner, mit innovativen Lösungen, kompetenter Beratung und umfassenden Schulungen.

Beratung in allen Phasen und für alle Marktrollen. Unser besonderes Augenmerk gilt den bestehenden Geschäftsabläufen und deren IT-seitiger Umsetzung. Sobald hier alle Möglichkeiten ausgeschöpft sind, ermitteln wir gemeinsam mit unseren Kunden, wie sich die vorhandene Systemlandschaft ergänzen oder weiterentwickeln lässt.

Die vier Kernkompetenzen von Utiligence schaffen die Grundlage für ein klares Ziel: intelligente Lösungen für jede energiewirtschaftliche Herausforderung! Process Mining ist für Utiligence GmbH ein neues, unerprobtes Geschäftsfeld. Daher ist der Zweck des Praktikums, eine Grundlage für Utiligence GmbH zu schaffen, auf welcher das neue Geschäftsfeld Process Mining erschlossen werden kann.

![Abbildung 1: Die vier Kernkompetenzen von Utiligence (unternehmenseigene Darstellung)](path/to/image1)

# 2 Tätigkeitsbeschreibung

## 2.1 (15.02 17.02) | Einführung in das Unternehmen

In der ersten Woche, die ich an einem Mittwoch begann, wurde ich begrüßt und mit einem Laptop ausgestattet, auf dem ich alle Accounts und Programme erstellte und konfigurierte, die ich für meine Arbeit benötigen werde.

Während meines Praktikums werde ich mich hauptsächlich mit der Softwareentwicklung im SAP-System beschäftigen, unter Verwendung der Sprache ABAP. ABAP (Advanced Business Application Programming) ist eine von SAP entwickelte Programmiersprache, die es ermöglicht, prozedurale und objektorientierte Programmierung (ABAP OOP) durchzuführen. ABAP ist sehr gut in das SAP-System integriert und erlaubt die Automatisierung von Prozessen in diesem. Einer seiner größten Vorteile besteht darin, dass er speziell für SAP entwickelt wurde und daher sehr einfach auf die im System vorhandenen Daten zugreifen und diese verwalten kann (auch dank der Integration der SQL-Sprache). Eine der ersten Aufgaben, die mir zugewiesen wurden, war das Vertrautmachen mit der Programmiersprache ABAP und mit dem SAP-System. Da ich diese Programmiersprache nicht kannte, beschäftigte ich mich mit einem umfassenden und detaillierten Kurs, der von dem Unternehmen angeboten wurde. Neben dem ABAP-Kurs besuchte und beendete ich einen weiteren vom Unternehmen angebotenen Kurs zum Thema " Datenschutz und Informationssicherheit". Gegen Ende dieser Woche gab es ein kleines Meeting mit einem der Mitarbeiter und den Azubis, um zu besprechen, welche Themen in Bezug auf ABAP und SAP uns nicht klar waren, sodass eine interne Schulung organisiert werden konnte, um alles zu klären.

## 2.2 (20.02 24.02) | ABAP-Schulung

Diese Woche habe ich den ABAP-Kurs abgeschlossen, in dem ich die Syntax, verschiedene KeyWords, Kontrollstrukturen und verschiedene Arten von Datenstrukturen der Programmiersprache ABAP kennengelernt habe.

Die Syntax von ABAP erschien mir nicht besonders kompliziert, es erinnert mich ein wenig an die Syntax von Microsofts VBA (Visual Basic for Applications). Logischerweise ist es so wie bei anderen Programmiersprachen wie C, C++, Java: es hat die klassischen Kontrollstrukturen wie IF, FOR, SWITCH, usw. Aber diese sind syntaktisch eloquenter, es werden nicht zu viele Sonderzeichen verwendet, und alles wird in Worten ausgedrückt.

Ich habe auch gelernt, wie sich Programme im SAP Ecosystem erstellen lassen und wie diese mit den Daten interagieren, die bereits im System vorhanden sind. Eine der sehr praktische Funktion ist, dass sich SQL-Anfragen erstellen lassen, ohne dass eine Bibliothek benötigt wird, denn es ist komplett in die Programmiersprache integriert.

Normalerweise wird in vielen anderen Programmiersprachen eine externe Bibliothek benötigt, die heruntergeladen und konfiguriert werden muss, um eine Verbindung zu einer externen Datenbank herzustellen, und dann werden die Anfragen als Strings an den SQL-Server gesendet, wobei die Variablen interpoliert werden. In ABAP hingegen genügt es, eine Datenstruktur zu definieren oder zu verwenden, die mit der empfangenen Antwort kompatibel ist, und zum Senden der Anfrage wird ein klassischer SQL-Befehl definiert (das SQL von ABAP verfügt im Gegensatz zum klassischen SQL auch über zusätzliche Funktionen).

Außerdem habe ich diese Woche einen weiteren Kurs über ABAP OOP (Object Oriented Programming) angefangen, wo die Grundlagen des Umgangs mit Klassen und Objekten erklärt wurden.

Dann wurde ich in ein Projekt eingeführt, an dem ich jetzt arbeiten soll. Es handelt sich dabei um einen Simulator für Webdienste, der zum Testen von SOAP-Aufrufen an den Smart Meter Gateway Dienst verwendet werden soll.

Um fortzufahren, habe ich mir einen Überblick über XML und XSD verschafft, die verwendet werden, um eine WSDL-Datei (Web Service Definition Language) zu definieren, die zur Beschreibung eines Web Service verwendet wird: die Funktionen, die angefordert werden können, die Parameter, die übergeben werden müssen, und die Antwort, die zurückgesendet wird.

Am Ende der Woche nahm ich an einer "Schulung Agile Projektmethoden (SCRUM)" teil, in welcher das SCRUM-Arbeitsmodell anhand von Beispielen realer Projekte, die dieses Modell verwenden, erläutert wurde.

## 2.3 (27.02 03.03) | ABAP OOP und SOAP Web Services

Ich habe den Kurs über ABAP OOP abgeschlossen, in dem ich gelernt habe, wie sich mit ABAP in Objekt orientiert programmieren lässt. Das unterscheidet sich auch nicht so sehr von anderen Programmiersprachen wie JAVA, es gibt die klassischen Klassenattribute, die Methoden, und diese können auch statisch sein usw. Einige Unterschiede sind, dass eine Art Klasseninterface definiert werden muss, bevor Methoden implementiert werden können. Aber das wird normalerweise über eine grafische Oberfläche gemacht, sodass das Einzige, was man mit dem Programmcode machen muss, sind die verschiedenen Methoden.

In dieser Woche habe ich auch gelernt, was SOAP API (Simple Object Access Protocol) ist, nämlich ein Protokoll, das es Anwendungen ermöglicht, Nachrichten zu übermitteln, auch wenn sie in verschiedenen Programmiersprachen geschrieben sind, und zwar auf sichere und dokumentierte Weise.

SOAP ist eine viel kompliziertere API (Application Programming Interface) als REST API (Representational State Transfer), die ich bereits kenne und die häufiger in Web Services verwendet wird, welche mit dem HTTP-Protokoll arbeitet und JSON verwendet, dass es besser lesbar ist. Einige Vorteile der SAOP-API sind, dass es ein eingebautes Sicherheitsprotokoll und eingebaute Fehlerbehandlungsoptionen bietet.

Ich habe auch SOAP UI gelernt, ein sehr nützliches Programm, mit dem SOAP-Anfragen getestet werden können.

Dann lernte ich, dass zum Senden und Empfangen von SOAP-Anfragen innerhalb des SAP-Systems zwei Elemente erforderlich sind: der Service Provider und der Service Consumer. Der Service Provider stellt über einen End-Point eine Funktion oder Klasse zur Verfügung, die ankommende Anfragen verarbeitet. Auf der anderen Seite wird der Service Consumer verwendet, um Anfragen an einen Service Provider zu senden.

Und ich begann mit dem Versuch, einen Service Consumer zu erstellen und einen Web Service in ABAP aufzurufen.

## 2.4 (06.03 10.03) | SAP Grundlagen

Zu Beginn der Woche hat ein Mitarbeiter eine Schulung über die Grundlagen von ABAP abgehalten, in der ich einige SAP-Funktionen kennengelernt habe, die ich noch nicht kannte, wie: Jobplanung, Debugging in SAP, "Mandanten", Transaktionen, Entwicklungs-, Test- und Produktivsystem, usw.

Während der Woche habe ich dann weiter Web Services in SAP mit Service Consumers ausprobiert. Eine neue Sache, die ich gelernt habe, war, wie sich 2 Mandanten mit Hilfe von SOAP miteinander kommunizieren lassen. Das ist nicht zu schwierig, aber es macht die Konfiguration etwas komplexer, da der Service Provider auf der einen Seite und der Service Consumer auf der anderen Seite konfiguriert werden muss. Dann lernte ich, wie sich der SOAMANAGER, ein Tool von SAP, verwenden lässt, um Endpunkte und Bindungen zu erstellen, damit der Consumer mit dem Provider kommunizieren kann.

Außerdem bereitete ich eine kurze Präsentation für die Monthly Presentation vor, die wir Praktikanten/Azubis jeden Monat im Unternehmen halten, um zu berichten, woran wir in diesem Monat gearbeitet haben und was wir im nächsten Monat tun werden.

## 2.5 (13.03 17.03) | Einrichtung eines eigenen Providers/Consumers

Nachdem ich diese Woche die Kommunikation zwischen 2 Mandanten zum Laufen gebracht hatte, habe ich einen Service Provider erstellt, der, anstatt direkt eine Antwort auf eine Anfrage von einem Service Consumer zu senden, die Antwort im Asynchronous Mode gesendet wird, sodass er die Antwort schickt, wenn diese bereit ist.

Dann habe ich mich mit der SAP Transaktion SRT_MONI (Web Services Message Monitor) vertraut gemacht. Dies ist ein internes SAP Programm zur Überwachung unterschiedlicher Requests, die eingehen, es enthält XML, das mit dem Request gesendet wurde, und ob es dabei Fehler gab.

Gegen Ende der Woche habe ich auch einige Interfaces erhalten, die ich zu implementieren haben werde, um den Smart Meter Gateway Simulator zu erstellen.

## 2.6 (20.03 24.03) | SAP AMI Logs

Ich habe eine der Interfaces, die mir letzte Woche gegeben wurden, genommen und begonnen, einen Service Provider dafür zu erstellen und diesen durch die Verarbeitung der eingegangenen Daten zu implementieren. Ich habe die Datenstrukturen erstellt, die die Anfragedaten enthalten sollten, und auch die Struktur der Antwort, die zurückgesendet werden sollte.

Nachdem es mir gelang, eine passende Rückantwort auf die Request zu erstellen, wurde mir auch die Aufgabe zugewiesen, die Daten in einem AMI-Log (Advanced-Metering-Infrastruktur) zu speichern, welches die Daten überwacht, die zwischen SAP Utilities und dem MDUS-System (Meter Data Unification & Synchronisation) ausgetauscht werden. Also habe ich nach einer Möglichkeit gesucht, die Daten im AMI-Log zu speichern.

## 2.7 (27.03 31.03) | Erste Unternehmens-Retrospektive

Um einen Entry im AMI-Log zu erstellen, entdeckte ich, dass sich ein Geräteinfosatz erstellen lässt, also studierte ich diese Woche, wie ein Geräteinfosatz funktioniert, wie er sich erstellen lässt. Zuerst durch eine grafische Benutzeroberfläche von SAP, danach verbrachte ich die Woche damit, herauszufinden, wie man einen Geräteinfosatz durch ABAP erstellt, indem man einer der zwei Klassen verwendet, die vom SAP-System bereitgestellt werden.

Gegen Ende der Woche, am 31. März, war der Sprint für das erste Quartal beendet. Ich nahm mit dem gesamten Team an Meetings zum Review des ersten Sprints teil, in denen die Fortschritte während des Sprints und das, was nicht geschafft wurde, besprochen wurden, an der Retrospektive, in der besprochen wurde, was gut gelaufen ist, ob es Probleme gab und was für den nächsten Sprint beibehalten werden sollte, und an der Planung für den Sprint des zweiten Quartals, in der die im zweiten Quartal zu erledigenden Tasks geplant wurden.

Das war eine sehr interessante Erfahrung, die mir zeigte, wie Reviews, Retrospektiven und Planungen in einem Unternehmen ablaufen, im Vergleich zu dem, was wir letztes Semester im Projektsemester gemacht haben.

## 2.8 (03.04 07.04) | IS-U Schulung

Diese Woche habe ich weiter versucht, einen Geräteinfosatz zu erstellen und dies im AMI-Log zu speichern. Es ist mir gelungen, einen Eintrag im AMI-Log zu erstellen, bei dem einige Daten per Request bei dem von mir erstellten Service Provider eingegangen sind.

Dann hatte ich diese Woche eine Besprechung mit einem neuen Mitarbeiter, bei der mir mehr über die Funktionsweise von Geräteinfosätzen im SAP-System erklärt wurden.

## 2.9 (10.04 14.04) | IS-U Basis-Stammdaten Schulung

Diese Woche habe ich begonnen, zwei interne Schulungen zu besuchen, die sich damit befassen, was "Basis-Stammdaten" und IDEX "Common Layer" sind und wie sie funktionieren. Diese sind auch nützlich, um zu verstehen, wie sich verschiedene Prozesse in SAP konfigurieren und steuern lassen, die auch Web-Services verwenden, und um in etwa zu verstehen, unter welchen Umständen sie verwendet werden.

## 2.10 (17.04 21.04) | Energiewirtschafts Schulungen

Diese Woche habe ich die beiden Schulungen über "Basis-Stammdaten" und IDEX "Common Layer" weiter geschaut und am Ende der Woche abgeschlossen. In der Zwischenzeit habe ich auch eine weitere, sehr interessante Schulung über "Energiewirtschaft" begonnen. Während der Woche habe ich auch weiter an Problemen gearbeitet, die ich mit Web Services und AMI-Logs hatte.

## 2.11 (24.04 28.04) | Implementierung von WS-Schnittstellen

Ich habe mir weiterhin die Schulung "Energiewirtschaft" angesehen, in der ich Dinge wie "Was ist Energie", "Netzzugangsmodell", "Marktprozesse", "Energieeffizienz und Energiedienstleistungen" usw. gelernt habe.

Gegen Ende der Woche habe ich dann begonnen, alle Interfaces, die ich erhalten habe, zu implementieren, indem ich die Klassen, Service Provider und Service Consumer für jedes Interface erstellt habe.

## 2.12 (01.05 05.05) | SAP SOA-Manager

In dieser Woche habe ich einige Probleme mit den Service Providern gelöst, indem ich die URLs innerhalb des SOAManagers korrigiert habe, und ich habe alle URLs aller Service Provider End-Points der von mir erstellten Interfaces gespeichert.

Am letzten Tag der Woche habe ich wieder eine Präsentation für die "Monthly Presentation" gehalten, in der ich über den Status meines Praktikums, meine Tätigkeiten und den Fortschritt berichtet habe.

Außerdem nahm ich an einem kurzen "Mitarbeiter-Interview" teil, bei dem ich einige Fragen über mich beantwortete, die im Blog des Unternehmens veröffentlicht werden sollte.

## 2.13 (08.05 12.05) | Prozessdokument in SAP

Diese Woche habe ich mich mit Prozessdokumenten befasst, die im Grunde dafür sorgen, dass die Schritte, die beim Start eines Prozesses gestartet, und der Status dieser Schritte gespeichert werden, sodass eine detaillierte Ansicht eines Prozesses möglich ist. Und ich habe mich um diese Prozesse gekümmert, indem ich die Prozessschritte erstellt habe, die erstellt wurden, wenn eine Anfrage an den Simulator gesendet wurde, und die Antwort, die empfangen wurde.

Während der Woche gab es dann den Jour Fix der Auszubildenden und ein Meeting, um über das Praktikum zu sprechen, um Feedback zu geben und zu erhalten.

Gegen Ende der Woche begann ich damit, alle Endpunkte der Webservices in Confluence zu dokumentieren, einem Wissensmanagementsystem, einem Tool, in dem Dokumentationen und Guides zu verschiedenen Themen gespeichert werden, auf die jeder im Unternehmen zugreifen und bei Bedarf nachschlagen kann.

## 2.14 (15.05 19.05) | Entwicklung von Geräteinfosätzen

Anfang dieser Woche habe ich an einer Schulung eines Mitarbeiters zum Thema "Smart Metering" teilgenommen. Dieses Thema ist für meine derzeitige Tätigkeit sehr nützlich. In dieser Präsentation habe ich gelernt, was "Smart Metering" ist, was die Vor- und Nachteile aus der Sicht des Endkunden, des Energieversorgers und der Netzbetreiber sind. Es wurde auch deren Funktionalität erklärt und welche Einsparungen und Kosten damit verbunden sind.

Im Laufe der Woche habe ich dann alle Endpunkte der Service Consumer im SOAManager aktualisiert, damit sie auf die von mir erstellten Service Provider verweisen. Ich habe auch wieder versucht, Geräteinfosätze zu erstellen, wenn eine Anfrage eingeht.

Gegen Ende der Woche habe ich erneut versucht, den Geräteinfosatz zu erstellen, da beim letzten Versuch Fehler auftraten. Es gelang mir, die alten Probleme zu lösen, aber um die Erstellung des Gerätinfosatzes abzuschließen, muss ich zunächst ein TAF-Register erstellen, den ich dann an den Gerätinfosatz weitergeben muss (Aufgaben für die nächste Woche).

## 2.15 (22.05 26.05) | Konfiguration von Service Consumer

Diese Woche habe ich erneut versucht, einen Geräteinfosatz zu erstellen, womit ich ein paar Probleme hatte. Ich habe einen anderen Mitarbeiter um Hilfe gefragt, damit er mir bei der Fehlersuche hilft und eine TAF-Tabelle erstellt. Dieses TAF-Register, den wir ausgearbeitet haben, habe ich an die Methode zur Erstellung des Geräteinfosatzes übergeben. Nachdem ich den Geräteinfosatz erstellt hatte, konnte ich den Objektschlüssel extrahieren. Dann habe ich einen Eintrag im AMI-Log ausgearbeitet, in dem ich den Schlüssel des Geräteinfosatzes übergab. Auf diese Weise verweisen die Einträge im AMI-Log auf den erstellten Geräteinfosatz, wenn die Logs gelesen werden.

Dann habe ich im Laufe der Woche weiter an den Webdiensten gearbeitet, den Service Provider code aktualisiert und einen logischen Port für jeden Service Consumer erstellt, den ich im Laufe der Woche erstellt habe.

## 2.16 (29.05 02.06) | Neues Projekt (JAVA)

In dieser Woche habe ich weiter an den Web Services gearbeitet und bekam außerdem die Aufgabe, NPM Pakete für ein Projekt zu aktualisieren und zu überprüfen, ob das Frontend funktioniert.

Ich habe Zugang zu einem Gitlab-Repository mit dem Projekt erhalten, welches ich aktualisieren musste. Es handelt sich um einen LogViewer mit einem Backend in Java mit Spring Boot Framework und mit einem Frontend in JavaScript mit NodeJS, das zum Kompilieren benutzt wird. NodeJS wird verwendet, um einige Bibliotheken zu importieren. Beispielsweise sind bei diesem Projekt Bibliotheken wie STOMP, SOCKETIO, die dafür sorgen, dass mit dem Backend kommuniziert wird und LESS, um CSS zu erweitern. Letzteres ruft dynamische Verhaltensweisen hervor und fügt Variablen und Funktionen hinzu sowie bietet auch die Möglichkeit, CSS-Komponenten zu schichten, um es kompakter und lesbarer zu machen. Außerdem gibt es GULP3, um bestimmte Aufgaben zu automatisieren.

Ich begann mit dem Herunterladen des Repositorys und der Installation von NodeJS und Java. Ich schaute mir an, wie der Backend des Projekts arbeitet, wie Spring Boot funktioniert und sich das Java Backend mit Maven kompiliert (einem Tool zur Verwaltung von Projektabhängigkeiten und zur Erstellung von Skripten, um alles zu kompilieren). Dann habe ich den Code des Backends gelesen, um zu verstehen, wie die Kommunikation abläuft, und bin dann zum Frontend übergegangen. Das Frontend verwendet SocketIO, um in Echtzeit mit dem Backend über Websockets zu kommunizieren, und STOMP (Simple Text Orientated Messaging Protocol) wird verwendet, um Nachrichten aneinander zu übermitteln, ein Messaging-Broker, der einfache Kommunikation über einfachen Text ermöglicht.

Außerdem habe ich mich ein wenig mit der Funktionsweise von GULP3 beschäftigt, das zum Kompilieren der LESS- und JS-Dateien in diesem Projekt verwendet wird.

Zuerst aktualisierte ich die NPM-Pakete mit "npm audit", einem Terminalbefehl, der den Status der Pakete überprüft und diejenigen erneuert, die automatisch aktualisiert werden können. Nach der Aktualisierung kompilierte ich das gesamte Projekt und überprüfte, ob alles funktionierte. Dann erneuerte ich die anderen Pakete manuell, und zwar durch Überprüfung der neuesten verfügbaren Version im Internet.

Am Freitag habe ich versucht, einen Fehler zu beheben, der auftrat, als ich versuchte, das Projekt in ein Paket zu packen, und ich hatte ein Meeting mit einigen Kollegen, um über den "ABAP Arbeitskreis" zu sprechen. Bei diesem Meeting wurde erläutert, wie der "ABAP Arbeitskreis" zustande kam und welche Termine für die Wiedereinführung geplant waren.

## 2.17 (05.06 09.06) | Behebung von Pdocs Fehlern

Ich begann diese Woche mit der Implementierung des ABAP-Teils des WebServvices "Evalucation Communication Profile" des Smart-Meter-Gateways. Dann hatte ich diese Woche ein paar Meetings mit einem Arbeitskollege, um einige Probleme zu lösen, die sich mir aus Prozessdokumenten ergaben. Es ist uns gelungen, ein paar Probleme zu lösen. Dann habe ich ein Programm von einem anderen Kollegen kopiert und verändert, um die von mir benötigten Prozesse neu zu starten.

Donnerstag war ein Feiertag und am Freitag experimentierte ich weiter mit Processdokumenten, um zu sehen, wie sie mit den Webservices interagierten. Ich habe auch versucht, andere Probleme zu lösen, die mir das Programm bereitet hat. Dann entwickelte ich das Programm weiter, um die Prozesse neu zu starten, und analysierte die Teile des Programms, die mir nicht ganz klar waren, um zu verstehen, was das Programm von Anfang bis Ende tat.

## 2.18 (12.06 16.06) | Betriebausflug

Bei der Entwicklung von Simulator und WebServices wird es immer komplizierter, und ich brauche immer mehr Vorwissen über einige der verwendeten Technologien. So erhielt ich diese Woche von einem Arbeitskollegen einige PDFs. Diese PDFs enthielten recht nützliche Informationen darüber, wie man IM4G konfigurierte und wie man es verwendete.

Dann habe ich weiter mit Prozessdokumenten und Webservices experimentiert, außerdem habe ich einige Provider aktualisiert und einen Beispielcode für alle erstellten Consumer bereitgestellt.

Außerdem habe ich einen Kollegen um Zugang zum S/4HANA-System gebeten, damit ich versuchen konnte, Dienste in diesem System zu erstellen.

Am Freitag habe ich an einem schönen Betriebsausflug mit allen Arbeitskollegen und Studenten im Odenwald teilgenommen.

## 2.19 (19.06 23.06) | Erstellung von Webservice-Dokumentation

Diese Woche habe ich einen Benutzer und ein Passwort für den Zugang zum S/4HANA-System erhalten. Nachdem ich die Logins erhalten hatte, habe ich mich daran gesetzt, ein wenig zu sehen, wie es funktioniert. (Die Oberfläche unterscheidet sich nicht sehr von der des UI2-Systems)

Ich begann auch, die Dokumentation zu lesen, die ich vor ein paar Monaten zusammen mit einem anderen Praktikanten über die Erstellung von Webdiensten in SAP geschrieben hatte. Und ich habe begonnen, neue Informationen hinzuzufügen, auf die ich seit der Erstellung der Dokumentation gestoßen bin.

Am Freitag bin ich in den Urlaub gefahren.

## 2.20 (26.06 30.06) | Urlaub

Ich war diese Woche im Urlaub.

## 2.21 (03.07 07.07) | Webservice-Dokumentation

Diese Woche habe ich mich darauf konzentriert, meinem Projektbericht eine Struktur zu geben und schon etwas zu schreiben, wie die Zusammenfassung und die Einleitung. Dann habe ich meine Wochenberichte der letzten Wochen überprüft und fertig geschrieben.

Außerdem habe ich die Dokumentation für die Webservices weitergeschrieben und eine Zusammenfassung der von mir erstellten Services erstellt.

## 2.22 (10.07 14.07) | SAP BTP / SAP HANA Cloud

Heute wurde ich beauftragt, ein Konto zu erstellen, um mich mit SAP BTP Cockpit und SAP HANA Cloud vertraut zu machen und zu versuchen, eine Datenbank zu erstellen, Daten von einem SmartMeter hochzuladen und einen Algorithmus für maschinelles Lernen laufen zu lassen.

Zunächst erstellte ich ein kostenloses Testkonto für SAP BTP (Business Technology Platform), eine Plattform zur Verwaltung der von SAP bereitgestellten Cloud-Dienste, ähnlich wie Amazon AWS oder Google Cloud. Zu den aktuellen Diensten, die SAP BTP anbietet, gehören: "SAP HANA Cloud". SAP HANA Cloud wiederum ist eine neue SAP-Datenbank, die die Daten im RAM-Speicher speichert, so dass sie schnell abgerufen und geändert werden können; außerdem gibt es HANA Data Lake, die Variante, die die Daten auf der Festplatte speichert, was für die Speicherung großer Datenmengen (z. B. BigData) nützlich ist.

Nach der Konfiguration des SAP BTP Cockpits habe ich eine HANA Cloud Instanz erstellt und meinen Benutzer so konfiguriert, dass er alle Berechtigungen zur Verwaltung dieser Instanz hat.

Nach dem Anlegen und Einrichten der HANA-Instanz habe ich eine Datenbank im Speicher angelegt und die Funktionsweise des Database Explorer und des SAP Business Application Studio untersucht.

Der Database Explorer ermöglicht den Zugriff auf die Datenbanken, die in der HANA-Instanz erstellt wurden. Es gibt also Schnittstellen, um Tabellen, Schemata, Daten in bestimmten Tabellen usw. einzusehen, außerdem können Sie SQL-Befehle direkt vom Browser aus ausführen, ohne externe Clients wie DBeaver oder HeidiSQL verwenden zu müssen.

Stattdessen erscheint das SAP Business Application Studio wie ein Fork von Microsoft Visual Studio Code, wird aber online gehostet und verfügt über zusätzliche Funktionen, die es ihm ermöglichen, dank HDI isoliert mit einer HANA-Datenbank zu kommunizieren. Dieser Editor in Verbindung mit HDI ermöglicht es, Programme zu erstellen, die nur auf die benötigten Daten und mit den erforderlichen Berechtigungen zugreifen können, so dass die Datenbank sicher bleibt.

Um diese neuen Technologien ein wenig auszuprobieren, folgte ich einem Tutorial auf SAP, in dem erklärt wurde, wie man eine HDI-Verbindung mit der von mir erstellten Datenbank herstellt. Nachdem ich alles in der Datenbank eingerichtet und einige Testdaten geladen hatte, begann ich, ein Programm zu erstellen, das die Daten einer Tabelle anzeigt und drei Tabellen gruppiert und das Ergebnis anzeigt.

## 2.23 (17.07 21.07) | Hochladen von Daten in die SAP HANA Cloud

Diese Woche erhielt ich einige sehr große csv-Dateien, die Daten enthielten, die von den Smart Meters gesammelt worden waren. Meine Aufgabe war es, diese Daten in die SAP HANA Cloud hochzuladen, damit ich mit diesen Daten einige Analysen mit der PAL-Bibliothek (Predictive Analysis Library) durchführen konnte.

Bevor ich die Originaldaten in die HANA Cloud hochgeladen habe, habe ich einen Teil der Daten extrahiert, damit ich Tests mit einem kleineren Datensatz durchführen konnte. Außerdem waren die Originaldaten etwa 15 bis 30 GB groß, und das Hochladen dieser Daten hätte einige Zeit in Anspruch genommen.

Nachdem ich einen Teil der Daten geladen hatte, machte ich mich daran, die Dokumentation der PAL-Bibliothek zu lesen und einige Tests mit den geladenen Daten durchzuführen. Außerdem legte ich einen neuen Benutzer an, um die PAL-Bibliothek nutzen zu können, da der Benutzer, den ich zum Laden der Daten verwendet hatte, nicht über die erforderlichen Rechte verfügte. Nachdem ich herausgefunden hatte, wie ich die Bibliothek verwenden kann, erfuhr ich nach einigen Versuchen, dass die PAL-Bibliothek in der Free Tier-Version von HANA Cloud nicht verfügbar ist. Also machte ich mich auf die Suche nach anderen Diensten, die von SAP BTP angeboten wurden, und testete sie.

Ich testete einen Dienst für maschinelles Lernen, der Daten aus PDF-Dateien extrahierte, und ich probierte auch SAP Fiori aus, ein Framework, mit dem Benutzeroberflächen unter Verwendung des SAP-Systems erstellt werden können.

## 2.24 (24.07 28.07) | Verwenden von Python zum Hochladen von Daten

Diese Woche habe ich mich hauptsächlich damit beschäftigt, herauszufinden, wie man csv-Dateien in die HANA-Datenbank hochlädt, da es mit den auf der Schnittstelle angebotenen Tools keine Möglichkeit gab, so große Dateien hochzuladen, da das Limit bei 1 GB lag. Zunächst versuchte ich es mit DBeaver, einem Programm, das eine Schnittstelle und nützliche Funktionen für die Verwaltung verschiedener Datenbanktypen bietet, darunter auch die HANA Cloud. Bevor ich DBeaver anschloss, richtete ich SAP BTP und den HANA Databrawser so ein, dass sie Datenbankverbindungen von der Büro-IP akzeptieren.

Nachdem ich die Datenbank so konfiguriert hatte, dass sie die Verbindungsanforderung akzeptiert, stellte ich eine Verbindung zu DBeaver her und begann, die Dateien mit den Smart-Meter-Daten hochzuladen. Obwohl DBeaver die Möglichkeit bot, große Dateien in die Datenbank hochzuladen, gab es keine Kontrolle darüber, wie schnell das geschehen konnte. Also machte ich mich daran, ein Skript in Python zu erstellen, um die Daten hochzuladen.

Mit dem von mir erstellten Python-Skript konnte ich festlegen, wie groß die an die Datenbank gesendeten Chunks sein durften, so dass ich die Größe der Chunks optimieren konnte, damit der Upload schneller ging. Außerdem habe ich in dem Skript dafür gesorgt, dass ein fehlgeschlagener Upload in einem Ordner mit der Fehlermeldung gespeichert wird, so dass die Möglichkeit besteht, die fehlgeschlagenen Chunks zu korrigieren und nur die fehlgeschlagenen Chunks erneut hochzuladen, so dass die Fehler behoben werden können und der Upload ohne erneute Suche durchgeführt werden kann.

Gegen Ende des Wochenendes, während ich die Daten in die Datenbank hochlud (was etwa 8 Stunden, aufgeteilt auf 2 Tage, dauerte), traf ich mich mit einem Azubi, um einen Fehler zu beheben, den das Logviewer-Projekt verursachte. Der Fehler bestand darin, dass bei zwei oder mehr gleichnamigen Dateien in zwei verschiedenen Ordnern das Programm die Änderungen an der Datei nicht aktualisieren konnte, wenn beide Dateien geöffnet waren. Also haben wir den Datei- und Ordnernamen zu dem Endpunkt hinzugefügt, der an den Client übergeben wurde, um auf Änderungen an der Datei zu warten, so dass der Client sogar Dateien mit demselben Namen unterscheiden konnte.

## 2.25 (31.07 04.08) | Neues React-Projekt

Diese Woche habe ich neben der Fertigstellung des Fixes für den LogViewer auch den iMS-Kostenverteiler entwickelt. Der iMS-Kostenverteiler ist eine Web-App, die dabei hilft, die Kosten zu berechnen, die der Netzbetreiber und der Anschlussnutzer haben würden, je nachdem, was der Benutzer auswählt. Um diese Web-App zu erstellen, wurde das Projekt mit React erstellt: eine JavaScript-Bibliothek zur Erstellung dynamischer und reaktionsfähiger Benutzeroberflächen. Um das Projekt zu erstellen, haben wir den Befehl create-react-app verwendet, der ein Projekt mit allen Abhängigkeiten erstellt, die für die Erstellung einer React-App erforderlich sind.

![Abbildung 2: iMS-Kostenverteiler: Endergebnis](path/to/image2)

Zur Erstellung der GUI haben wir keine externen Bibliotheken verwendet, sondern die Oberfläche in mehrere kleine Komponenten aufgeteilt. Zum Beispiel ist die Komponente Button eine Komponente, die einen Button repräsentiert, der als Parameter das Like des Buttons und eine Funktion erhält, die ausgeführt wird, wenn der Benutzer ihn drückt. Und jeder Komponente haben wir eine CSS-Datei zugeordnet, um den Stil zu definieren, zum Beispiel hat die Komponente Button die Datei Button.css. Auf diese Weise haben wir eine sehr modulare und leicht zu bearbeitende GUI geschaffen.

Die App bestand aus einem Formular, das in mehrere Schritte unterteilt war. Jeder Schritt stellte einen Abschnitt des Formulars dar. Zum Beispiel ist der erste Schritt eine Auswahl zwischen "Verbraucher und Einspeiser", der zweite Schritt ist eine Auswahl von kWh, der dritte Schritt ist eine Auswahl von zusätzlichen Optionen und der letzte Schritt zeigte das Ergebnis mit der Kostenberechnung.

Um die verschiedenen Schritte zu verwalten, habe ich eine Funktion erstellt, die die verschiedenen Seiten, die in den verschiedenen Schritten angezeigt werden, als Parameter nimmt und dem Benutzer erlaubt, fortzufahren, wenn alle Anforderungen erfüllt sind (d.h. wenn der Benutzer die erforderlichen Felder ausgefüllt oder ausgewählt hat).

Anschließend werden die verschiedenen Optionen, die dem Benutzer zur Auswahl stehen, in einer JSON-Datei gespeichert. Auf diese Weise ist es sehr einfach, Optionen hinzuzufügen, zu entfernen oder zu ändern, ohne selbst Hand an den Code legen zu müssen. Um die vom Benutzer eingegebenen Daten zu speichern, habe ich stattdessen einen React Context erstellt (dies ist eine Art von Speicher, der von einer übergeordneten Komponente an eine untergeordnete Komponente weitergegeben werden kann). Der React Context hilft bei der Weitergabe von Daten von einer Formularseite zu einer anderen, so dass die Seiten je nach Benutzereingabe angepasst werden können.

## 2.26 (07.08 11.08) | Dokumentationserstellung

In der letzten Woche war ich damit beschäftigt, die letzten Aufgaben für das IMS-Projekt zu erledigen.

Dann habe ich mich darum gekümmert, die Dokumentation für das gesamte Projekt zu schreiben, in der beschrieben wird, wie es erstellt wurde, wie es strukturiert ist und wie man alles kompiliert und auf eine Website stellt. In der Dokumentation habe ich auch die Struktur des Codes und die Aufteilung des Projekts in Ordner und Dateien beschrieben, damit jeder, der das Projekt weiterführen möchte, eine Vorstellung davon hat, wo sich die verschiedenen Komponenten befinden.

# 3 Projektberich

## 3.1 Überblick / Abstract

Angesichts des Klimawandels und des Krieges in der Ukraine herrscht Knappheit an Energie und Gas. Die Erzeugung von Energie auf erneuerbare Weise mit Energiequellen wie: Sonnenkollektoren, Staudämme, Windturbinen, geothermische Kraftwerke usw. können zwar Energie erzeugen, aber nicht auf regelmäßige und konstante Weise. Und es gibt nicht viele Möglichkeiten, Energie effizient und nachhaltig zu speichern. Die Bevölkerung muss also anfangen, ihren Verbrauch zu optimieren. Die Lösung dafür ist: Intelligent Metering for German Energy Utilities (IM4G) und Smart Meter Gateway (SMG), welche die Verbraucher in Echtzeit über ihren Verbrauch auf dem Laufenden halten, sodass sie ihren Energiekonsum optimieren und Geld sparen können.

Im folgenden Bericht wird die Arbeit von Kaj Oskar Rusilowski dokumentiert, die er während eines Praktikums bei der UTILIGENCE GmbH im Bereich der SAP-Softwareentwicklung geleistet hat. Der Praktikant war für die Erstellung eines Web-Services-Simulators verantwortlich. Der Simulator befasst sich mit der Simulation der Kommunikation zum SMG-System von SAP, damit Webservices intern entwickelt und getestet werden können. Dies erleichtert das Testen und liefert sofortiges Feedback.

## 3.2 Einleitung

Um die Erstellung von Webservices zu erleichtern, beschloss das Unternehmen, einen Simulator zu entwickeln. Dieser Simulator hilft bei der Erstellung von Webservices, indem eine Testumgebung bereitgestellt wird. So kann, sobald der ABAP-Code für das Senden von Anfragen erstellt wurde, der Simulator als Endpunkt anstelle des eigentlichen Servers festgelegt werden. Auf diese Weise kann getestet werden, ob die Anfrage korrekt gesendet wird, ohne das Produktiv-System zu kompromittieren oder zu beschädigen.

Der Simulator wurde im SAP-System auf der Mandant 930 konfiguriert, die als Provider für andere Mandant fungiert, die den Client darstellen. Für jeden Endpunkt, den der Simulator haben muss, gibt es eine in XML und XSD geschriebene WSDL-Datei, die die Definitionen enthält, wie die Anfragen zusammengesetzt werden sollen und was als Antwort zu erhalten ist. Für jeden Endpunkt wurden im SAP-System Provider angelegt und im SOAMANAGER konfiguriert. Schließlich wurde jeder Endpunkt in ABAP programmiert, um Antworten zurückzusenden.

## 3.3 Grundlagen

### 3.3.1 ABAP

ABAP (Advanced Business Application Programming) ist eine von SAP entwickelte Programmiersprache, die es ermöglicht, prozedurale und objektorientierte Programmierung (ABAP OOP) durchzuführen. ABAP ist sehr gut in das SAP-System integriert und erlaubt die Automatisierung von Prozessen in diesem. Einer seiner größten Vorteile besteht darin, dass er speziell für SAP entwickelt wurde und daher sehr einfach auf die im System vorhandenen Daten zugreifen und diese verwalten kann (auch dank der Integration der SQL-Sprache).

### 3.3.2 XML & XSD

Die Extensible Markup Language (dt. Erweiterbare Auszeichnungssprache), abgekürzt XML, ist eine Auszeichnungssprache zur Darstellung hierarchisch strukturierter Daten im Format einer Textdatei. XML wird auch für den plattform- und implementationsunabhängigen Austausch von Daten zwischen Computersystemen eingesetzt, insbesondere über das Internet. Die aktuelle Version von XML ist XML 1.1, die zurzeit von der W3C empfohlen ist.2

XML Schema (beziehungsweise XSD für XML-Schema-Definition) ist die moderne Möglichkeit, die Struktur von XML-Dokumenten zu beschreiben. XML Schema bietet auch die Möglichkeit, den Inhalt von Elementen und Attributen zu beschränken, z. B. auf Zahlen, Datumsangaben oder Text

### 3.3.3 WSDL

Die Web Services Description Language (WSDL) ist eine plattform-, programmiersprachen- und protokollunabhängige Beschreibungssprache für Netzwerkdienste (Webservices) zum Austausch von Nachrichten auf Basis von XML.3 Die folgende Abbildung 3 präsentiert ein praktisches Beispiel eines WSDL- Dokuments.

![Abbildung 3: Toplevel Element eines WSDL-Dokuments](path/to/image3)

In diesem Beispiel ist die erste Stufe der Elemente angezeigt. <wsdl:definition> ist das Wurzelelement und beinhaltet die weiteren Elemente und hier werden die Namensräume definiert. Die Datentypen werden in <wsdl:types> definiert. Die Eingabe- und Ausgabeparameter sind ein wichtiger Bestandteil der Services. Die se Angaben erfolgen durch <wsdl:message>. Es wird dabei nicht betrachtet, ob es sich um eine eingehende oder ausgehende Nachricht handelt. Das wird im Element <wsdl:operation> des Elements <wsdl:portTyp> festgelegt. Bleibt das Binding Element <wsdl:binding> und das Service Element <wsdl:service>. Das erste definiert das Nachrichtenformat und das Protokoll für die Operationen und Messages, die in der Porttype definiert sind. Das zweite Element enthält eine konkrete physikalische Adresse, unter der der Webservice aufgerufen werden kann.

Die Idee von WSDL ist es, das Verhalten von Webservices plattformneutral zu beschreiben, um die Verwendung von Webservices auf verschiedenen Plattformen zu ermöglichen. Das bedeutet, dass keine programmiersprachenspezifischen Artefakte verwendet werden. Ein Beispiel hierfür ist die Verwendung der XML-Schema-Definition für die Beschreibung der Datentypen, die von gängigen Typsystemen (zum Beispiel Java, C++, ABAP, SQL) abstrahiert.4

### 3.3.4 SOAP

SOAP (ursprünglich für Simple Object Access Protocol) ist ein Netzwerkprotokoll, mit dessen Hilfe Daten zwischen Systemen ausgetauscht und Remote Procedure Calls (RFC) durchgeführt werden können. SOAP stützt sich auf XML zur Repräsentation der Daten und auf Internet-Protokolle der Transport- und Anwendungsschicht zur Übertragung der Nachrichten.5

Durch die Möglichkeit, individuelle Header und Erweiterungen zu definieren, können Entwickler SOAP-Nachrichten an die spezifischen Anforderungen ihrer Anwendungen anpassen. Dies ermöglicht die nahtlose Integration von Sicherheitsmechanismen, Transaktionsunterstützung und verschiedenen Datenformaten.

Eine SOAP-Nachricht ist ein normales XML-Dokument, das die folgenden Elemente enthält:6

- ein obligatorisches Element Envelope aus dem Namensraum http://www.w3.org/2003/05/soap-envelope, das das XML-Dokument als SOAP-Nachricht identifiziert und das Wurzelelement der Nachricht ist
- ein optionales Element Header, das Metainformationen zur Nachricht enthalten kann, wie zum Beispiel Verschlüsselung oder Transaktionsidentifizierung
- ein obligatorisches Element Body, das die eigentlichen Nutzdaten enthält, die aus den Daten bestehen können, die ausgetauscht werden sollen, oder aus Anweisungen für einen entfernten Prozeduraufruf
- ein optionales Element Fault als Kinderelement eines Body-Elementes, das Informationen über Fehler enthält, die während der Verarbeitung der Nachricht aufgetreten sind

Der schematische Aufbau der SOAP-Nachricht ist in Abbildung 4 illustriert.

![Abbildung 4: Aufbau einer SOAP-Nachricht](path/to/image4)

### 3.3.5 Enterprise Services

SAP IS-U kommuniziert nach Außen über SAP Enterprise Services. Dieser Abschnitt stellt diese vor. Zuerst wird eine allgemeine Betrachtung vorgenommen bzw. wird auf den Ansatz der Serviceorientierten Architektur (SOA) eingegangen. Dann werden die Arten der SAP Enterprise Services vorgestellt. Das Metamodell der SAP Enterprise Services beschreibt die Struktur der Services, die zunächst im Detail betrachtet wird. Zum Schluss wird das Enterprise Service Repository und die Registry kurz vorgestellt.

Gartner definiert SOA als ein Paradigma, das die Nutzung von Services in verteilten Systemen beschreibt.

Es ist in der vorherigen Definition zu merken, dass das Wort Service eine zentrale Rolle spielt. Daher werden zunächst ihre Eigenschaften betrachtet.

- In einer sogenannten Service Registry werden die Services zur Verfügung gestellt damit sie in der Systemlandschaft erreichbar sind.
- Die Beschreibung der Services durch Schnittstellen und deren Metadaten verbreitet keine Informationen über die Implementierung.
- Außer dass ein Service plattformunabhängig ist, wird er eigenständig ausgeführt.

Die vorgestellten Eigenschaften sind technisch orientiert. Das reicht aber für eine sinnvolle Nutzung der Services nicht aus. Es fehlt noch die semantische Seite, die durch die Definition eines Enterprise Services ergänzt wird. Darunter wird verstanden, einen Webservice der bestimmte Kriterien erfüllen muss. Diese sind:

- Die SAP Methodik gibt das Gestalten des Services vor.
- Der Service ist im Gesamtkontext der SAP Lösung integriert.

Nun wie sieht die Definition eine Enterprise SOA aus: Sie ist das Modell einer Architektur, die Innovation und Standardisierung in einer einzigen Umgebung ermöglicht und die es IT-Abteilungen erlaubt, die Anforderungen mit der von Unternehmen geforderten Geschwindigkeit und Effizienz zu erfüllen.

Gartner verfolgt mit dem Einsatz der Enterprise SOA zwei grundlegende Ziele, Agilität und Effizienz. Diese zwei Ziele werden durch das Mittel der Zerlegung der Funktionalität in Komponenten sowie durch lose Kopplung erreicht.

### 3.3.6 RFC

RFC ist ein Anwendungsprotokoll, das den Aufruf der ABAP-Funktionsbausteine von Fremdsystemen sowie innerhalb des SAP Systems ermöglicht. Beim Erstellen eines Funktionsbausteins kann dieses Protokoll aktiviert werden. Damit wird der Funktionsbaustein remotefähig und zum Aufrufen bereitgestellt. Der Aufruf kann synchroner (sRFC), asynchroner (aRFC), transaktionaler (tRFC) oder queuender (qRFC) Art sein. Dieses Protokoll ist von besonderem Interesse für diese Arbeit, da es später in den nächsten Abschnitten fürs Erstellen der Webservices eine Voraussetzung ist.

### 3.3.7 IM4G & SMG

Um die Kommunikation mit einem intelligenten Messsystem in Ihrem SAP zu ermöglichen, hat SAP ein Add-on namens "SAP Intelligent Metering for German Energy Utilities"(kurz IM4G) entwickelt.

Dieses Add-on basiert auf etablierten Technologien wie SAP AMI, MDUS, BPEM und Common Layer und ist sowohl für das System des Netzbetreibers als auch für einen Messstellenbetreiber einsetzbar.

Es deckt alle Gerätewechselprozesse und die Installation neuer Geräte im Bereich der Smart Metering Systeme ab und hilft, die Anforderungen des Bundesamtes für Sicherheit in der Informationstechnik (BSI) an das Smart-Meter-Gateway (SMGW) und den Gateway Administrator zu erfüllen. Die zentralen Komponenten der Lösung sind Tabelle 2:

| Komponente | Beschreibung |
|------------|--------------|
| Messinstanz | Eine Messinstanz erbt die Daten und Parameter des vordefinierten Messprodukts und damit auch die des jeweiligen Tarifanwendungsfalls. Alle vererbten Eigenschaften werden zählpunktscharf und zeitabhängig anhand von Messinstanz-Zeitscheiben erfasst und ggf. übersteuert. Eine Messinstanz erlaubt mehrere Sichten, was die Zuordnung von unterschiedlichen Marktrollen am gleichen Zählpunkt zur gleichen Zeit ermöglicht. |
| Tarifanwendungsfälle (TAF) | Ein TAF kann mit dem Tariftyp oder dem Tarif verglichen werden. Dieser beinhaltet die grundlegenden Parameter zur Parametrierung des virtuellen Zählwerk und zur Überführung der Messwerte in den Abrechnungsprozess. Das BSI hat 12 Anwendungsfälle definiert, welche alle im IM4G abbildbar sind. |
| Messprodukt | Ein Messprodukt kann mehrere Tarife beinhalten und beinhaltet die jeweiligen Parameter des vordefinierten Tarifanwendungsfalls (TAF). Das jeweilige Messprodukt wird dem relevanten Zählpunkt über die individuelle Messinstanz zugeordnet. |
| Elektronischer Lieferschein | Ein elektronischer Lieferschein ist eine im SAP AMI integrierte Lösung, die es ermöglicht, Gerätestammdaten automatisiert anzulegen. |
| Parametrierung SMG | Die Parametrierung eines Smart-Meter-Gateway über das IM4G wird über ein Common-Layer-basiertes Prozessdokument gesteuert. Hierbei werden die relevanten Stammdaten an den Gateway-Administrator übermittelt und das Smart-Meter-Gateway parametriert. |

SMG (Smart Meter Gateway) ist ein Gerät, das intelligente Zähler mit dem Internet verbindet und den Datenaustausch zwischen den Zählern und den Energieversorgern ermöglicht. SMGs werden in der Regel in Haushalten und Unternehmen installiert und spielen eine wichtige Rolle im intelligenten Stromnetz.

Das intelligente Stromnetz (Smart Grid) ist ein neues Elektrizitätsnetz, das digitale Technologien nutzt, um die Effizienz, Zuverlässigkeit und Sicherheit des Elektrizitätssystems zu verbessern. Das intelligente Stromnetz befindet sich noch in der Entwicklung, aber es wird erwartet, dass es eine immer wichtigere Rolle bei der Deckung des Energiebedarfs der Zukunft spielen wird.

IM4G und SMG sind beide wichtige Bestandteile des intelligenten Stromnetzes in Deutschland. Die intelligenten IM4G-Zähler werden den Verbrauchern die Informationen liefern, die sie benötigen, um Energie zu sparen und ihren CO2-Ausstoß zu verringern. SMG wird es den Energieversorgern ermöglichen, Daten von intelligenten Zählern zu sammeln und zu analysieren, um die Effizienz und Zuverlässigkeit des Stromnetzes zu verbessern.

### 3.3.8 Stammdaten & SAP IS-U

Stammdaten sind alle Daten, die für das Funktionieren eines Unternehmens von entscheidender Bedeutung sind. Sie beschreiben Personen (Kunden, Mitarbeitende und Lieferanten), Orte (Büros und Standorte) und Dinge (Produkte und Anlagen). Stammdaten machen in der Regel nur einen kleinen Prozentsatz aller Unternehmensdaten aus, gehören aber zu den komplexesten – und wertvollsten - Daten in einem Unternehmen. z.B.: Kundenstammdaten, Lieferantenstammdaten, Standortstammdaten, Produktstammdaten, Anlagenstammdaten.

Abgesehen davon, dass es Unternehmen dabei hilft, gute Entscheidungen zu treffen und wichtige Fragen zu beantworten, bietet das Stammdatenmanagement eine Reihe weiterer Vorteile, wie z. B.:

- Weniger Fehler und Redundanzen bei Daten in verschiedenen Anwendungen. Wenn dieselben Informationen, z. B. ein Kundendatensatz, von verschiedenen Teams inkonsistent eingegeben werden, führt MDM die doppelten Daten zusammen und gleicht sie ab.
- Bessere analytische Erkenntnisse und datengestützte Entscheidungen. Hier trifft die Aussage „Wenn die Eingaben nicht brauchbar sind, können keine brauchbaren Ergebnisse dabei herauskommen“ zu. Wenn die Daten, die analysiert werden, nicht korrekt sind, dann sind es auch die Ergebnisse nicht.
- Optimierte Geschäftsprozesse und höhere Effizienz. Mit qualitativ hochwertigen, konsistenten Stammdaten können Sie durchgängige Geschäftsszenarien wie Lead-to-Cash, Source-to-Pay und Design-to-Operate beschleunigen und automatisieren.
- Verbesserte Transparenz und Einhaltung des Datenschutzes und anderer Vorschriften. Die DSGVO beispielsweise gibt den Menschen mehr Kontrolle darüber, wie ihre Daten erfasst, verwaltet und weitergegeben werden. Ohne MDM können Datensätze über mehrere Abteilungssilos verstreut sein, was die Einhaltung der Vorschriften erschwert.
- Unterstützung bei Fusionen und Übernahmen mit einem optimierten Prozess für die Zusammenführung und den Abgleich mehrerer Datenbestände.

Daten sind entscheidend für digitale Geschäftsprozesse, und Stammdaten bilden die Grundlage für alle anderen Daten. Unternehmen, die über genaue und konsistente Stammdaten verfügen, haben eine stabile Basis, um erfolgreich zu sein.

SAP IS-U (Industry Solutions for Utilities) ist eine prozessorientierte Branchenlösung zur Unterstützung aller Dienstleistungen von Ver- und Entsorgungsunternehmen. Branchenteilnehmer wie Strom-, Gas- und Wasserversorger nutzen SAP IS-U, um ihre Netze in Echtzeit zu überwachen, Interessenten zu verwalten und Kunden abzurechnen. Die Anwendung vereint eine Vielzahl von Funktionen, um Prozesse effizient zu gestalten und einen reibungslosen Ablauf zu gewährleisten. Zu den wichtigsten Funktionen zählen bspw. Verwaltung von Kundenstammdaten, Abrechnungserstellung, Gerätemanagement, Instandhaltung, Verkauf, Service und Buchhaltung.

### 3.3.9 S-HANA

SAP S/4HANA ist eine ERP-Software (Enterprise Resource Planning), die auf der In-Memory-Datenbank SAP HANA basiert. SAP S/4HANA ist die vierte Generation der SAP Business Suite. SAP S/4HANA ist die Nachfolgeversion von SAP R/3 und SAP ERP und wurde 2015 veröffentlicht. SAP S/4HANA ist in der Lage, die Unternehmensprozesse eines Unternehmens zu integrieren und zu automatisieren. Dies geschieht mithilfe von SAP S/4HANA-Modulen, die verschiedene Aspekte eines Unternehmens abdecken. SAP S/4HANA hat die Fähigkeit, die Geschäftsprozesse in Echtzeit zu verarbeiten und zu analysieren. Darüber hinaus kann es auch vorhersagen, empfehlen und entscheiden.

## 3.4 Lösungsmethode

In questo capitolo viene descritto il metodo di soluzione del problema, ovvero come è stato tirato su il simulatore e quali

### 3.4.1 Struttura del simulatore

## 3.5 Ausblick

Die Basis des Simulators und seine Struktur wurden erstellt und implementiert, jedoch war es aufgrund von Zeit- und Wissensbeschränkungen nicht möglich, alle gewünschten Funktionalitäten zu implementieren und vollständige Simulationen mit Testdaten durchzuführen. Dies führte zu einer partiellen, aber dennoch aussagekräftigen Implementierung der meisten der Provider und Consumer. So war es zum Beispiel nicht möglich, den Provider so zu implementieren, dass er zuverlässig Geräteinfosätze erstellt und die notwendigen Logs generiert, um den gesamten Prozess zu verfolgen.

Wichtig ist, dass der Simulator so konzipiert wurde, dass er leicht erweitert und verändert werden kann. Diese Eigenschaft bietet die Möglichkeit, den Simulator in der Zukunft zu vervollständigen, insbesondere mit einem höheren Grad an Wissen über SAP-Systeme und deren Komponenten. Dies könnte den Simulator zu einem wertvollen Werkzeug machen, das die Entwicklung von Webservices erleichtert und eine flexible Plattform bietet, auf der weitere Funktionen und Erweiterungen aufgebaut werden können. Die bisher geleistete Arbeit stellt eine Grundlage dar, auf der ein immer ausgefeilterer Simulator aufgebaut werden kann.

## 3.6 Ergebnisse

Die Umsetzung des Projekts erfolgte unter zeitlichen Beschränkungen und unter Berücksichtigung begrenzter Kenntnisse des SAP-Systems. Der Projektfortschritt reichte bis zu einem bestimmten Punkt, wobei die Implementierung der Mehrheit der Funktionen und Endpunkte der Provider und Consumer sowie partielle Tests unter Verwendung von begrenzten manuellen Testdaten durchgeführt wurden.

Das Projekt verdeutlicht die Durchführbarkeit der Entwicklung eines Simulators dieser Art, selbst bei beschränkten Ressourcen.

Die potenziellen Auswirkungen einer vollständigen Realisierung des Simulators sind vielversprechend. In einer Umgebung, in der SAP zwar SMG-Dienste bereitstellt, jedoch keine speziellen Testumgebungen zur Verfügung stellt, könnte ein abgeschlossener Simulator ein wertvolles Instrument für die Entwicklung und Prüfung von Webdiensten sein, insbesondere im Zusammenhang mit Smart Meter Gateways (SMG).

Diese Ergebnisse legen nahe, dass die Implementierung des Simulators bei ausreichender Zeit und Expertise die Möglichkeit bietet, die Effizienz und Sicherheit der SMG-Funktionalitäten in einer kontrollierten Umgebung zu validieren.

![Abbildung 5: test test test](path/to/image5)

# 4 Abkürzungsverzeichnis

SMG Smart Meter Gateway  

IM4G Intelligent Metering for German Energy Utilities  

---

## Literatur

[08] Anwendungsentwicklung mit Enterprise SOA. Galileo Press, Bonn, Jan. 2008.  

[10] How To... Develop, Monitor and Debug WS Consumer and Provider. Jan. 2010.  

[Bjö21] Björn Lambertz. SAP IS-U. [Online; accessed 15-Oktober-2023]. 2021. URL: https://mindsquare.de/knowhow/sap-is-u/.  

[Gar23] Gartner. Die Offizielle Webseite des Unternehmens. [Online; accessed 15-Oktober-2023]. 2023. URL: https://www.gartner.com/en.  

[hoc23] hochfrequenz. SAP IM4G. [Online; accessed 15-Oktober-2023]. 2023. URL: https://www.hochfrequenz.de/kompetenz/messwesen-und-energiedatenmanagement/sap-im4g/.  

[PP09] Thomas Pohl und Markus Peter. Entwicklung von Enterprise Services für SAP®. Galileo Press, Bonn, 2009. ISBN: 978-3-8362-1200-7.  

[Wik23a] Wikipedia contributors. Extensible Markup Language — Wikipedia, The Free Encyclopedia. [Online; accessed 07-Juli-2023]. 2023. URL: https://de.wikipedia.org/wiki/XML.  

[Wik23b] Wikipedia contributors. SOAP — Wikipedia, The Free Encyclopedia. [Online; accessed 07-Juli-2023]. 2023. URL: http://de.wikipedia.org/wiki/SOAP.  

[Wik23c] Wikipedia contributors. Web Services Description Language — Wikipedia, The Free Encyclopedia. [Online; accessed 07-Juli-2023]. 2023. URL: https://de.wikipedia.org/wiki/Web_Services_Description_Language.
