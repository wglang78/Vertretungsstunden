# Vertretungsstunde – Klassenquiz

Ein Quiz für den Beamer: Allgemeinwissen, Flaggen, Englisch- und Französisch-Vokabeln, Kopfrechnen und Rätsel (mit eigener Quizliste).

## So läuft das Quiz
1. Sparte und Anzahl der Fragen (5–25) wählen, **Quiz starten**.
2. Wer zuerst auf **🖐 Lösen** drückt (oder die Leertaste), darf antworten.
3. Antwort eintippen, **Lösung anzeigen** (Enter).
4. Richtig → nächste Frage. Falsch → die Frage kommt nach 2 anderen Fragen noch einmal.
5. Das Quiz ist zu Ende, wenn alle Fragen richtig beantwortet wurden.

Mit „Doch richtig werten“ / „Doch falsch werten“ kann die Lehrkraft die Bewertung korrigieren.
Beim Start wechselt die Seite in den Vollbildmodus, beim Beenden zurück.
Zum Antworten erscheint eine Bildschirmtastatur (beim Kopfrechnen ein Ziffernblock), damit alles an der Tafel bedient werden kann.
Groß-/Kleinschreibung, Akzente und Artikel (der/die/das, the, to, le/la/l') spielen beim Vergleich keine Rolle.

## Lehrerzugang
- Oben rechts **🔒 Lehrerzugang** (Passwort kennt die Lehrkraft)
- Sparte wählen, Liste einfügen oder als .txt/.csv laden → **Liste speichern**.
  Die Liste ersetzt dann die Standardliste dieser Sparte.
- Format: eine Zeile pro Eintrag, getrennt mit `;` oder Tabulator (Spalten aus Excel lassen sich direkt einfügen):
  ```
  Hund;dog
  Fahrrad;bike/bicycle
  ```
  Mehrere richtige Antworten mit `/` trennen.
- Bei Allgemeinwissen kann als 3. Spalte ein Link stehen (z. B. YouTube). Er wird nach der Lösung angezeigt, YouTube-Videos werden direkt eingebettet.
- **Wichtig:** Eigene Listen werden nur im Browser des jeweiligen Rechners gespeichert und **nach 60 Minuten automatisch gelöscht**.
  Danach gilt wieder die Standardliste.

## Standardlisten ändern
Die Standardfragen stehen in `data.js` und können dort direkt bearbeitet werden.

## Auf GitHub hosten (GitHub Pages)
1. Auf GitHub ein neues Repository `Vertretungsstunden` anlegen (öffentlich).
2. **Add file → Upload files**: `index.html`, `data.js` und `README.md` hochladen, **Commit changes**.
3. **Settings → Pages** → bei *Source* „Deploy from a branch“, Branch `main`, Ordner `/ (root)` → **Save**.
4. Nach 1–2 Minuten ist die Seite erreichbar unter
   `https://DEIN-BENUTZERNAME.github.io/Vertretungsstunden/`

Die Flaggenbilder werden von flagcdn.com geladen – dafür braucht der Rechner Internet.
