# CoKLIMAx I: Microclimate Analysis and Visualization Toolkit

Welcome to the **CoKLIMAx I** toolkit! This project provides a comprehensive set of scripts and notebooks for processing, analyzing, and visualizing high-resolution microclimate simulation data.

---

## About the Project

Our focus is on extracting valuable insights from detailed microclimate simulations performed using **PALM-4U (PALM Model System for Urban Applications)**. PALM-4U is a powerful 3D atmospheric model designed to simulate urban environments. It accounts for complex urban features like buildings, vegetation, and intricate atmospheric processes, making it an invaluable tool for:

- **Urban Climate Research:** Understanding phenomena like urban heat islands and wind patterns.
- **Climate Adaptation Strategies:** Evaluating and informing planning decisions for more resilient urban spaces.

The output from these simulations, in netCDF4 format, is efficiently handled and explored through the documented resources within this repository. PALM-4U is an open-source model continuously developed by a consortium of institutions, notably under the German Federal Ministry of Education and Research (BMBF)'s "[UC²] - Urban Climate Under Change" program.

## Awesome Germany - Geospatial Data 🚀

A curated list of awesome resources for geospatial data related to Germany. This list aims to categorize data by common types, focusing on official and open sources.

---

### 🇩🇪 National & General Geoportals

These portals provide access to a wide variety of geospatial data and services for Germany.

