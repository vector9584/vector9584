<p align="center"><sub><a href="README.md">English</a> · <a href="README.zh-CN.md">简体中文</a></sub></p>

<h1 align="center">Ruibing Wang <img src="https://raw.githubusercontent.com/vector9584/vector9584/main/assets/earth-spin.gif" width="44" align="absmiddle" hspace="16" alt="" /></h1>

<p align="center">
PhD Candidate · <b>Surveying and Mapping Engineering</b><br/>
School of Artificial Intelligence, China University of Geosciences, Beijing
</p>

---

## About

Spatial data on the web on one side, self-hosted services on the other.

I came into remote sensing through land administration, not through code. The thread running through the work is **3D reconstruction and geometric perception from multi-source data**: fusing UAV oblique photogrammetry with handheld laser scanning, pulling individual structures out of the fused result, and organising multi-scale models so a whole city survives being loaded at once.

The interesting part is never the point cloud. It is the seam: where one sensor's strength ends and the other's begins, how the two are registered without trusting either too much, and what "one building" even means when the whole scene arrived as a single mesh.

## Education & Experience

| Period | Position | Institution |
| :--- | :--- | :--- |
| **2026 –** | PhD, Surveying and Mapping Engineering | China University of Geosciences, Beijing · School of Artificial Intelligence |
| **2024 – 2026** | Engineer, spatial information systems | Chongqing Planning and Natural Resources Information Center |
| **2021 – 2024** | M.Eng., Surveying and Mapping Engineering | Chongqing Jiaotong University |
| **2017 – 2021** | B.Sc., Geographic Information Science | Chongqing Jiaotong University |

### PhD · Change detection on remote sensing imagery

A different question from the master's, not a continuation of it: the master's fused two sensors into one scene, this asks what changed between two.

- **Task** — change detection on remote sensing imagery
- **Supervision** — sparse LiDAR point clouds standing in for dense labels
- **Methods** — monocular depth priors and decoupled 3D geometric perception, brought to bear on that problem

### 2024 – 2026 · Chongqing Planning and Natural Resources Information Center

Core member of *Smart Industrial Land Governance*, a flagship municipal application. Parks, parcels and enterprises were documented by separate departments, so no question that crossed them could be answered.

- **Spatial foundation** — multi-source park, parcel and enterprise data integrated into one base, with standardised one-file-per-entity profiles
- **Industrial chain agglomeration** — spatial big-data analysis over that base
- **Intelligent parcel recommendation** — site selection with LLM-powered natural language interaction
- **Remote site inspection** — cloud-based review without field visits
- **Idle land governance** — monitoring and cross-departmental disposal of underutilised parcels
- **Closed loop** — `planning → supply → supervision → stock revitalisation`

### 2021 – 2024 · Master's thesis

*Multi-scale 3D model integrated expression*, Chongqing Jiaotong University.

UAV oblique photogrammetry covers large areas but loses near-ground detail wherever something occludes it. Handheld laser scanning captures precisely that detail but cannot reach rooftops and does not scale by hand. The thesis fuses the two.

- Coarse feature matching before `ICP`, cutting registration iterations — final **RMSE 1.09**
- `SAM` with text and point prompts to extract building masks, vectorised and bound to attribute records — **IoU 0.75**
- `Unreal Engine` visualisation with HLOD organisation — mean frame count **+134.78 %**, load latency **−6.25 ms**
- Applied to viewshed, inundation and contour analysis

### 2017 – 2021 · Undergraduate thesis

*Development of an intelligent early-warning platform for complex environmental and ecological risks in Chongqing.*

Fifteen indicators across natural, economic and social systems, weighted by entropy, graded into five alarm levels by natural breaks, and scored per district with a normal cloud model — 38 districts, 2015 against 2019. Risk contracted toward the urban core over those four years, with the sharpest improvement in the northeast.

## Projects

### Maintained

- **rui-calendar** — Self-hosted calendar. One dataset serves four clients — web, iOS, Android, Windows — with React + Electron + PWA in front and Baikal speaking CalDAV/CardDAV behind.
  `TypeScript` `React` `Electron` `PWA` `CalDAV`
- **nas-search** — Millisecond filename search across an entire NAS. A prebuilt SQLite FTS5 index means queries never touch the filesystem, and the tool carries zero third-party dependencies.
  `Python` `SQLite FTS5`
- **esp32-epd-photo** — Four-colour e-paper photo frame on an ESP32-S3, 800×480, JD79665AA driver. The Python side quantises photos to four colours with Atkinson or Bayer dithering and corrects EXIF orientation; the device serves its own Wi-Fi setup page.
  `C` `Python` `ESP32-S3`
- **nowen-note** — Self-hosted notes: Markdown, mind maps, task management, full-text search. Built on the croplfire/nowen-note branch and deployed with a single Docker command.
  `Docker` `Markdown` `Full-text search`
- **agent-field-notes** — Operating rules for AI agents driving physical devices, each one paired with the incident that produced it.
  `Writing` `Agents` `Post-mortems`

### Earlier

- **eco-monitoring-dashboard** — Undergraduate thesis. A single-screen dashboard for ecological health assessment across Chongqing, covering land use, risk sources and risk receptors. Plain ECharts, no build step.
  `JavaScript` `ECharts`

## Stack

**Languages**  
<kbd>Python</kbd> <kbd>TypeScript</kbd> <kbd>JavaScript</kbd> <kbd>C++</kbd> <kbd>C</kbd> <kbd>Java</kbd>

**Geospatial**  
<kbd>PostGIS</kbd> <kbd>Cesium</kbd> <kbd>Leaflet</kbd> <kbd>Mapbox GL</kbd> <kbd>ArcGIS API</kbd> <kbd>GDAL</kbd>

**3D & rendering**  
<kbd>Unreal Engine</kbd> <kbd>Three.js</kbd> <kbd>Blender</kbd> <kbd>CloudCompare</kbd>

**Infrastructure & hardware**  
<kbd>Docker</kbd> <kbd>Linux</kbd> <kbd>SQLite FTS5</kbd> <kbd>ESP32-S3</kbd>

## Elsewhere

[vector9584.github.io](https://vector9584.github.io)

---

<p align="center"><b>🐈‍⬛</b></p>

> **About the avatar**
>
> Zhenzhen. The *zhēn* in her name is the character from 「梦想成真」 — may your dreams come true.
>
> If you see a black cat walk past twice, that is a glitch in the Matrix. Look at what changed.
