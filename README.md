# Ieperboog 14–18 · WOI-bezoekersgids

Nederlandstalige WOI-bezoekersgids over de Ieperboog (Leaflet, geschikt voor mobiel): kaart, simulatie, tijdlijn, verhalen en woordenlijst voor wie de plekken rond Ieper bezoekt.

**Startpagina:** https://rvwest67.github.io/ieper-loopgravenkaart/

- **Loopgravenkaart:** https://rvwest67.github.io/ieper-loopgravenkaart/kaart.html
- **Simulatie 1914–1918:** https://rvwest67.github.io/ieper-loopgravenkaart/simulatie.html (een stap openen kan direct met `#stap1` t/m `#stap8`)
- **Tijdlijn:** https://rvwest67.github.io/ieper-loopgravenkaart/tijdlijn.html (een moment openen kan direct met `#e-<datum>`, bijv. `#e-1917-06-07`; een jaar met `#j1917` of `#jna`)
- **Verhalen:** https://rvwest67.github.io/ieper-loopgravenkaart/verhalen.html (een verhaal openen kan direct met `#<id>`, bijv. `#mccrae`; een plek met `#g-boezinge`)
- **Begrippen & legers:** https://rvwest67.github.io/ieper-loopgravenkaart/begrippen.html (een begrip met `#t-<id>`, bijv. `#t-yperiet`; een leger met `#l-<id>`, bijv. `#l-nz`; een type begraafplaats met `#b-cwgc`, `#b-de`, `#b-fr`, `#b-be`)
- **Wandelen & fietsen:** https://rvwest67.github.io/ieper-loopgravenkaart/routes.html (een route met `#r-<id>`, bijv. `#r-palingbeek`; onderdelen `#makkelijk`, `#wandelen`, `#fietsen`, `#huren`, `#knooppunten`)
- **Praktisch:** https://rvwest67.github.io/ieper-loopgravenkaart/praktisch.html (onderdelen `#musea`, `#lastpost`, `#parkeren`, `#reis`, `#info`, `#eten`, `#nood`, `#weer`)
- **Dagprogramma’s:** https://rvwest67.github.io/ieper-loopgravenkaart/programma.html (onderdelen `#ieper`, `#dag1`, `#dag2`, `#dag3`, `#regen`, `#tips`)

## Bestanden

