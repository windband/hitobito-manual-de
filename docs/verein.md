# Verein administrieren ![iconSchloss](media/image2.png)

In diesem Kapitel werden Spezialfunktionen erläutert, um Vereine zu
verwalten. Diese sind nur für Personen sichtbar oder zugänglich, welche
die entsprechenden Gruppenzugehörigkeit und Rollen besitzen.

```{tip}
Der **Kurzname** soll zum Beispiel für "Musikgesellschaft Eintracht
Windisch" nicht "MGE" sein, weil der Verein so nicht mehr
identifizierbar ist. Besser wäre "MG Eintracht Windisch". Generell: Im
Kurznamen wird nur die Bezeichnung "Musikgesellschaft" o.ä. gekürzt.
```

## Modul Gruppen

### Menü Personen

#### Neues Mitglied erfassen

![image](media/image19.png)

Im Menü Personen über den Button **Person hinzufügen** können
Mitglieder, Ehemalige oder auch neue Personen, die zuerst erfasst werden
müssen, der gewünschten Gruppe (mit entsprechender Rollenzuteilung)
zugewiesen werden.

![image](media/image20.png)

Zuerst soll die Person über das Suchfeld mit Namen gesucht werden.

Anhand des Namens wird eine treffende Auswahl der bereits vorhandenen
Mitgliedern mit Wohnort und Jahrgang angezeigt. Falls die gesuchte
Person existiert, ist sie

  - der gewünschten Gruppe,
  - mit entsprechender Rolle,
  - allenfalls einer weiteren Bezeichnung
  - und dem Eintrittsdatum zuzuweisen.

Anschliessend empfiehlt es sich, die Angaben der Person zu prüfen und
gegebenenfalls anzupassen. Hat das Mitglied noch keine
Haupt-E-Mailadresse ist diese für den Login auf die Datenbank
einzusetzen.

![image](media/image21.png)

Wenn bei der Eingabe des Namens keine Auswahl angezeigt wird, kann
direkt über die Tastatur **Enter** gedrückt werden und man gelangt in
die Maske für **Neue Person erfassen**.

Hier müssen mindestens die mit einem Stern markierten Felder (Vorname,
Nachname und Geburtstag) ausgefüllt werden.

Allenfalls muss die Gruppenzugehörigkeit und Rolle angepasst werden.

Um weitere wichtige Schritte gleich zu erledigen, empfiehlt es sich auch
gleich die Felder **Haupt-E-Mail** und das Datum des **Eintritts**
auszufüllen.

#### Liste importieren

```{tip}
Damit der Import klappt, muss zwingend die Korrespondenzsprache jedes Benutzers
definiert werden. Diese ist entweder `de`, `fr` oder `it` (Gross-/Kleinschreibung beachten).
```

#### Mitglieder bearbeiten

Personen mit den Rollen Adressverwaltung, Präsident oder Administrator
kann die Daten sämtlicher Personen im Verein bzw. der ihm zugeteilten
Gruppe bearbeiten. Dazu ist die zu bearbeitende Person aufzurufen. In
der Ansicht "Info" findet sich der Button "Bearbeiten":

![image](media/Uebersicht_Person.png)

#### Rollen bearbeiten

Um einem Mitglied eine neue **aktive** Rolle in einem Verein/Verband
hinzuzufügen, in welchem das Mitglied bereits eine Rolle besitzt, wählen
Sie im Abschnitt "Aktive Rollen" **+Rolle hinzufügen** bei derjenigen
Gruppe, bei welcher Sie eine neue Rolle hinzufügen möchten. Sie können
dann innerhalb der gewählten Gruppe dem Mitglied eine zusätzliche Rolle
hinzufügen und angeben, seit wann die Rolle gültig ist.

Wie Sie einem Mitglied eine neue **nicht mehr aktive** Rolle in einem
Verein/Verband hinzuzufügen siehe unter [Veteranen verwalten](Veteranen_verwalten)

