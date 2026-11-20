# Lichtplan

Camera- en lichtplattegronden tekenen in de browser. Eén zelfstandig HTML-bestand, geen build-stap en geen afhankelijkheden.

## Gebruik

Open `index.html` in een moderne browser (Chrome, Edge, Safari of Firefox). Projecten worden automatisch opgeslagen in de `localStorage` van die browser. Gebruik **Exporteren** op het dashboard om een project als `.json` te bewaren of te delen, en **Importeren** om het weer in te laden.

## Functies

- **Dashboard** met projecten (nieuw, hernoemen, dupliceren, exporteren, verwijderen) en sjablonen: leeg, studio, interview.
- **Wit canvas met puntenraster** (10, 25, 50 of 100 cm) en snappen met een vergrootglas-effect op de punten. Houd `Alt` ingedrukt om tijdelijk vrij te bewegen.
- **Muren, ruimtes, deuren en ramen**: sleep of klik om muren te trekken; een afgesloten ruimte krijgt automatisch een vloer met kleurverloop en oppervlakte. deuren en ramen klikken vast op de dichtstbijzijnde muur en maken een opening waar licht doorheen gaat.
- **Objecten** om in het veld te slepen: persoon (met kijkrichting, huid-, haar- en kledingkleur), tafel, camera, piepschuim/bounce, spiegel, diffusiescherm, floppy en negatieve fill.
- **Lampen**: COB-lamp met wisselbare koppen (reflector, fresnel, softbox met of zonder grid, lantaarn) en barndoors, LED-paneel, gobo-spot met verschillende gobo's (raam, jaloezie, bladeren, tralies, stippen, ster, kerkraam, cirkel) en practicals (peertje, schemerlamp, staande lamp, TL-buis, kaars). Elke lamp kan in Kelvin, RGB of met een gel.
- **Lichtsimulatie**: lampen schijnen met een bundel die je met handvatten groter, kleiner, verder of anders gericht maakt. Spiegels reflecteren de bundel, piepschuim kaatst zacht terug (wit, zilver of goud), diffusie maakt het licht zachter en breder, negatieve fill neemt licht weg, en muren, mensen, tafels en floppy's werpen schaduw.
- **Camerabeeld**: beeldkegel met handvatten en lenskeuze (16–135 mm full frame).
- **3D-camerabeeld** rechtsboven: laat in 3D zien wat de gekozen camera ziet: gedetailleerde personen, lampen op statieven met hun koppen, gobo-patronen op de muren, schaduwen en het licht op personen. Spiegels, bounce, diffusie en muren kaatsen licht terug. Sleep het bolletje linksonder om het venster te vergroten of te verkleinen. Gebruikt three.js van cdnjs, dus dit onderdeel heeft internet nodig.
- **Bedienen**: tik een object aan om het te selecteren en te verplaatsen. Houd het ingedrukt (een gloed wordt steeds sterker) om het eigenschappen-menu te openen.
- **Tekstvakken met verbindingslijnen**: beweeg over een tekstvak, pak het puntje rechtsonder en sleep naar een object. De lijn volgt het object en is aan te passen (kleur, dikte, pijl, kromming, stippel).
- **Vrij tekenen**, ongedaan maken/opnieuw en PNG-export.
- **Subtiele animaties** overal: objecten poppen in en faden uit, lampen ademen, selecties en camerakegels lopen, raster, licht en kegels faden bij aan/uit en zoomen gaat soepel. Staat "minder beweging" aan in je systeem, dan zijn ze uit.

## Sneltoetsen

| Toets | Actie |
|-------|-------|
| `V` `H` `W` `R` `D` `N` `T` `P` | Selecteren, verschuiven, muur, ruimte, deur, raam, tekst, tekenen |
| `G` / `S` | Raster / snappen aan of uit |
| `L` / `C` | Lichtbundels / camerakegels aan of uit (of kies Alles · Licht · Camera · Uit in de werkbalk) |
| `3` | 3D-camerabeeld aan of uit |
| `F` | Alles in beeld |
| `[` / `]` | Selectie 15° draaien |
| Pijltjes (+`Shift`) | Selectie verschuiven (per rasterstap) |
| `Ctrl/Cmd+Z`, `Ctrl/Cmd+Shift+Z` | Ongedaan maken / opnieuw |
| `Ctrl/Cmd+D`, `Delete` | Dupliceren / verwijderen |
| `Spatie` + slepen | Canvas verschuiven |
