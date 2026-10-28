<h1 align="left">Ruibing Wang <img src="assets/earth-spin.gif" width="46" align="right" alt="" /></h1>

PhD Candidate · **Surveying and Mapping Engineering**  
School of Artificial Intelligence, China University of Geosciences, Beijing

---

## About

A crater's shape is three-dimensional: wall slope, floor roughness, central-peak height, rim relief. Most catalogues still describe it in two — circularity, diameter, depth-to-diameter ratio.

I am working on measuring that geometry properly on the Moon: fusing laser altimetry and stereo imagery into DEMs, extracting 3D morphometric indices from them, and using the fused description to classify craters and explain where they cluster.

Before this I spent two years building government spatial information systems, and before that a master's degree fusing drone photogrammetry with handheld laser scans.

## Education & Experience

| Period | Position | Institution |
| :--- | :--- | :--- |
| **2026 –** | PhD, Surveying and Mapping Engineering | China University of Geosciences, Beijing · School of Artificial Intelligence |
| **2024 – 2026** | Engineer, spatial information systems | Chongqing Planning and Natural Resources Information Center |
| **2021 – 2024** | M.Eng., Surveying and Mapping Engineering | Chongqing Jiaotong University |
| **2017 – 2021** | B.Sc., Geographic Information Science | Chongqing Jiaotong University |

### PhD · Lunar crater morphology

Three problems, one pipeline.

- **Morphometry** — extract quantitative 3D indices (depth, volume, mean wall slope, asymmetry, central-peak relative height, rim undulation) from fused DEMs rather than 2D imagery
- **Classification** — combine geometry with multispectral, thermal and gravity features, then cluster or classify into morphologic types and tie them back to degradation stage
- **Spatial distribution** — point-pattern analysis where distance is measured along terrain, not on a flat map; separate primary craters, secondaries and volcanic collapses

Data: `LOLA` laser altimetry, `LROC NAC` stereo, multispectral and gravity. Methods: DEM fusion, `SAM`-style segmentation, deep learning on fused geometry.

### 2024 – 2026 · Chongqing Planning and Natural Resources Information Center

Core member of *Smart Industrial Land Governance*, a flagship municipal application. Parks, parcels and enterprises were documented by different departments, so no question that crossed them could be answered.

- **Spatial foundation** — multi-source park, parcel and enterprise data integrated into one base, with standardised one-file-per-entity profiles
- **Industrial chain agglomeration** — spatial big-data analysis over that base
- **Intelligent parcel recommendation** — site selection with LLM-powered natural language interaction
- **Remote site inspection** — cloud-based review without field visits
- **Idle land governance** — monitoring and cross-departmental disposal of underutilised parcels
- **Closed loop** — `planning → supply → supervision → stock revitalisation`

### 2021 – 2024 · Master's thesis

*Multi-scale 3D model integrated expression.* UAV oblique photogrammetry covers large areas but loses near-ground detail under occlusion; handheld laser scanning captures exactly that detail but cannot reach rooftops. The thesis fuses the two.

- Coarse feature matching before `ICP`, cutting registration iterations — final **RMSE 1.09**
- `SAM` with text and point prompts to extract building masks, vectorised and bound to attribute records — **IoU 0.75**
- `Unreal Engine` visualisation with HLOD organisation — mean frame count **+134.78 %**, load latency **−6.25 ms**
- Applied to viewshed, inundation and contour analysis

### 2017 – 2021 · Undergraduate

Geographic Information Science. Final project: an ecological health assessment dashboard for Chongqing — land use, risk sources and risk receptors on one screen.

## Projects

<table>
<tr>
<td width="50%" valign="top">

<b><a href="https://github.com/vector9584/rui-calendar">rui-calendar</a></b><br/>
Self-hosted calendar. One backend, four clients: Web, iOS, Android and Windows.<br/>
<sub>TypeScript · React · Electron · PWA · Baikal / CalDAV</sub>

</td>
<td width="50%" valign="top">

<b><a href="https://github.com/vector9584/nas-search">nas-search</a></b><br/>
Millisecond filename search across a NAS without walking the filesystem — a pre-built FTS5 index answers every query.<br/>
<sub>Python · SQLite FTS5 · zero dependencies</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<b><a href="https://github.com/vector9584/esp32-epd-photo">esp32-epd-photo</a></b><br/>
Four-colour e-paper photo frame for 800×480 JD79665AA panels, with on-device Wi-Fi setup.<br/>
<sub>ESP32-S3 · C++ · Python · Atkinson / Bayer dithering</sub>

</td>
<td width="50%" valign="top">

<b><a href="https://github.com/vector9584/nowen-note">nowen-note</a></b><br/>
Self-hosted notes: Markdown, mind maps, task management, full-text search, one-command Docker deploy.<br/>
<sub>TypeScript · SQLite · Docker</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<b><a href="https://github.com/vector9584/agent-field-notes">agent-field-notes</a></b><br/>
Operating rules and incident post-mortems from running AI agents on real hardware — what broke, what fixed it.<br/>
<sub>Markdown · field reports</sub>

</td>
<td width="50%" valign="top">

<b><a href="https://github.com/vector9584/eco-monitoring-dashboard">eco-monitoring-dashboard</a></b><br/>
Ecological health assessment for Chongqing on a single screen. Undergraduate thesis, 2021.<br/>
<sub>JavaScript · ECharts · no build step</sub>

</td>
</tr>
</table>

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

> **About the avatar**
>
> This is my cat, Zhenzhen. The *zhēn* in her name is the same character from the Chinese well-wish "may your dreams come true". Hope she brings you a little good luck with whatever you're building.