Um aktive Rollen zu entfernen, wählen Sie auf der Ansicht "Info" im
Abschnitt "Aktive Rollen" das Symbol 'Abfalleimer'. Sie beenden damit
die entsprechende Rolle per sofort.

#### Tags

Um Mitgliedern eine bestimmte Kennzeichnung zu geben, können sog. Tags
verwendet werden, wobei dies strukturiert (z.B. "Mailing: Newsletter",
"Mailing: Print" etc.) oder unstrukturiert (z.B. "Helferpool",
"Webmaster" etc.) erfolgen kann.

Tags von Personen in einer Gruppe können nur von Personen mit der Rolle
Adressverwaltung oder von Personen mit weitergehenden Berechtigungen
gelesen und geschrieben werden[^1] . Personen mit der Rolle Mitglied
können weder ihre eigenen noch diejenigen Tags der anderen
Gruppenmitglieder sehen.

Damit sind Tags eine Alternative dazu, thematisch zusammengehörende
Personen in einer eigenen (Unter-)Gruppe zusammenzufassen. Mitglieder
einer Gruppe sehen sich gegenseitig. Tags sind für Mitglieder nicht
ersichtlich.

Neue Tags können in der Ansicht "Info" einer Person über den Button "Tag
hinzufügen" generiert werden. Das Übernehmen der bereits erstellten Tags
kann für das Filtern massgeblich sein.

![image](media/image23.jpg)

Hinzufügen neuer unstrukturierter Tags (rechtes: Auswählen eines früher
erstellten Tags)

![image](media/image24.jpg)

Hinzufügen neuer strukturierter Tags (Trennung der beiden Begriffe durch
einen Doppelpunkt)

#### Funktionäre (Präsident, Dirigent etc.) erfassen

Es ist wichtig, dass die Vereinsfunktionäre als solche im System erfasst
bzw. gekennzeichnet sind. So stellen Sie sicher, dass Ihre Funktionäre
die entsprechenden Nachrichten Ihres Kantonalverbandes und des Schweizer
Blasmusikverbandes auch erhalten. Um unnötige E-Mail und Briefe zu
vermeiden, versuchen der SBV und seine Kantonalverbände ihre
Informationen zielgerichtet zu verschicken: Einladungen für
Dirigentenkonferenzen gehen nur an die Dirigenten; Informationen im
Zusammenhang z.B. mit COVID-19 wie Hinweise zu
Kurzarbeitsentschädigungen betreffend die PräsidenInnen der Verein etc.

(Dirigent_erfassen)=
##### Dirigent erfassen

Bei der Erfassung der Dirigent:innen ist zu unterscheiden, ob
diese selber auch Mitglied des entsprechenden Vereins sind oder nicht.

```{important}
Für Mitglieder sind die entsprechenden Jahresbeiträge (SBV, SUISA und
kantonale Musikverbände) zu entrichten und zählen die Aktivjahre der
Mitglieder für die Berechnung der Veteranenehrungen. Bei
Nicht-Mitgliedern entfallen die Jahresbeiträge und entsprechend auch die
Aktivjahre.
```

Dirigent:innen ist **in jedem Fall** die Rolle `[Musikgesellschaft XY] →
DirigentIn` zuzuordnen:

![image](media/image25.png)

Ist ein(e) Dirigent:in auch Mitglied im entsprechenden Verein, ist
ihm/ihr **zusätzlich** die Rolle `Mitglieder → Mitglied` zuzuweisen:

![image](media/image26.png)

##### Präsident erfassen

Neben der Rolle `Mitglieder → Mitglied` (falls der Präsident auch selber
Aktivmitglied ist), ist ihm ihm auch die Rolle `Vorstand → Präsident`
zuzuordnen.

```{tip}
Das Vorgehen ist für das Erfassen von Vizepräsident, Kassier,
Veteranenchef, Präsident der Musikkommission etc. ist analog zum
Vereinspräsidenten.
```

