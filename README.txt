Matsmart 0.1 – installationsguide (iPhone/iPad)

INNEHÅLL
index.html – appen
manifest.webmanifest – PWA-inställningar
sw.js – offline-cache
icon-192.png och icon-512.png – appikoner

SNABBTEST
1. Packa upp ZIP-filen i appen Filer.
2. Öppna index.html för en snabb visuell kontroll. OBS: lokal lagring och PWA-installation kan fungera annorlunda när en HTML-fil öppnas direkt från Filer. För ett riktigt test, publicera via HTTPS enligt nedan.

PUBLICERA UTAN MAC
1. Skapa ett kostnadsfritt konto på GitHub via Safari.
2. Skapa ett nytt PUBLIC repository, exempelvis matsmart-test. Publicera inga personuppgifter där.
3. Ladda upp de fem filerna från den uppackade mappen till repositoryts rot via GitHubs webbgränssnitt (Add file > Upload files). Om mobilgränssnittet är begränsat: välj Begär webbplats för dator i Safari.
4. Öppna Settings > Pages > Build and deployment och välj Deploy from a branch, main, /(root). Spara.
5. Vänta på att GitHub Pages visar din publicerade HTTPS-adress. Öppna den i Safari på iPhone.
6. Testa: Lägg till en vara, stäng fliken, öppna igen och kontrollera att varan finns kvar. Testa filtren och ändra/förbruka.
7. I Safari: Dela > Lägg till på hemskärmen. Välj Öppna som webbapp om alternativet visas.

VIKTIGT
- Appen lagrar data ENDAST lokalt på respektive enhet. Ingen familjesynk finns i version 0.1.
- Ingen streckkodsskanning, AI eller automatisk pushnotis finns ännu.
- Datumövervakningen sker när appen öppnas; inga bakgrundspåminnelser.
- Rensa inte webbplatsdata utan att först ha sparat informationen på annat sätt. Export/backup kommer i en senare version.
- Om ni öppnar appen via en ny domän eller annan webbläsarprofil följer inte data automatiskt med.
- För bästa säkerhet: använd testdata i den här första versionen. GitHub Pages är publik.
