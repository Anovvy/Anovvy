<div align="center">

# Bayu Nabiil

**Geospatial Data & ML Engineer · GeoAI, Remote Sensing & Production GIS Tooling**

[![Portfolio](https://img.shields.io/badge/Portfolio-0F172A?style=flat-square&logo=vercel&logoColor=white)](https://my-portfolio-olive-ten-24.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bayunabiil)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:bayunabiil1365@gmail.com)

I design and ship production-grade geospatial automation systems that bridge **Deep Learning**, **Earth Observation**, and **Desktop GIS**. My work focuses on containerized computer vision pipelines for satellite and UAV imagery, multi-sensor data ingestion workflows, and zero-conflict QGIS plugins backed by automated testing and reproducible provenance.

</div>

---

## Core Engineering Focus

| Domain | Scope & Engineering Practice |
|---|---|
| **GeoAI & Computer Vision** | Object detection and semantic segmentation on UAV orthophotos and 30 cm VHR satellite imagery using PyTorch, YOLOv8, SegFormer, DeepLabV3+, U-Net, and SAHI. |
| **Earth Observation Pipelines** | Multi-sensor satellite acquisition, cloud masking, server-side compositing, and georeferenced chipping with Google Earth Engine, GDAL, Rasterio, and Roboflow. |
| **Production GIS & MLOps** | Dependency-isolated QGIS plugins (Qt5/Qt6 & Docker backends), deterministic vector topology QA/QC, CI/CD pipelines, and SHA-256 execution provenance. |

---

## Featured Projects

<table width="100%">
<tr>
<td width="50%" valign="top">
<b><a href="https://github.com/Anovvy/vector-data-office-boy">Vector Data Office Boy</a></b><br>
<sub><code>QGIS 3.22+ / Qt6</code> · <code>PyQGIS</code> · <code>Shapely / GEOS</code> · <code>Processing Provider</code></sub><br><br>
All-in-one QGIS plugin (<code>v1.0.3</code>) for automated 4-stage polygon topology auditing and in-place geometry cleaning across spatial planning (RTRW) and land-cover datasets. Detects and repairs ring self-intersections, overlaps, internal gaps (strictly preserving outer boundaries), and slivers with automatic UTM metric normalization, atomic overwrite, 8 Processing algorithms, and zero external dependencies.
<br><br>
<a href="https://github.com/Anovvy/vector-data-office-boy">
<img src="assets/vdob_banner.gif" width="100%" alt="Vector Data Office Boy">
</a>
</td>
<td width="50%" valign="top">
<b><a href="https://github.com/Anovvy/GeoChip">GeoChip</a></b><br>
<sub><code>Python</code> · <code>Docker</code> · <code>Google Earth Engine</code> · <code>Rasterio</code> · <code>Roboflow</code></sub><br><br>
Interactive CLI (<code>v2.0</code>) and containerized pipeline for multi-satellite Earth Observation ingestion (Sentinel-2 L2A, Landsat 8/9, Sentinel-1 SAR, MODIS, NASA SRTM DEM). Supports date and cloud-cover filtering, server-side GEE compositing (Median, Q25, Mean, Min-Cloud), single-raster chipping (160–1280 px) with WGS84 <code>manifest.json</code>, and automated Roboflow Annotation Batch uploads.
<br><br>
<a href="https://github.com/Anovvy/GeoChip">
<img src="assets/geochip_banner.gif" width="100%" alt="GeoChip">
</a>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<b><a href="https://github.com/Anovvy/PalmAI_Plugin">PalmAI - QGIS Plugin</a></b><br>
<sub><code>QGIS 3.x</code> · <code>Docker</code> · <code>PyTorch</code> · <code>YOLOv8</code> · <code>DeepLabV3+</code> · <code>GHCR</code></sub><br><br>
Decoupled QGIS plugin (<code>v2.0.0</code>) powered by an isolated Docker/Virtualenv backend with automatic CUDA-to-CPU fallback for oil palm UAV imagery. Automates tree counting, crown centroid localization, 3-class health classification, and canopy-resistant road vectorization (skeletonization &amp; A* pathfinding), backed by SHA-256 verified weights, 34 automated tests, and CI/CD.
<br><br>
<a href="https://github.com/Anovvy/PalmAI_Plugin">
<img src="assets/palmai_banner.webp" width="100%" alt="PalmAI - QGIS Plugin">
</a>
</td>
<td width="50%" valign="top">
<b><a href="https://github.com/Anovvy/vhr-satellite-segmentation-pipeline">VHR Satellite Segmentation Pipeline</a></b><br>
<sub><code>Docker</code> · <code>PyTorch</code> · <code>SegFormer</code> · <code>U-Net</code> · <code>DeepLabV3+</code> · <code>GDAL</code></sub><br><br>
100% containerized deep-learning pipeline for urban land-cover segmentation from 30 cm VHR RGB satellite imagery. Benchmarks SegFormer (MiT-B0, 71.2% OA / 56.0% mIoU), U-Net (ResNet34), and DeepLabV3+ (ResNet50) via 512×512 sliding-window Gaussian blending, generating georeferenced GeoTIFFs, polygonized GeoPackages, confusion matrices, 29 tests, and SHA-256 provenance manifests.
<br><br>
<a href="https://github.com/Anovvy/vhr-satellite-segmentation-pipeline">
<img src="assets/vhr_banner.webp" width="100%" alt="VHR Satellite Segmentation Pipeline">
</a>
</td>
</tr>
</table>

---

## Additional Tools & Portfolio

| Project | Description | Stack |
|---|---|---|
| **[ArcMap LULC Keyshortcuts](https://github.com/Anovvy/ArcMap-LULC-Keyshortcuts)** | Ergonomic desktop GIS workflow toolkit bringing OpenStreetMap iD Editor home-row shortcuts (`W-A-S-D`, `1-3`, `Space`) to ArcMap 10.x wall-to-wall LULC Cut & Merge digitizing. | `Python Add-In`, `AutoHotkey v2`, `ArcMap 10.x` |
| **[Interactive Portfolio](https://my-portfolio-olive-ten-24.vercel.app)** | Web portfolio showcasing GeoAI deployments, mapping consultancy experience, and spatial engineering projects. | `JavaScript`, `HTML/CSS`, `Vercel` |

---

## Tech Stack

| Category | Technologies |
|---|---|
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white) |
| **Deep Learning & CV** | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![YOLOv8](https://img.shields.io/badge/YOLOv8-111F24?style=flat-square&logo=ultralytics&logoColor=white) ![SegFormer](https://img.shields.io/badge/SegFormer-4A154B?style=flat-square) ![DeepLabV3+](https://img.shields.io/badge/DeepLabV3%2B-2A2F35?style=flat-square) ![U-Net](https://img.shields.io/badge/U--Net-0A66C2?style=flat-square) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![Roboflow](https://img.shields.io/badge/Roboflow-6706CE?style=flat-square&logo=roboflow&logoColor=white) |
| **Geospatial & EO** | ![QGIS](https://img.shields.io/badge/QGIS-589632?style=flat-square&logo=qgis&logoColor=white) ![Google Earth Engine](https://img.shields.io/badge/Google_Earth_Engine-4285F4?style=flat-square&logo=googleearthengine&logoColor=white) ![GDAL](https://img.shields.io/badge/GDAL-497B59?style=flat-square) ![Rasterio](https://img.shields.io/badge/Rasterio-1E88E5?style=flat-square) ![GeoPandas](https://img.shields.io/badge/GeoPandas-139C5A?style=flat-square) ![Shapely](https://img.shields.io/badge/Shapely-3E82F7?style=flat-square) ![ArcGIS](https://img.shields.io/badge/ArcGIS-005E95?style=flat-square&logo=arcgis&logoColor=white) |
| **Containers, CI/CD & QA** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white) ![Ruff](https://img.shields.io/badge/Ruff-D7FF64?style=flat-square&logo=ruff&logoColor=black) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) |

---

<div align="center">

Open to collaborations on **GeoAI**, **Remote Sensing Automation**, and **Open-Source GIS Tooling**.

[Portfolio](https://my-portfolio-olive-ten-24.vercel.app) · [LinkedIn](https://www.linkedin.com/in/bayunabiil) · [Email](mailto:bayunabiil1365@gmail.com)

</div>
