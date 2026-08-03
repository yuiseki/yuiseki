# Yui Matsumura (yuiseki)

Tokyo, Japan

- https://yuiseki.net/
- Email: yuiseki@gmail.com
- LinkedIn: https://www.linkedin.com/in/yuiseki/
- GitHub: https://github.com/yuiseki
- X: https://x.com/yuiseki_

## Summary

- Product manager for geospatial platforms, and a software engineer building user-facing products and data systems since 2010.
- Currently PM at Geolonia, a location-technology company, after seven years leading product for Gyazo at Helpfeel.
- Works across the open geospatial stack: OSM/Overpass, MapLibre, vector tiles (Planetiler, PMTiles), tile distribution, and browser-native spatial analysis (DuckDB + spatial).
- Hands-on with Python for backend and data processing, Linux/Docker, AWS serverless delivery, and REST API design.
- Proven at shaping roadmaps through research and analytics; comfortable leading small, cross-functional teams.
- Active OSS contributor (UN Open GIS, MapLibre). Built TRIDENT, planetiler-ai, and related datasets for geo-aware LLMs.

## Skill set

- Programming: Python, JavaScript, Ruby, Java; TypeScript; HTML/CSS
- Data and analytics: BigQuery, Athena, DynamoDB, MongoDB, Mixpanel
- Geospatial and GIS: OSM/Overpass API and Overpass QL, MapLibre, vector tiles/Planetiler, PMTiles, Charites, browser-side spatial analysis (DuckDB + spatial)
- Platforms and infra: Linux, Docker; AWS serverless (CloudFront, Lambda, S3); embedded Android; iOS/Android app development
- Product operations: usage-based pricing design, metering and billing integration (Stripe)
- Domains: GIS, NLP, web data mining/scraping, image processing/recognition, machine learning, deep learning, LLMs/Generative AI
- Collaboration: Git/GitHub, code review, lightweight RFCs, documentation

## Work Experience (including intern)

### Geolonia Inc., Product Manager, Business Development Department

_Mar 2026 – Present, Tokyo, Japan_

- Owns product management for Geolonia Maps, the company's map delivery platform (vector tiles, map styles, and developer APIs).
- Defines the product roadmap and usage-based pricing model, and validates the metering and billing pipeline end to end.
- Sets KPIs and works across engineering, sales, and support to turn customer requirements into shipped features.
- Acts as a hands-on PM: reviews pull requests, verifies behavior in staging environments, and builds prototypes directly.

### Helpfeel Inc., Product Manager / Software Engineer (Gyazo Team)

_Jan 2019 – Feb 2026, Tokyo, Japan_

- Led product strategy and roadmap for Gyazo, mixing user research with analytics (BigQuery, MongoDB, Mixpanel).
- Owned KPI setting and funnel analysis; ran experiments end to end to improve retention and revenue.
- Acted as a hands-on PM/engineer: feasibility spikes, small prototypes, and delivery coordination across functions.
- Guided a team of 5–6 full-time engineers (≈10 including contractors); practiced agile delivery and pair programming.
- Gyazo operates at large scale (22M+ users, 3B+ items) as a profitable standalone service.

### Cerevo Inc., Software Engineer

_Apr 2010 – Dec 2018, Tokyo, Japan_

- 2017–2018: Lumigent
  - Mobile apps (Android/iOS), MQTT/GStreamer integration; supported embedded Linux.
- 2015–2016: Tipron
  - Embedded Android and Android app; infrastructure on Linux/Docker/Shell/AWS.
- 2015: OTTO
  - Cloud and mobile stack using Node.js/Redis/Python/Flask/SQLAlchemy/MySQL; Android/iOS clients.
- 2012: Alarm BRICK
  - Server-side Python/Flask/SQLAlchemy/MySQL; front-end integration.
- 2011–2012: iConvex
  - iOS application (Objective-C).
- 2011: LiveShell
  - Server-side Python/Flask/SQLAlchemy/MySQL; front-end (Closure Library).
