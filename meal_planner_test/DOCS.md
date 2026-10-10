# Meal Planner (Test)

Testinstallation von Meal Planner 0.2. Hier werden neue Versionen ausprobiert, bevor sie in den
Haushalt kommen. Die Daten hier sind Testdaten.

## Einstellungen

- **admin_users**: HA-Benutzernamen, die gekoppelte Geräte entfernen dürfen (z. B. `adrian`).
- **cookidoo_email**, **cookidoo_password**: die Cookidoo-Zugangsdaten. Leer: Cookidoo ist
  simuliert (aufgezeichnete Testrezepte).
- **simulate_cookidoo_failure**: nur zum Ausprobieren — jede Cookidoo-Abfrage schlägt fehl, auch mit
  Zugangsdaten (dann ohne Anmeldung bei Cookidoo).
- **dev_tools** (an, solange nicht ausgeschaltet): zeigt Admins in Meal Planner in Home Assistant
  Einstellungen › System › Entwicklung — „Alle Pläne löschen“ und „Auf Werkszustand
  zurücksetzen“ (gekoppelte Geräte, diese Optionen und die Berichte bleiben).
- **share_host**: wie der PC die Netzwerkfreigabe erreicht (z. B. `192.168.178.55`); wird in den
  Rezeptquellen als Pfad zum Rezeptordner angezeigt.
- **gemini_key**: der Schlüssel aus Google AI Studio, mit dem der Agent arbeitet. Damit liest
  Einstellungen › Agent › Modell Googles Modell-Liste. Leer: „Kein Google-Schlüssel hinterlegt“.

## Rezeptordner

Eigene Rezepte sind `.cook`-Dateien im Ordner `rezepte` dieses Add-ons
(`addon_configs/…_meal_planner_test/rezepte` auf der Freigabe). Danach in Meal Planner unter
Einstellungen › Rezeptquellen „Jetzt einlesen“.

## Planen

Plan-Tab › Plan-Konfiguration: Zeitraum und Mahlzeiten wählen, „Plan generieren“. Der Agent
schlägt aus den nicht pausierten Rezepten vor; jeder Vorschlag ist ein Aufruf bei Google mit dem
Schlüssel **gemini_key** und dem Modell aus Einstellungen › Agent › Modell. Ohne Schlüssel oder
Verbindung zeigt die Seite, was fehlt. Pläne ändern braucht eine Verbindung zum Home Assistant.

## Zugang

- In Home Assistant: über das Seitenmenü „Meal Planner (Test)“.
- Als App auf dem Handy: über die Testadresse; das Handy wird mit einem Code gekoppelt
  (Einstellungen › Gerät koppeln in Home Assistant).
