# Math Drop Ultimate – Schulversion

Diese Kopie ist für ein eigenes GitHub-Repository gedacht, getrennt von der Bewerbungsseite.

## Dateien
- `index.html`: das Spiel
- `assets/neon-bg.jpg`: optionaler Neon-Hintergrund (noch nicht enthalten)

## Hintergrundbild hinzufügen
Lege dein Neon-Bild in den Ordner `assets` und benenne es `neon-bg.jpg`.
Die HTML-Datei erwartet diesen Pfad: `assets/neon-bg.jpg`.

## Supabase einrichten
In `index.html` nach `SUPABASE_URL` und `SUPABASE_ANON_KEY` suchen und die Werte aus deinem Supabase-Projekt eintragen.
**Nicht** den `service_role`-Key verwenden. Nur den öffentlichen anon/publishable Key.
Die Tabelle `public.highscores` wird verwendet.

## GitHub Pages
1. Neues Repository erstellen (z.B. `math-drop-schulversion`).
2. Diese Dateien hochladen.
3. Repository → Settings → Pages.
4. Bei Build and deployment: Deploy from a branch auswählen, Branch `main`, Folder `/ (root)`, Save.
5. Nach Veröffentlichung die GitHub-Pages-URL öffnen und testen.

## Moodle
Nach Veröffentlichung kann die Seite je nach Moodle-Konfiguration als URL-Ressource verlinkt werden oder per iframe eingebettet werden. Ob iframe erlaubt ist, hängt von den Moodle-Rechten/Filter-Einstellungen der Schule ab.
