---
title: EHRI für bestandshaltende Institutionen: Integrieren Sie Ihre Daten in das EHRI-Portal 
---

Informationen über Quellen zum Holocaust sind eine wesentliche Voraussetzung für Forschung, Bildung und Gedenken. Bewahren Sie oder Ihre Institution Quellen zum Holocaust auf und möchten Sie diese sichtbar machen? Hier erfahren Sie, wie Sie Ihre Findmittel und Metadaten im EHRI-Portal verfügbar machen können. 

## Warum EHRI? 

Das [EHRI-Portal](https://portal.ehri-project.eu/) eröffnet Zugänge zu Informationen über Holocaust-bezogenes Archivgut, das in Einrichtungen in ganz Europa und darüber hinaus verwahrt wird und stellt Verbindungen zwischen diesen her. Wenn Sie Bestandsbeschreibungen Ihres Archivs in das EHRI-Portal integrieren, stärken Sie das internationale Profil Ihrer Institution, erhöhen die Sichtbarkeit Ihrer Daten und Ihrer Einrichtung und machen Ihre Daten auffindbar, zugänglich, interoperabel und wiederverwendbar [(FAIR)](https://www.nature.com/articles/sdata201618). Darüber hinaus schließen Sie sich einem Kreis weiterer Institutionen und Fachleute an, mit denen Sie Ihre Expertise teilen können. Wichtig ist dabei, dass Sie stets die Kontrolle über Ihre Daten behalten. 

Ein kurzes Einführungsvideo zum Portal auf Englisch finden Sie [hier](https://www.youtube.com/watch?v=IUFqR7l5qW8). 

Forschende müssen wissen, wo sich Archive befinden und ob Unterlagen eingesehen werden können. Prüfen Sie deshalb als ersten Schritt, ob Ihre Institution – oder Sie als Privatperson – bereits im EHRI-Portal verzeichnet sind. Ist das nicht der Fall, schreiben Sie uns bitte an archives@ehri-project.eu mit dem Betreff „new input for the EHRI Portal“ und teilen Sie uns mit, welche Institution aufgenommen werden soll. 

## Welche (Meta-)Daten unterstützt das Portal? 

Das EHRI-Portal bietet Zugänge zu Bestandsbeschreibungen (auch als Findmittel oder Repertorium bezeichnet) zu Holocaust-bezogenem Archivgut. Bestandsbeschreibungen informieren Forschende über die Struktur des Materials, sein Format, seinen Inhalt und darüber, wie sie selbst Zugang zur physischen Quelle erhalten können. 

Das Material selbst sowie etwaige digitale Reproduktionen, die davon angefertigt wurden und online verfügbar sind, verbleiben der bei der verwahrenden Einrichtung. Diese Unterscheidung wird gelegentlich als Unterschied zwischen „Daten“ (dem Archivgut selbst) und „Metadaten“ (der Beschreibung der Daten) bezeichnet. 

## Auswahl des relevanten Materials 

Zu klären ist zunächst, ob sich alle Ihre Bestandsbeschreibungen auf den Holocaust beziehen. Falls nicht: Kann Ihre Institution gezielt nur diejenigen auswählen, die einen Holocaust-Bezug herstellen? Wenden Sie sich bei Fragen dazu an EHRI. 

## Wie kann ich die Metadaten meiner Bestandsbeschreibungen an EHRI weitergeben? 

Es gibt mehrere Möglichkeiten, Ihre Bestandsmetadaten in das EHRI-Portal zu integrieren. Der technische Aufwand ist dabei jeweils unterschiedlich: 

![Schaubild](Schaubild_übersetzt.jpg)

*Manuelle Dateneingabe*: Bestandsbeschreibungen werden über ein Administratorenkonto direkt in das EHRI-Portal eingegeben.

*Sammelimport*: EHRI importiert Ihre Bestandsbeschreibungen aus XML (vorzugsweise im standardisierten Format Encoded Archival Description – EAD). 

*Wiederkehrende Sammelimporte*: EHRI lädt Ihre Bestandsmetadaten automatisch von einem über das Web zugänglichen Speicherort herunter und importiert sie. Der Vorgang wird in regelmäßigen Abständen wiederholt, damit Ihre Beschreibungen auf dem aktuellen Stand bleiben. 

## Nächste Schritte 

Wenn Sie sich bei diesem Prozess von EHRI unterstützen lassen möchten, richten Sie Ihre Fragen bitte an reichlmaier@ifz-muenchen.de

## FAQ 

### Welches Datenformat verwendet EHRI für den Sammelimport? 

EHRI nutzt für den Import von Bestandsbeschreibungen in das Portal das Format [EAD 2002](https://en.wikipedia.org/wiki/Encoded_Archival_Description). Die Daten müssen nicht nur gemäß dem EAD-Schema valide sein; wir setzen darüber hinaus voraus, dass jede Verzeichnungseinheit (in EAD eine Komponente, die durch einen <did>-Abschnitt gekennzeichnet ist) über einen <unitid>-Identifikator verfügt, der innerhalb der Einheiten derselben Ebene eindeutig ist. Das EAD-Schema selbst schreibt dies nicht vor – es lässt auch „anonyme“ Einheiten zu –, für die Nachvollziehbarkeit der Datenherkunft ist es jedoch notwendig. Idealerweise ist jede <unitid> innerhalb der gesamten Institution eindeutig; zwingend erforderlich ist das aber nicht. 

Vor dem Import normalisiert EHRI die Daten zudem, um bestimmte selten verwendete EAD-Elemente zu entfernen, die überwiegend der Textformatierung dienen und vom Portal derzeit noch nicht unterstützt werden. 

### Was ist, wenn ich keine EAD-Daten bereitstellen kann? 

Uns ist bewusst, dass nicht jede Archivsoftware EAD unterstützt. Aus diesem Grund verfügen wir über Werkzeuge, die beliebige XML-Formate vor dem Import in EAD konvertieren können, sofern bestimmte strukturelle Anforderungen erfüllt sind, etwa, dass eine Datei nicht mehr als einen Bestand enthält. EHRI-DE berät Sie gerne über die entsprechenden technischen Anforderungen.  

Für Daten, die nicht im XML-Format vorliegen, etwa CSV- oder Excel-Dateien, kann eine Konvertierung erforderlich sein. 

### Wie sieht es mit EAD-3 aus? 

Den Import der neuesten EAD-Variante EAD-3 unterstützen wir ebenfalls, auch wenn sie bislang weniger ausführlich getestet wurde als EAD 2002. 

### Werden mehrsprachige Findmittel unterstützt? 

Mehrsprachige Findmittel können wir über EAD importieren, sofern jede Sprache in einer eigenen XML-Datei vorliegt. Die mehrsprachigen Funktionen von EAD-3 unterstützen wir noch nicht. 
