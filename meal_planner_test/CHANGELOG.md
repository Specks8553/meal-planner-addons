# Changelog

## 0.2.26

- Plan: Unter dem neuesten Plan steht nicht mehr gleich der neue Plan, sondern „Ende des Plans“
  und ab wann nichts geplant ist. Weiterziehen oder Antippen öffnet „Neuer Plan“.
- Plan: Ein Tipp auf das Datum oben öffnet die Planauswahl.
- Plan: Wer ein Essen verschiebt, kann jetzt auch nach oben scrollen – knapp unter der großen Karte
  halten.
- Einkaufsliste: In „Nach Rezept“ steht „Manuell hinzugefügt“ jetzt oben.
- Einkaufsliste: Ist nichts ungesendet, kommt bei Verbindungsproblemen kein roter Hinweis mehr,
  sondern die ruhige Zeile „Keine Verbindung zum Server“.
- Rezepte: Neuer Filter „Eigene“ für die Rezepte, die nicht von Cookidoo kommen.
- Update: Die App übernimmt bei einem Update nur Dateien der neuen Version – nach 0.2.25 fehlte
  auf einem Handy die Gestaltung der Ersetzungen.
- Einkaufsliste: Wo sich der Agent beim Zusammenfassen nicht sicher war, steht in den Hinweisen
  „N Zuordnungen unsicher · Prüfen“. Eine Karte nach der anderen: in welche Abteilung, meist im
  Haus oder nicht, eine Zeile oder zwei. Eine Antwort ändert die Liste sofort und wird gemerkt;
  was offen bleibt, bleibt, wie der Agent es gelegt hat.
- Einkaufsliste: Wer eine Zeile in eine andere Abteilung zieht, gibt dem Agenten damit ein
  Beispiel für diese Abteilung.
- Einstellungen › Supermärkte: Jede Abteilung hat eine eigene Seite mit Name, Beispielen (was
  dorthin gehört – der Agent liest sie beim Sortieren) und „Abteilung entfernen“. Die Beispiele
  der Standard-Abteilungen sind schon eingetragen.
- Einstellungen › Supermärkte: Fehlt einem Supermarkt eine Standard-Abteilung, steht sie unter
  „Vorschläge“; beim Verlassen fragt die App einmal („So lassen“ oder „Hinzufügen“). Neue
  Supermärkte starten mit 14 Abteilungen, neu ist „Backzutaten“.
- Im Hintergrund: Die App zählt Zutaten ohne eigenes Icon; die Ansicht dafür kommt später.

## 0.2.25

- Rezepte: Zutaten lassen sich pro Rezept ersetzen oder weglassen – eine Zutat antippen, „Zutat
  ersetzen“: z. B. Veggie-Hack statt Rinderhackfleisch, die Menge wie im Rezept oder eigene.
  Cookidoos Alternative ist ein Vorschlag im selben Fenster (die Box „Alternativen“ ist weg).
  Die Einkaufsliste und der Agent nehmen ab dann den Ersatz; eine weggelassene Zutat kommt nicht
  auf die Liste. Cookidoo selbst bleibt unverändert.

## 0.2.24

- Rezepte: Eigene Rezepte bekommen ein Foto direkt vom Handy – „Foto hinzufügen“ öffnet Kamera
  oder Galerie. Das Foto landet neben der Rezeptdatei im Rezeptordner. Im ⋮-Menü: „Foto ändern“
  und „Foto entfernen“ (kommt in den Ordner „.entfernt“, „Rückgängig“ holt es zurück).
- Plan: Im aufgeklappten Rezept lässt sich die Bewertung direkt antippen. Die Zurück-Geste klappt
  ein aufgeklapptes Rezept wieder zu.
- Bewertung: Die Sterne flackern nach dem Antippen nicht mehr.
- Einkaufsliste: Mengen in verschiedenen Einheiten werden zusammengerechnet – TL und EL in eine
  Menge, mit bekanntem Gewicht in Gramm („1 EL ≈ 14 g“), eine Prise geht in der Menge auf.
  Stück, Dose, Glas und Bund bleiben, wie sie sind. Eine neu berechnete Zeile erscheint sofort.