(Veteranen_verwalten)=
#### Veteranen verwalten

##### Überprüfen der Einträge gemäss Musikerpass

Damit die Berechnung der
Aktivjahre eines Musikanten korrekt erfolgen kann, müssen dessen
aktuellen und bisherigen Mitgliedschaften in den Verbandsvereinen in
hitobito erfasst sein. Um dies zu überprüfen, rufen Sie das
entsprechende Mitglied auf, indem Sie dessen Namen im grossen Suchfeld
zuoberst auf der Seite eingeben. Nach der Eingabe von drei Zeichen
erfolgt bereits eine Suche, so dass nicht der ganze Name eingegeben
werden muss.

Auf der Personen-Übersicht sehen Sie alle zur Person gehörenden Daten,
unter anderem im Abschnitt «Weitere Angaben» auch die Anzahl «Aktivjahre
aktuell» (im nachfolgenden Beispiel: 21 Jahre):

![image](media/image27.png)

Die aktuellen und bisherigen Mitgliedschaften in den Verbandsvereinen
können unter der Ansicht «Verlauf» angezeigt werden. Dort interessieren
uns die Einträge mit der Rolle «Mitglied» in einer Gruppe «\[Musikverein
XY\] / Mitglieder».

Sind noch nicht alle Mitgliedschaften der Person erfasst, können
fehlende Mitgliedschaften über den Befehl «Neue Rolle» (nach-)erfasst
werden. Dazu ist die Rolle `[Musikgesellschaft XY] → Administrator` oder
`Mitglieder → Adressverwaltung` notwendig:

![image](media/image28.png)

Es können auch (heute) nicht mehr existierende, d.h. inzwischen aufgelöste, Vereine erfasst werden.

```{tip}
Soll eine Rolle eines fremden Vereins erfasst werden, muss der Eintrag zwingend in der Ansicht «Verlauf» gemacht werden. Der Button `Rolle hinzufügen` in der Ansicht «Info» kann dazu nicht verwendet werden, da dort kein fremder Verein ausgewählt werden kann.
```

```{tip}
Für die Berechnung der **Aktivjahre** zählt nur die Rolle `Mitglieder →
Mitglied`. Die Rollen `Mitglieder → Ehrenmitglied`, `Mitglieder →
Adressverwaltung` und `Mitglieder → Passivmitglied` generieren keine
Aktivjahre und sind entsprechend auch nicht finanzrelevant, d.h. für
Personen mit (nur) diesen Rollen, müssen keine Mitgliederbeiträge
entrichtet werden. Wird ein aktives Mitglied zum (aktiven) Ehrenmitglied ernannt,
ist diese Rolle deshalb **zusätzlich** zu vergeben (und nicht die Rolle
`Mitglieder → Mitglied` durch die Rolle `Mitglieder → Ehrenmitglied`
abzulösen), damit das Mitglied weiterhin Akivjahre sammelt und für
dieses die Mitgliederbeiträge in Rechnung gestellt werden.
```

Sind nun alle Engagements des Mitglieds vollständig erfasst, können
dessen Aktivjahre, welche für die Berechnung der kantonalen und
eidgenössischen Ehrungen massgebend sind, auf der Personen-Übersicht
abgelesen werden. Diese Angabe erscheint übrigens auch auf den
Mitgliederlisten des Vereins (online sowie in den exportierten Listen).

##### Veteranenliste erstellen

Will ein Verein wissen, welche seiner Mitglieder im aktuellen Jahr zum kantonalen Veteranen
ernannt werden können (25 Aktivjahre), kann seine Mitgliederliste
entsprechend gefiltert werden. Dazu muss der Verein aufgerufen und das
Menü «Personen» geöffnet werden. Unter «Weitere Ansichten» kann ein
neuer Filter erstellt werden: Aktivjahre aktuell ist genau 25


![image](media/image29.png)

![image](media/image30.png)

