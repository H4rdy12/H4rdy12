- 👋 Hi, I’m @H4rdy12
- 👀 I’m interested in all things GIS and remote sensing 🛰 🌍 using both GIS platforms and Python integration.
- 🌱 I’m currently working on: Building DEMs using ASTER for Polar outlet glaciers and improving DEMs within internal ice sheets.

<!---
H4rdy12/H4rdy12 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<p align="center">
  <img height="24" src="https://cdn.jsdelivr.net/npm/simple-icons@v7/icons/python.svg">
  <img height="24" src="https://cdn.jsdelivr.net/npm/simple-icons@v7/icons/anaconda.svg">
  <img height="24" src="https://cdn.jsdelivr.net/npm/simple-icons@v7/icons/latex.svg">
  <img height="24" src="https://cdn.jsdelivr.net/npm/simple-icons@v7/icons/github.svg">
  <img height="24" src="https://cdn.jsdelivr.net/npm/simple-icons@v7/icons/qgis.svg">
  <img height="24" src="https://simpleicons.org/icons/postgresql.svg">
  <img height="24" src="https://cdn.jsdelivr.net/npm/simple-icons@7.21.0/icons/duckdb.svg">
  <!-- <img height="24" src="https://simpleicons.org/icons/c.svg">
  <img height="24" src="https://simpleicons.org/icons/cplusplus.svg"> -->
</p>

## Projects:
[TerraTexture](https://h4rdy12.github.io/TerraTexture/): This project explores generating textured relief basemaps by combining open-source DEMs with basemap imagery from Contextily. DEMs are pulled directly from open-source STAC endpoints (ArcticDEM, REMA, and OpenTopography), and terrain texture is derived from surface curvature and hillshade, blended with soft-light and luminosity techniques to make ridges and channels stand out. As part of the project, I experimented with an optional, configurable Rust-accelerated backend for the hillshade, curvature, and data-burning steps, giving both memory and speed improvements, and used it as a learning opportunity to explore how best to stream DEMs efficiently across networks.
  
[DEMSquad](https://h4rdy12.github.io/DEMSquad/): Developed as part of my PhD, this package coregisters polar ice sheet DEMs with satellite altimetry. It encapsulates altimetry retrieval from ERS, Envisat, ICESat, ICESat-2, CryoTEMPO Land Ice, and CryoTEMPO EOLIS, and supports chaining multiple coregistration methods together, alongside tools for visualising and validating coregistration performance. The code is now used in the [GLOBE](https://cpom.org.uk/globe/) (Greenland Subglacial Lake Observatory) project to support the [detection of Greenland's active subglacial lakes](https://research.lancaster-university.uk/en/publications/optimising-detection-of-greenlands-active-subglacial-lakes-with-d/).

<!--
## Learning Projects (ongoing)
I'm currently building a couple of projects to explore cloud-native geospatial data engineering system design:

[Altimetry Lakehouse](<GitHub link>) · [live demo](<demo link>): An elevation data platform for ICESat-2, built around an incremental, idempotent ETL pipeline that converts NASA HDF5 granules into partitioned, Hilbert-sorted GeoParquet on object storage, catalogued with DuckLake. The project explores how far data layout alone can improve spatial query performance, and serves the same data three ways (in-browser DuckDB-WASM, a FastAPI service, and PostGIS) to compare and document the trade-offs between them.
  TODO (add once measured): cuts bounding-box query time from [X s] to [Y s] and bytes read by [Z×] versus the raw files.

[Greenland Terrain Basemap](<GitHub link>) · [live demo](<demo link>): A 2D/3D web map of Greenland, built on a tiling pipeline that produces seamless relief and 3D terrain tiles from ArcticDEM and Sentinel-2, packaged as PMTiles. Tiles are served serverless from Cloudflare R2 through an edge Worker, with builds automated using GitHub Actions.
  TODO (add once measured): serves [N] tiles for ~$[cost]/month.
-->

  <picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/H4rdy12/H4rdy12/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/H4rdy12/H4rdy12/output/github-contribution-grid-snake.svg" />
  <img alt="github-snake" src="github-snake.svg" />
</picture>


