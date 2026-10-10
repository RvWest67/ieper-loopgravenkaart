# Ieperboog 14–18 · Weekend 16–18 oktober 2026

WOI-website over de Ieperboog (Leaflet, Nederlandstalig, geschikt voor mobiel), gemaakt voor een weekend in Ieper (16–18 oktober 2026).

**Startpagina:** https://rvwest67.github.io/ieper-loopgravenkaart/

- **Loopgravenkaart:** https://rvwest67.github.io/ieper-loopgravenkaart/kaart.html
- **Simulatie 1914–1918:** https://rvwest67.github.io/ieper-loopgravenkaart/simulatie.html (een stap openen kan direct met `#stap1` t/m `#stap8`)

## Bestanden

- `index.html` – startpagina met keuzemenu: Loopgravenkaart, Simulatie 1914–1918 en (binnenkort) Weekendprogramma. De klaproos is een eigen SVG-tekening; er staan geen afbeeldingen van derden op de pagina.
- `kaart.html` – de loopgravenkaart (één bestand; frontlijnen, loopgraven en plekken zitten erin, achtergrondkaarten en WOI-luchtfoto's worden live geladen). Een plek of uitsnede openen kan met `kaart.html#lat,lng,zoom`.
- `simulatie.html` – geanimeerde tijdlijn van de Ieperboog in acht stappen (1914, gasaanval 22 april 1915, mei 1915, 1916, mijnen van Mesen 7 juni 1917, Passendale 1917, Leie-offensief april 1918, bevrijding vanaf 28 september 1918). Bevat frontlijnen uit de bron, pijlen, gaswolk en de 19 mijnkraters op hun echte plek, een korte uitleg met slachtofferaantallen en bronnen, en links naar de plekken die je nu kunt bezoeken. Pijlen, gaswolk en animaties zijn visualisaties. De lijn ‘na Mesen’ en de zone van het bevrijdingsoffensief (sept.–okt. 1918) zijn **benaderingen**; zie het ⓘ-paneel.
- Navigatie: 🏠 op de kaart en in de simulatie gaat terug naar het menu. ‘▶ Simulatie 1914–1918’ op de kaart gaat naar de simulatie, ‘🗺 Kaart’ in de simulatie naar de kaart, en ‘Op loopgravenkaart’ bij een plek in de simulatie opent `kaart.html` op die plek.
- `ww1-ieper.kml` – dezelfde 21 plekken, om te importeren in Google My Maps.

‘Mijn locatie’ vraagt locatietoegang in je browser.

## Bronnen en licenties

- **Frontlijnen 1914 / 1915 / 1917 / 1918**: Provincie West-Vlaanderen, Geoportaal ‘Luchtfoto 1914-1918’ (ArcGIS-dienst *AGS_WO1_Frontlijnen*, gwadmin.west-vlaanderen.be). Opgehaald op 10-10-2026 en vereenvoudigd (±5 m). Geen expliciete licentie vermeld: persoonlijk, niet-commercieel gebruik met bronvermelding.
- **WOI-luchtfoto's**: Provincie West-Vlaanderen (*AGS_WO1_LuchtFotos*), luchtfoto's uit de archieven van In Flanders Fields Museum, Imperial War Museums en War Heritage Institute, verwerkt door UGent (Vakgroep Archeologie). Live geladen. © de respectieve archieven. Zie https://www.luchtfoto1914-1918.be/nl/geoportaal
- **Loopgraven uit luchtfotokartering**: Gheyle, W., Verdegem, S. & Stichelbaut, B. (2021), *Dataset archeologisch syntheseonderzoek loopgraven Eerste Wereldoorlog in Vlaanderen* (UGent / Onroerend Erfgoed), Zenodo [10.5281/zenodo.4740452](https://zenodo.org/records/4740452), CC BY 4.0.
- **UNESCO-kernzones en beschermde monumenten**: Agentschap Onroerend Erfgoed via de Mercator WMS (www.mercator.vlaanderen.be), Gratis Open Data Licentie Vlaanderen v1.2.
- **Achtergrondkaarten**: © [OpenStreetMap](https://www.openstreetmap.org/copyright)-bijdragers (ODbL); Esri World Imagery (Esri, Maxar, Earthstar Geographics en de GIS User Community).
- Kaartbibliotheek: [Leaflet](https://leafletjs.com/).

Frontlijnen zijn overzichtslijnen (schaal 1:10.000 à 1:25.000); reken lokaal op tientallen meters afwijking. Openingsuren nagekeken op 10-10-2026; check ze ter plaatse.

## Bronnen simulatie

- Frontlijnen: Provincie West-Vlaanderen (*AGS_WO1_Frontlijnen*), zie hierboven.
- Mijnen van Mesen (plaatsen, ladingen): Wikipedia, [Mines in the Battle of Messines (1917)](https://en.wikipedia.org/wiki/Mines_in_the_Battle_of_Messines_(1917)) (naar Holt & Holt 2014, Turner 2010, Jones 2010).
- Verloop en slachtoffers: Wikipedia-artikels *First*, *Second* en *Fifth Battle of Ypres*, *Actions of St Eloi Craters*, *Battle of Mount Sorrel*, *Battle of Messines (1917)*, *Battle of Passchendaele*, *Battle of the Lys (1918)*, *Battle of Courtrai (1918)*; Passchendaele Museum (passchendaele.be); Kemmelberg 31 aug. 1918: webmatters.net en german1914.com.
- Slachtofferaantallen zijn ordes van grootte (doden, gewonden, vermisten en gevangenen samen) en vaak omstreden.
- Startpagina: citaat uit *In Flanders Fields* van John McCrae (1915, publiek domein).
