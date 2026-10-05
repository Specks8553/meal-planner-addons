# Meal Planner (Test)

Testinstallation von Meal Planner 0.2. Hier werden neue Versionen ausprobiert, bevor sie in den
Haushalt kommen. Die Daten hier sind Testdaten.

## Einstellungen

- **admin_users**: HA-Benutzernamen, die gekoppelte Geräte entfernen dürfen (z. B. `adrian`).
- **cookidoo_email**, **cookidoo_password**: die Cookidoo-Zugangsdaten. Leer: Cookidoo ist
  simuliert (aufgezeichnete Testrezepte).
- **simulate_cookidoo_failure**: nur zum Ausprobieren — jede Cookidoo-Abfrage schlägt fehl.
- **share_host**: wie der PC die Netzwerkfreigabe erreicht (z. B. `192.168.178.55`); wird in den
  Rezeptquellen als Pfad zum Rezeptordner angezeigt.

## Rezeptordner

Eigene Rezepte sind `.cook`-Dateien im Ordner `rezepte` dieses Add-ons
(`addon_configs/…_meal_planner_test/rezepte` auf der Freigabe). Danach in Meal Planner unter
Einstellungen › Rezeptquellen „Jetzt einlesen“.

## Zugang

- In Home Assistant: über das Seitenmenü „Meal Planner (Test)“.
- Als App auf dem Handy: über die Testadresse; das Handy wird mit einem Code gekoppelt
  (Einstellungen › Gerät koppeln in Home Assistant).
