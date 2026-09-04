# Volleybal Rotatiehulp – PWA

Upload alle bestanden uit deze map naar de hoofdmap van je GitHub Pages repository.

Daarna: GitHub → Settings → Pages → Deploy from a branch → `main` → `/ (root)`.

De app gebruikt localStorage voor de opstelling en rotatiestand. Daardoor blijft de gegevensset behouden bij een gewone refresh, ook op Android.

De service worker zorgt daarnaast voor offline caching. Een service worker werkt alleen via HTTPS of localhost; `file://` is daarvoor niet geschikt.