- Einkaufsliste: Eine Änderung, die der Server nicht annehmen kann, hält die anderen nicht mehr
  auf – die App sagt, welche es war, alles andere wird gesendet. „steht schon auf der Liste“
  verdeckt die Zeile nicht mehr.
- Test-Add-on: „Auf Werkszustand zurücksetzen“ legt neben Standard auch Rewe mit 30 Abteilungen an.

## 0.2.23

- Einkaufsliste: Gemini Decision 1 macht die Liste – in ein paar Sekunden statt ein bis zwei
  Minuten. Verschiedene Einheiten stehen nebeneinander (½ TL + 2 Prisen), ohne Umrechnung und ohne
  Kommentar. Klappt es nicht, macht Gemini 3.8 Flash die Liste wie bisher.
- Einstellungen › Agent › Einkaufsliste: Admins wählen, welches Modell die Liste macht.
- Eine Zeile mit Mengen in verschiedenen Einheiten wird sofort neu berechnet, ohne Warten.

## 0.2.22

- Einkaufsliste: Der Name einer Zutat hat Vorrang. Eine lange Menge (z. B. "2 ½ TL + 3 Prisen +
  0,5–0,75 TL") bricht rechts nach einem "+" um oder rückt in die zweite Zeile, statt den Namen
  zu verdecken.
- Vorräte: Ein Tipp auf einen Artikel zeigt, welche Rezepte ihn brauchen; lange drücken holt ihn
  wie bisher zurück.

## 0.2.21

- Einkaufsliste: Nur Zutaten, die mehrere Rezepte brauchen, lassen sich aufklappen. Beim
  Aufklappen bleiben Bild und Name einer Zutat, wo sie sind.
- Rezept: Ein Tipp auf Zutaten, Zubereitung oder Notizen schiebt das Rezept sanft nach oben, bis
  der Titel oben steht.
- Notizfeld: wächst mit dem Text und bricht um; Enter macht eine neue Zeile, + speichert. Beim
  Antippen steht das ganze Feld über der Tastatur.
- Die App meldet einmal, was die Tastatur auf dem Gerät tut (für den hellen Streifen in Chrome).

## 0.2.20

- Die Tastatur legt sich über die App, statt sie zu verkleinern – der helle Streifen über der
  Tastatur beim Öffnen ist weg. Eingabeleiste, Mengenfeld und Notizfeld bleiben über der Tastatur.
- Zurück-Geste bei offener Tastatur schließt nur die Tastatur; man bleibt, wo man ist.
- Einkaufsliste: Eine Zeile gleitet beim Schließen zu, ohne dass ihr Inhalt erst nach unten rutscht.
- Rezept: drei Reiter – Zutaten, Zubereitung, Notizen. Unter den Notizen und ihrem Eingabefeld
  steht jetzt der Verlauf.

## 0.2.19

- Die Leiste unten (HA, Plan, Einkauf, Rezepte) kommt zurück, sobald die Tastatur zu ist – auch
  wenn man sie mit der Zurück-Geste schließt und das Feld noch ausgewählt bleibt.
- Einkaufsliste: Schließt man eine aufgeklappte Zeile, bleibt ihr Inhalt oben stehen, statt erst
  nach unten zu springen und dann hochzurutschen.

## 0.2.18

- Plan: Zieht man zum früheren Plan hinauf, liegt dessen Bild nicht mehr über der Kopfzeile des
  nächsten Plans.
- Einkaufsliste: Eine aufgeklappte Zeile gleitet auf ihre Höhe, ohne zu weit zu gehen und
  zurückzuspringen; kommt etwas aus den Vorräten zurück, macht die Liste ihm ruhig Platz.
- Einkaufsliste: „Zeigen“ heißt jetzt „Ansehen“; unter den Vorräten bleibt nur so viel Platz wie
  nötig. Die Vorräte heißen schlicht „Vorräte“, eine Zeile von dort „meist im Haus“.
- Einkaufsliste: Lange Rezeptnamen in einer aufgeklappten Zeile enden mit „…“, die Menge bleibt
  sichtbar. Beim Ändern einer Menge bleibt die Zeile über dem Eingabefeld.
- Das Eingabefeld der Einkaufsliste und die Felder unter Supermärkte und Vorräte zeigen Chromes
  Leiste für Passwörter, Karten und Adressen nicht mehr.
- Das Zusammenfassen verwirft keine Antwort mehr, weil eine Menge 0 ist – das sparte bisher einen
  zweiten Durchgang.
- Rezeptordner: Ein gleichnamiges Bild neben einer `.cook`-Datei wird ihr Rezeptbild.

## 0.2.17

- Einkaufsliste: Antippen öffnet eine Zeile – darunter jedes Rezept, das die Zutat braucht, mit
  seiner Menge. Abgehakt wird nur noch über das Kästchen rechts.
- Einkaufsliste: Nach Rezept lässt sich jedes Rezept über seine Überschrift zu- und aufklappen;
  das Handy merkt es sich pro Liste.
- Einkaufsliste: Was aus den Vorräten zurückkommt, landet in seiner Abteilung statt in
  Undefiniert, mit derselben Animation wie auf dem Weg hinein.
- Einkaufsliste: Beim Wechsel des Supermarkts kommt jede Zeile in ihre gemerkte Abteilung oder in
  die gleichnamige; den Rest sortiert der Agent sofort ein.
- Einkaufsliste: „Zeigen“ gleitet zu den Vorräten statt zu springen; Vorräte, Hinweise und
  aufgeklappte Zeilen öffnen und schließen ruhiger. Abteilungsüberschriften gehen über die volle
  Breite.
- Hinweise unten (Toasts) lassen sich zur Seite wegwischen.
- Das Zusammenfassen ist schneller: gleiche Zutaten mit gleicher Einheit rechnet die App selbst
  zusammen, der Agent bekommt weniger zu tun. Wird eine Antwort verworfen, steht der Grund im
  Berichte-Ordner.
- Rezeptordner: Cooklang-Dateien mit „prep time“, „cook time“ und „total time“ bringen ihre
  Zeiten mit; optionale Zutaten („@?Reis“) werden gelesen statt die Datei zu überspringen.

## 0.2.16

- Einkaufsliste: Die Liste springt nicht mehr nach oben, wenn man eine Zeile antippt oder das
  Scrollen auf einer Zeile beginnt; die Einstellungen-Seiten behalten ihre Stelle ebenso.
- Einkaufsliste: Der Supermarkt lässt sich wieder wechseln (ein Tippen ins Menü schloss es bisher
  nur), ebenso die Liste oben in der Kopfzeile. Der Supermarkt-Knopf ist jetzt immer da; mit nur
  einem Markt führt er zu „Supermarkt hinzufügen …“.
- Einkaufsliste: Der Pfeil fügt beim ersten Tippen hinzu, die Tastatur bleibt danach offen.
- Einkaufsliste: „Zeigen“ unter Hinweise bringt die Vorräte genau unter den Fortschritt;
  Abteilungsüberschriften schieben sich gegenseitig weg statt sich zu überlagern.
- Einkaufsliste: Zurück aus den Vorräten geht jetzt mit langem Drücken, mit „Zurück“; Antippen
  sagt, wie es geht.
- Einkaufsliste: Beim Zusammenfassen sagt das Banner, was passiert, und zählt die Zeit mit.
- Einstellungen › Supermärkte: Beim Ziehen scrollt die Seite am oberen und unteren Rand mit, und
  nach dem Ablegen bleibt sie an ihrer Stelle.
- Plan: Die Kopfzeile kommt erst am Anfang des Plans zurück; zum „Neuen Plan“ braucht es einen
  längeren Zug.
- Jeder Lauf des Agenten (planen, zusammenfassen, sortieren) hinterlässt eine Zeile mit Dauer und
  Kosten im Berichte-Ordner; Rückmeldungen nennen auch die letzten Knöpfe und Tabs.

## 0.2.15

- C1: Die Einkaufsliste kommt aus dem Plan. Beim Bestätigen steht die Liste sofort da – jede
  Zutat jedes Rezepts als eigene Zeile, gleich benutzbar –, und der Agent fasst sie im Hintergrund
  zusammen („Wird zusammengefasst …“, dann „Liste zusammengefasst“). Wo eine Menge keine einfache
  Summe ist, steht sein Kommentar unter der Zeile; oben unter „Hinweise“ sein Hinweis zur Liste und
  wie viele Zutaten er als „vermutlich da“ zu den Vorräten gelegt hat. Klappt das Zusammenfassen
  nicht: „Noch nicht zusammengefasst · Nochmal versuchen“.
- C1: Nach Abteilung und Nach Rezept; abhaken je Zeile oder je Rezept; Menge antippen und ändern
  (die ganze Zeile oder den Anteil eines Rezepts); lange auf das Häkchen drücken legt eine Zutat für
  diese Liste zu den Vorräten, Antippen dort holt sie zurück; lange auf die Zeile drücken und ziehen
  verschiebt sie in eine andere Abteilung – gemerkt für diesen Supermarkt. Beides mit „Zurück“.
- C1: Hinzufügen mit Menge vorn oder hinten („tomaten 500g“); Vorschläge ab zwei Buchstaben aus
  der Liste, den Vorräten und früheren Listen; steht es schon drauf, sagt die App das. Von Hand
  Hinzugefügtes wartet in „Undefiniert“ auf „Sortieren“.
- C1: Zutaten aus Cookidoo-Rezepten zeigen ihr Bild (nach dem nächsten Abgleich mit Cookidoo).
- C1: Mehrere Pläne – oben in der Kopfzeile zwischen ihren Listen wechseln; der Supermarkt-Knopf
  sortiert nach einem anderen Markt.
- C1: Einstellungen › Supermärkte (Abteilungen in Lauf-Reihenfolge ziehen, umbenennen, anlegen,
  vorausgewählt) und › Vorräte (was ihr immer da habt).
- A1s „Testliste“ ist entfernt. Die Datenbank wird beim Update umgestellt; vorher wird eine Kopie
  angelegt.

## 0.2.14

- B2: Einstellungen › Haushalt & Vorlieben. Die sechs Einflüsse stehen fest; durch Ziehen legt ihr
  ihre Reihenfolge fest – ziehen zwei gegeneinander, gewinnt der obere. Im Freitext steht, wer ihr
  seid und was ihr euch wünscht; der Agent bekommt ihn bei jeder Planung. Nach dem Speichern prüft
  er im Hintergrund, ob er alles davon befolgen kann, und nennt die Stellen, die er nicht befolgt.
  Unter „Assistent“ bekommt der Agent einen Namen und einen Artikel; die App spricht dann so von
  ihm. Gespeichert wird mit „Speichern“, und nur mit Verbindung.
- B2: Einstellungen › Vorlagen. Vorlagen legen fest, welche Mahlzeiten an welchen Wochentagen
  geplant werden; anlegen, umbenennen (auch Standard), löschen, eine ist vorausgewählt. Beim neuen
  Plan steht jede Vorlage als Chip bereit, die vorausgewählte zuerst; „+ Speichern“ macht aus dem
  gerade eingestellten Raster eine neue Vorlage.
- B2: Beim ersten Vorschlag eines Plans kann der Agent oben eine kurze Bemerkung zum Rezeptbestand
  machen (z. B. wenn viele Rezepte pausiert sind); ✕ blendet sie auf allen Geräten aus. Dieselbe
  Art kommt höchstens alle vier Wochen. Einstellungen › System › Entwicklung: „Kommentar-Sperre
  aufheben“.
- Farbschema (System · Hell · Dunkel) kommt jetzt aus dem gemeinsamen Design System; die Wahl
  jedes Geräts bleibt erhalten, beim Start blitzt kein falsches Schema mehr auf.
- Die Datenbank wird beim Update umgestellt; vorher wird eine Kopie angelegt.

## 0.2.13

- B1: In der Durchsicht schwebt unten eine Leiste mit „n neu generieren“ und „Plan bestätigen“.
  Solange eine Mahlzeit abgelehnt ist, sagt „Plan bestätigen“ beim Antippen, was noch fehlt;
  Bestätigen nimmt alle noch nicht beantworteten Vorschläge an. Der aktuelle Tag steht als Zeile
  unter dem Fortschritt.
- B1: Beim Scrollen nach unten macht die Kopfzeile Platz (im Plan und in der Durchsicht), beim
  Scrollen nach oben kommt sie zurück. Getauschte Gerichte gleiten immer gleich ruhig, auch über
  eine weite Strecke.
- Rezepte: Die Gesamtzeit lässt sich im Feld „Min gesamt“ selbst eintragen; die eigene Zeit steht
  groß, die der Quelle klein in Klammern, leer gilt wieder die der Quelle. Im Menü „Kein eigenes
  Gericht“: so markierte Rezepte schlägt der Agent nie vor, selbst wählen geht weiter. Fehlt die
  Datei eines eigenen Rezepts, lässt es sich mit „Aus Meal Planner entfernen“ entfernen; frühere
  Pläne zeigen es weiter.
- Einstellungen › System › Entwicklung (nur Admins, Option **dev_tools**): „Alle Pläne löschen“ und
  „Auf Werkszustand zurücksetzen“, jeweils mit Bestätigung.
- Die Datenbank wird beim Update umgestellt; vorher wird eine Kopie angelegt.

## 0.2.12

- B1: Die Plan-Auswahl oben reagiert wieder auf Antippen. Tauschen durch Halten und Ziehen ist
  ruhiger: die beiden Gerichte gleiten an ihren neuen Platz, sonst bewegt sich nichts. In der
  Durchsicht steht der Fortschritt fest über der Liste (kein Streifen mehr darüber); ein Gericht,
  das für eine Mahlzeit abgelehnt wurde, kommt für sie nicht wieder; ein Tipp auf einen Vorschlag
  öffnet das Rezept, Zurück führt an dieselbe Stelle.

## 0.2.11

- B1: Eine Woche planen. Im Plan-Tab: Plan-Konfiguration (Zeitraum und Mahlzeiten aus „Standard“,
  Extras mit Hinweis), der Agent schlägt vor (meist unter 15 Sekunden), Durchsicht mit Ja/Nein und
  Grund, neue Vorschläge für die abgelehnten, Rezept selbst wählen, Slots bearbeiten oder entfernen,
  Tauschen durch Halten und Ziehen, Plan bestätigen. Bestätigte Pläne liegen auf der Zeitleiste
  (wischen, Plan-Auswahl oben, „Zum aktuellen Plan“), das Gericht oben wächst beim Antippen zum
  Rezept. Im Rezept zeigt „Verlauf“, wann es geplant oder abgelehnt wurde; die Rezeptliste kennt
  „Neu“ und sortiert nach Häufigkeit.
- Jeder Vorschlag ist ein echter Aufruf bei Google mit dem Schlüssel **gemini_key** (etwa 1 Cent
  pro Woche mit Gemini 3.8 Flash).

## 0.2.10

- B0: Einstellungen › Agent › Modell (nur Admins, in Home Assistant): wählt das Google-Modell, mit
  dem der Agent später plant und einkauft. Die Liste kommt von Google („Liste neu laden“);
  voreingestellt ist Gemini 3.8 Flash. Der Google-Schlüssel ist eine neue Einstellung des Add-ons
  (**gemini_key**).
- A2 (Test): „simulate_cookidoo_failure“ wirkt jetzt auch mit eingetragenen Cookidoo-Zugangsdaten —
  jede Abfrage schlägt fehl, ohne sich bei Cookidoo anzumelden.

## 0.2.9

- A2: Rezeptfotos flackern beim Öffnen nicht mehr (iPhone); Suche und Filter liegen fest über dem
  Raster, beim Scrollen scheint nichts mehr durch; Filter auf beiden Handys gleich groß.
- A1 (iPhone): Die untere Leiste rückt näher an den Bildschirmrand.

## 0.2.8

- A2: Zurück-Geste für Chrome: Plan ist der Startbildschirm. Zurück führt durch die Bildschirme,
  von Einkauf und Rezepte zum Plan; auf dem Plan erscheint „Noch einmal zurück zum Schließen“, ein
  zweites Zurück schließt die App.
- A2: Die Filter bei den Rezepten sind größer; alle Rezeptkarten sind gleich hoch; über der Suche
  scheint beim Scrollen nichts mehr durch (iPhone).
- A1 (iPhone): Die untere Leiste sitzt wieder ganz auf dem Bildschirm (der Versuch aus 0.2.7 schob
  sie zu weit nach unten).

## 0.2.7

- A2: Zurück-Geste, dritter Versuch, diesmal am Quelltext von Firefox geprüft: Firefox zählt ein
  Tippen erst beim Loslassen. Zurück führt jetzt durch die Bildschirme; auf Einkauf, Plan und
  Rezepte schließt Firefox die App (graue Seite, dann noch einmal zurück) – ohne Hinweis.
- A1 (iPhone): Die untere Leiste reicht bis zum Bildschirmrand (Versuch); die App meldet dazu einmal
  ihre Bildschirmmaße.

## 0.2.6

- A2: Zurück-Geste, zweiter Versuch: Firefox übersprang die Seite, weil der Rückschritt angelegt
  wurde, bevor jemand getippt hatte; jetzt erst nach dem ersten Tippen.

## 0.2.5

- A2: Die Zurück-Geste von Android führt durch die Bildschirme (Rezept → Rezepte, Einstellungen →
  zurück) statt auf eine leere graue Seite; auf Einkauf, Plan und Rezepte schließt erst ein zweites
  Zurück die App.
- A2 (iPhone): Das Zeichen „Eigenes“ und der Zurück-Pfeil bei Rezepten ohne Foto haben wieder
  ihre Größe; beim Öffnen eines Rezepts erscheint sofort das kleine Foto; über der Suche scheint
  beim Scrollen kein Streifen des Rasters mehr durch.

## 0.2.4

- A2: Rezeptfotos für unterwegs werden vollständig gespeichert, auch wenn die Verbindung beim
  ersten Laden kurz abreißt (fehlende Fotos werden beim nächsten Öffnen nachgeladen).

## 0.2.3

- A2 Rezepte: Rezepte durchsuchen, filtern und sortieren; Rezept mit Zutaten, Zubereitung, Verlauf
  und Notizen; bewerten, pausieren, Notizen schreiben, bearbeiten und löschen. Ohne Empfang bleibt
  alles lesbar; Ändern braucht Verbindung.
- A2 Einstellungen: Rezeptquellen (Cookidoo-Sammlungen, in Cookidoo erstellte Rezepte, lokaler
  Rezeptordner mit übersprungenen Dateien), Farbschema pro Gerät.
- Test: Cookidoo ist simuliert (aufgezeichnete Rezepte), solange keine Zugangsdaten eingetragen
  sind; der Rezeptordner bekommt beim ersten Start erfundene Testrezepte.
- A1: Firefox wählt die Farbe der Statusleiste selbst (Versuch; Symbol auf dem Startbildschirm neu hinzufügen).

## 0.2.2

- A1: Skripte werden bei jedem Öffnen geprüft, damit der Browser nach einer Aktualisierung keine alte Fassung weiterverwendet.
- A1: Die Statusleiste des Telefons nimmt die Seitenfarbe an, auch im dunklen Design.

## 0.2.1

- A1: wie 0.2.0-a1.2, mit einer Versionsnummer, die Home Assistant als neuer erkennt (die Aktualisierung war ausgegraut).

## 0.2.0-a1.2

- Öffnet jetzt auch in Home Assistant (Seitenleiste, Companion-App): die Seite blieb über HTTP leer.
- Ein fehlgeschlagener Start zeigt den Grund statt einer leeren Seite.

## 0.2.0-a1.1

- Erste Testversion (A1 Einstiegsprobe): Testliste, Geräte koppeln, offline abhaken, Rückmeldung.
