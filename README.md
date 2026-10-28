<div align="center">

### 王瑞兵

中国地质大学（北京）&nbsp;·&nbsp;摄影测量与遥感&nbsp;·&nbsp;博士研究生

<img src="assets/earth-spin-light.gif" width="96" alt="Earth" />

</div>

## 关于我

研究方向聚焦**遥感影像变化检测**与**三维几何感知**，拥有两年政务空间信息化项目工程实践经历。

日常会开发自用工具，涉足自托管服务、NAS 工具、ESP32 嵌入式相关开发，偏向通过代码解决实际业务与生活场景问题。

## 研究与工作经历

| 阶段 | 时间 | 方向 |
| :--- | :--- | :--- |
| 博士 | 在读 | 单目深度先验与解耦式三维几何感知用于遥感变化检测，稀疏 LiDAR 点云作监督 |
| 工作 | 2023 – 2025 | 重庆市规划和自然资源信息中心，政务空间信息化 |
| 硕士 | — | 多源三维数据采集、点云 ICP 配准融合、SAM 图像分割 |
| 本科 | — | 生态系统模型研究，生态健康评估可视化看板 |

> [!IMPORTANT]
> **工作阶段（2023 – 2025）** — 任职于重庆市规划和自然资源信息中心，核心参与重庆「政务·产业用地智治」重大应用建设。

构建产业用地空间数字底座，归集园区、地块、企业多源业务与空间数据，落地「一园一档、一地一档、一企一档」；基于空间大数据完成产业链集聚分析，实现智能选地模型与大模型自然语言交互能力；配套云上看地、闲置低效用地监测处置、园区动态监管模块，形成 **规划 → 供应 → 监管 → 存量盘活** 的业务闭环，支撑制造业土地要素保障。

## 开源项目

### 长期维护

#### [rui-calendar](https://github.com/vector9584/rui-calendar)

自托管日历服务，同一套后端数据支撑 Web / iOS / Android / Windows 多端访问。

<details>
<summary>技术细节</summary>

- 基于 Baikal 实现 CalDAV / CardDAV 协议
- 前端 React + Electron + PWA，TypeScript 开发
- 一套数据源，四种客户端形态，不依赖任何第三方日历云

</details>

#### [nas-search](https://github.com/vector9584/nas-search)

NAS 文件名毫秒检索工具。

<details>
<summary>技术细节</summary>

- 预构建 SQLite FTS5 索引，搜索过程不遍历文件系统
- 纯 Python 实现，零第三方依赖
- 面向百万级文件名的全盘检索场景

</details>

#### [esp32-epd-photo](https://github.com/vector9584/esp32-epd-photo)

ESP32-S3 驱动四色墨水屏电子相框，适配 800×480 JD79665AA 屏幕。

<details>
<summary>技术细节</summary>

- Python 侧完成图片四色量化、Atkinson / Bayer 双抖动、EXIF 方向校正
- 设备端提供 Web 配网页面，无需 App
- 输出可直接烧写的四色位图数据

</details>

#### [nowen-note](https://github.com/vector9584/nowen-note)

自托管笔记应用，Fork 自 [croplfire/nowen-note](https://github.com/croplfire/nowen-note)。

<details>
<summary>技术细节</summary>

- 支持 Markdown 编辑、思维导图、任务管理、全文检索
- Docker 一键部署，数据完全自持

</details>

#### [agent-field-notes](https://github.com/vector9584/agent-field-notes)

AI Agent 真实设备操作的规则文档，记录运行故障案例与复盘总结。

### 过往项目

#### [eco-monitoring-dashboard](https://github.com/vector9584/eco-monitoring-dashboard)

2023 本科毕设，重庆区域生态健康评估可视化看板。

<details>
<summary>技术细节</summary>

- 基于原生 ECharts 开发，无需编译构建
- 展示土地利用、风险源、风险受体等业务指标
- 单屏呈现，面向非技术使用者

</details>

## 技术栈

| 类别 | 内容 |
| :--- | :--- |
| 编程语言 | `Python` `C++` `TypeScript` `JavaScript` `C` |
| GIS 与空间技术 | `PostGIS` `Cesium` `Leaflet` `ArcGIS API for JavaScript` |
| 其他 | `Docker` `ESP32 嵌入式开发` `Unreal Engine` |

## 链接

个人博客：[vector9584.github.io](https://vector9584.github.io)

---

做遥感变化检测、空间数据平台或自托管基础设施的同行，欢迎交流。