Die mittels eines solchen Filters erstellte Liste kann nun entweder
ausgedruckt (PDF) oder heruntergeladen und elektronisch
weiterverarbeitet werden (CSV, Excel, vCard, Etiketten,...).

### Menü Anlässe

#### Anlass erstellen

![image](media/image31.jpg)

Ein Administrator und der Präsident können Anlässe für den Verein
erstellen. Ein Adressverwalter darf dies für "seine" Gruppe.

```{tip}
**Hinweis für das Erstellen von Anlässen**

Vorggegebene Antworten mit Kommas trennen, damit der Benutzer eine Auswahl treffen kann (z.B. "T-Shirtgrösse: s,m,l,xl")
```

![image](media/image32.jpg)

Im Register **Allgemein** muss mindestens der Name des Anlasses stehen.

![image](media/image33.jpg)

Im Register **Anmeldung** wird eingerichtet, wer sich wie für den Anlass
anmelden kann. Soll keine Anmeldung möglich sein, wird als
Anmeldeschluss ein Datum in der Vergangenheit eingesetzt.

![image](media/image34.jpg)

Im Register **Anmeldeangaben** können Fragen definiert werden, die bei
der Anmeldung beantwortet werden müssen. Werden mögliche Antworten
vorgegeben, sind die durch ein Komma zu trennen.

Unter **Administratorenangaben** können Fragen definiert werden, die bei
der Anmeldung beantwortet werden müssen und deren Antworten nur durch
die Kursadministration eingesehen werden können.

![image](media/image35.jpg)

Im Register **Kontaktangaben** wird bestimmt, welche Mitgliederdaten für
die Anmeldung mitgesendet bzw. benötigt werden. Sind bestimmte, für die
Anmeldung zwingend benötigte Angeaben beim Benutzer nicht ausgefüllt,
ist eine Anmeldung nicht möglich und muss der Benutzer diese Angaben
zuerst in seinem Profil ausfüllen.

![image](media/image36.jpg)

Nach dem Speichern wird der erstellte Anlass angezeigt. Hier kann über
**Anhänge +hinzufügen** z.B. ein Konzertprogramm oder andere Dokumente
zum Download angeboten werden. Fehler können über den Button Bearbeiten
korrigiert werden. Der erstellte Anlass kann natürlich auch wieder
gelöscht, für einen weiteren Anlass dupliziert oder als Kalendereintrag
exportiert werden.

![image](media/image37.jpg)

Darstellung der Anlässe mit und ohne Anmeldemöglichkeit

### Menü SUISA

#### SUISA-Meldung

Jeweils per 31. Dezember jeden Jahres müssen die Vereine der SUISA
melden, welche Werke im vergangenen Jahr aufgeführt wurden. Damit wird
der SUISA ermöglicht, den jeweiligen Künstlerinnen und Künstlern einen
Betrag entsprechend der Häufigkeit der Aufführung ihrer Werke
auszubezahlen.

##### Gespeicherte Aufführungen anschauen

Personen mit der Rolle «Verantwortlicher SUISA» können im Modul Gruppen
unter dem Menüpunkt «SUISA» die bisher für ihren Verein gespeicherten
Aufführungen anzeigen und bei Bedarf exportieren (CSV, Excel). Die
Einträge sind nach dem Aufführungsjahr getrennt (im Beispiel «2019»)
und nach Aufführung geordnet:

![image](media/image38.png)

```{tip}
Die Rolle Administrator wird in hitobito nicht gleichgesetzt mit dem
Zugriff auf alle Funktionen. Auch Administratoren sehen gewissen
Funktionen in hitobito nicht, wie zum Beispiel den Menüpunkt «SUISA» oder «Rechnungen».
Administratoren, welche z.B. ihre SUISA-Verantwortliche unterstützen möchten,
müssen sich deshalb auch selber die Rolle «Verantwortlicher SUISA»
erteilen.
```

##### Status Meldeliste

