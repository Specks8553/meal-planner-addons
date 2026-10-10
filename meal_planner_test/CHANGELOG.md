# Changelog

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