* **[Geoportal.de](https://www.geoportal.de/)** - Central gateway of the Spatial Data Infrastructure Germany (GDI-DE) for searching and accessing geospatial data, services, and applications from federal, state, and local authorities. It serves as the national access point for INSPIRE-compliant data.
    * *[European Context: INSPIRE Geoportal](https://inspire-geoportal.ec.europa.eu/)* - Central access to INSPIRE data from all EU member states.
* **[GovData.de](https://www.govdata.de/)** - The data portal for Germany, providing open data from federal, state, and municipal administrations, including many geospatial datasets.
* **[Bundesamt für Kartographie und Geodäsie (BKG)](https://www.bkg.bund.de/)** - The Federal Agency for Cartography and Geodesy, a key provider of official geodetic reference data and geoinformation for Germany.
    * **[BKG Geodata Centre (GDZ)](https://gdz.bkg.bund.de/)** - Central access point for BKG's digital geodata products and services, including many open datasets.
    * **[basemap.de](https://www.basemap.de/)** - Official nationwide web map service (vector tiles & raster) based on ATKIS data from the state survey offices (AdV), provided via BKG/GDZ. Offers various map styles and is a key component of GDI-DE.
* **[OpenStreetMap Germany Extracts (Geofabrik)](https://download.geofabrik.de/europe/germany.html)** – Downloadable, community-driven OpenStreetMap data for Germany, frequently updated. Covers a vast range of features including roads, buildings, landuse, points of interest, etc.

### 🏞️ Terrain Models (DTM, DSM)

Digital Terrain Models (DTM - bare earth) and Digital Surface Models (DSM - including buildings/vegetation). Also includes laser scanning point clouds (LiDAR).

* **[BKG - Digital Terrain Models (DGM)](https://gdz.bkg.bund.de/index.php/default/digitale-geodaten/digitale-gelandemodelle.html)** - The BKG provides various DTM products for Germany, with different grid resolutions (e.g., DGM1, DGM5, DGM200). Some are open data (e.g., DGM200, DGM1000).
* **[State Survey Offices (Landesvermessungsämter)](https://www.adv-online.de/Service/Die-Laenderverwaltungen/)** - Each German federal state has its own survey office, which typically produces and distributes high-resolution DTM and DSM data. Availability as open data varies by state.
    * *Example (Baden-Württemberg): [LGL BW - Open Data DGM](https://www.lgl-bw.de/Produkte/Open-Data/Gel%C3%A4ndemodelle/)*
    * *Example (Bayern): [Geoportal Bayern - OpenGeodata](https://geodaten.bayern.de/opengeodata/)* - Provides DGM1, DGM5, DOM20 (Digital Surface Model 20cm), and laser scanning data (point clouds).
* **[Copernicus DEM](https://spacedata.copernicus.eu/collections/copernicus-digital-elevation-model)** - A global DSM (GLO-30) based on WorldDEM™ data, available via the Copernicus program. Covers Germany with a 30m resolution.

### 🛰️ Satellite Imagery & Orthophotos

Multispectral satellite imagery and georeferenced aerial photographs.

* **[BKG - Digital Orthophotos (DOP) & Satellite Data](https://gdz.bkg.bund.de/index.php/default/digitale-geodaten/digitale-orthophotos-und-satellitenbilddaten.html)** - The BKG offers access to Sentinel-2 satellite imagery (WMS services) and, in some cases, digital orthophotos. DOPs are often managed by state authorities.
* **[Copernicus Data Space Ecosystem](https://dataspace.copernicus.eu/)** - Access to data from the European Union's Copernicus programme, including Sentinel-1 (radar) and Sentinel-2 (multispectral optical) imagery covering Germany.
    * *Alternative Access: [CODE-DE (Copernicus Data and Exploitation Platform - Germany)](https://code-de.org/)* - German national platform for Copernicus data.
* **[DLR EOWEB GeoPortal](https://eoweb.dlr.de/)** - The German Aerospace Center (DLR) provides access to various satellite data archives.
* **[State Survey Offices (Landesvermessungsämter)](https://www.adv-online.de/Service/Die-Laenderverwaltungen/)** - Often the primary source for high-resolution orthophotos (DOPs) for their respective states. Open data status varies.
    * *Example (Baden-Württemberg): [LGL BW - Open Data DOP](https://www.lgl-bw.de/Produkte/Open-Data/Luftbilder-Orthophotos/)*
    * *Example (Bayern): [Geoportal Bayern - OpenGeodata](https://geodaten.bayern.de/opengeodata/)* - Offers Digital Orthophotos (DOP20 RGB/CIR, DOP40 RGB).

### 🗺️ ALKIS & ATKIS Data

Official real estate cadastre (ALKIS) and topographic (ATKIS) information systems.

* **[AdV-Online - ALKIS & ATKIS Information](https://www.adv-online.de/AAA-Projekt/ALKIS-und-ATKIS/)** - The Working Committee of the Surveying Authorities of the States of the Federal Republic of Germany (AdV) provides information about the ALKIS and ATKIS standards (part of the AAA project).
* **[State Survey Offices (Landesvermessungsämter)](https://www.adv-online.de/Service/Die-Laenderverwaltungen/)** - These are the primary holders and distributors of ALKIS and ATKIS data for their respective states. Open data availability for ALKIS is limited due to privacy, but ATKIS data (or parts of it, like Digital Landscape Models - DLM) is increasingly available as open data.
    * *Example (Baden-Württemberg): [LGL BW - Open Data ATKIS](https://www.lgl-bw.de/Produkte/Open-Data/Digitale-Landschaftsmodelle/)*
    * *Example (Bayern): [Geoportal Bayern - OpenGeodata](https://geodaten.bayern.de/opengeodata/)* - Provides ALKIS® parcel maps, actual use, administrative areas, and ATKIS® Basis-DLM.
* **[BKG - Digital Landscape Models (DLM)](https://gdz.bkg.bund.de/index.php/default/digitale-geodaten/digitale-landschaftsmodelle.html)** - The BKG derives nationwide Digital Landscape Models from ATKIS data (e.g., Basis-DLM, DLM50, DLM250). Some DLM products are open data.

### 🏗️ Building Cadastre & 3D Building Models

Data on buildings, including footprints, heights, and 3D models.

* **[BKG - 3D Building Models (LoD1, LoD2-DE)](https://gdz.bkg.bund.de/index.php/default/3d-modelle/3d-gebaeudemodelle.html)** - The BKG is developing nationwide 3D building models. LoD1-DE is available as open data.
* **[State Survey Offices & Municipalities](https://www.adv-online.de/Service/Die-Laenderverwaltungen/)** - Often the source for more detailed 3D building models (e.g., LoD2) and building footprint data (often part of ALKIS). Openness varies.
    * *Example (Baden-Württemberg - Stuttgart): [Stuttgart 3D (Official Portal Page)](https://www.stuttgart.de/leben/bauen/geoportal/stuttgart-3d.php) - City model of Stuttgart.*
    * *Example (Baden-Württemberg - State): [LGL BW - 3D Building Models](https://www.lgl-bw.de/Produkte/Open-Data/3D-Gebaeudemodelle/)*
    * *Example (Bayern): [Geoportal Bayern - OpenGeodata](https://geodaten.bayern.de/opengeodata/)* - Provides 3D Building Models (LoD2) and building outlines (Hausumringe).
* **[OpenStreetMap](https://www.openstreetmap.org/)** - A global, community-driven map. Contains building footprints and some 3D attributes, contributed by volunteers. Quality and completeness vary significantly. (See Geofabrik link in National Portals for bulk downloads).

### 🌳 Tree Cadastre

Inventories of public trees, often maintained by municipalities or state agencies.

* **Municipal Open Data Portals:** The best source for urban tree cadastres is usually city-level open data portals.
    * *Example (Stuttgart): [Open Data Portal Stuttgart](https://opendata.stuttgart.de/)* (Search for "Baumkataster" on the portal).
    * *Example (Berlin): [Open Data Portal Berlin](https://daten.berlin.de/search/type/dataset?query=baumkataster)*
    * *Example (Hamburg): [Open Data Portal Hamburg](https://transparenz.hamburg.de/treffer/-/searchresult?USE_TEXT_FOR_ORGANIZATION=true&CATEGORY_OF_ORGANIZATION_NODE_ID=2801173&QUERY=Baumkataster)* (Search on Hamburg's Transparency Portal)
    * *Example (Dortmund): [Open Data Dortmund - Baumkataster](https://open-data.dortmund.de/explore/dataset/baumkataster/)*
* **State-Level Data:** Some states may offer tree data as part of broader datasets.
    * *Example (Bayern): [Geoportal Bayern - OpenGeodata](https://geodaten.bayern.de/opengeodata/)* - Offers data for "Einzelbäume" (Individual Trees).
* **[German National Forest Inventory (Bundeswaldinventur - BWI)](https://www.bundeswaldinventur.de/)** - Provides statistical data about forests in Germany, including tree species, age, etc., but not an individual tree cadastre for urban areas. Data is available via the Thünen Institute.

### 🌱 Soil Type & Soil Class Classification

Maps and data regarding soil types, properties, and classifications.

* **[Bundesanstalt für Geowissenschaften und Rohstoffe (BGR) - Soil Information](https://www.bgr.bund.de/DE/Themen/Boden/boden_node.html)** - The Federal Institute for Geosciences and Natural Resources (BGR) is the central authority for soil science in Germany.
    * **[BGR - Soil Maps & Data](https://www.bgr.bund.de/DE/Themen/Boden/Produkte/Karten/karten_node.html)** - Provides various soil maps (e.g., BÜK1000 - Soil Map 1:1,000,000) and data. Some are available via their product center or geoportal.
    * **[BGR Geoportal](https://geoportal.bgr.de/)** - Search for soil-related datasets and services.
* **[State Geological Surveys (Staatliche Geologische Dienste)](https://www.infogeo.de/organisationen/staatliche-geologische-dienste-sgd/)** - Each federal state has a geological survey office that often produces detailed soil maps and data for their region. Open data availability varies.
* **[LUBW UDO - Umwelt-Daten und -Karten Online (Baden-Württemberg)](https://udo.lubw.baden-wuerttemberg.de/public/)** - The State Institute for Environment Baden-Württemberg (LUBW) provides extensive environmental data, including detailed soil information (maps, properties) for Baden-Württemberg.

### 🗺️ Land Use & Land Cover Classification Maps

Maps depicting the use (e.g., agricultural, urban) and physical cover (e.g., forest, water) of the land.

* **[BKG - Digital Land Cover Models (LBM-DE)](https://gdz.bkg.bund.de/index.php/default/open-data/digitales-landbedeckungsmodell-deutschland-stand-2021-lbm-de.html)** - The BKG provides the LBM-DE (Digital Land Cover Model for Germany), derived from ATKIS, remote sensing data, and other sources. Available as open data. (e.g., LBM-DE2021).
* **[CORINE Land Cover (CLC)](https://land.copernicus.eu/pan-european/corine-land-cover)** - European-wide land cover inventory, coordinated by the European Environment Agency (EEA) and implemented by member states. Data for Germany is available.
    * *German CLC data can often be found via BKG or UBA (Umweltbundesamt - Federal Environment Agency).*
* **[Umweltbundesamt (UBA) - Land Use Data](https://www.umweltbundesamt.de/daten/flaeche-boden-land-oekosysteme/flaeche)** - The Federal Environment Agency provides statistics and data related to land use and its changes in Germany.
* **[OpenStreetMap](https://www.openstreetmap.org/)** - A global, community-driven map. Contains extensive land use and land cover information contributed by volunteers. Quality and completeness vary significantly. (See Geofabrik link in National Portals for bulk downloads).

### 🌊 Water & Environmental Data

Portals and datasets focused on water resources, hydrology, and broader environmental topics.

* **[LUBW UDO - Umwelt-Daten und -Karten Online (Baden-Württemberg)](https://udo.lubw.baden-wuerttemberg.de/public/)** - Provides comprehensive environmental data for Baden-Württemberg, including water quality, water management, flood maps, protected areas, and more, in addition to soil information.
* **[WaterBLICK](https://www.wasserblick.net/)** - Information platform for hydrological data from federal and state authorities, providing access to water levels, discharge rates, and other water-related information.
* *(Many State Geological Surveys and Environmental Agencies also provide specific water and environmental data - see "State Geological Surveys" and other regional portals).*

### 🏛️ Regional & City-Specific Open Data Portals

Many German states and larger cities offer their own open data portals, which are rich sources of local geospatial information across various categories.

* **Baden-Württemberg**
    * [**Geoportal Baden-Württemberg**](https://www.geoportal-bw.de) - Central geoportal for Baden-Württemberg.
    * [**LUBW UDO - Umwelt-Daten und -Karten Online**](https://udo.lubw.baden-wuerttemberg.de/public/) - State Institute for Environment data portal (soil, water, nature conservation, etc.).
* **Bayern (Bavaria)**
    * [**Geoportal Bayern - OpenGeodata**](https://geodaten.bayern.de/opengeodata/) - Comprehensive open geodata portal for Bavaria, including DTM/DSM, orthophotos, ALKIS, 3D building models, tree data, and more.
* **Brandenburg**
    * [**Geoportal Brandenburg**](https://geoportal.brandenburg.de/de/cms/portal/geodaten/entdecken) - Central geoportal for Brandenburg.
    * [**Open Data Brandenburg (LGB)**](https://geobroker.geobasis-bb.de/gb-viewer/index.html) - Specific open data offerings (Geobroker) from the State Surveying and Geobasis Information Brandenburg (LGB).
* **Nordrhein-Westfalen (NRW)**
    * [**GEOportal.NRW**](https://www.geoportal.nrw/?activetab=portal) - The central geoportal for North Rhine-Westphalia, providing access to a wide range of geobasis and thematic geodata.
    * [**OpenGeodata.NRW**](https://www.opengeodata.nrw/) - Direct download portal for open geobasis data from NRW.
* **Rheinland-Pfalz (Rhineland-Palatinate)**
    * [**GeoPortal.rlp.de**](https://www.geoportal.rlp.de/) - Central geoportal for Rhineland-Palatinate, offering access to various geodata including ALKIS, topographic maps, orthophotos, and 3D models.
    * [**Open Data Rheinland-Pfalz (LVermGeo)**](https://lvermgeo.rlp.de/geodaten-geoshop/open-data) - Specific open data offerings from the State Office for Surveying and Geobasis Information.
* **Stuttgart**
    * [**Open Data Portal Stuttgart**](https://opendata.stuttgart.de/) - Open data for the city of Stuttgart.
* *(This is not an exhaustive list - many other states like Hessen, Berlin, Hamburg, etc., and cities have their own portals. Search for "\[State/City Name\] Open Data" or "\[State/City Name\] Geoportal").*

---

**Contributing:**
Feel free to suggest additions or corrections!