Auf dieser Seite ist auch ersichtlich, ob die SUISA-Liste bereits eingereicht wurde oder noch
eingereicht werden muss. Der Button kann folgende Zustände haben:

![image](media/image39.png)

Die Meldeliste wurde bereits eingereicht und kann nicht erneut
eingereicht werden.

![image](media/image40.png)

Die Meldeliste ist ausgefüllt, wurde aber noch nicht eingereicht.

![image](media/image41.png)

Die Meldeliste ist leer und kann nicht eingereicht werden. Bitte
erfassen Sie zuerste Ihre Werke.

##### Neue Aufführung erfassen

Um eine neue Aufführung zu erfassen, klicken Sie auf den Button «Aufführung hinzufügen». Im im
Dialog «SUISA Erfassung» erscheinen die von Ihnen aufgeführten Werke des
letzten Jahres in einer Liste sowie ein Suchfeld «Werk suchen...».

Bei bereits aufgeführten Werken kann die Anzahl Aufführungen direkt
eingetragen oder mittels der Pfeiltasten eingestellt werden:

![image](media/image42.png)

Die Felder «Aufführung» und «Datum» am Ende der Liste bezeichnen den
Anlass näher und sind beide optional.

Nicht aufgeführte Werke können über das Suchfeld gesucht werden:

![image](media/image43.png)

Solange die Meldeliste noch nicht eingereicht ist (vgl. [Meldeliste
einreichen](Meldeliste_einreichen)) können Sie beliebig oft neue
Aufführungen erfassen und bearbeiten.

##### Neues Werk erstellen

Ist ein Werk noch gar nicht in der Datenbank von SUISA erfasst, findet
sich kein Suchergebnis. Es erscheint stattdessen der Befehl «Werk
erstellen»:

![image](media/image44.png)

Um ein Werk zu erstellen, müssen mindestens Titel und Komponist
eingetragen werden. Die Angabe von Arrangeur und Verlag sind optional:

![image](media/image45.png)

(Meldeliste_einreichen)=
##### Meldeliste einreichen

Sind alle Werke erfasst, muss die Meldeliste eingereicht werden. Dazu
klicken Sie auf den Button «Meldeliste einreichen». Als Bestätigung
erhalten sie die Meldung «Meldeliste eingereicht» und der Button ist
deaktiviert und umbenannt in «Meldeliste eingereicht»:

![image](media/image46.png)

##### Meldeliste einreichen ohne Werk erfassen

Vereine können Ihre Meldeliste auch einreichen, ohne ein Werk zu
erfassen. Dazu stehen folgende alternative Optionen zur Verfügung:

  - Spielgemeinschaft  
    Vereine, welche sich zu einer Spielgemeinschaft zusammengeschlossen
    haben, melden ihre Werke nur einmal, d.h. ein Verein der
    Spielgemeinschaft reicht die Meldeliste wie gewohnt ein und die
    weiteren an der Spielgemeinschaft beteiligten Vereine wählen die
    Option Spielgemeinschaft.

  - nicht spielfähig in diesem Jahr  
    Vereine, welche aufgrund von zu wenigen Mitgliedern oder aufgrund
    äusserer Umstände (z.B. einer Pandemie) in einem Jahr keine
    Auftritte hatten, wählen diese Option.

  - SUISA über Dritte abgerechnet  
    Einige Mitgliedsvereine (z.B. Musikschulen) haben mit der SUISA
    bereits Verträge. Diese müssen ihre Auftritte über hitobito nicht
    melden.

![image](media/suisa_alternative_erledigung.png)

### Menü Listen

Hier werden alle Listen angezeigt, welche die zur Zeit gewählte Gruppe
erstellt hat. Listen sind gefilterte Personenlisten mit besonderen
Funktionalitäten:

  - Einer Liste kann eine E-Mailadresse zugeordnet werden. Ein auf diese
    Adresse verschicktes E-Mail wird von hitobito an alle Abonenten
    verteilt.
  - Abonnenten können aufgrund von Filtern (gemäss ihrer Rolle, Tag
    etc.) oder spefizisch aufgrund des Namens eines Person einer Liste
    zugeordnet werden.
  - Listen können "offen" sein, d.h. interessierte Personen können sich
    selber an-/abmelden, oder "geschlossen", d.h. der Listenersteller
    bestimmt verbindlich, wer Abonnent ist.

