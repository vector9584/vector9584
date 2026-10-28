<div align="center">

<h1>Ruibing Wang <img src="assets/earth-spin.gif" width="44" alt="Earth" align="absmiddle" /></h1>

<sub>PhD Candidate in Photogrammetry and Remote Sensing</sub><br/>
China University of Geosciences, Beijing

</div>

---

## About Me

My research focuses on **remote sensing change detection** and **3D geometric perception**, with two years of engineering experience in government spatial information projects.

Outside the lab I build practical self-hosted tools, NAS utilities and ESP32 embedded projects — solving real-world problems with minimal, purpose-driven code.

## Research & Professional Experience

| Stage | Period | Focus |
| :--- | :--- | :--- |
| **PhD** | current | Change detection via monocular depth priors and decoupled 3D geometric perception, supervised by sparse LiDAR point clouds |
| **Industry** | 2023 – 2025 | Spatial data foundation and land governance, Chongqing |
| **M.Sc.** | — | Multi-source 3D acquisition, point cloud ICP registration and fusion, SAM-based image segmentation |
| **B.Sc.** | 2023 | Ecosystem modeling, ecological health assessment dashboard |

### 2023 – 2025 &nbsp;·&nbsp; Chongqing Planning and Natural Resources Information Center

> Core member of *Smart Industrial Land Governance*, a flagship municipal application.

The problem was fragmentation: parks, parcels and enterprises were documented by different departments, so no question that crossed them could be answered.

- **Spatial foundation** — multi-source park, parcel and enterprise data integrated into one base, with standardized one-file-per-entity profiles
- **Industrial chain agglomeration** — spatial big-data analysis built on that base
- **Intelligent parcel recommendation** — site selection with LLM-powered natural language interaction
- **Cloud-based remote site inspection** — review without field visits
- **Idle land governance** — monitoring and cross-departmental disposal of underutilized parcels
- **Closed loop** — `planning → supply → supervision → stock revitalization`, supporting high-quality manufacturing development

### PhD Candidate &nbsp;·&nbsp; current

Remote sensing image change detection using **monocular depth priors** and **decoupled 3D geometric perception**, with **sparse LiDAR point clouds** as supervision.

### M.Sc.

Multi-source 3D data acquisition, point cloud **ICP** registration and fusion, and applied research on **SAM**-based image segmentation.

### B.Sc. &nbsp;·&nbsp; 2023

Ecosystem modeling and development of an ecological health assessment visualization dashboard.

## Projects

### Active

#### [rui-calendar](https://github.com/vector9584/rui-calendar)

Self-hosted calendar service. One backend, four clients: Web, iOS, Android and Windows.

CalDAV/CardDAV on `Baikal`; frontend in `React` + `Electron` + `PWA`, written in `TypeScript`.

#### [nas-search](https://github.com/vector9584/nas-search)

Millisecond filename search across a NAS, without walking the filesystem.

A pre-built `SQLite FTS5` full-text index answers every query. Pure `Python`, zero third-party dependencies.

#### [esp32-epd-photo](https://github.com/vector9584/esp32-epd-photo)

Four-colour e-paper photo frame on `ESP32-S3`, built for an 800×480 `JD79665AA` panel.

The `Python` pipeline handles four-colour quantization, `Atkinson` / `Bayer` dithering and EXIF orientation correction; the device serves its own Wi-Fi setup page.

#### [nowen-note](https://github.com/vector9584/nowen-note)

Self-hosted note-taking application[^1]. Markdown editing, mind maps, task management and full-text search.

One-click `Docker` deployment.

#### [agent-field-notes](https://github.com/vector9584/agent-field-notes)

Operating rules and incident post-mortems for AI agents running on physical hardware.

### Earlier

#### [eco-monitoring-dashboard](https://github.com/vector9584/eco-monitoring-dashboard)

Undergraduate thesis, 2023. Ecological health assessment for Chongqing on one screen — land use, risk sources and risk receptors.

Vanilla `ECharts`, no build step.

## Tech Stack

| Category | Stack |
| :--- | :--- |
| **Languages** | `Python` `C++` `TypeScript` `JavaScript` `C` |
| **GIS & spatial** | `PostGIS` `Cesium` `Leaflet` `ArcGIS API for JavaScript` |
| **Other** | `Docker` `ESP32 embedded` `Unreal Engine` |

## Links

[Blog](https://vector9584.github.io) &nbsp;·&nbsp; [GitHub](https://github.com/vector9584)

---

> **About the avatar**
> This is my cat, Zhenzhen. The *zhēn* in her name is the same character from the Chinese well-wish "may your dreams come true". Hope she brings you a little good luck with whatever you're building.

[^1]: Forked from [croplfire/nowen-note](https://github.com/croplfire/nowen-note).
