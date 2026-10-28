<div align="center">

<table>
<tr>
<td align="right" valign="middle">

<strong>Ruibing Wang</strong><br/>
China University of Geosciences, Beijing<br/>
Photogrammetry and Remote Sensing · PhD

</td>
<td align="left" valign="middle">
<img src="assets/earth-spin.webp" width="92" alt="Earth" />
</td>
</tr>
</table>

</div>

## About

Research focuses on change detection in remote sensing imagery and 3D geometric perception, with two years of engineering practice in government spatial information systems.

I write tools for myself — self-hosted services, NAS utilities, ESP32 firmware — mostly to fix problems that show up in daily work and life.

## Research and Experience

| Stage | Period | Focus |
| :--- | :--- | :--- |
| PhD | current | Monocular depth priors and decoupled 3D geometric perception for change detection in remote sensing imagery, supervised by sparse LiDAR point clouds |
| Work | 2023 – 2025 | Chongqing Planning and Natural Resources Information Center |
| MSc | — | Multi-source 3D acquisition, ICP point cloud registration and fusion, SAM segmentation |
| BSc | — | Ecosystem modelling, ecological health assessment dashboard |

### Chongqing Planning and Natural Resources Information Center &nbsp;·&nbsp; 2023 – 2025

Core contributor to *Government Affairs · Industrial Land Intelligent Governance*, a major municipal application.

Built the spatial foundation for industrial land — business and spatial data on parks, parcels and enterprises consolidated from multiple departments into one base, with a single canonical record per park, per parcel and per enterprise. On top of it: industrial chain agglomeration analysis, a site selection model with natural-language interaction, remote land inspection, monitoring and disposal of idle and low-efficiency land, and dynamic park supervision. Together they form a closed loop of **planning → supply → supervision → reactivation of stock**, supporting land element guarantees for manufacturing.

## Open Source

### Maintained

#### [rui-calendar](https://github.com/vector9584/rui-calendar)

Self-hosted calendar serving one backend dataset to web, iOS, Android and Windows clients. CalDAV / CardDAV on Baikal; React + Electron + PWA in TypeScript.

#### [nas-search](https://github.com/vector9584/nas-search)

Millisecond filename search across a NAS. A prebuilt SQLite FTS5 index answers queries without walking the filesystem. Pure Python, no third-party dependencies.

#### [esp32-epd-photo](https://github.com/vector9584/esp32-epd-photo)

Four-colour e-paper photo frame driven by an ESP32-S3, built for an 800×480 JD79665AA panel. Python performs four-colour quantisation, Atkinson / Bayer dithering and EXIF orientation correction; the device serves its own WiFi setup page.

#### [nowen-note](https://github.com/vector9584/nowen-note)

Self-hosted notes, forked from [croplfire/nowen-note](https://github.com/croplfire/nowen-note). Markdown editing, mind maps, task management, full-text search, deployed with a single Docker command.

#### [agent-field-notes](https://github.com/vector9584/agent-field-notes)

Operating rules I gave an AI agent running on real hardware, each one written down after a failure and its post-mortem.

### Earlier

#### [eco-monitoring-dashboard](https://github.com/vector9584/eco-monitoring-dashboard)

Undergraduate thesis, 2023. Ecological health assessment dashboard for the Chongqing region — land use, risk sources and risk receptors on one screen, built with plain ECharts and no build step.

## Stack

| | |
| :--- | :--- |
| Languages | `Python` `C++` `TypeScript` `JavaScript` `C` |
| GIS | `PostGIS` `Cesium` `Leaflet` `ArcGIS API for JavaScript` |
| Other | `Docker` `ESP32` `Unreal Engine` |

## Elsewhere

[Blog](https://vector9584.github.io)

---

If you work on remote sensing, spatial data platforms or self-hosted infrastructure, I would like to hear what you are building.
