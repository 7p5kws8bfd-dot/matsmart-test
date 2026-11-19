Matsmart 0.2 – uppdatering av befintlig GitHub Pages-app

Ladda upp/ersätt dessa filer i repositoryts ROT: index.html, scanner.js, sw.js, manifest.webmanifest, icon-192.png, icon-512.png. OBS: den tidigare appen använder sw.js och manifest.webmanifest (inte service-worker.js/manifest.json).

GitHub Pages: Settings > Pages > Deploy from a branch > main > /(root). Efter Commit changes, vänta på publicering och öppna appen. Stäng och öppna den igen för att få ny cacheversion.

Matsmart 0.2 använder samma localStorage-nyckel som 0.1 (matsmart-v01-items). Ingen avsiktlig radering av gamla varor. Ladda ned en säkerhetskopia när appen uppdaterats.

Skanning kräver HTTPS och en webbläsare med BarcodeDetector. Om den saknas, skriv streckkodens siffror manuellt. Produktinformation hämtas från Open Food Facts och kan saknas. Kamera- och produktuppslag kräver nät och behörighet.

Säkerhetskopia är en JSON-fil. Återställning ERSÄTTER aktuellt lager efter bekräftelse. Spara kopian i Filer/iCloud Drive. Ingen familjesynkronisering eller AI finns ännu.
