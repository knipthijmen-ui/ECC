# Lichtplan

Camera- en lichtplattegronden tekenen in de browser. Eén zelfstandig HTML-bestand, geen build-stap en geen afhankelijkheden.

## Gebruik

Open `index.html` in een moderne browser (Chrome, Edge, Safari of Firefox). Projecten worden automatisch opgeslagen in de `localStorage` van die browser. Gebruik **Exporteren** op het dashboard om een project als `.json` te bewaren of te delen, en **Importeren** om het weer in te laden.

## Functies

- **Dashboard** met projecten (nieuw, hernoemen, dupliceren, exporteren, verwijderen) en sjablonen: leeg, studio, interview.
- **Wit canvas met puntenraster** (10, 25, 50 of 100 cm) en snappen met een vergrootglas-effect op de punten. Houd `Alt` ingedrukt om tijdelijk vrij te bewegen.
- **Muren, ruimtes, deuren en ramen**: sleep of klik om muren te trekken; een afgesloten ruimte krijgt automatisch een vloer met kleurverloop en oppervlakte. deuren en ramen klikken vast op de dichtstbijzijnde muur en maken een opening waar licht doorheen gaat.
- **Objecten** om in het veld te slepen: persoon (met kijkrichting), tafel, camera, fresnel, LED-paneel, softbox, piepschuim/bounce, spiegel, diffusiescherm en floppy.
- **Lichtsimulatie**: lampen schijnen met een bundel die je met handvatten groter, kleiner, verder of anders gericht maakt. Spiegels reflecteren de bundel, piepschuim kaatst zacht terug (wit, zilver of goud), diffusie maakt het licht zachter en breder, muren, mensen, tafels en floppy's werpen schaduw.
- **Camerabeeld**: beeldkegel met handvatten en lenskeuze (16–135 mm full frame).
- **Eigenschappen-popup**: klik of houd een object lang ingedrukt.
- **Tekstvakken met verbindingslijnen**: beweeg over een tekstvak, pak het puntje rechtsonder en sleep naar een object. De lijn volgt het object en is aan te passen (kleur, dikte, pijl, kromming, stippel).
- **Vrij tekenen**, ongedaan maken/opnieuw en PNG-export.

## Sneltoetsen

| Toets | Actie |
|-------|-------|
| `V` `H` `W` `R` `D` `N` `T` `P` | Selecteren, verschuiven, muur, ruimte, deur, raam, tekst, tekenen |
| `G` / `S` | Raster / snappen aan of uit |
| `L` / `C` | Lichtbundels / camerabeeld aan of uit |
| `F` | Alles in beeld |
| `[` / `]` | Selectie 15° draaien |
| Pijltjes (+`Shift`) | Selectie verschuiven (per rasterstap) |
| `Ctrl/Cmd+Z`, `Ctrl/Cmd+Shift+Z` | Ongedaan maken / opnieuw |
| `Ctrl/Cmd+D`, `Delete` | Dupliceren / verwijderen |
| `Spatie` + slepen | Canvas verschuiven |
