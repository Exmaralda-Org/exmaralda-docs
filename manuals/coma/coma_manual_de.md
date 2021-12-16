EXMARaLDA Coma –Handbuch

![](RackMultipart20211216-4-q9ctu1_html_dbb4dcd4940e7cf3.png)

## **EXMARaLDA Corpus Manager**

**Manual**

**Version 1.6**

Last update: October, 2016

Main contributor: Kai Wörner

Further contributors: Anne Ferger, Carolin Frontzek,
 Karolina Kaminska, Heidemarie Sambale

**Inhaltsverzeichnis**

**[1](#_Toc476827479)****Über Coma 4**

**[2](#_Toc476827480)****Die Coma-Datenstruktur 5**

[2.1 Korpus](#_Toc476827481)

[2.2 Kommunikationen](#_Toc476827482)

[2.3 Sprecher](#_Toc476827483)

[2.4 Aufnahmen](#_Toc476827484)

[2.5 Transkriptionen](#_Toc476827485)

[2.6 Verknüpfte Dateien 6](#_Toc476827486)

[2.7 Weitere Datentypen 6](#_Toc476827487)

[2.7.1 Locations 7](#_Toc476827488)

[2.7.2 Description 7](#_Toc476827489)

[2.7.3 Anmerkung zu selbstgewählten Metadatenschlüsseln 7](#_Toc476827490)

**[3](#_Toc476827491)****Die Programmoberfläche 8**

[3.1 Reiter 8](#_Toc476827492)

[3.2 Menüs 8](#_Toc476827493)

[3.2.1 Datei-Menü 8](#_Toc476827494)

[3.2.2 Bearbeiten-Menü 10](#_Toc476827495)

[3.2.3 Ansicht-Menü 10](#_Toc476827496)

[3.2.4 Werkzeuge-Menü 10](#_Toc476827497)

[3.2.5 Analyse-Menü 10](#_Toc476827498)

[3.2.6 Wartung-Menü 11](#_Toc476827499)

[3.2.7 Hilfe-Menü 12](#_Toc476827500)

**[4](#_Toc476827501)****Korpusverwaltung 13**

[4.1 Korpus aus Transkriptionen erstellen 14](#_Toc476827502)

[4.1.1 Verwenden des Assistenten 14](#_Toc476827503)

[4.2 Importieren und Exportieren von Metadaten 19](#_Toc476827504)

[4.2.1 Basistranskriptionen Importieren 19](#_Toc476827505)

[4.2.2 Sprecher importieren 19](#_Toc476827506)

**[5](#_Toc476827507)****Verwaltung von Metadaten 21**

[5.1 Aufbau des Daten-Reiters 21](#_Toc476827508)

[5.2 Verwalten von Kommunikationen 22](#_Toc476827509)

[5.3 Metadaten-Anzeige 23](#_Toc476827510)

[5.4 Eingabedialoge 25](#_Toc476827511)

[5.4.1 Location 25](#_Toc476827512)

[5.4.2 Language 26](#_Toc476827513)

[5.5 Templates 27](#_Toc476827514)

[5.5.1 Templates speichern 28](#_Toc476827515)

[5.6 Verwalten von Personen und Sprechern 28](#_Toc476827516)

[5.6.1 Importieren von Sprechern 28](#_Toc476827517)

[5.7 Verknüpfen von Kommunikationen und Sprechern 29](#_Toc476827518)

[5.8 Verwalten von Transkriptionen 29](#_Toc476827519)

[5.9 Verwalten von Aufnahmen 30](#_Toc476827520)

[5.10 Verwaltung von zusätzlichen Dateien 31](#_Toc476827521)

**[6](#_Toc476827522)****Analysieren von Daten 32**

[6.1 Filter 32](#_Toc476827523)

[6.1.1 Filter anlegen 32](#_Toc476827524)

[6.1.2 Filter modifizieren 33](#_Toc476827525)

[6.1.3 Vorgefertigte Filter 33](#_Toc476827526)

[6.1.4 Filter löschen 33](#_Toc476827527)

[6.1.5 Filter bei Sprechern 33](#_Toc476827528)

[6.2 Suchen 33](#_Toc476827529)

[6.3 In Transkriptionen suchen 34](#_Toc476827530)

[6.4 Drucken der Metadatenansicht 34](#_Toc476827531)

[6.5 Korpusstatistik erstellen 35](#_Toc476827532)

[6.6 Wortliste erstellen 36](#_Toc476827533)

[6.7 Wortliste für ausgewählte Sprecher erstellen 37](#_Toc476827534)

[6.8 Ausgabe als html-Datei 37](#_Toc476827535)

[6.9 Korpus-Korb 37](#_Toc476827536)

[6.9.1 Verwalten des Korbes 37](#_Toc476827537)

[6.10 TreeTagger 38](#_Toc476827538)

**[7](#_Toc476827539)****Wartung 40**

[7.1 Überprüfung verknüpfter Transkriptionen 40](#_Toc476827540)

[7.1.1 Transkriptionen segmentieren 40](#_Toc476827541)

[7.1.2 Auf Strukturfehler überprüfen 40](#_Toc476827542)

[7.1.3 Fehlerliste 41](#_Toc476827543)

[7.1.4 Auf Segmentierungsfehler überprüfen 42](#_Toc476827544)

[7.1.5 Sprecherzuordnung prüfen 42](#_Toc476827545)

[7.1.6 Suchen und Ersetzen im Korpus 42](#_Toc476827546)

[7.2 Pflege der Metadaten 43](#_Toc476827547)

[7.2.1 Segmentzahlen aktualisieren 43](#_Toc476827548)

[7.2.2 Aufnahmen aus Transkriptionen aktualisieren 43](#_Toc476827549)

[7.2.3 Description-Schlüssel angleichen 43](#_Toc476827550)

**[8](#_Toc476827551)****Einstellungen 45**

**[9](#_Toc476827552)****Anmerkungen und Haftung 47**

[9.1 Haftungsbegrenzung 47](#_Toc476827553)

[9.2 Preview-Versionen 47](#_Toc476827554)

[9.3 Dieses Dokument 47](#_Toc476827555)

# 1 Über Coma

Der **EXMARaLDA Corpus-Manager** (Coma) ist ein Softwarewerkzeug, mit dem EXMARaLDA-Transkriptionen und die dazu gehörigen Aufnahmen mit relevanten Metadaten versehen und zu Korpora zusammengefasst werden. Unter anderem beinhaltet der Corpus-Manager folgende Funktionen:

- Eingabe und Verwaltung von Informationen zur Kommunikation, zu den beteiligten Personen, zu den Aufnahmen und zu den Transkriptionen;
- Organisation dieser Informationen und Verknüpfung mit den Aufnahme- und Transkriptionsdateien;
- Filtern von Metadaten und Zusammenstellung von Teil-/Untersuchungskorpora anhand der Metadaten. Diese Teilkorpora dienen dann als Ausgangspunkt für das Suchwerkzeug EXAKT;
- Hilfe bei der Erstellung neuer Transkripte mithilfe des Partitureditors und der Funktion **„Neu aus Assistenten…&quot;** (siehe [http://www.exmaralda.org/pdf/PartiturEditor\_Handbuch.pdf](http://www.exmaralda.org/pdf/PartiturEditor_Handbuch.pdf)).

Bitte beachten Sie: Das Programm befindet sich in einer fortwährenden Weiterentwicklung („Work in Progress&quot;). Informationen über aktuelle Änderungen finden Sie unter http://www.exmaralda.org/files/changes.html).

# 2Die Coma-Datenstruktur

Die Struktur, in der Metadaten in Coma verwaltet werden, kennt einige vorgegebene „Datencontainer&quot;:

- Korpora,
- Kommunikationen,
- Sprecher,
- Transkriptionen,
- Aufnahmen,
- und verknüpfte Dateien.

Unter diesen „Containern&quot; existieren verschiedene Datentypen, die in mehreren dieser Container Verwendung finden können. Da es wichtig ist, das Zusammenspiel dieser Container zu verstehen, sollen sie hier kurz beschrieben werden:

## 2.1Korpus

Ein Korpus bildet den Container für alle anderen Metadatentypen. Ein Korpus enthält Metadaten (zu Kommunikationen und Sprechern) sowie Verweise auf alle zum Korpus gehörenden Dateien.

## 2.2Kommunikationen

Mit Kommunikationen werden Gesprächsereignisse verwaltet. An Kommunikationen nehmen typischerweise Sprecher teil und es kann Aufnahmen und Transkriptionen zu den Kommunikationen geben. Das heißt im Datenmodell können Aufnahmen, Transkriptionen, Dateien und Sprecher diesen Kommunikationen zugeordnet sein. Mit den Kommunikationen werden alle Konstellationsdaten zu dem Gesprächsereignis gespeichert, also Dinge wie Ort, Zeit, besondere Umstände, beteiligte Sprachen etc.

## 2.3Sprecher

Sprecher sind Personen, die sich an der Kommunikation beteiligen. Es muss sich dabei nicht um natürliche Personen handeln (es kann beispielsweise auch ein automatisiertes Dialogsystem als Sprecher geführt werden) und die Sprecher müssen in der Kommunikation auch nicht unbedingt sprechen; wenn sie für die Kommunikation von Belang sind, werden sie hier erfasst. Die Daten, die zu den Sprechern erfasst werden, sind von der Kommunikation zunächst unabhängig. Es sollten keine kommunikationsbezogenen Daten mit den Sprechern erfasst werden, damit Sprecher mehreren Kommunikationen zugeordnet werden können. Erfasst werden dagegen Daten wie: Geburtsort und -Datum, biographische Angaben, gesprochene Sprachen und deren Status etc.

## 2.4Aufnahmen

Aufnahmen beziehen sich auf Audio- oder Videoaufnahmen, die zu Kommunikationen angefertigt wurden. Das Coma-Datenmodell unterscheidet: Aufnahmen und tatsächliche Mediendateien. Einer Aufnahme können mehrere tatsächliche Mediendateien zugeordnet werden. Aufnahmen lassen sich nur anlegen, wenn es bereits eine Kommunikation gibt, zu der sie sich zuordnen lassen.

## 2.5Transkriptionen

Im Datentyp Transkriptionen werden Verknüpfungen zu EXMARaLDA-Transkriptionen gespeichert. Coma verwaltet dabei sowohl Basis- (Dateiendung „.exb) als auch segmentierte Transkriptionen (Dateinendung „.exs&quot;). Zur Anzeige von Basistranskriptionen und zu ihrer Behandlung lassen sich in den Einstellungen von Coma Vorgaben machen ( **Bearbeiten \&gt; Einstellungen** , s. auch Abschnitt _ **Einstellungen** _). Transkriptionen sind, genau wie Aufnahmen, mit Kommunikationen verknüpft. Sie lassen sich also ohne Kommunikation nicht verwalten. Auch mit den Aufnahmen sind sie nur über die Kommunikation verbunden.

## 2.6Verknüpfte Dateien

Zu Kommunikationen lassen sich auch Dateien zuordnen, die keine Aufnahmen oder Transkriptionen sind. Dies können beispielsweise: Aufnahmeprotokolle, Pläne, gescannte Metadaten-Erfassungsbögen oder ähnliches sein.

![](RackMultipart20211216-4-q9ctu1_html_862e82fcddcbabf8.png)

## 2.7Weitere Datentypen

Zur Erfassung der eigentlichen Metadaten existieren noch weitere Datentypen, z.B. zur einheitlichen Erfassung von Sprachen und Orten. Zwei dieser Datentypen sind dabei von besonderer Bedeutung:

### 2.7.1Locations

Eine Location bezeichnet in Coma nicht einfach nur einen bestimmten Ort, sondern _einen bestimmten Ort zu einer bestimmten Zeit_, da biographische und andere relevante Ereignisse häufig einen bestimmten Ort und eine bestimmte Zeit haben.

![Shape1](RackMultipart20211216-4-q9ctu1_html_8965136bbf7b578e.gif) ![](RackMultipart20211216-4-q9ctu1_html_6928511e53822929.png)

In dem oben angegeben Fall wird mit einer **„(Location)&quot;** beispielsweise Geburtsdatum und -Ort eines Sprechers erfasst. Es müssen in Locations nicht immer Ort UND Zeit vermerkt werden, es kann auch nur ein Zeitpunkt oder nur ein Ort angegeben werden. Es ist aber wichtig zu beachten, dass man auch dann eine Location verwenden muss, wenn man nur einen Zeitpunkt vermerken will.

### 2.7.2Description

Da es extrem schwierig ist, standardisierte Metadaten für alle erdenklichen Fälle vorzusehen, wird in Coma der überwiegende Teil der Metadaten mit freien Schlüssel-Wert-Paaren erfasst. Diese Paare werden unter dem Datentyp Descriptions zusammengefasst. Sie existieren für die meisten der in Coma existierenden Datentypen: So lassen sich Descriptions für Korpora, Kommunikationen, Sprecher, Locations, Aufnahmen etc. anlegen.

![Shape2](RackMultipart20211216-4-q9ctu1_html_8965136bbf7b578e.gif) ![](RackMultipart20211216-4-q9ctu1_html_dbe26f4114efb379.png)

In diesem Beispiel sind in einer **„Description (Speaker)&quot;** Metadaten zu einem Sprecher erfasst.

### 2.7.3Anmerkung zu selbstgewählten Metadatenschlüsseln

Dass sich die Felder innerhalb von Descriptions frei benennen lassen, macht sie nicht beliebig: Jeder Anwender sollte sich für sein Korpus ein festes Inventar an Description-Schlüsseln ausdenken und dokumentieren, um später mit den Metadaten auch gewinnbringend arbeiten zu können. Die Dokumentation dieser Metadatenschlüssel und ihrer möglichen Werte kann beispielsweise in Form eines Handbuchs geschehen.

Metadatenschlüssel werden in Coma automatisch alphabetisch sortiert. Um zusammengehörige Schlüssel nacheinander zu gruppieren, bietet es sich an ein passendes Präfix vor den Metadatenschlüssel zu setzen. Im obigen Beispiel wurde dies bei **„Ausbildung: schulisch&quot;** und **„Ausbildung: beruflich&quot;** angewendet.

# 3Die Programmoberfläche

## 3.1Reiter

![](RackMultipart20211216-4-q9ctu1_html_b57418d2e530d5aa.png)

Die meisten Funktionen von Coma lassen sich direkt im Programmfenster vornehmen. Das Fenster wird von drei Reitern gegliedert, über die sich die Funktionen für einzelne Bereiche des Programms erreichen lassen.

- Korpus-Reiter führt Sie zur Verwaltung der Korpora. Hier lassen sich die Metadaten, die das Korpus als Ganzes betreffen, eingeben (s. Kapitel _ **Korpusverwaltung** _).
- Daten-Reiter wählt den zentrale Bereich des Programms an. Hier lassen sich die Metadaten zu Gesprächsereignissen, Konstellationen, Sprechern, Transkriptionen und Aufnahmen eingeben, filtern und selektieren (s. Kapitel _ **Verwaltung von Metadaten** _).
- Korpus-Korb-Reiter bietet Zugriff auf einen **„Korb&quot;** , in dem sich Transkriptionen zur späteren Untersuchung ablegen lassen. Das dahinter liegende Prinzip ist in der Einleitung kurz und im Kapitel _**[Korpus-Korb](#_Korpus-Korb)**_ näher beschrieben.

## 3.2Menüs

In den Programmmenüs finden sich weitere Funktionen, die sich nicht direkt innerhalb des Programmfensters anwählen lassen:

### 3.2.1Datei-Menü

![](RackMultipart20211216-4-q9ctu1_html_6d082884979e5cde.png)

- Neues Dokument: Erstellt ein leeres Coma-Dokument und legt ein unbenanntes Korpus in ihm an. Nähere Informationen zu Korpora in Coma finden sie im Kapitel _**[Korpusverwaltung](#_ailkcxsyi8g7)**_.
- Dokument öffnen...: Zeigt ein Dateiauswahlfenster, über das sich eine Coma-Datei mit Metadaten öffnen lässt.
- Dokument speichern: Speichert die aktuell geöffnete Coma-Datei. Wenn die Datei noch nicht gespeichert wurde erscheint ein Dateiauswahlfenster, in dem sie den Dateinamen- und Ort angeben können. Beachten Sie dabei die Ausführungen unter _**[Korpusverwaltung](#_ailkcxsyi8g7)**_ für einen sinnvollen Speicherort.
- Dokument speichern als...: Lässt Sie das Dokument an einem anderen Ort als dem aktuellen Speicherort speichern. Darauf folgt eine Liste der zuletzt geöffneten Dateien, die sich direkt anwählen lassen.
- Liste löschen: Löscht die Liste der zuletzt geöffneten Dateien.
- Korb speichern als…: Speichert den Korb (_**[Korpus-Korb](#_Korpus-Korb)**_) als separates Korpus (s. auch _ **Korpus-Korb** _).
- Templates öffnen…: Zeigt ein Dateiauswahlfenster, mit dem Sie eine Template-Datei öffnen können. Nähere Informationen zu Templates bekommen Sie unter _**[Templates](#_Templates)**_.
- Templates speichern: Speichert die aktuell geöffnete Templates-Datei mit allen angelegten Templates. Sollte keine Templates-Datei geöffnet sein, so erscheint ein Dateiauswahl-Dialog, in dem sich ein Speicherort- und Name für die Datei wählen lässt.
- Templates speichern als...: Speichert die angelegten Templates in eine Datei, die über einen Dateiauswahl-Dialog bestimmt wird.
- Templates beim Start laden: Bestimmt, ob die geladene Templates-Datei beim Start von Coma automatisch geöffnet wird.
- Coma-Datei hinzufügen…: Mit dieser Funktionen können andere existierende Coma-Dateien ausgewählt und in das geöffnete Dokument eingebunden („gemerged&quot;) werden. Es werden sowohl die Kommunikationen als auch die Sprecher eingefügt.
- Basistranskription importieren…: Lässt sie Metadaten aus einer existierenden Basistranskription importieren (s. _ **Basistranskriptionen Importieren** _).
- Sprecher importieren: Lässt Sie Sprecher-Metadaten aus einer anderen Coma-Datei importieren. Siehe (s. _ **Importieren von Sprechern** _).
- Korpus aus Transkriptionen erstellen: Mit dieser Funktion lässt sich aus EXMARaLDA-Transkriptionen, die bereits mit Kopfdaten versehen sind, eine Coma-Datei erstellen. Diese Funktion ist unter _ **Korpus aus Transkriptionen erstellen** _ beschrieben.
- Ausgabe…: Erstellt eine .html-Ausgabedatei mit Metadaten, deren Pfad ausgewählt werden kann (s. _ **Ausgabe als html-Datei** _).
- Programm beenden: Beendet das Programm.

### 3.2.2Bearbeiten-Menü

Hier können die Einstellungen des Programms verändert werden. Siehe hierzu das Kapitel _**[Einstellungen](#_Einstellungen)**_.

### 3.2.3Ansicht-Menü

Die Optionen des **Ansicht**** -**Menüs wirken sich nur auf die Ansicht der Metadaten im Daten-Reiter (s. _**Aufbau des Daten-Reiters**_) aus.

![](RackMultipart20211216-4-q9ctu1_html_4286fec004103a65.png)

- Sprecher bei Kommunikationen: Bestimmt, ob unter den Metadaten zu einer ausgewählten Kommunikation die Metadaten der zugeordneten Sprecher angezeigt werden sollen.
- Millisekunden: Bestimmt, ob bei Angaben zur **„Location&quot;** bei dem Schlüssel **„PeriodDuration&quot;** die Zeitspanne auch in Millisekunden angezeigt wird (sowohl bei Kommunikationen als auch bei Sprechern).
- geschützte Metadaten: Einige Metadatenfelder (wie die Anzahl der Segmente in einer segmentierten Transkription, s. Graphik unten) lassen sich in Coma nicht editieren. An dieser Stelle können Sie bestimmen, ob diese Felder angezeigt werden sollen oder nicht.

![](RackMultipart20211216-4-q9ctu1_html_e54dd02b17c2a0a5.png)

- Sprachnamen (Englisch): Bestimmt, ob die Sprachkürzel in der Metadatenübersicht aufgelöst werden sollen. Angezeigt werden immer nur die Englischen Sprachnamen.
- farbig, schwarz/weiß: Bestimmt, ob die Metadatenansicht farbig oder monochrom erfolgt.

### 3.2.4Werkzeuge-Menü

Hier kann das Werkzeug TreeTagger (siehe [http://www.cis.uni-muenchen.de/~schmid/tools/TreeTagger/](http://www.cis.uni-muenchen.de/~schmid/tools/TreeTagger/)) angewendet werden. Zur genaueren Erklärung der Funktionalität siehe _**[TreeTagger](#_TreeTagger)**_.

### 3.2.5Analyse-Menü

Das **Analyse**** -**Menü bietet Optionen, mit denen sich das Korpus als Ganzes analysieren lässt.

![](RackMultipart20211216-4-q9ctu1_html_85f6966cb0340256.png)

- Mit EXAKT im Korpus suchen…: Öffnet ein Suchfenster, mit dem sich in den Transkriptionen des geöffneten Korpus suchen lässt. Nähere Informationen entnehmen Sie bitte der **Dokumentation des Suchwerkzeuges EXAKT**
[(http://exmaralda.org/](////VSSFB538/HZSK/DATEN/Schulungsmaterial/Manuals/COMA/(http:/www.exmaralda.org/pdf/Quickstart_working_with_EXAKT_DE.pdf) im Menü „Hilfe/Support&quot; ).
- Korpusstatistik generieren…: Ermöglicht es, eine Statistik über die im geöffneten Korpus vorhandenen Transkriptionen zu generieren (s. _ **Korpusstatistik erstellen** _).
- Wortliste erstellen: Erstellt eine Wortliste der in der Transkription verwendeten Wörter (s. _**[Wortliste erstellen](#_Wortliste_erstellen)**_). Diese Wortliste kann auch gefiltert oder als Datei gespeichert werden.
- Wortliste für ausgewählte Sprecher: Erstellt eine Wortliste der in der Transkription verwendeten Wörter für die Sprecher, die vorher markiert wurden (s. _ **Wortliste für ausgewählte Sprecher erstellen** _).

### 3.2.6Wartung-Menü

Im **Wartung**** - **Menü finden sich Optionen, mit denen sich Fehler in Metadaten sowie Transkriptionen des geöffneten Korpus bequem finden und beheben lassen. Das Menü ist in Optionen zu** „Transkriptionen&quot; **und zu** „Metadaten&quot;** unterteilt.

![](RackMultipart20211216-4-q9ctu1_html_e37cafbdcaeadb58.png)

**Transkriptionen** :

- Transkriptionen segmentieren: Segmentiert die eingebundenen Basistranskriptionen nach einem gewählten Segmentieralgorithmus. Nähere Informationen zu verschiedenen Segmentierungsalgorithmen bekommen Sie in der Dokumentation zum EXMARaLDA-Partitur-Editor (s. _ **Transkriptionen segmentieren** _).
- Auf Strukturfehler überprüfen… **:** Überprüft alle verknüpften Transkriptionen auf Strukturfehler (s. _ **Auf Strukturfehler überprüfen** _).
- Auf Segmentierungsfehler überprüfen… **:** Überprüft alle verknüpften Transkriptionen auf Segmentierungsfehler (s. _ **Auf Segmentierungsfehler überprüfen** _).
- Sprecherzuordnung prüfen: Überprüft, ob Sprecher im Korpus vorhanden sind, denen keine Transkriptionsspur zugeordnet ist (s. _ **Sprecherzuordnung prüfen** _).
- Suchen und Ersetzen im Korpus…: Öffnet ein Menü, durch das die Basistranskriptionen des Korpus mit regulären Ausdrücken verändert werden können (s. _ **Suchen und Ersetzen im Korpus** _).

**Metadaten** :

- Segmentzahlen aktualisieren: Extrahiert die Segmentzahlen aus allen verknüpften Transkriptionen und fügt diese in die Metadaten ein, so dass sie sich in Coma anzeigen und addieren lassen (s. _ **Segmentzahlen aktualisieren** _).
- Aufnahmen aus Transkriptionen aktualisieren: Aktualisiert die Aufnahmen in Coma mit den Aufnahmen, die mit den Transkriptionen verknüpft sind. Bereits verknüpfte Aufnahmen, die nicht mehr existieren, werden dabei nicht gelöscht (s. _ **Aufnahmen aus Transkriptionen aktualisieren** _).
- Description-Schlüssel angleichen...: Öffnet ein Fenster, in dem Sie Fehler, die Sie gegebenenfalls bei der Benennung von Metadaten-Schlüsseln gemacht haben, korrigieren können (s. _ **Description-Schlüssel angleichen** _).
- XML-Dokument anzeigen: Öffnet ein Fenster mit der XML-Darstellung der Coma-Datei. Beachten Sie, dass es bei großen Coma-Dateien eine Weile dauern kann, bis das Fenster erscheint.

### 3.2.7Hilfe-Menü

Im **Hilfe**** -**Menü finden sich Optionen zur Lösung von etwaigen Problemen mit Coma.

- Hilfe (im Web): Öffnet die Coma-Webseite mit Links zu diesem und weiteren Hilfe-Dokumenten.
- Nach Updates suchen: Stellt eine Verbindung mit dem EXMARaLDA-Webserver her und überprüft, ob eine neuere Version als die installierte von Coma erschienen ist. Falls dies der Fall ist, können Sie durch klicken auf die **„Download-Seite besuchen&quot;** -Schaltfläche die EXMARaLDA-Download-Seite besuchen und die neueste Version herunterladen. In den _**[Einstellungen](#_Einstellungen)**_ können Sie bestimmen, ob die Update-Überprüfung in regelmäßigen Intervallen automatisch durchgeführt wird und ob _**[Preview-Versionen](#_Preview-Versionen)**_ in die Update-Prüfung mit einbezogen werden.
- Debug-Information in die Zwischenablage kopieren: Kopiert den Inhalt des Log-Files in die Zwischenablage. Wenn Sie einen Fehler im Programm entdecken, so können sie ein Email mit diesem Inhalt an die Programmierer senden.
- Über Coma: Zeigt ein Fenster mit Programminformationen und der Versionsnummer des Programms an.

# 4Korpusverwaltung

Auf dem **„Korpus&quot;** -Reiter werden alle Daten verwaltet, die sich mit dem Korpus als Ganzes befassen. Der Reiter - hier mit einem geladenen Korpus - sieht so aus:

![](RackMultipart20211216-4-q9ctu1_html_f25df14d920d4aeb.png)

Zu allen angelegten Korpora lassen sich in Coma beschreibende Metadaten eingeben: Vorgegeben sind dabei der **„Korpusname&quot;** und das Feld der **„Unique Speaker Distinction&quot;**. Sie lassen sich im oberen Bereich des Programms editieren, durch einen Klick auf das folgende Symbol ![](RackMultipart20211216-4-q9ctu1_html_ec598d023faef61.png) .

![](RackMultipart20211216-4-q9ctu1_html_b1b2436a0c7c4ef9.png)

Das Feld **„Unique Speaker Distinction&quot;** muss vom Anwender nur geändert werden, wenn die Sprecherabkürzungen für die erfassten Sprecher nicht eindeutig sind und die eindeutige Zuordnung über ein anderes Metadatenfeld erfolgt. In diesem Fall muss der XPath zu diesem Metadatenfeld an dieser Stelle eingegeben werden. Für Korpora, die aus bestehenden Transkriptionen erzeugt werden, wird dieser Wert automatisch generiert.

Zu jedem Korpus lässt sich in der großen Tabelle eine **„Description&quot;** (siehe _**[Die Coma-Datenstruktur](#_Die_Coma-Datenstruktur)**_) anlegen, in der sich freie Attribut-Wert-Paare zu Eigenschaften des Korpus eingeben lassen. Die Schaltfläche **„Dublin Core Metadata&quot;** auf der linken Seite der Tabelle fügt die Schlüssel für eine Dublin-Core
# 1
-konforme Ressourcenbeschreibung in die Tabelle ein - eine solche Beschreibung erleichtert die Auffindbarkeit eines Korpus z.B. im Internet. In der Abbildung sind für das ausgewählte Korpus Dublin-Core-Metadaten erfasst.

## 4.1Korpus aus Transkriptionen erstellen

Die Funktion **Datei \&gt; Korpus aus Transkriptionen erstellen** , dient dazu, aus vorhandenen EXMARaLDA-Transkriptionen, bei denen bereits Metadaten als Kopfdaten eingegeben wurden, automatisch eine Coma-Datei zu erstellen.

Bevor man diese Funktion benutzt sollte man sich noch einmal klar machen, wie die Dateien eines EXMARaLDA-Korpus sinnvollerweise organisiert sein sollten:

- Mediendateien sollten im selben oder einem untergeordneten Verzeichnis liegen wie die Transkription, der sie zugeordnet sind;
- Transkriptionen, die thematisch oder organisatorisch zusammengehören sollten in Verzeichnissen zusammengefasst sein;
- Die Coma-Datei sollte oberhalb dieser Verzeichnisse gespeichert sein.

Wenn sie die **„Korpus aus Transkriptionen erstellen&quot;** -Funktion verwenden, müssen Sie sich um den letzten Punkt nicht kümmern - die Datei wird von dem Assistenten an die richtige Stelle gespeichert.

### 4.1.1Verwenden des Assistenten

Die Funktion zum Erstellen einer Coma-Datei aus Transkriptionen ist als Assistent aufgebaut, der sie durch die notwendigen Schritte führt.

Wenn Sie den Assistenten aufrufen sollten Sie folgenden Bildschirm sehen:

![](RackMultipart20211216-4-q9ctu1_html_80b5a0ec452f52cc.png)

Im Feld **„Korpus-Name&quot;** geben Sie den Namen ein, den Ihr Korpus später haben soll.

Klicken Sie dann auf die drei Punkte hinter dem Feld **„Coma-Datei&quot;** und wählen dort das Verzeichnis über dem Verzeichnis/den Verzeichnissen aus, in denen Ihre Transkriptionen liegen und wählen Sie ggf. einen anderen Dateinamen.

![](RackMultipart20211216-4-q9ctu1_html_739691b853fc0b23.png)

Daraufhin durchsucht der Assistent alle Verzeichnisse unterhalb des gewählten Verzeichnisses nach Transkriptionen und analysiert deren Kopf-/Metadaten.

![](RackMultipart20211216-4-q9ctu1_html_76170a005274c7e2.png)

Klicken Sie daraufhin auf die **Weiter** -Schaltfläche, um zum Bildschirm mit der Auswahl der Transkriptionen zu kommen. Eine Zusammenfassung wird angezeigt.

![](RackMultipart20211216-4-q9ctu1_html_9d7d9150ec0ea016.png)

In diesem Schritt können Sie festlegen, welche der gefundenen Transkriptionen in die Coma-Datei übernommen werden sollen. In der ersten Spalte der Tabelle können Sie Dateien an- oder abwählen, in der zweiten Spalte ist der Dateiname der Transkription angegeben und in der dritten Spalte wird angezeigt, ob es sich um eine segmentierte Transkription handelt oder nicht. Wollen Sie beispielsweise nur segmentierte Transkriptionen in ihre Coma-Datei übernehmen, so wählen sie zunächst mit der Schaltfläche **„alle abwählen&quot;** am unteren Rand alle ab und fügen die segmentierten anschließend mit **„Segmentierte Transkriptionen wählen&quot;** wieder hinzu.

Beachten Sie, dass die Auswahl der Transkriptionen natürlich einen Einfluss auf die Menge der Metadatenfelder haben kann, die Ihnen zur Verfügung stehen.

Wenn Sie Ihre Auswahl getroffen haben, klicken Sie auf **Weiter**.

![](RackMultipart20211216-4-q9ctu1_html_72a9234ea99b79ee.png)

Im nächsten Bildschirm können Sie wählen, ob Basistranskriptionen automatisch segmentiert werden sollen. Nähere Informationen zu verschiedenen Segmentierungsalgorithmen bekommen Sie in der **Dokumentation zum EXMARaLDA-Partitur-Editor** ([www.exmaralda.org](http://www.exmaralda.org/), Sektion „Hilfe/Support&quot;)

- Das Kontrollfeld **„Transkriptionen segmentieren&quot;** bestimmt, ob überhaupt Basistranskriptionen segmentiert werden sollen. Wenn dieses Kontrollfeld abgewählt ist, stehen auch die anderen Optionen nicht zur Verfügung.
- Beim Auswahlmenü **„Segmentierungs-Algorithmus&quot;** können Sie zwischen den verfügbaren Algorithmen auswählen.

Die nächsten Kontrollfelder bestimmen, was die Segmentierungsroutine machen soll, wenn sich eine Transkription aufgrund eines Fehlers (meist bedingt durch nicht eingehaltene Transkriptionskonventionen) nicht segmentieren lässt:

- Bei gewählter Option **„abbrechen&quot;** wird der Segmentierungsprozess abgebrochen, sobald sich eine Transkription nicht segmentieren lässt. Auch die vorher bereits segmentierten Transkriptionen werden wieder gelöscht.
- Wenn die **„überspringen&quot;** -Option angewählt ist, werden nur die fehlerhaften Transkriptionen nicht segmentiert, die Transkriptionen, bei denen keine Fehler auftreten, werden dagegen geschrieben.
- Mit der Option **„Default-Segmentierung verwenden&quot;** werden Transkriptionen, bei denen ein Fehler auftritt, mithilfe des Default-Algorithmus behandelt, der zwar keine eigentliche Segmentierung durchführt, aber trotzdem eine Transkription vom Typ „segmentierte Transkription&quot; erstellt.
- Mit der Checkbox **„Fehlerliste schreiben&quot;** können Sie bestimmen, ob eine Liste mit den Fehlern, die bei der Segmentierung aufgetreten sind, geschrieben wird. Die Datei wird an dieselbe Stelle geschrieben wie die Coma-Datei (die Stelle, die am Anfang ausgewählt wurde) und heißt „segmentation-errors.xml&quot;. Diese Datei können Sie benutzen, um die Segmentierungsfehler direkt im Partitureditor zu korrigieren (_ **Fehlerliste** _).

- Unter **„Zielort&quot;** können Sie bestimmen, an welche Stelle die segmentierten Transkriptionen geschrieben werden sollen – entweder in dasselbe Verzeichnis wie die Basistranskriptionen ( **„selbes Verzeichnis&quot;** ) oder in ein **„neues Verzeichnis&quot;** im Stammordner des Korpus. Den Namen des neuen Verzeichnisses müssen Sie in dem Eingabefeld bestimmen.
- Mit **„Suffix&quot;** bestimmen Sie, was an den Dateinamen der Transkriptionen angehängt wird, um zu kennzeichnen, dass es sich um segmentierte Transkriptionen handelt.

Wenn Sie die Einstellungen vorgenommen haben, klicken Sie auf **weiter**.

![](RackMultipart20211216-4-q9ctu1_html_a32266f252b64cfc.png)

Auf dem Bildschirm **„Metadaten-Zuordnung&quot;** bestimmen Sie, welche der gefundenen Metadaten mit welchem Namen und an welche Stelle in der Coma-Datei übernommen werden.

- In der ersten Spalte können Sie bestimmen, ob der jeweilige Schlüssel überhaupt in die Coma-Datei übernommen werden soll oder nicht.
- In der zweiten Spalte sehen Sie alle Transkriptions-Kopfdatenschlüssel (außer denen der Sprechertabellen), die in allen Transkriptionen des Korpus gefunden wurden. Felder, die als „frei bestimmbare Attribute&quot; eingegeben wurden haben in der Liste ein vorangestelltes **„ud\_&quot;** (für „user defined&quot;).
- In der folgenden dritten Spalte ( **„target name&quot;** ) können Sie den Namen bestimmen, die die entsprechenden Schlüssel in Coma bekommen sollen; in der Regel werden das die vorgegebenen sein, die bereits im Partitur-Editor vergeben wurden. An dieser Stelle lassen sich allerdings auch Daten vereinheitlichen: Im obigen Beispiel ist der Schlüssel **„ud\_Aufnahme\_dörch&quot;** markiert, der direkt unterhalb des Schlüssels **„ud\_Aufnahme\_durch&quot;** steht - offensichtlich ein Eingabefehler. In der dritten Spalte liesse sich an dieser Stelle **„Aufnahme durch&quot;** eintragen, um die Felder in Coma zu vereinheitlichen.
- In der vierten Spalte **„target&quot;** („Ziel&quot;) wird bestimmt, an welcher Stelle in der Coma-Datei die Metadaten schließlich landen: Metadaten, die in einem Transkriptionskopf standen beziehen sich ja nicht notwendigerweise auf eine Coma-Communication. Zur Auswahl stehen **„communication&quot;** für Metadaten zur Gesprächskonstellation, **„recording&quot;** für Metadaten zur Aufnahme und **„transcription&quot;** für Metadaten zur Transkription.
- Häufig existieren zu einer Gesprächssituation („communication&quot;) mehrere Transkriptionen. Im Drop-Down-Menü am unteren Bildschirmrand bestimmen Sie, nach welchen Metadatenschlüssel Transkriptionen zu einer Kommunikation zusammengefasst werden - wenn sie also mehrere Transkriptionen in Kommunikationen zusammenfassen wollen, sollten Sie in den Transkriptionen einen Metadatenschlüssel haben, der die entsprechende Kommunikation eindeutig definiert. Wenn jede Transkription genau einer Kommunikation zugeordnet ist, dann wählen Sie **„one file -\&gt; one communication&quot;** aus dem Menü.

Sollten Sie nach dem Schreiben der Coma-Datei feststellen, dass sie an dieser Stelle irgendetwas falsch zugeordnet haben, so können Sie einfach mit dem **zurück** -Knopf wieder an diese Stelle springen und die Zuordnungen ändern - der eigentliche Vorgang des Erstellens der Coma-Datei geht nämlich relativ schnell vonstatten.

Wenn Sie die Zuordnungen vorgenommen haben, klicken Sie auf **weiter**.

![](RackMultipart20211216-4-q9ctu1_html_1c35324bc1910426.png)

Im nächsten Bildschirm können Sie bestimmen, welche der gefundenen Sprecher ( **„Personen&quot;** ) in die Coma-Datei übernommen werden soll, indem sie in der ersten Spalte der Tabelle die Sprecher an- oder abwählen.

- Mit dem linken Drop-Down-Menü bestimmen Sie, anhand welches Metadatenfeldes in den Partitur-Sprechertabellen die jeweiligen Sprecher im Korpus auseinandergehalten werden. In den meisten Fällen wird das Namenskürzel aus der im Folgenden abgebildeten Sprechertabelle im Partitur-Editor für die jeweiligen Sprecher eindeutig sein, in den wenigsten Fällen die durchnummerierten Sprecherkürzel („SPK0, SPK1...&quot;), die im Assistenten als „Id&quot; erscheinen. Wenn Sie die Auswahl im linken Drop-Down-Menü ändern, so wird die Tabelle mit den zu importierenden Sprechern sofort aktualisiert - so können Sie gleich erkennen, ob Sie das richtige Feld für eine eindeutige Zuordnung ausgewählt haben.
- In Coma haben alle Sprecher ein Kürzel und einen (Pseudo-)Namen. Aus welchem Metadatenfeld dieser Name bestimmt werden soll, bestimmen Sie mit dem rechten Drop-Down-Menü.

Wenn Sie die entsprechenden Auswahlen vorgenommen haben, klicken Sie auf **weiter**.

![](RackMultipart20211216-4-q9ctu1_html_2daa323090141293.png)

Im nächsten Bildschirm sehen Sie noch einmal eine Zusammenfassung der vorgenommenen Einstellungen. Wenn Sie noch etwas ändern wollen, klicken Sie auf die Schaltfläche **zurück** und nehmen Sie Änderungen vor. Ansonsten klicken Sie auf **abschliessen** , um die Coma-Datei zu erzeugen. Wenn die Datei fehlerlos geschrieben wurde wird das Fenster geschlossen und die Coma-Datei in Coma geöffnet.

## 4.2Importieren und Exportieren von Metadaten

### 4.2.1Basistranskriptionen Importieren

Mit dieser Option lassen sich Metadaten aus einer EXMARaLDA-Basistranskription importieren. Wenn Sie den Menüpunkt anwählen, erscheint ein Dateiauswahlfenster, in dem Sie die Basistranskription auswählen, die Sie in Coma integrieren wollen. Beachten Sie auch hier wieder, dass die Datei in einem Verzeichnis unterhalb der Coma-Datei (oder im selben Verzeichnis) liegen muss.

Weitere Eingaben sind nicht erforderlich; sofern die Transkription noch nicht mit der Coma-Datei verknüpft ist, wird eine neue Kommunikation und neue Sprecher (sofern noch nicht vorhanden) mit den Metadaten der Transkription angelegt und diese gleichzeitig verknüpft.

![](RackMultipart20211216-4-q9ctu1_html_5db8e7f35e469a35.png)

### 4.2.2Sprecher importieren

Um Sprecher, die in einer anderen Coma-Datei bereits angelegt sind, in die geöffnete Coma-Datei zu importieren, wählen Sie **Datei \&gt; Sprecher importieren**. Daraufhin öffnet sich ein Dateiauswahl-Fenster, in dem Sie die Coma-Datei auswählen, in der sich die Metadaten der Sprecher befinden, die sie importieren wollen. Wenn Sie die Datei ausgewählt haben, öffnet sich ein Dialog mit einer Liste aller Sprecher, die in der ausgewählten Datei angelegt sind:

![](RackMultipart20211216-4-q9ctu1_html_83d48ad23f7292d0.png)

Wählen Sie aus der Liste die Sprecher aus, die Sie importieren wollen, und bestätigen Sie die Auswahl mit **importieren**. Die Metadaten der entsprechenden Sprecher werden daraufhin importiert.

# 5Verwaltung von Metadaten

Alle Metadaten zu Gesprächskonstellationen, Sprechern, Aufnahmen und Transkriptionen werden auf dem **„Daten&quot;** -Reiter vorgenommen.

## 5.1Aufbau des Daten-Reiters

Der Bildschirm gliedert sich in drei Bereiche:

![](RackMultipart20211216-4-q9ctu1_html_3fb417836dd2ea1f.png)

- Auf der linken Seite befindet sich eine Tabelle mit den Kommunikationen des gewählten Korpus. Über dieser Tabelle liegt der Bereich, in dem sich Filter für diese Tabelle modifizieren und anlegen lassen (_ **Filter** _). Unter der Tabelle finden sich Schaltflächen zum Hinzufügen, Entfernen und Duplizieren von Kommunikationen sowie für die Bedienung des _**[Korpus-Korbes](#_Korpus-Korb)**_ und zur _**[Segment-Zählung](#_Segmentzahlen_aktualisieren)**_:

![](RackMultipart20211216-4-q9ctu1_html_c2dbc579350a396f.png)

- In der mittleren Spalte werden die Metadaten der ausgewählten Kommunikationen oder Sprecher angezeigt und bearbeitet. Über dieser Anzeige findet sich ein Suchfeld, mit dem sich im Volltext der Metadaten _**[Suchen](#_Suchen)**_ lässt:

![](RackMultipart20211216-4-q9ctu1_html_1990f3634098fd25.png)

- Unterhalb der Anzeige findet sich eine Schaltfläche zum [Drucken der Metadatenansicht](#_Drucken_der_Metadatenansicht), sowie zwei Schaltflächen zum _**[Verknüpfen von Kommunikationen und Sprechern](#_Verkn%C3%BCpfen_von_Kommunikationen)**_.
- In der rechten Spalte werden – analog zur Kommunikationen-Spalte – die Sprecher verwaltet.
- Die Trenner zwischen den drei Spalten lassen sich verschieben, um mehr Platz für einzelne Spalten auf dem Bildschirm zu bekommen. Am oberen Rand dieser Trenner befinden sich kleine Dreiecke - mit einem Klick auf diese Pfeile lassen sich Spalten ganz ein- oder ausblenden, so dass sich beispielsweise nur Kommunikationen und deren Metadaten anzeigen lassen.

## 5.2Verwalten von Kommunikationen

Mit den Kommunikationen werden alle Konstellationsdaten zu dem Gesprächsereignis gespeichert, also Dinge wie Ort, Zeit, besondere Umstände, beteiligte Sprachen etc.

![](RackMultipart20211216-4-q9ctu1_html_b9c979a991f0f155.png)

Die **„Kommunikationen&quot;** werden in einer dreispaltigen Tabelle auf der linken Seite des Reiters angezeigt. In der zweiten Spalte steht der **„Kommunikationsname&quot;** , ein in Coma vorgegebenes Feld, in der dritten Spalte erscheint ein wählbares Element aus den Metadaten zu der jeweiligen Kommunikation – im Falle des obigen Screenshots ein ausführlicherer Name für die Kommunikation. Das Element, das hier angezeigt wird, wird durch einen Klick auf den entsprechenden Schlüssel der Kommunikationen oder Sprecher gewählt.

In der ersten Spalte erscheint ein Büroklammer-Symbol, falls diese Kommunikation mit einem in der Sprecher-Spalte ausgewählten Sprecher verknüpft ist. Wenn auf der rechten Seite ein oder mehrere Sprecher angewählt werden kann man so erkennen, ob diese Sprecher der jeweiligen Kommunikation zugeordnet sind, d.h. an ihr teilgenommen haben.

Mit einem Klick auf die Spaltenüberschriften lässt sich die Tabelle nach dieser Spalte sortieren - dies ist insbesondere für die Warenkorb-Funktionalität hilfreich, aber auch, um sich beispielsweise schnell einen Überblick zu verschaffen, an welchen Kommunikationen ein bestimmter Sprecher teilgenommen hat: Sortieren Sie dazu die Tabelle anhand der ersten Spalte und wählen Sie auf der rechten Seite einen Sprecher aus - die relevanten Kommunikationen stehen jetzt untereinander am Anfang (oder am Ende) der Tabelle.

Mit den Schaltflächen unterhalb der Tabelle lassen sich u.a. Kommunikationen anlegen und löschen.

- ![](RackMultipart20211216-4-q9ctu1_html_1113f51f8a7b3528.png)Ein Klick auf diese Schaltfläche legt eine neue Kommunikation an. Sie erscheint üblicherweise am Ende der Tabelle und hat den Namen **„unnamed&quot;**. Eine eindeutige ID wird automatisch vergeben und kann in Coma nicht geändert werden.
- ![](RackMultipart20211216-4-q9ctu1_html_37ca5a2d6bec1679.png) Diese Schaltfläche löscht die ausgewählte(n) Kommunikationen. Achtung: Es erfolgt keine Sicherheitsabfrage und dieser Schritt lässt sich nicht rückgängig machen.
- ![](RackMultipart20211216-4-q9ctu1_html_e5fff9cbf7431e4c.png)Diese Schaltfläche erstellt eine Kopie der ausgewählten Transkription. Die Kopie erhält eine neue Id und den Namen der Quell-Kommunikation mit einem angehängten **„\_cloned&quot;** , die Metadaten sind ansonsten identisch. Sind beim Betätigen der Schaltfläche mehrere Kommunikationen ausgewählt, so wird nur von der obersten eine Kopie erstellt.
- ![](RackMultipart20211216-4-q9ctu1_html_43a95054462d6c7a.png)Mit dieser Schaltfläche werden alle Transkriptionen, die den augenblicklich ausgewählten Kommunikationen zugeordnet sind, in den **„Korpus-Korb&quot;** gelegt. Nähere Informationen finden sich im Kapitel zum _**[Korpus-Korb](#_Korpus-Korb)**_.
- ![](RackMultipart20211216-4-q9ctu1_html_b79e0f4b71682645.png)Die Taschenrechner-Schaltfläche führt eine Segment-Zählung durch. Dazu addiert sie die Segmentzahlen aller segmentierten Transkriptionen, die den ausgewählten Kommunikationen zugeordnet sind, und gibt sie in einem kleinen Fenster aus. In diesem Beispiel:

![](RackMultipart20211216-4-q9ctu1_html_5ee72226ed0ea80c.png)

haben die (nach HIAT) segmentierten Transkriptionen zu den ausgewählten Kommunikationen beispielsweise 2412 _utterances_ und 23210 _words_.

## 5.3Metadaten-Anzeige

Wenn eine Kommunikation ausgewählt ist, werden in der mittleren Spalte die erfassten Metadaten angezeigt.

I ![](RackMultipart20211216-4-q9ctu1_html_10d0d89c42f8bead.png) m oberen Balken steht der Name der Kommunikation, der auch immer in der zweiten Spalte der Kommunikations-Tabelle erscheint. Es folgen die **„Descriptions&quot;** zur Kommunikation und weitere Metadatenfelder, die ebenfalls über eine Description verfügen können.

In der Metadaten-Ansicht lassen sich einige Elemente anklicken, um mit dem Programm zu interagieren:

- Mit einem Klick auf den Metadatenschlüssel werden die Werte des Metadatenschlüssels, der sich in dieser Zeile befindet, als zweite Spalte in der Tabelle mit den Kommunikationen angezeigt. Möchte man sich also z.B. einen schnellen Überblick darüber verschaffen, zu welchem Gesprächstyp die jeweiligen Kommunikationen im obigen Beispiel gehören, so würde man auf den Schlüsselnamen „Gesprächstyp&quot; in der Metadatenansicht klicken.
- Mit einem Klick auf einen Metadatenwert wird ein Filter für die Kommunikationstabelle erstellt. Klickt man im obigen Beispiel auf den Wert „Fernsehdebatte&quot; hinter dem Metadatenschlüssel „Gesprächstyp&quot;, so werden in der Kommunikationstabelle nur noch Kommunikationen angezeigt, bei denen dem Attribut „Gesprächstyp&quot; der Wert „Fernsehdebatte&quot; zugewiesen ist. Nähere Informationen zu der Verwendung von Filtern finden sie unter _**[Filter](#_Filter)**_.

- ![](RackMultipart20211216-4-q9ctu1_html_2a2cac25050e2346.png)Mit dieser Schaltfläche lassen sich die Metadaten editieren. Ein Klick auf das Symbol öffnet je nach Metadatenfeld unterschiedliche Dialoge, in denen sich die entsprechenden Änderungen vornehmen lassen. Die einzelnen _**[Eingabedialoge](#_Eingabedialoge)**_ werden ein wenig später erklärt.
- ![](RackMultipart20211216-4-q9ctu1_html_9e98ac2b7378f0fe.png)Analog zu den anderen Schaltflächen in Coma lassen sich mit den Plus- und Minus-Schaltflächen Metadatenfelder hinzufügen oder entfernen. Im obigen Beispiel ist ein Plus-Symbol neben der Überschrift **„Language(s)&quot;**; mit einem Klick auf das Symbol ließe sich der Kommunikation eine Sprache zuordnen.
- ![](RackMultipart20211216-4-q9ctu1_html_566627c5c16ada0e.png)Mit einem Klick auf das Minus-Symbol neben der **„Recording&quot;** ließe sich diese bereits zugeordnete Aufnahme nach einer Sicherheitsabfrage entfernen.

Es werden keine Metadaten angezeigt, wenn mehrere Kommunikationen ausgewählt sind. In diesem Fall wird nur die Anzahl ausgewählter Kommunikationen und zugeordneter Sprecher angezeigt:

![](RackMultipart20211216-4-q9ctu1_html_c150bb8a853aded1.png)

## 5.4Eingabedialoge

![](RackMultipart20211216-4-q9ctu1_html_2a2cac25050e2346.png) Wenn in der Metadatenanzeige auf diese Schaltfläche gedrückt wird, erscheint je nach ausgewähltem Metadatenfeld ein Dialog, mit dem dieses Metadatenfeld bearbeitet werden kann. Diese Dialogfelder werden im Folgenden kurz erläutert.

### 5.4.1Location

Das Location-Dialogfeld dient zur Bearbeitung des Datentyps **„Location&quot;** – es handelt sich dabei um einen speziellen Datentyp, der bei _**[Locations](#_Location)**_ besprochen ist.

![](RackMultipart20211216-4-q9ctu1_html_f84d96cb87c76ed.png)

„ **Locations&quot;** beschreiben – wie dort erwähnt – eine Kombination von Zeit(-abschnitt) und Ort.

Das Feld **„Type&quot;** kann eine nähere Beschreibung der Location enthalten. Wird hier ein Wert eingegeben, so erscheint in der Metadatendarstellung später statt der Bezeichnung **„Location&quot;** der entsprechende Wert.

Die Felder **„Street&quot;,**** „City&quot;, „PostalCode&quot; **und** „Country&quot;** erklären sich weitgehend von selber. Die (optionale) Startzeit lässt sich bequem durch Anklicken des Kalendersymbols an der rechten Seite einstellen: Es erscheint ein Kalender-Auswahlfenster, in dem das Datum nur angeklickt werden muss.

![](RackMultipart20211216-4-q9ctu1_html_41d50be180e7c0e6.png)

Die Dauer wird in dem Feld eingegeben, das aus mehreren kleinen Eingabefeldern besteht. Diese stehen (von rechts nach links) für: Jahre, Monate, Tage, Stunden, Minuten, Millisekunden. Will man also die Dauer von 2 Jahren und 3 Monaten eintragen, so genügt es, die ersten beiden Felder mit 2 und 3 auszufüllen und die restlichen Felder leer zu lassen.

Unterhalb findet sich das Feld zur Eingabe der **„Description&quot;** , die die Location näher beschreibt.

Am oberen Rand des Eingabefensters findet sich ein Panel, mit dem sich Templates anlegen und abrufen lassen. Dies ist unter _**[Templates](#_Templates)**_ näher besprochen.

### 5.4.2Language

Der Language-Eingabedialog dient der Erfassung von Sprachen bei Sprechern und Kommunikationen. In Coma werden Sprachen in Form von 3-stelligen Sprachkürzeln erfasst, die dem **„ISO-Standard 639-3&quot;** entsprechen
# 2
.

![](RackMultipart20211216-4-q9ctu1_html_f3cc452bbd034a67.png)

In das Feld **„ISO 639-3 Code&quot;** wird der Code für die gewünschte Sprache direkt eingetragen. Mit einem Druck auf die **Enter** -Taste wird der eingegeben Code in der Tabelle verfügbarer Codes nachgeschlagen und ein (englischer) Name für die Sprache mit diesem Kürzel erscheint in dem Feld **„Name&quot;**. Erscheint dort kein Name, so existiert dieser Code vermutlich nicht.

Durch die Eingabe eines (englischen) Sprachnamens in das Feld **„Name&quot;** können Sie das gesuchte Kürzel ermitteln. Geben Sie dazu den Namen (oder einen Teil des Namens) der gesuchten Sprache ein und wählen Sie die Sprache aus den angezeigten Vorschlägen. Das entsprechende Sprachenkürzel wird dann in das ISO-Feld eingetragen. Der Inhalt des Feldes **„Name&quot;** selber dient nur der Orientierung und zur Unterstützung bei der Eingabe der Kürzel – der dort hinterlegte Wert wird in der Coma-Datei nicht gespeichert.

Unter **„Type&quot;** lässt sich die erfasste Sprache für den aktuellen Sprecher oder die aktuelle Kommunikation (analog zum **„Type&quot;** bei Locations) näher Kategorisieren. Für Sprecher bietet es sich an, hier den Status (L1, L2, …) der Sprache für diesen Sprecher anzugeben – dieser wird dann in der Metadatenübersicht direkt angezeigt.

## 5.5Templates

Für häufig benötigte Datensätze lassen sich in Coma **„Templates&quot;** anlegen. Die Datentypen, für die Templates zur Verfügung stehen, erkennt man daran, dass sich ein standardisierter Template-Balken am oberen Rand des Eingabefensters findet.

![](RackMultipart20211216-4-q9ctu1_html_39c4f96c2d532ec5.png)

![](RackMultipart20211216-4-q9ctu1_html_88b2058c54f93ebb.png) Mit einem Klick auf den Plus-Button werden die Daten, die im Eingabefenster eingegeben wurden, in ein neues Template übernommen. Es erscheint ein Eingabefenster, in dem sich ein Name für das Template eingeben lässt. Danach lassen sich Eingabefenster desselben Datentyps (also z.B. für **„Communications&quot;** oder **„Descriptions&quot;** ) automatisch mit diesen Werten ausfüllen, indem aus dem Dropdown-Menü das Template mit dem vergebenen Namen ausgewählt wird.

![](RackMultipart20211216-4-q9ctu1_html_98a73c2aab9d3dd9.png)

![](RackMultipart20211216-4-q9ctu1_html_ffafb3615114eb26.png) Ein Klick auf die Minus-Schaltfläche löscht das im Dropdown-Menü ausgewählte Template.

### 5.5.1Templates speichern und öffnen

Die angelegten Templates lassen sich über das Datei-Menü abspeichern und wieder öffnen. Dort (und in den _**[Einstellungen](#_Einstellungen)**_) lässt sich auch festlegen, dass eine bestimmte Template-Datei beim Start des Corpus-Managers automatisch geöffnet wird (s. Graphik unten).

![](RackMultipart20211216-4-q9ctu1_html_23aba0e080d4ab54.png)

Durch die Option „Templates öffnen&quot; lassen sich angelegte Templates in anderen Dateien öffnen. Diese können dort weiterbearbeitet und wiederum in überarbeiteter Version abgespeichert werden. Alternativ können gespeicherte Templates in anderen Programmen bearbeitet werden. Diese lassen sich problemlos in überarbeiteter Version in Coma öffnen.

Um eine bestimmte Template-Datei beim Start von Coma automatisch zu öffnen, muss dies zunächst in den Einstellungen ausgewählt und auf die entsprechende Datei verwiesen werden. Hier lässt sich weiterhin festlegen, erstellte Templates nach Beenden von Coma automatisch zu speichern.

## 5.6Verwalten von Personen und Sprechern

Die Verwaltung von Personen und Sprechern erfolgt grundsätzlich analog zu der Verwaltung von Kommunikationen.

![](RackMultipart20211216-4-q9ctu1_html_a4cd24d315c5263f.png)

Zu beachten ist, dass für Sprecher – im Gegensatz zu Kommunikationen – mehrere Locations angelegt werden können, um Stationen der Biographie von Sprechern abbilden zu können.

### 5.6.1Importieren von Sprechern

Wenn Metadaten zu Sprechern bereits in einer anderen Coma-Datei vorliegen, so lassen sich diese in die geöffnete Coma-Datei importieren (_ **Importieren von Sprechern** _).

## 5.7Verknüpfen von Kommunikationen und Sprechern

![](RackMultipart20211216-4-q9ctu1_html_2b756cbb0a8831a0.png) Um **„Verknüpfungen&quot;** zwischen Kommunikationen und den beteiligten Sprechern herzustellen, markieren sie in der Kommunikationen-Tabelle die gewünschten Kommunikationen (auch mehrere - verwenden sie dazu die betriebssystemspezifischen Tasten zur Auswahl mehrerer Objekte) und in der Sprechertabelle die beteiligten Sprecher und klicken Sie auf die **„Verknüpfen&quot;** -Schaltfläche (Kettensymbol).

Beachten Sie: Es werden alle selektierten Sprecher zu allen selektierten Kommunikationen hinzugefügt, unabhängig davon, ob sie bereits verknüpft waren oder nicht.

![](RackMultipart20211216-4-q9ctu1_html_3b0a854f6f7fbf4c.png) Um Verknüpfungen zwischen Sprechern und Kommunikationen aufzuheben, verfahren Sie analog: Markieren Sie alle Kommunikationen und Sprecher, zwischen denen Sie die Verknüpfung aufheben wollen, und klicken Sie auf die **„Verknüpfung aufheben&quot;** -Schaltfläche.

Alle Verknüpfungen zwischen den gewählten Kommunikationen werden aufgehoben, ob sie vorher bestanden oder nicht.

**ACHTUNG** : Beide Aktionen können nicht rückgängig gemacht werden!

## 5.8Verwalten von Transkriptionen

Alle Transkriptionen sind in Coma Kommunikationen zugeordnet und werden entsprechend mit ihnen verwaltet.

![](RackMultipart20211216-4-q9ctu1_html_2ae82e4aa2a794e3.png)

Wenn Sie sich die Metadaten zu einer Kommunikation anzeigen lassen, so sehen Sie immer einen Abschnitt für die Verwaltung von Transkriptionen.

![](RackMultipart20211216-4-q9ctu1_html_9e98ac2b7378f0fe.png) Analog zu den anderen Metadatenobjekten können Sie mit einem Klick auf diese Schaltfläche eine Transkription hinzufügen. Es öffnet sich daraufhin ein Dateiauswahlfenster, mit dem Sie die Transkription, die zur ausgewählten Kommunikation gehört, auswählen.

Beachten Sie, dass die Transkriptionen im selben Verzeichnis wie die Coma-Datei oder in einem Verzeichnis unter dem Verzeichnis der Coma-Datei liegen müssen.

Wenn Sie die Datei(en) ausgewählt haben, wird die Transkription der ausgewählten Kommunikation zugeordnet. Die Transkription bekommt in Coma einen Namen – dieser entspricht entweder dem Dateinamen oder dem Namen der Kommunikation, der sie zugeordnet ist – welche Option gewählt wird lässt sich in den _**[Einstellungen](#_Einstellungen)**_ bestimmen. Bei mehreren Transkriptionen werden an die Namen fortlaufende Nummern angehängt.

Bei der Zuordnung wird in die Transkriptionsdatei hineingeschaut. Dabei wird überprüft, ob es sich überhaupt um eine EXMARaLDA-Transkription handelt, ob es eine Segmentierte- oder eine Basistranskription ist und es werden die Metadaten zu Segmentzahlen ausgelesen. Es findet allerdings keine weitergehende Prüfung auf Korrektheit der Transkription statt. Die ermittelten Segmentzahlen werden in die Description der neu angelegten Transkription in Coma eingefügt, lassen sich aber nicht mit der Description editieren – es sind sogenannte „geschützte Metadaten&quot;, deren Schlüsselname mit einem **„#&quot;** -Zeichen beginnt. Im **Ansicht** -Menü lässt sich die Anzeige dieser Metadaten ein- oder ausschalten.

Die Transkriptionen bekommen auch eine eindeutige ID in Coma, die einer eindeutigen ID in der Transkriptionsdatei entsprechen sollte. Standardmäßig schreibt Coma diese ID bei der Zuordnung in den Kopf der Transkriptionsdatei hinein. Sollten Sie nicht wünschen, dass Coma in die Transkriptionsdateien schreibt, so können Sie das ebenfalls in den _**[Einstellungen](#_Einstellungen)**_ abschalten (d.h. „**Coma-ID beim Zuordnen in Transkriptionen schreiben (sofern nicht vorhanden)&quot;**).

![](RackMultipart20211216-4-q9ctu1_html_566627c5c16ada0e.png) Mit dieser Schaltfläche können Sie die Zuordnung der Transkription löschen. Beachten Sie, dass die eigentliche Transkription nicht gelöscht wird – dies müssen Sie von Hand erledigen.

## 5.9Verwalten von Aufnahmen

Die Verwaltung von Aufnahmen erfolgt analog zu der von Transkriptionen direkt in der Metadatenansicht von Kommunikationen:

![](RackMultipart20211216-4-q9ctu1_html_9ef3367d142f5afa.png)

![](RackMultipart20211216-4-q9ctu1_html_5f244585c3934652.png) Mit dieser Schaltfläche ordnen Sie eine Aufnahme einer Kommunikation zu. Wenn Sie die Schaltfläche betätigen, erscheint ein Dateiauswahlfenster, in dem Sie die entsprechende(n) Mediendatei(en) auswählen können. Wenn sie die Auswahl bestätigt haben so wird eine Verknüpfung zu dieser Datei innerhalb der Kommunikation angelegt. Die Coma-Datei muss vorher gespeichert sein, da der Link zu der Mediendatei relativ zur gespeicherten Coma-Datei angelegt wird.

![](RackMultipart20211216-4-q9ctu1_html_15193ebdacfb95f9.png) Mit dieser Schaltfläche entfernen Sie eine Verknüpfung mit einer Aufnahme.

Sofern Java für den Dateityp einer Aufnahme einen entsprechenden Player vorgesehen hat, so können Sie mit einem Klick auf den Dateinamen, der hinter **„File:&quot;** steht, die Mediendatei direkt aus Coma abspielen.

## 5.10Verwaltung von zusätzlichen Dateien

Zusätzlich zu Transkriptionen und Aufnahmen lassen sich an Kommunikationen auch Dateien anhängen, die nicht mit EXMARaLDA-Werkzeugen verarbeitet werden können. Diese können beispielsweise für die Situationsbeschreibung interessant sein.

![](RackMultipart20211216-4-q9ctu1_html_9ab8891d815e15e5.png)

Die Verwaltung dieser Dateien erfolgt analog zu der von Aufnahmen. Beachten Sie auch hier, dass die Dateien in einem Verzeichnis unterhalb der Coma-Datei liegen müssen, um die Auflösung der relativen Pfade gewährleisten zu können.

# 6Analysieren von Daten

## 6.1Filter

Mit Filtern lässt sich bestimmen, welche Kommunikationen in der linken und welche Sprecher in der rechten Spalte angezeigt werden.

### 6.1.1Filter anlegen

An einfachsten lassen sich Filter anlegen, indem in der Metadatendarstellung auf einen Metadatenwert geklickt wird.

Über der Spalte mit den Kommunikationen wird dann der gerade erstellte Filter angezeigt, in der Tabelle werden alle Kommunikationen herausgefiltert, die nicht über dieses Attribut-Wert-Paar verfügen.

![](RackMultipart20211216-4-q9ctu1_html_25db5ae16d2295ce.png)

![](RackMultipart20211216-4-q9ctu1_html_722ce0b3e5097f5.png)

Rechts neben einer kurzen Referenz auf den Filter befinden sich drei Schaltflächen:

![](RackMultipart20211216-4-q9ctu1_html_fed8266fe9656d8f.png)

Die erste Schaltfläche aktiviert- oder deaktiviert den Filter.

Die zweite Schaltfläche invertiert den Filter. Im obigen Beispiel würde ein Klick auf die Schaltfläche dazu führen, dass nur noch Kommunikationen angezeigt werden, deren „transcription-convention&quot; nicht **„HIAT (vereinfacht)&quot;** ist.

Die dritte Schaltfläche bestimmt, ob dieser Filter mit weiteren Filtern (sofern vorhanden) mit logisch UND oder mit logisch ODER verknüpft wird. Wenn ein weiterer Filter beispielsweise nur Kommunikationen zulassen würde, in denen die Sprache DEU (=Deutsch) vorkommt, so würde mit dieser Schaltfläche bestimmt, ob die Bedingungen beide erfüllt sein müssen oder nur eine von beiden.

### 6.1.2Filter modifizieren

Die Filter selber bestehen aus einem XPath-Ausdruck, der auf das XML der Coma-Datei angewendet wird. Dieser XPath-Ausdruck lässt sich von fortgeschrittenen Anwendern modifizieren, in dem man in die Beschreibung des Filters hinein klickt:

![](RackMultipart20211216-4-q9ctu1_html_76bec5451d742a2d.png)

Das Feld färbt sich daraufhin gelb und Sie können den verwendeten XPath modifizieren. Mit einem Druck auf die **Enter** -Taste wird der XPath übernommen. Handelt es sich um einen ungültigen XPath, so färbt sich das Eingabefeld rot und der Filter wird nicht übernommen.

### 6.1.3Vorgefertigte Filter

Für Kommunikationen gibt es einige vorgefertigte Filter. Sie lassen sich über das Ordnersymbol in der rechten Spalte auswählen:

![](RackMultipart20211216-4-q9ctu1_html_3c11beeee8331d14.png)

- Leerer Filter: Erstellt einen Filter mit einem leeren XPath, der dann vom Anwender modifiziert werden kann.
- alle mit Transkriptionen: Erstellt einen Filter, der nur Kommunikationen anzeigt, für die Transkriptionen vorliegen.
- alle mit Aufnahmen: Erstellt einen Filter, der nur Kommunikationen anzeigt, für die Aufnahmen vorliegen.

### 6.1.4Filter löschen

Die Schaltfläche **„Alle Filter löschen&quot;** löscht alle Filter ohne Rückfrage. Einzelne Filter lassen sich nur deaktivieren, nicht löschen.

### 6.1.5Filter bei Sprechern

Für die Sprecher-Spalte funktionieren die Filter analog zu denen der Kommunikationen-Spalte, es gibt jedoch keine vorgefertigten Filter.

## 6.2Suchen

Eine erweiterte Form des Filterns lässt sich über das Suchfeld oberhalb der Metadaten-Spalte erreichen.

Wird in das Feld eine Zeichenfolge eingegeben und auf den **Suchen** -Button geklickt, so wird sowohl bei den Kommunikationen als auch bei den Sprechern ein Filter eingerichtet, der nur die Elemente anzeigt, die diese Zeichenfolge in irgendeinem Metadatenwert enthalten.

Zusätzlich wird die gesuchte Zeichenfolge in der Metadatenanzeige farblich hervorgehoben. Im hier abgebildeten Beispiel wurde nach der Zeichenfolge **„schland&quot;** gesucht; im Screenshot ist zu sehen, dass in der markierten Kommunikation zwei Metadatenwerte die Zeichenfolge enthalten (jeweils Deut_schland_).

![](RackMultipart20211216-4-q9ctu1_html_198c739a0432f1da.png)

## 6.3In Transkriptionen suchen

Aus Coma lassen sich Suchabfragen über alle Transkriptionen des geladenen Korpus anstoßen. Wählen Sie dazu die **Analyse \&gt; Mit EXAKT im Korpus suchen**. Weitere Informationen zur Suche in EXAKT finden Sie in der EXAKT-Anleitung, die Sie unter [http://www.exmaralda.org/](http://www.exmaralda.org/), Sektion „Hilfe/Support&quot; herunterladen können.

## 6.4Drucken der Metadatenansicht

Mit einem Klick auf das Druckersymbol unter der Metadatenansicht wird die aktuell sichtbare Metadatenansicht (Kommunikation, Kommunikation+Sprecher oder Sprecher) an einen Webbrowser geschickt, von wo aus sie sich ausdrucken lässt. Beachten Sie, dass sie die Ansicht über **Ansicht \&gt; schwarz/weiß** umschalten können, um möglicherweise eine bessere Druckansicht zu erhalten.

## 6.5Korpusstatistik erstellen

Über die Option **Analyse \&gt; Korpusstatistik generieren** lässt sich Statistik für die Segmentzahlen des geöffneten Korpus erstellen, und zwar entweder nach Kommunikationen oder nach Sprechern. Wenn Sie die Option aufrufen, werden zunächst die Segmentzahlen aller verknüpften Transkriptionen ermittelt:

![](RackMultipart20211216-4-q9ctu1_html_1189a6335e67333d.png)

Dann erscheint ein Dialog, in dem Sie auswählen können, ob die Segmentzahlen nach Kommunikationen oder nach Sprechern ausgegeben werden sollen. Sie können auch ein eigenes, externes Stylesheet bestimmen, das die Auswertung übernehmen soll.

![](RackMultipart20211216-4-q9ctu1_html_ce0e6a0f70d23dbf.png)

Nach einem Klick auf die **OK** -Schaltfläche wird die Korpusstatistik generiert und in einem Webbrowser geöffnet:

![](RackMultipart20211216-4-q9ctu1_html_782af13470e124fd.png)

In diesem Beispiel wurde die Statistik nach Sprechern erstellt: Für alle Sprecher (hier mit Kürzeln repräsentiert) wird eine Tabelle mit allen Kommunikationen, an denen Sie teilgenommen haben, und einer genauen Aufschlüsselung der enthaltenen Segmente ausgegeben.

Wenn Sie die Auswertung in einem anderen Programm weiterverwenden wollen, so können Sie den Inhalt des Browserfensters entweder über die Zwischenablage z.B. in Word einfügen oder die HTML-Datei aus dem Browser speichern.

## 6.6Wortliste erstellen

Mit der Option **Analyse \&gt; Wortliste erstellen** lässt sich eine Liste aller Wörter in allen Transkriptionen des geöffneten Korpus erstellen. Wenn Sie die Option anwählen, werden zunächst alle Wörter aller Transkriptionen (sofern sie segmentiert sind) ermittelt. Dies kann je nach Korpusgröße durchaus eine Weile dauern.

Anschließend wird die Wortliste angezeigt:

![](RackMultipart20211216-4-q9ctu1_html_5766506cabba275a.png)

In der Tabelle auf der linken Seite sehen Sie in der linken Spalte die gefundenen Wörter und in der rechten Spalte die Anzahl der Vorkommen im Korpus. Beide Spalten lassen sich durch Klick auf den Spaltenkopf sortieren.

Mit Hilfe des **„Filter&quot;** -Eingabefeldes am oberen Rand des Fensters lässt sich die Anzeige auf bestimmte Wörter reduzieren.

Unter der Tabelle lässt sich die Wortliste über die Schaltfläche **Save wordlist…** als HTML-Datei abspeichern, die sich u.a. auch in MS Word öffnen lässt.

In die rechte, mit **„Selection&quot;** überschriebene Spalte lassen sich durch Klick auf die ![](RackMultipart20211216-4-q9ctu1_html_9e98ac2b7378f0fe.png) Schaltfläche ausgewählte Wörter in eine Auswahlliste überführen.

Mit einem Klick auf die Schaltfläche **XPath** wird ein XPath erzeugt und in die Zwischenablage kopiert, der sich als Suchausdruck im Suchwerkzeug EXAKT verwenden lässt.

Ein Klick auf die Schaltfläche **Regex** kopiert einen regulären Ausdruck in die Zwischenablage, der sich ebenfalls in EXAKT zur Suche nach den ausgewählten Wörtern einsetzen lässt.

## 6.7Wortliste für ausgewählte Sprecher erstellen

Diese Option funktioniert grundsätzlich genau wie _**[Wortliste erstellen](#_Wortliste_erstellen)**_, nur müssen zuvor die Sprecher angewählt werden, für die die Wortliste erstellt werden soll.

## 6.8Ausgabe als html-Datei

Ein Klick auf **Datei\&gt;Ausgabe…** erstellt eine html-Ausgabedatei, deren Speicherplatz selbst gewählt werden kann. Es öffnet sich das folgende Fenster:

![](RackMultipart20211216-4-q9ctu1_html_2dc59dc9c1d36e8b.png)

Hier kann beispielsweise eine Tabelle aller Kommunikationen und der zugehörigen Descriptions erstellt werden. Es kann entweder ein vorgegebener Ausgabe-Stylesheet aus dem Menü oder ein eigener Stylesheet (custom stylesheet) ausgewählt werden. Außerdem kann beim Umfang ausgewählt werden, ob die Ausgabedatei das gesamte Korpus oder den Korpus-Korb miteinbeziehen soll. Bei Klick auf die vorgegebenen Stylesheets wird daneben eine Beschreibung angezeigt.

## 6.9Korpus-Korb

Um anhand von Metadaten eine Auswahl an Transkriptionen vornehmen zu können, die dann einer weiteren Analyse zugeführt werden können, gibt es in Coma den sogenannten **„Korpus-Korb&quot;**. Es handelt sich dabei um eine Liste von Transkriptionen, die man – analog zu einem Einkaufskorb in einem Online-Shop – nach und nach füllen kann.

Um die Trankriptionen in den Korb zu legen, muss man zum Reiter Daten wechseln, die entsprechende(n) Kommunikation(en) auswählen und dann auf das Einkaufswagensymbol ![](RackMultipart20211216-4-q9ctu1_html_677dc462e700f59a.png) in der Leiste unter den Kommunikationen klicken.

Den aktuellen Inhalt des Korpus-Korbes kann man sich anschauen, wenn man auf den entsprechenden Reiter am oberen Rand von Coma klickt.

### 6.9.1Verwalten des Korbes

Der Korpus-Korb-Reiter bietet drei Schaltflächen zur Verwaltung:

- Transkription entfernen: Wenn in der Liste eine Transkription ausgewählt ist, so lässt sie sich mit einem Klick auf diese Schaltfläche aus dem Korb entfernen. Die Transkription wird nur aus dem Korb genommen; am eigentlichen Korpus ändert sich dadurch nichts.
- Korb leeren: Entfernt alle Transkriptionen aus dem Korb.

![](RackMultipart20211216-4-q9ctu1_html_7396d36e58990636.png)

- Korb speichern als: Mit dieser Schaltfläche können Sie den Inhalt des Korbes auf dem Computer abspeichern. Der Korb wird dabei als eine vollwertiges Coma-Korpus gespeichert und lässt sich anschließend sowohl in Coma als auch in EXAKT öffnen, enthält aber eben nur die Metadaten zu den Transkriptionen, die vorher in den Korb gelegt wurden.

Um die volle Funktionsfähigkeit des gespeicherten Korpus zu erhalten, sollten Sie es in dasselbe Verzeichnis speichern wie die Coma-Datei, aus dem Sie es generiert haben.

## 6.10TreeTagger

In Coma gibt es zusätzlich die Möglichkeit, die eingefügten segmentierten Transkriptionen direkt mit dem TreeTagger (siehe [http://www.cis.uni-muenchen.de/~schmid/tools/TreeTagger/](http://www.cis.uni-muenchen.de/~schmid/tools/TreeTagger/)) zu taggen. Hierzu muss zunächst das Programm TreeTagger über den angegebenen Link installiert werden. Bitte beachten Sie die Hinweise zur Installation auf den jeweiligen Betriebssystemen. Bei der Installation für Windows ist es wichtig, dass der TreeTagger-Ordner direkt beim Laufwerk C:\ eingefügt wird. Der entsprechende Pfad sollte dann C:\TreeTagger heißen.

Die Parameter-Dateien für die entsprechenden Sprachen, die mit dem TreeTagger annotiert werden sollen, müssen zusätzlich von der Webseite herunter geladen werden. Anschließend müssen sie in den richtigen Ordner der TreeTagger-Datei eingefügt werden, wie es auf der Webseite erklärt wird.

Wenn die Installation vollständig ist, kann der TreeTagger direkt aus der Coma-Datei über **Werkzeuge\&gt;TreeTagger…** aufgerufen werden. Danach muss als Directory der Pfad des TreeTagger-Ordners ausgewählt werden. Als Parameters file muss die Parameter-Datei der Sprache, die im Korpus annotiert werden soll, ausgewählt werden. Hinter der Parameter-Datei muss die Kodierung des Parameters festgelegt werden. Bei den Parametern auf der Webseite handelt es sich vor allem um UTF-8-kodierte Parameter.

Beim **„Output:&quot;** kann ausgewählt werden, ob entweder nur **„Part of Speech Tags&quot;** oder **„Lemmas&quot;** oder beides ausgegeben werden soll.

![](RackMultipart20211216-4-q9ctu1_html_78565304211c15f2.png)

Bei den **„Tagging Options&quot;** kann ein **„Tagging Profile&quot;** , das sich auf die verwendete Transkriptionskonvention bezieht, ausgewählt werden. Außerdem ist das Suffix, das die neuen Dateien erhalten sollen, frei wählbar.

Durch die anwählbaren Kästchen unterhalb des Suffixes lässt sich das Ergebnis des TreeTaggers modfizieren. Es kann ausgewählt werden, ob eine Standoff-Annotation-Datei (.ESA-Datei) mit den Ergebnissen, die sich mit Sextant öffnen lässt, erstellt werden soll. Außerdem kann entschieden werden, ob die Ergebnisse in die segmentierte Transkription (.exs-Datei) eingefügt werden soll.

Wenn das Tagging mit dem TreeTagger erfolgreich war, erhält man also je nach Auswahl eine neue .exs- und .esa-Datei mit dem ausgewählten Suffix, die die Ergebnisse des TreeTaggers enthalten. Diese Dateitypen lassen sich unter anderem mit dem EXMARaLDA Programm Sextant ([http://exmaralda.org/de/sextant/](http://exmaralda.org/de/sextant/)) öffnen.

# 7Wartung

Coma bietet einige Optionen zur Datenpflege sowohl der mit dem Korpus verknüpften Transkriptionen als auch der Metadaten.

## 7.1Überprüfung verknüpfter Transkriptionen

### 7.1.1Transkriptionen segmentieren

Im Allgemeinen finden alle Änderungen an Transkriptionen im Partitur-Editor auf der Grundlage von den Basistranskriptionen (Dateiendung .exb) statt. Das segmentierte Transkriptionsformat („.exs&quot;) dient hingegen zum Integrieren der Transkriptionen in einen Korpus in Coma (.coma Datei) und als Grundlage für das Suchen in EXAKT. Wann immer sie Fehlerkorrekturen und Änderungen in Ihrer .exb Datei speichern, können Sie Ihre segmentierte(n) Transkription(en) im Partitur-Editor (über: **Transkription \&gt; Segmentierte Transkription exportieren...** ) aktualisieren. Sie können Fehler auch zuerst in Ihren .exb Dateien korrigieren und dann die folgenden Coma Funktionen verwenden. Hierfür wählen Sie **„Transkriptionen segmentieren&quot;** im Menüpunkt Wartung an und setzen Ihre Einstellungen (d.h. Segmentierungsalgorithmus, Zielverzeichnis, Suffix2 etc.).

![](RackMultipart20211216-4-q9ctu1_html_bed2891b13b65417.png)

Bestätigen Sie die Eingaben mit OK. Die .exs Dateien für alle Basistranskriptionen in ihrem Korpus werden automatisch generiert. Der folgende Dialog wird angezeigt.

![](RackMultipart20211216-4-q9ctu1_html_f66171e77246c30a.png)

Klicken sie zum Bestätigen **OK**.

### 7.1.2Auf Strukturfehler überprüfen

Diese Funktion überprüft alle verknüpften Transkriptionen des Korpus auf eventuelle Strukturfehler. Wird in einer oder mehreren Transkriptionen ein solcher Fehler gefunden, so erscheint eine Meldung, aus der heraus man eine Fehlerliste für das Korpus speichern kann:

![](RackMultipart20211216-4-q9ctu1_html_9967f77336c1e759.png)

### 7.1.3Fehlerliste

Bei dieser Fehlerliste handelt es sich um eine XML-Datei, die sich – nachdem man sie auf seinem Computer gespeichert hat – im Partitureditor öffnen lässt. Die entsprechende Option befindet sich im **Transcription** -Menü des Partitureditors:

![](RackMultipart20211216-4-q9ctu1_html_b5b8596069c26138.png)

Im sich öffnenden Fenster kann man durch Druck auf das **„Datei öffnen&quot;** -Symbol die eben gespeicherte Fehlerliste öffnen und bekommt dann eine Liste der gefundenen Fehler.

![](RackMultipart20211216-4-q9ctu1_html_7509597caa538f85.png)

Ein Doppelklick auf einen Fehler (hier eine verwaiste Transkriptionsspur) öffnet die entsprechende Transkription und springt an die Stelle mit dem Fehler.

### 7.1.4Auf Segmentierungsfehler überprüfen

Analog zur Suche nach Strukturfehlern lässt sich auch nach Segmentierungsfehlern suchen. Wird die Funktion aufgerufen, muss zunächst bestimmt werden, nach welchem Segmentierungsalgorithmus die Transkriptionen segmentiert wurden:

![](RackMultipart20211216-4-q9ctu1_html_6cdbcc01bcc489f7.png)

Das weitere Vorgehen entspricht dem bei der Suche nach Strukturfehlern.

### 7.1.5Sprecherzuordnung prüfen

Diese Option sucht nach „undefinierten Sprechern&quot; (d.h. Sprecher, denen keine Spur zugeordnet ist). Es öffnet sich ein neuer Dialog mit den Ergebnissen.

Die Fehlerliste kann genau wie bei den Strukturfehlern gespeichert werden.

![](RackMultipart20211216-4-q9ctu1_html_a91d5f9339a608a2.png)

### 7.1.6Suchen und Ersetzen im Korpus

Diese Funktion sucht und ersetzt reguläre Ausdrücke in den ins Korpus eingefügten Basistranskriptionen. Nach der Auswahl der Funktion erscheint eine Warnmeldung:

![](RackMultipart20211216-4-q9ctu1_html_faa280d04313cd15.png)

Klicken Sie zum Fortfahren **OK** , dadurch erscheint folgender Dialog:

![](RackMultipart20211216-4-q9ctu1_html_fe0f323387fc2587.png)

Jetzt können Sie Elemente in allen Basistranskriptionen des Korpus suchen und ersetzen. Beachten Sie, dass Sie das Feld Originaldateien sichern anwählen können, falls Sie die Ursprungsdatei speichern möchten. Bestätigen Sie mit **OK**. Am Ende erhalten Sie eine Zusammenfassung aller vorgenommenen Änderungen. Falls nötig, kopieren Sie die Ergebnisse und fügen Sie diese in einen Editor oder Word ein.

## 7.2Pflege der Metadaten

### 7.2.1Segmentzahlen aktualisieren

Extrahiert aus allen mit dem Korpus verknüpften (segmentierten) Transkriptionen die Segmentzahlen und schreibt sie als geschützte Metadaten in deren Description.

Beim Verknüpfen von Transkriptionen werden die Segmentzahlen ebenfalls in die Description geschrieben; die Funktion aus dem **Wartung** -Menü ist nützlich, wenn sich Transkriptionen (und Segmentzahlen) geändert haben.

### 7.2.2Aufnahmen aus Transkriptionen aktualisieren

Diese Funktion schaut in den Kopfdaten aller Transkriptionen im Korpus nach zugewiesenen Mediendateien und fügt diese als Recording in die Coma-Datei ein. In Coma bereits existierende Recordings werden nicht verändert oder gelöscht.

Diese Funktion ist insbesondere nützlich, wenn bereits verknüpften Transkriptionen nachträglich weitere Mediendateien (z.B. in anderen Audio- oder Videoformaten) zugewiesen werden.

### 7.2.3Description-Schlüssel angleichen

Häufig wird die Vergabe von Schlüsselnamen nicht einheitlich geregelt oder bei der Eingabe passieren Flüchtigkeitsfehler – dies führt dazu, dass die entsprechende Information später nicht aufgefunden werden kann. Die Funktion **„Description-Schlüssel angleichen&quot;** dient dazu, die Schlüsselnamen, die in den Descriptions in Coma verwendet werden, zu vereinheitlichen.

Wird die Funktion aufgerufen, erscheint eine Tabelle mit allen Schlüsselnamen, die in Descriptions des geöffneten Korpus verwendet wurden.

![](RackMultipart20211216-4-q9ctu1_html_42ab5022dc7242c5.png)

Schlüsselnamen, die sich ähneln (und damit einen Hinweis auf einen möglichen Fehler geben), werden mit gelber Farbe hervorgehoben.

In der rechten Spalte lassen sich die Schlüsselnamen editieren. Wird also im obigen Beispiel in der rechten Spalte **„Gesprähchstyp&quot;** durch **„Gesprächstyp&quot;** ersetzt, so wird (nach drücken der **OK** -Schaltfläche) der entsprechende Schüsselname in allen Descriptions des Korpus ersetzt.

# 8Einstellungen

Über das Menü **Bearbeiten\&gt;Einstellungen** können Sie die Voreinstellungen des Programms ändern. Die einstellbaren Optionen sind im Folgenden erläutert:

![](RackMultipart20211216-4-q9ctu1_html_feadc371776a066c.png)

- Sprachdatei: An dieser Stelle lässt sich die Sprache der Benutzeroberfläche von Coma einstellen.

**ACHTUNG** : Die Bezeichnungen der verschiedenen Oberflächenelemente werden in einer Ressourcendatei verwaltet - die Deutsche und Englische Version ist weitestgehend vollständig, für die anderen angebotenen Sprachen sind wir auf die Hilfe der Anwender angewiesen. Wenn sie also gerne bei der Lokalisierung von Coma helfen wollen, so melden Sie sich bei Kai Wörner [kai.woerner@uni-hamburg.de].

Wenn Sie die Sprache der Benutzeroberfläche geändert haben, müssen Sie das Programm neustarten, um die Änderungen zu sehen.

- Filter: An dieser Stelle lässt sich einstellen, wie _**[Filter](#_Filter)**_ für die Kommunikationen- und Sprechertabellen angelegt werden:

- „ **Filter standardmässig aktivieren&quot;** : Mit dieser Einstellung werden Filter sofort angewendet, wenn sie hinzugefügt werden.
- „**Neue Filterergebnisse standardmässig addieren (logisch ‚oder&#39; statt ‚und&#39;)&quot;**: bestimmt, ob beim Hinzufügen von weiteren Filtern die Ergebnisse logisch ‚oder&#39; bzw. ‚und&#39; verknüpft werden. Nähere Erläuterungen zu den Auswirkungen finden Sie im Kapitel _**[Filter](#_Filter)**_.

- Benutzerinterface

- „ **Löschen bestätigen&quot;** : Hier können Sie festlegen, ob eine Sicherheitsabfrage erfolgt, wenn Sie Elemente aus den Metadaten löschen wollen.

- Neue Transkriptionen erhalten den Namen der...: Wenn einer Kommunikation eine Transkription zugeordnet wird (siehe _ **Verwaltung von Metadaten** _), so erhält diese einen Namen; an dieser Stelle lässt sich auswählen, ob dieser Name dem Dateinamen oder dem Namen der Kommunikation entsprechen soll. Der Dateiname der Transkription wird davon nicht beeinflusst. Wird die Einstellung „Kommunikation&quot; gewählt und eine Kommunikation hat mehrere zugeordnete Transkriptionen, so werden die Namen aufsteigend durchnummeriert.
- Transkription Im EXMARaLDA-System lassen sich die meisten Operationen (Suchen, Visualisierungen etc.) nur mit segmentierten Transkriptionen durchführen. An dieser Stelle können Sie festlegen, ob Basistranskriptionen in Coma überhaupt berücksichtigt werden:

- „ **Nur segmentierte Transkriptionen in den Korb legen&quot;** : Wenn sie diese Option einschalten, so werden nur segmentierte Transkriptionen in den Korpus-Korb gelegt, unabhängig davon, ob Kommunikationen auch Basistranskriptionen zugeordnet sind.

- Vorlagenverwaltung Für bestimmte Datentypen in Coma lassen sich _**[Templates](#_Templates)**_ (Vorlagen) anlegen. An dieser Stelle in den Einstellungen können Sie bestimmen, ob eine Template-Datei beim Start von Coma automatisch geladen werden soll und beim Verlassen automatisch wieder gespeichert wird. Mit der Schaltfläche zwischen diesen Optionen können Sie die entsprechende Template-Datei auswählen. Die Option zum automatischen Laden einer Template-Datei findet sich übrigens auch im **Datei** -Menü des Programms.

# 9Anmerkungen und Haftung

## 9.1Haftungsbegrenzung

In keinem Fall, außer wenn durch geltendes Recht gefordert oder schriftlich zugesichert, ist irgendein Urheberrechtsinhaber oder irgendein Dritter, der das Programm wie oben erlaubt modifiziert oder übertragen hat, Ihnen gegenüber für irgendwelche Schäden haftbar, einschließlich jeglicher allgemeiner oder spezieller Schäden, Schäden durch Seiteneffekte (Nebenwirkungen) oder Folgeschäden, die aus der Benutzung des Programms oder der Unbenutzbarkeit des Programms folgen (einschließlich – aber nicht beschränkt auf – Datenverluste, fehlerhafte Verarbeitung von Daten, Verluste, die von Ihnen oder anderen getragen werden müssen, oder dem Unvermögen des Programms, mit irgendeinem anderen Programm zusammenzuarbeiten), selbst wenn ein Urheberrechtsinhaber oder Dritter über die Möglichkeit solcher Schäden unterrichtet worden war.

## 9.2Preview-Versionen

Von EXMARaLDA-Versionen werden in regelmäßigen Abständen Preview-Versionen veröffentlicht ([http://exmaralda.org/de/preview-version/](http://exmaralda.org/de/preview-version/)), die den neuesten Entwicklungsstand der Software repräsentieren. Obwohl wir auch für die regulär veröffentlichten Versionen der Software keine Funktionsgarantie und Gewährleistung geben (können) – siehe oben – möchten wir doch darauf hinweisen, dass regulär veröffentlichte Versionen immerhin den Anspruch erheben, vor der Veröffentlichung sorgfältig getestet worden zu sein. Fehlfunktionen und unerwartetes Verhalten der Software sind bei Preview-Versionen durchaus zu erwarten und sie sollten immer eine Sicherheitskopie ihrer Daten machen, bevor Sie sie mit Preview-Software bearbeiten.

## 9.3Dieses Dokument

Dieses Dokument wurde von Kai Wörner ([kai.woerner@uni-hamburg.de](mailto:kai.woerner@uni-hamburg.de)) erstellt und wird vom Hamburger Zentrum für Sprachkorpora (HZSK) gepflegt. Falls Ihnen Fehler auffallen oder falls Sie bestimmte Funktionen des Programms nicht erläutert sehen, wenden Sie sich bitte an [corpora@uni-hamburg.de](mailto:corpora@uni-hamburg.de).

[1](#sdfootnote1anc) See: [http://dublincore.org](http://dublincore.org/)/.

[2](#sdfootnote2anc) Siehe [http://www.ethnologue.com/codes/default.asp](http://www.ethnologue.com/codes/default.asp)

1