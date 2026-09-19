# Awesome-Manufacturing-Intelligence

## Top Manufacturing Intelligence Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Industrial Data, OEE, Process Analytics, Edge Connectivity, Digital Twins & AI-Driven Production Insights*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Manufacturing Intelligence**. These systems connect machines and process data, calculate OEE and KPIs, enable advanced analytics, support edge-to-cloud architectures, and deliver actionable insights for continuous improvement and predictive operations.



**Examples** include Sight Machine, MachineMetrics, Litmus, Seeq, Braincube, SymphonyAI Industrial, C3 AI Manufacturing, HighByte, TrendMiner, and Ignition Cloud (the category leaders).



**Open-source emphasis**: Full industrial intelligence platforms are mostly commercial, but strong open building blocks exist. **Libre**, **OpenMES**, Node-RED, Prometheus/Grafana, InfluxDB, and related IIoT stacks allow teams to build capable manufacturing intelligence solutions. This section lists the strongest available open resources.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Sight Machine](https://sightmachine.com/)**  

  Manufacturing intelligence platform that builds a digital twin of production processes for quality, throughput, and loss analysis across plants.



- **[MachineMetrics](https://www.machinemetrics.com/)**  

  Industrial IoT and analytics platform focused on CNC and discrete manufacturing, delivering real-time machine monitoring, OEE, and operator insights.



- **[Litmus](https://litmus.io/)**  

  Edge data platform for industrial IoT that collects, normalizes, and contextualizes machine data for analytics and enterprise systems.



- **[Seeq](https://www.seeq.com/)**  

  Advanced analytics platform specialized in time-series process data for process manufacturing engineers and data scientists.



- **[Braincube](https://braincube.com/)**  

  Industrial IoT and AI platform providing process and production intelligence, digital twins, and continuous improvement tools for manufacturers.



- **[SymphonyAI Industrial](https://www.symphonyai.com/)**  

  Industrial AI and manufacturing intelligence solutions covering predictive maintenance, process optimization, and plant performance.



- **[C3 AI Manufacturing](https://c3.ai/)**  

  Enterprise AI application suite applied to manufacturing use cases including predictive maintenance, quality, and yield optimization.



- **[HighByte](https://www.highbyte.com/)**  

  Industrial data operations platform focused on contextualizing and governing OT data for IT and analytics systems (Intelligence Hub).



- **[TrendMiner](https://www.trendminer.com/)**  

  Self-service industrial analytics platform for process manufacturing, enabling search, diagnostics, and monitoring on time-series data.



- **[Ignition Cloud (Inductive Automation)](https://inductiveautomation.com/)**  

  Cloud and hybrid offerings of the Ignition industrial application platform for SCADA, IIoT, and manufacturing intelligence applications.



## Open-Source GitHub Projects

- **[Libre (Spruik)](https://github.com/Spruik/Libre)**  

  Open-source manufacturing execution and performance monitoring system built on Grafana, InfluxDB, and Postgres—focused on OEE and production analytics.



- **[OpenMES](https://getopenmes.com/)**  

  Free, open-source Manufacturing Execution System with real-time OEE, downtime analysis, production monitoring, and shop-floor integration capabilities.



- **[Node-RED](https://github.com/node-red/node-red)**  

  Flow-based open-source programming tool widely used in industrial IoT for collecting, transforming, and routing machine data into intelligence pipelines.



- **[Prometheus + Grafana industrial stacks](https://github.com/prometheus/prometheus)**  

  Open metrics collection and visualization stack frequently adapted for machine telemetry, OEE calculation, and plant dashboards.



- **[InfluxDB + Telegraf industrial collectors](https://github.com/influxdata)**  

  Open time-series database and collectors commonly used as the backbone of manufacturing intelligence and historian-style workloads.



- **[Apache StreamPipes](https://github.com/apache/streampipes)**  

  Open-source self-service industrial IoT toolbox for analyzing industrial data streams without heavy coding.



- **[OPC UA open stacks and clients](https://github.com/)**  

  Open implementations of OPC UA for securely connecting to PLCs and industrial equipment to feed intelligence platforms.



- **[Ignition open modules and community resources](https://github.com/)**  

  Community modules, scripts, and templates that extend Ignition-based manufacturing intelligence deployments.



- **[Edge and MQTT open brokers for machine data](https://github.com/)**  

  Lightweight open brokers and edge agents used to collect and forward high-frequency machine data to analytics backends.



- **[OEE calculation open libraries and samples](https://github.com/)**  

  Reference implementations and IoT samples for computing Availability, Performance, and Quality components of OEE.



### Additional Strong Open-Source Options

- Building an OEE and machine-monitoring stack with **Libre** or **OpenMES** on top of Grafana/Influx.

- Using **Node-RED + MQTT + Prometheus/Grafana** for flexible, low-cost industrial data pipelines.

- Combining open historians (Influx, Timescale) with open visualization for process and discrete intelligence.

- Accepting that advanced AI diagnostics, multi-plant digital twins, industrial data operations at scale, and turnkey vendor support still favor commercial platforms (Sight Machine, MachineMetrics, Litmus, Seeq, Braincube, C3 AI, HighByte, TrendMiner, Ignition Cloud, etc.).

- Focusing open-source efforts on data ownership, cost control, and avoiding lock-in to proprietary connectors.



**Frameworks for building custom systems**: Connect machines via OPC UA / MQTT / native protocols → contextualize data at the edge or in a data ops layer → store time-series in Influx or Prometheus → calculate OEE and KPIs → visualize in Grafana, Libre, or OpenMES → layer anomaly detection with open ML tools. Suitable for plants with internal engineering capacity. Many manufacturers still adopt commercial manufacturing intelligence platforms for faster time-to-value and supported machine integrations.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Manufacturing intelligence systems interact with production equipment and can influence operational decisions. Open-source or self-built solutions require proper OT/IT security, validation, and change control. This list is not operational or safety advice.



---

**Made for manufacturing engineers, plant managers, and industrial data teams seeking open intelligence options.**

Let's keep production intelligence actionable, transparent, and as open as practical.