- `index.html` – startpagina met keuzemenu: Loopgravenkaart, Simulatie 1914–1918, Tijdlijn, Verhalen, Begrippen & legers, Wandelen & fietsen, Praktisch en Dagprogramma’s. De klaproos is een eigen SVG-tekening; er staan geen afbeeldingen van derden op de pagina.
- `kaart.html` – de loopgravenkaart (één bestand; frontlijnen, loopgraven en plekken zitten erin, achtergrondkaarten en WOI-luchtfoto's worden live geladen). Een plek of uitsnede openen kan met `kaart.html#lat,lng,zoom`.
- `simulatie.html` – geanimeerde tijdlijn van de Ieperboog in acht stappen (1914, gasaanval 22 april 1915, mei 1915, 1916, mijnen van Mesen 7 juni 1917, Passendale 1917, Leie-offensief april 1918, bevrijding vanaf 28 september 1918). Bevat frontlijnen uit de bron, pijlen, gaswolk en de 19 mijnkraters op hun echte plek, een korte uitleg met slachtofferaantallen en bronnen, en links naar de plekken die je nu kunt bezoeken. Pijlen, gaswolk en animaties zijn visualisaties. De lijn ‘na Mesen’ en de zone van het bevrijdingsoffensief (sept.–okt. 1918) zijn **benaderingen**; zie het ⓘ-paneel.
- `tijdlijn.html` – chronologische tijdlijn in 56 momenten, van de Duitse inval (4 augustus 1914) via de vijf slagen om Ieper tot de wederopbouw, de Menenpoort, de Last Post en de herdenkingsjaren 2014–2018 en 2023–2025. Met springknoppen per jaar, een filter per soort (slagen; gas, mijnen en nieuwe wapens; herdenking en monumenten; Ieper en dagelijks leven), landenlabels (BE, GB, Commonwealth, FR, DE), bronnummers per item en ⚠️ bij onzekere of omstreden cijfers. 📍 opent de plek op de kaart, ▶ de stap in de simulatie; elke simulatiestap linkt terug naar de tijdlijn.
- `verhalen.html` – 20 persoonlijke verhalen, gegroepeerd per plek (Boezinge, Sint-Juliaan en Langemark, Passendale, Ieper, Poperinge/Brandhoek/Lijssenthoek, Hill 60, Wijtschate/Mesen/Loker, Ploegsteert en verder weg Vladslo). Bij elk verhaal: 📍 Op de kaart, waar het past 📜 Tijdlijn en ▶ Simulatie, en de bronnen. ‘In Flanders Fields’ staat er volledig in (tekst van de uitgave van 1919, publiek domein) met een **eigen Nederlandse vertaling**. Citaten komen uit bronnen die publiek domein zijn; vertalingen zijn eigen vertalingen. ⚖️ markeert legendes en omstreden punten.
- `begrippen.html` – drie delen: (1) een doorzoekbare woordenlijst A–Z met 49 begrippen (van ‘Ieperboog’, ‘sappe’ en ‘pillbox’ tot ‘yperiet’, ‘Blighty’, ‘Known unto God’ en ‘demarcatiepaal’), met links naar kaart, tijdlijn, simulatie en verhalen; (2) **Wie vocht er?**: 13 kaarten (Belgen, Britten, Canadezen, Australiërs, Nieuw-Zeelanders, Indiërs, Zuid-Afrikanen, Ieren, Newfoundlanders, Fransen, Duitsers, Chinese Labour Corps, Amerikanen) met wanneer en waar, een kernfeit en een plek om te bezoeken; (3) **Begraafplaatsen herkennen**: Commonwealth, Duits, Frans en Belgisch, met waar je op let en tips voor je bezoek (registerkastje, bezoekersboek, Last Post). Genummerde bronnen onderaan; ⚖️ bij onzekere of omstreden punten.
- `routes.html` – **Wandelen & fietsen**: 10 bestaande, bewegwijzerde routes van de toeristische diensten (7 wandelingen, 3 fietsroutes), met de makkelijke routes bovenaan. Per route: start en parkeren, afstand, duur (geschat waar de bron niets zegt), ondergrond, een regel **Toegankelijkheid**, hoogtepunten met links naar de kaart, links naar de officiële routepagina en GPX/PDF, en een klein Leaflet-kaartje. Een routelijn staat er alleen als er een OpenStreetMap-routerelatie is waarvan de lengte klopt met de officiële afstand (6 routes); anders alleen start en hoogtepunten. Verder fietsverhuur in en rond Ieper en uitleg over fietsknooppunten. ⚖️ bij afwijkende afstanden.
- `praktisch.html` – **Praktisch** (nagekeken okt. 2026): tabel met openingstijden, prijzen, sluitingsdagen en reserveren voor 12 musea en sites (In Flanders Fields Museum, belforttoren, Passchendaele Museum, Tyne Cot, Hooge Crater, Hill 62, Bayernwald, Plugstreet, Talbot House, Lijssenthoek, Langemark, Yorkshire Trench), combitickets en museumpas, gratis plekken; Last Post (tijd, hoe vroeg, gedragsregels, kransen); parkeren in Ieper; bereikbaarheid met auto en trein; Toerisme Ieper; een korte lijst eetadressen en streekbieren; noodnummers en handige sites; weer, licht en kleding in oktober. Op mobiel wordt de tabel een lijst van kaartjes.
- `programma.html` – **Dagprogramma’s** (nagekeken okt. 2026): vijf voorbeeldprogramma’s met de auto vanuit Ieper (halve dag Ieper te voet; Dag 1 Noord & Oost/Passendale; Dag 2 Zuid: mijnen & Mesen; Dag 3/ochtend Poperinge & Lijssenthoek; regenprogramma). Per programma: tijdlijn met voorgestelde tijden en verblijfsduur, rij-/wandelafstand en -tijd per stuk (eigen OSRM-schatting op OpenStreetMap-data, zonder verkeer), lunchtips met eigen links, sluitingsdagen, een Google Maps-route met de stops in volgorde, links naar kaart, verhalen, tijdlijn en routes, een Leaflet-kaartje met genummerde stops en een ‘rustig tempo’-variant met minder stops en korte, vlakke stukjes. Plus algemene tips voor weekend en weekdagen. Geen persoonlijke gegevens of data.
- Navigatie: 🏠 op de kaart en in de simulatie gaat terug naar het menu. ‘▶ Simulatie 1914–1918’ op de kaart gaat naar de simulatie, ‘🗺 Kaart’ in de simulatie naar de kaart, en ‘Op loopgravenkaart’ bij een plek in de simulatie opent `kaart.html` op die plek. Het ⓘ-paneel van kaart en simulatie linkt naar de tijdlijn, de verhalen, de begrippen, de routes, de praktische info en de dagprogramma’s. Popups op de kaart hebben ‘📖 Verhaal’-links naar `verhalen.html#…` als er een verhaal bij die plek hoort. Opent de kaart via `#lat,lng,zoom`, dan staat er een rode cirkel op dat punt.
- Lakenhalle (kaart, KML en tijdlijn): wederopbouw vanaf 1928 (eerst het belfort, 1928–1934) tot de inhuldiging op 4 november 1967, volgens de Inventaris Onroerend Erfgoed. Sommige bronnen (Engelstalige Wikipedia) noemen 1933 als start; dat staat er als onzeker bij.
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

## Bronnen tijdlijn

De 40 bronnen staan genummerd onderaan `tijdlijn.html`, met een link bij elk item. Vooral Wikipedia (Engels en Nederlands; artikels over de slagen, gedenktekens en begraafplaatsen), CWGC (Tyne Cot), de Last Post Association (lastpost.be), Talbot House, VRT NWS (brand van de Lakenhalle), KW.be (interview met Dominiek Dendooven van het In Flanders Fields Museum, over de evacuatie in 1915 en de terugkeer in 1919) en german1914.com (Duitse cavalerie in Ieper, 7–8 oktober 1914). Geraadpleegd op 10 oktober 2026.

## Bronnen verhalen

Onder elk verhaal staan de bronnen (geraadpleegd op 10 oktober 2026). Vooral CWGC (graven en begraafplaatsen), Wikipedia (Engels, Nederlands en Duits), de Last Post Association, Talbot House, Inventaris Onroerend Erfgoed, Toerisme Poperinge, de Volksbund (over de Langemarck-mythe), 1914-1918-online, UCL (Christophe Declercq, over de Belgische vluchtelingen) en The Guardian (over de Birdcage-mijn). Omstreden punten staan in de tekst aangeduid: de datum van de Birdcage-explosie (17 juni of 17 juli 1955), het aantal executies in Poperinge, of er bij het kerstbestand werd gevoetbald, Valentine Strudwick als ‘jongste’ gesneuvelde, en wat Hitler in 1914 precies in de Ieperboog deed.

## Bronnen begrippen & legers

De 78 bronnen staan genummerd onderaan `begrippen.html` (geraadpleegd op 10 oktober 2026). Vooral Wikipedia (Engels, Nederlands en Duits), CWGC, de Volksbund, de Inventaris Onroerend Erfgoed (Saint-Charles de Potyze, Belgische militaire begraafplaatsen, Houthulst), Chemins de mémoire (Franse ossuarium Kemmelberg), de American Battle Monuments Commission (Kemmel American Monument), WO1.be en Toerisme Poperinge (Chinese site Busseboom), de South African Legion en de Last Post Association.

## Bronnen wandelen & fietsen

De 24 bronnen staan genummerd onderaan `routes.html` (geraadpleegd op 10 oktober 2026): Visit Ieper en Stad Ieper (Vestingroute, Ieperboogfietsroute, Vredesfietsroute, fietsverhuur, parkeren), Toerisme Zonnebeke (toegankelijke Tyne Cot-route, Tyne Cot-wandelroute, The Legacy), Toerisme Heuvelland (Kraters en Mijnenpad, Kemmelbergwandelroute, Bayernwald), Visit Flanders, Visit West-Vlaanderen en Provincie West-Vlaanderen (Palingbeek), KW.be, Cycling Flanders, Visit Wallonia en fietsnet.be. Routelijnen: © OpenStreetMap-bijdragers, Open Database License (ODbL), vereenvoudigd (relaties 19521422, 3551066, 1851857, 17920241, 15883334, 4149418). GPX-bestanden van de toeristische diensten worden alleen gelinkt, niet overgenomen.

## Bronnen praktisch

De 50 bronnen staan genummerd onderaan `praktisch.html` (geraadpleegd op 10 oktober 2026): de eigen sites van de musea (In Flanders Fields Museum, Passchendaele Museum, Hooge Crater, Hill 62, Plugstreet 14-18, Talbot House, Lijssenthoek), Toerisme Heuvelland (Bayernwald), Visit Ieper en Stad Ieper (Toerisme Ieper, parkeren, Last Post, belfort), de Last Post Association, de Gidsenkring Ieper-Poperinge, Volksbund, CWGC, museumPASSmusées, de eetadressen zelf, Brouwerij Kazematten, Leroy Breweries, In de Vrede, Vlaanderen.be, het Crisiscentrum, FOD Volksgezondheid, Apotheek.be en het KMI. Rijafstanden zijn eigen berekeningen met OSRM (OpenStreetMap-data); zonsopkomst en -ondergang met de Python-bibliotheek astral.

## Bronnen dagprogramma’s
Openingstijden en toegankelijkheid van de officiële sites (In Flanders Fields Museum, Passchendaele Museum, Hooge Crater, Hill 62, Toerisme Heuvelland/Bayernwald, Plugstreet, Talbot House, Lijssenthoek, Toerisme Poperinge, Toerisme Zonnebeke, Last Post Association, Stad Ieper) en van de vermelde eetadressen; volledige, genummerde lijst onderaan `programma.html`. Rij- en wandeltijden: eigen berekening met OSRM (routing.openstreetmap.de) op OpenStreetMap-data, © OpenStreetMap-bijdragers (ODbL). Onzekere of tegenstrijdige openingsuren (o.a. Koklikoo, The Famous Belvedere, Hill 62 op maandag) zijn met ⚖️ gemarkeerd.
