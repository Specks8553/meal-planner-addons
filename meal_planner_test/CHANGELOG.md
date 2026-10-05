# Changelog

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
