# Andrea Mandrici – Projects & Labs Portfolio

A detailed overview of key international projects, research labs, and geospatial initiatives, presented in reverse chronological order.

---

### 1. JRC-DOPA-GBDV (Knowledge Centre for Biodiversity & Digital Observatory for Protected Areas)
* **Timeframe**: 02/2015 – Present (Ongoing)
* **Locations / Geographic Scope**: Global (covering 250,000+ protected and conserved areas, 800+ terrestrial/marine ecoregions, and 190+ countries/territories).
* **Purpose / Scope**: 
  * Support the European Union’s international biodiversity policy commitments, including the **Convention on Biological Diversity (CBD)**, the **Kunming-Montreal Global Biodiversity Framework (KM-GBF Target 3)**, Aichi Target 11, and the **EU Biodiversity Strategy for 2030**.
  * Develop, maintain, and document automated spatial workflows and REST APIs for the **Digital Observatory for Protected Areas (DOPA)** and the **Global Biodiversity Data Viewer (GBDV)** hosted by the European Commission's Knowledge Centre for Biodiversity (KCBD).
  * Compute over 50 standardized, reproducible indicators measuring species irreplaceability, protected area connectivity (**ProtConn**), carbon stocks, human development pressures, land cover dynamics, and climate resilience.
* **Tools & Methodologies**: 
  * **Databases & Spatial Processing**: PostgreSQL/PostGIS (custom multi-overlapping vector pseudo-topology 'flattening' algorithms, SQL/PL/pgSQL functions), GRASS GIS (raster continuous/discrete processing, carbon pool calculations), GDAL/OGR, SpatiaLite/SQLite.
  * **Automation & Analytics**: Parallel processing using BASH and Python scripts across 64,800 global 1-degree tiles, R, STAC APIs, REST Services, GeoServer, Docker.
  * **Data Standards**: **Darwin Core (DwC)**, **INSPIRE Directive**, IUCN Red List Spatial Data mapping standards, WDPA/WD-OECM schema.
* **Data Scale / Dimensions**: 
  * Multi-terabyte global spatial repository.
  * Vector pseudo-topology intersection grid of 64,800 1-degree tiles.
  * Flattening ~26,000 IUCN global species distribution range maps (corals, sharks, amphibians, reptiles, birds, mammals) into optimized PostGIS spatial tables (e.g., 30M+ records for ~11,000 bird species).
  * Processing ~250,000 protected areas from the World Database on Protected Areas (WDPA).
* **My Role**: **Senior Data Scientist, Application Architect, GIS & Database Developer** (seconded via Arcadia SIT S.r.l. to EC-JRC Unit D.6). Responsible for designing spatial data architectures, PostGIS ETL/ELT pipelines, parallel tile processing chains, topology QA/QC protocols, species array flattening, indicator algorithm implementation (ProtConn, species richness, carbon pools), REST API query structures, and co-authoring scientific technical reports and journal papers.

---

### 2. JRC-GCCA+ (Global Climate Change Alliance Plus)
* **Timeframe**: 02/2015 – 12/2020
* **Locations / Geographic Scope**: Global, with specific focus on climate-vulnerable regions including **Least Developed Countries (LDCs)** and **Small Island Developing States (SIDS)** across Africa, Asia, the Caribbean, and the Pacific.
* **Purpose / Scope**: 
  * Support the European Union flagship initiative designed to strengthen dialogue and technical cooperation with developing countries most vulnerable to climate change.
  * Develop global multi-criteria indices and indicators measuring vulnerability, adaptation capacity, ecosystem resilience, and risk exposure to inform climate finance and evidence-based decision-making.
* **Tools & Methodologies**: 
  * **GIS & Spatial Analysis**: ArcGIS, QGIS, SpatiaLite, PostgreSQL/PostGIS, Apache web servers.
  * **WebGIS & Frontend Integration**: Leaflet, GeoJSON, JavaScript, HTML5/CSS3.
  * **Scripting**: BASH, Python, R for statistical data harmonization.
* **Data Scale / Dimensions**: 
  * Global socio-economic and bio-climatic datasets (WorldClim, ERA5, IPCC climate scenarios, disaster risk indices) covering over 70 target countries and island territories.
* **My Role**: **GIS & Database Developer / Data Analyst** (Arcadia SIT S.r.l. for EC-JRC). Responsible for calculating global climate resilience indicators, designing database schemas for multi-criteria risk scoring, harmonizing spatial indicators, and integrating spatial queries into WebGIS tools.

---

### 3. SWLRI (Strategy for Water and Land Resources of Iraq)
* **Timeframe**: 04/2011 – 12/2014
* **Locations / Geographic Scope**: National scale across **Iraq** (Tigris and Euphrates river basins, Mesopotamian Marshes, Shatt al-Arab, and agricultural plains).
* **Purpose / Scope**: 
  * Formulate Iraq's National Water Master Plan (2015–2035) for sustainable management of water and land resources under Phase 2 of the SWLRI project for the Iraqi Ministry of Water Resources (MoWR).
  * Implement Integrated Water Resources Management (IWRM) principles, assessing water supply/demand balance, flood protection, hydropower, agricultural land suitability, environmental flows, and transboundary water agreements with upstream countries.