```{tip}
Mit Listen lassen sich einfach **Mailinglisten** erstellen. Die
Abonnenten verwalten ihre E-Mailadressen selber, womit Nachrichten an die
Liste jederzeit zugestellt werden können – Sie müssen keine
E-Mailadressen mehr nachführen. Wurde die Liste aufgrund eines Filters
(z.B. alle Vereinspräsidenten) erstellt, werden Nachrichten an die Liste
immer die im Zeitpunkt der Nachricht aktuellen Vereinspräsidenten
erreichen – ein Nachführen von manuellen Listen entfällt.
```

#### Liste erstellen

![image](media/Liste_erstellen_1.png)

Neben einem Listennamen (Pflichtfeld) können zudem eine Beschreibung,
der Herausgeber, eine Mailinglistenadresse (E-Mailadresse, an welche
Nachrichten für das Verteilen an die Abononenten geschickt werden
können) und zusätzliche Absender definiert werden. Werden keine
zusätzlichen Absender angegeben (und ist die Option "Beliebige
Absender/-innen dürfen auf die Mailingliste schreiben" nicht aktiviert),
können nur Administratoren Nachrichten an die Liste schicken. Sollen
weitere Personen Nachrichten an die Liste schicken dürfen, können diese
im Feld "zusätzliche Absender" definiet werden. Neben expliziten
E-Mailadressen (z.B. <info@windband.ch>) können auch ganze Domains (z.B.
\*@windband.ch) angegeben werden.

![image](media/Liste_erstellen_2.png)

Optional kann definiert werden, dass die Nachrichten nur an
E-Mailadressen mit bestimmten Labels oder an Haupt-E-Mail-Adressen
verschickt werden.

Weiter können die Abonenten mit einer MailChimp Audience synchronisiert
werden. Diese Aktion überschreibt die MailChimp-Liste und bestehende
Kontakte werden gelöscht. Personen, die sich bei MailChimp von dieser
Liste abgemeldet haben, bleiben abgemeldet.

Schliesslich stehen folgende Optionen zur Verfügung:

  - Abonnenten dürfen sich selbst an-/abmelden
  - Abonnenten dürfen auf die Mailingliste schreiben
  - Beliebige Absender/-innen dürfen auf die Mailingliste schreiben
  - E-Mail mit Bestätigung an Absender schicken

Ist die Option "Abonnenten dürfen sich selbst an-/abmelden" aktiviert,
erscheint die Liste bei den Personen in der Ansicht "Abos" unter
"Verfügbare Abos".

## Modul Rechnungen

![image](media/image47.png)

Im Modul Rechnungen sind die Einstellungen für die Rechnungen, die
einzelnen Rechnungsartikel sowie die erstellten Rechnungen zu finden.

#### Rechnungen

Hier finden Sie die Übersicht über alle erstellten Rechnungen und hier
können sie diese bearbeiten, löschen oder drucken. Auch Zahlungen
können hier mittels camt.054 XML-Datei[^2] eingelesen werden.

An dieser Stelle können auch **externe** Rechnungen erstellt werden,
d.h. Rechnungen, welche an externe Empfänger geschickt werden, welche
nicht in hitobito erfasst sind.

```{tip}
Rechnungen an Empfänger innerhalb von hitobito werden von
Personenlisten, von einer Teilnehmerliste (Kurse oder Anlässe) oder von
einer Einzelperson aus erstellt und können nicht im Modul Rechnungen
erstellt werden (vgl. [Rechnung erstellen](Rechnung_erstellen)).
```

#### Rechnungsartikel

Häufig verwendete Rechnungspositionen (z.B. Mitgliederbeitrag) können
hier vordefiniert werden. Diese Artikel können beim Erstellen von
Rechnungen ausgewählt und individuell angepasst werden.

![image](media/image48.png)

Modul Rechnungen → Rechnungsartikel

#### Einstellungen

In den Rechnungseinstellungen können allgemeine Angaben gemacht werden,
wie die Absenderadresse, Absender-E-Mail, Tage bis Fälligkeit,
MwSt.-Nummer etc. Hier können auch die Texte für die erste, zweite und
dritte Mahnung definiert werden.

Diese Einstellungen sind Verbands- bzw. Vereinsspezifisch und können für
jede Gruppe individuell vorgenommen werden.

Für die direkte Einbindung und Kontrolle der Zahlungen in hitobito
stehen Stand Januar 2022 Schnittstellen zu folgenden Finanzinstituten
zur Verfügung:

  - Postfinance
  - Credit Suisse
  - Raiffeisen Schweiz
  - UBS
  - Luzerner Kantonalbank
  - St. Galler Kantonalbank
  - Thurgauer Kantonalbank
  - Zürcher Kantonalbank
  - Valiant
  - BancoStato
  - BEKB | BCBE
  - Zuger Kantonalbank

![image](media/image49.png)

(Rechnung_erstellen)=
#### Rechnung erstellen

![image](media/image50.jpg)

Die eigentliche Rechnung wird über die Auswahl der Gruppe erstellt. Mit
dem Haken im Auswahlfeld können auch Rechnungen für einzelne Mitglieder
angefertigt werden.

![image](media/image51.jpg)

Die Rechnung mit einem eindeutigen Titel hilft bei der Kontrolle.

![image](media/image52.jpg)

Die erstellte Rechnung kann nun als Entwurf im Menü Rechnungen
eingesehen, bearbeitet, mit Fristen versehen, gedruckt oder über den
Button Rechnung stellen / mahnen direkt als E-Mail verschickt werden.

![image](media/image53.jpg)

Die erhaltene E-Mail:

![image](media/image54.jpg)

... und die Rechnung als PDF:

![image](media/image55.jpg)

#### Rechnungen prüfen und verwalten

Im Menü Rechnungen können die Debitoren verwaltet werden.

![image](media/image56.jpg)

Über den Button Zahlung erfassen kann eine camt.054 XML Datei
hochgeladen und automatisiert den Rechnungen zugeordnet werden kann.

Um eine einzelne Rechnung manuell als bezahlt zu markieren, öffnet man
die Rechnung und erfasst mit dem Befehl "+ Zahlung erstellen" die
eingeganene Zahlung (Betrag und Eingangsdatum):

![image](media/rechnung_zahlung_erstellen.png)

## Modul Anlässe

##### Übersicht

Im Modul Anlässe finden Sie eine Übersicht über Anlässe von Gruppen, bei
denen Sie Mitglied sind, sowie deren Übergruppen. Andere Anlässe finden
Sie bei der organisierenden Gruppe:

![image](media/Modul_Anlaesse.png)

Hier können Sie sich direkt für diese Anlässe anmelden, sofern die
Anmeldung bereits freigegeben bzw. der Anmeldeschluss noch nicht
eingetretten ist.

##### Neuen Anlass erstellen

![image](media/anlass_erstellen.png)

![image](media/anlass_erstellen_dialog.png)

Fussnoten:

[^1]: Technisch: Es dürfen die Personen Tags erfassen und anschauen, welche Schreibrechte auf der Person haben. Die Rollen gemäss <https://github.com/hitobito/hitobito_sbv/> mit \*\_full
[^2]: Eine camt.054 XML-Datei ist die Sammelbuchungs-auflösung und Belastungs- und Gutschriftsanzeige. Diese enthält eine Reihe verschiedene Buchungspositionen welche automatisiert auf Basis der ESR-Nummer bestehenden Rechnungen zugeordnet werden.
