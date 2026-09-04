# Volleybal Rotatiehulp – Progressive Web App

Deze map is een complete PWA-versie van de oorspronkelijke `volleybal-rotatie-mobiel.html`.

## Inhoud
- `index.html` – de webapp
- `manifest.json` – PWA-installatiegegevens
- `sw.js` – offline caching
- `icons/` – app-iconen voor Android/iPhone/iPad
- `.nojekyll` – voorkomt onnodige Jekyll-verwerking op GitHub Pages

## Publiceren via GitHub Pages

1. Maak op GitHub een nieuwe repository, bijvoorbeeld `volleybal-rotatie`.
2. Upload **de bestanden uit deze map** naar de hoofdmap van de repository.
3. Open in GitHub: **Settings → Pages**.
4. Kies bij de publicatiebron **Deploy from a branch**.
5. Selecteer de branch `main` en map `/ (root)`.
6. Sla op.
7. Na de GitHub Pages-deployment krijg je een adres in de vorm:
   `https://jouwgebruikersnaam.github.io/volleybal-rotatie/`

Gebruik daarna bij voorkeur Safari op iPhone/iPad en kies **Deel → Zet op beginscherm**.

## Belangrijk
De service worker werkt niet wanneer je `index.html` rechtstreeks opent via `file://`.
Dat is normaal. Op GitHub Pages draait de app via HTTPS en werkt de PWA-functionaliteit wel.

De huidige rotatie/opstelling wordt bovendien lokaal in de browser opgeslagen, zodat een refresh de gegevens niet meer direct wist.
