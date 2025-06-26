---
title: Reporting Grafana
publishDate: 2020-03-02 00:00:00
img: /assets/grafana.png
img_alt: Iridescent ripples of a bright blue and pink liquid
description: |
  🧠 Complete data project : installation and configuration of the Grafana environment,
  production and deployment of operational dashboards.
tags:
  - Grafana
  - Operationnal Reporting
  - SQL Server
  - MySQL
---

#### Context and challenges

As part of my role within the ERP team at Solustil, I was tasked with contributing to the digital transformation of the company’s industrial processes. One of the most strategic areas identified was the need for real-time visibility into production data, which until then was either inaccessible, scattered across different systems, or only available through time-consuming manual exports.

The Montélier site, which had recently migrated to a new ERP (Cegid PMI) and MES developed by Optimis, became the pilot location for implementing modern dashboards aimed at operational steering. The goal was to turn raw production data into actionable insights, accessible to the plant’s operational and strategic teams.

The challenges of the project were as follows:
	•	Enable real-time monitoring of key production indicators, including revenue, throughput, stock composition, and shop floor activity.
	•	Facilitate decision-making by transforming raw data from complex databases into clear, visual dashboards.
	•	Bridge technical complexity and business needs, making data understandable and usable by non-technical staff.
	•	Lay the foundations for scalable reporting, allowing dashboards to be quickly replicated across other production sites in the future.

To meet these challenges, I developed a comprehensive suite of dashboards using Grafana, a modern, open-source data visualization platform connected to SQL Server and MySQL databases.


#### Deployment and Outcomes

##### A - Dashboard development and customization

Several dashboards were built and deployed, focusing on the most critical operational indicators:
	•	Cumulative and daily revenue tracking, filtered by customer type (interco/external), order status, and time period.
	•	Real-time shop floor monitoring, displaying operator activity by sector, machine usage, and production progress by operation.
	•	Stock and resource composition visualization, including internal vs. external labor analysis over time.

Each dashboard required advanced SQL queries capable of joining numerous complex tables and performing sophisticated calculations. Special care was taken to optimize query performance, ensure data consistency, and provide dynamic filtering tailored to each user.


##### B - Cross-functional collaboration and training

The project involved constant collaboration with the plant director, production managers, and IT teams to align on business expectations, validate indicators, and adapt visualizations. I also conducted user training sessions to promote adoption and ensure that the dashboards could become daily decision-making tools.


##### C - Measurable impact
	•	Improved reactivity and visibility into production performance.
	•	Reduction in manual reporting efforts, freeing up time for analysis.
	•	Strengthened data culture by introducing a visual, data-driven approach to daily operations.
	•	Standardized monitoring framework that facilitates KPI tracking and cross-department alignment.


#### Outlook for the future

The Grafana dashboards were designed to be fully scalable and easily transferable to other Solustil sites. Once these sites migrate to the same ERP/MES infrastructure, dashboards will require only minimal adaptations (e.g., changes in site-specific identifiers or data sources) to be fully functional.

In the long term, this reporting system could become a central pillar of operational governance, offering Solustil a consistent, group-wide view of performance, and enabling continuous improvement through data.

Moreover, this project illustrates how data can become a strategic asset when made accessible, readable, and actionable—ushering in a culture of data-driven management across the organization.