- 2010: CEREVO CAM
  - Server-side Python/Django/MySQL; front-end JavaScript/jQuery.

### Metacast Inc., Part-time Software Engineer (Intern/Part-time)

_2008 – 2009_

- Built server-side and front-end features for a lifelog/video service (Ruby on Rails/MySQL/JavaScript).

## Open-source and Civic Tech Contributions (selected)

- UN Open GIS Initiative / DWG-7 “Smart Maps” contributor
  - Advanced an OSS-based Hybrid GIS aligned with UN PKO field requirements; promoted open web mapping and presented on GIS × Generative AI.
  - FOIL4G (transferred to UNopenGIS org)
    - Storybook-based UI library for open data visualization; established reusable UI/API/task definitions to streamline adoption.
  - vt-optimizer-rs (donated to the UN Vector Tile Toolkit / UNVT org)
    - Rust CLI to inspect and optimize MBTiles/PMTiles vector tiles; keeps compatibility with the original vt-optimizer while adding style-based pruning, PMTiles input/output, and per-layer size statistics.
- MapLibre Organization
  - maplibre-native-slint
    - proposed a high-performance Rust/C++ map UI stack combining Slint and MapLibre Native; moved under the official org and standardized CI.
- Code for Japan
  - mapprint / 紙マップ (top contributor by commits)
    - print-optimized map site that turns Google My Maps and uMap layers into paper maps of local support information, handed out at evacuation centers and city halls during disasters.
    - built out internationalization (multilingual UI, category names, and locale fallbacks) and modernized the CI and package tooling; added a disaster map for the 2021 Atami landslide.
    - migrated the application from Nuxt 2 to Nuxt 4 and replaced the unmaintained vue-mapbox with maplibre-gl, landing regression tests for the map logic before the migration.
  - covid19-surveyor
    - crowdsourced search tool aggregating national and local COVID-19 support programs to improve discoverability.
- Personal OSS R&D
  - TRIDENT (natural language → Overpass QL → map visualization)
    - interactive assistant that turns conversation into live OpenStreetMap maps; splits the task across inner/surface/deep inference roles plus embeddings, served locally by llama.cpp with pgvector retrieval.
  - text2geoql-dataset (dataset and model for geo-aware LLMs)
    - synthetic dataset translating a TRIDENT intermediate language into Overpass QL; a LoRA fine-tune of Qwen2.5-Coder-0.5B reaches 100% (112/112) on a held-out set of queries verified to return results, and runs at 25.8 tok/s on a Raspberry Pi 5, making the pipeline viable fully offline. Dataset and GGUF model published on Hugging Face Hub.
  - charites-ai (natural language → MapLibre style)
    - generates JSON conforming to the MapLibre style specification from natural language instructions, building on @unvt/charites.
  - planetiler-ai (thematic vector tiles)
    - automated schema, tile generation, and distribution for domain-specific layers (rivers, railways, undersea cables, water stress, biodiversity).
  - planetarble (open global raster basemap)
    - reproducible pipeline building a worldwide basemap from NASA/USGS Harmonized Landsat and Sentinel-2 imagery with Landsat Collection 2 cloud backfill and NOAA ETOPO bathymetry, shipped as a single PMTiles file; the whole stack stays license-free (public domain and CC0), with an AOI overlay architecture for high-resolution insets.

## Education / Degree

- Keio University, Graduate School of Media and Governance (M.A./M.S.), 2008–2010
- Musashi Institute of Technology (now Tokyo City University), B.S. in Environmental & Information Studies, 2004–2008

## Award

- OSS Encouragement Award (Japan OSS Promotion Forum), contributor to _sinsai.info_ (2012)
- Geospatial Hackers Program, Excellence Award (2020)
- Local AI Hackathon #000, Gold Prize (2024)

## Language

- Japanese: Native
- English: Business level

## Date of Birth

- December 2, 1984