* **Tools & Methodologies**: 
  * **GIS & Hydrological Modeling**: ArcGIS, ArcHydro, QGIS, GRASS GIS, MapServer, GeoNetwork metadata catalog.
  * **Databases & Infrastructure**: Enterprise PostgreSQL/PostGIS geodatabase, VMware ESXi 5 virtual server architecture, Apache, IIS7.
  * **WebGIS & Field Tools**: Leaflet, OpenLayers, JavaScript, Python, Trimble GPS field data collection, satellite remote sensing.
* **Data Scale / Dimensions**: 
  * Country-wide spatial database covering the entire Tigris–Euphrates basin (~437,000 km²).
  * High-resolution satellite imagery (QuickBird, WorldView, Landsat), multi-decade hydrometric and meteorological time-series datasets, soil classification, and irrigation network vector layers.
* **My Role**: **Resident Senior Expert & GIS/Database Manager** (employed by MED Ingegneria S.r.l. / SGI S.p.a., resident in Baghdad and Amman). Responsible for national geodatabase architecture design, OGC WebGIS services deployment, hydrological and agricultural spatial modeling, satellite image processing, GPS ground-truthing surveys, high-level technical advising to the Iraqi MoWR, and capacity building for ministry technical staff.

---

### 4. Oikos-East-Africa (Sustainable Land & Water Management in Northern Tanzania)
* **Timeframe**: 09/2008 – 02/2011
* **Locations / Geographic Scope**: Northern Tanzania (**Arusha Region**, **Arumeru District Council**, Maasai Steppe, Mt. Meru ecosystem).
* **Purpose / Scope**: 
  * Implement integrated sustainable development, food security, and natural resource conservation projects (including EU DCI FOOD 224-125 and Italian Ministry of Foreign Affairs 8152/Oikos/TZA).
  * Facilitate participatory **Village Land Use Plans (VLUPs)**, combat land degradation, improve food security through sustainable agricultural technologies, increase access to clean drinking water, and establish community-based wildlife conservation (Village Game Scouts).
* **Tools & Methodologies**: 
  * **Open Source GIS & Databases**: QGIS, GRASS GIS, SpatiaLite, PostgreSQL, VirtualBox.
  * **Field & Participatory Methods**: GPS field data collection, community mapping, photographic surveys, socio-economic household survey analysis, spatial Decision Support Systems (DSS).
* **Data Scale / Dimensions**: 
  * District and community level scale (~3,000 km² across Arumeru District and pilot Maasai villages like Ngabobo, Uwiro, Olkung'wado, Lekrumuni).
  * Integration of spatial wildlife transect censuses, land cover maps (Africover/LCCS), hydrographic networks, and socio-economic census data.
* **My Role**: **Resident Expert – GIS & Database Manager / IT Manager** (Istituto Oikos ONLUS / Italian Ministry of Foreign Affairs, resident in Arusha). Established the GIS Office at the Arumeru District Planning Unit, designed socio-economic and ecological spatial geodatabases, produced approved Village Land Use Plans, managed full IT server infrastructure, and delivered capacity-building training to district officers, community health workers, and Village Game Scouts.

---

### 5. Unipg / Regione Umbria (Regional Ecological Network & Wildlife Atlases)
* **Timeframe**: 08/2000 – 09/2008
* **Locations / Geographic Scope**: Regional scale across **Umbria Region**, Central Italy (~8,456 km²), including Apennine mountain ecosystems and Natura 2000 network sites.
* **Purpose / Scope**: 
  * Research, spatial modeling, and policy support for biodiversity protection, game management, and spatial planning.
  * Core outputs: **RERU (Rete Ecologica Regionale dell'Umbria)** - a multi-functional regional ecological network; published regional Atlases of Mammals, Amphibians, and Reptiles; species habitat suitability modeling (European wildcat *Felis silvestris*, Italian wolf *Canis lupus italicus*); Natura 2000 site management guidelines; Environmental Impact Assessments (EIA) for renewable energy (wind farms).
* **Tools & Methodologies**: 
  * **GIS & Statistical Modeling**: ArcView 3.x, QGIS, GRASS GIS, gvSIG, SQLite/SpatiaLite, PostgreSQL, R statistical software, BASH scripting.
  * **Field Techniques**: Ground and aerial VHF radio-tracking, GPS radio-collars, field transect surveys, radiotelemetric data management.
* **Data Scale / Dimensions**: 
  * Regional multi-taxa spatial dataset mapped across 10x10 km and 1x1 km UTM grid cells across Umbria.
  * High-resolution spatial environmental layers (elevation, slope, aspect, vegetation cover, CORINE Land Cover, hydrography, human infrastructure).
  * Long-term radiotelemetry point time series for large/medium carnivores.
* **My Role**: **Fellow Researcher & Scientific Consultant** (University of Perugia / Umbria Region / Italian Ministry of Environment). Responsible for species habitat suitability modeling, geodatabase development, cartographic layout production, scientific authoring of monographs and books, university-level lecturing, and undergraduate thesis supervision in Natural Sciences and Biology.
