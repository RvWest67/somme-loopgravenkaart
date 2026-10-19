# Somme 14–18 · WOI-bezoekersgids

Nederlandstalige bezoekersgids (Leaflet, geschikt voor mobiel, werkt offline als PWA) over de Eerste Wereldoorlog aan de Somme: de Slag aan de Somme (1 juli – 18 november 1916), de Duitse terugtocht naar de Hindenburglinie (1917), het Duitse lenteoffensief (operatie Michael, maart–april 1918) en de Honderd Dagen (vanaf 8 augustus 1918).

**Startpagina:** https://rvwest67.github.io/somme-loopgravenkaart/

- **Loopgravenkaart:** `kaart.html`. Bevat monumenten, slagveldparken en kraters, musea en begraafplaatsen (coördinaten uit OpenStreetMap), en frontlijnen voor 1 juli 1916, half sept. 1916, 18 nov. 1916, de Hindenburglinie 1917, april 1918 en eind aug. 1918 (≈ schematisch). Verder: IGN LiDAR HD-reliëf, loopgraafresten (OSM), een gevaarlaag, route via Google Maps, kompas/draaien en je eigen locatie. Een plek direct openen: `kaart.html#p=lochnagar` (met lidar: `#p=lochnagar&lidar`).

- **Simulatie:** `simulatie.html`. 18 fasen van 1914 tot 1918: het bombardement en de mijnen van 1 juli 1916 (7:20 Hawthorn, 7:28 Lochnagar), Bazentin, Delville Wood, Pozières, de eerste tanks (15 sept. 1916), Thiepval, de Ancre, operatie Alberich, operatie Michael (met gas), Villers-Bretonneux, Le Hamel, Amiens (8 aug. 1918), Mont-Saint-Quentin en de Hindenburglinie.
- **Pagina's:** `tijdlijn.html`, `verhalen.html` (met foto's uit Wikimedia Commons, publiek domein/CC0), `wapens.html`, `begrippen.html`, `wistjedat.html` (met labels Legende/Omstreden), `programma.html` (1–3 dagen) en `praktisch.html` (openingstijden okt. 2026, veiligheid).

## Bronnen en licenties

- Kaartdata © [OpenStreetMap](https://www.openstreetmap.org/copyright)-bijdragers (ODbL). Plekken en loopgraafresten (`military=trench`) zijn uit OSM gehaald via Nominatim/Overpass, in oktober 2026.
- Lidar: reliëfschaduw MNT LiDAR HD, © [IGN](https://geoservices.ign.fr/lidarhd), [Licence Ouverte Etalab 2.0](https://www.etalab.gouv.fr/licence-ouverte-open-licence/).
- Luchtfoto: Esri World Imagery (Esri, Maxar, Earthstar Geographics en de GIS User Community).
- Frontlijnen: zelf schematisch getekend langs plaatsen uit de bronnen (Wikipedia-slagpagina's met de West Point Atlas-kaarten, publiek domein; Michelin-slagveldgids 1919, publiek domein). Ze zijn **benaderd (≈)**.
- Historische loopgraafkaarten (NLS, McMaster) zijn **niet** opgenomen, omdat de licentie dat niet toestaat. Er staan alleen links naar.
- Openingstijden en prijzen: nagekeken op de officiële sites in oktober 2026.
- Foto's: Wikimedia Commons (publiek domein of CC0). Maker, datum, licentie en bronpagina staan bij elke foto en in een commentaar in `img/*.svg`.
- Software: [Leaflet](https://leafletjs.com) (BSD-2), [leaflet-rotate](https://github.com/Raruto/leaflet-rotate) (GPL-3.0), zie `vendor/`.
