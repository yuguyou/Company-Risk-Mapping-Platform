# Asia Shell Company Risk Mapping Platform

**Expose opaque corporate structures across Asia through open data.**
**This project is created and maintained by Xiaonan – an independent developer and researcher, not an NGO or registered organisation.**

---

## Overview

This is an **open‑source, non‑commercial** web platform that identifies and visualises possible shell companies and hidden corporate networks.  
As an independent developer, I built this tool to help journalists, regulators, and the public detect red flags such as:

- Densely shared registered addresses
- Abnormal dormancy or filing patterns
- Overlapping directors/shareholders across multiple jurisdictions

All derived data and source code are released **free of charge** to promote transparency and fight financial crime.

## How It Works

1. **Data source** – [OpenCorporates](https://opencorporates.com) API (bulk data)  
2. **Processing** – Automated risk scoring based on academic and NGO red‑flag indicators  
3. **Output** – Interactive maps, company networks, and downloadable risk datasets  

## Features

- 🔍 **Risk indicators** for each company (address density, age, status anomalies)  
- 🌏 **Geographic heatmap** of potentially risky entities
- 🕸️ **Network graph** showing shared directors / addresses  
- 📊 **Open data export** (CSV/JSON) – all aggregated results under ODbL  
- 🔓 **No paywall** – everything is free for everyone, no commercial use intended

## Data & Attribution

This project uses data from **OpenCorporates** (`from OpenCorporates`), the largest open database of companies in the world.  

When displaying data, the platform will clearly show:

> **from OpenCorporates** – hyperlinked to the original company page

The derived database (risk scores, aggregated indicators) is released under the **Open Database License (ODbL)** – you are free to share, adapt, and redistribute as long as you attribute OpenCorporates and keep any adapted version under ODbL.  

The source code of the web application is licensed under the **MIT License**.

## Tech Stack

- Frontend: React / Leaflet (maps) / D3.js (graphs)  
- Backend: Python (FastAPI) / PostgreSQL + PostGIS  
- Data pipeline: Apache Airflow (scheduled API calls)  

---

## Project Identity & Status

- All source code is released under an open‑source license (MIT).
- All derived risk indicators and aggregated datasets will be published under the ODbL license.
- The platform will remain completely free for journalists, regulators, and the public – no paywalls, no advertising, no commercial use.


*This project is solely dedicated to promoting corporate transparency.*

[![License: ODbL](https://img.shields.io/badge/License-ODbL-brightgreen.svg)](https://opendatacommons.org/licenses/odbl/)
[![License: MIT](https://img.shields.io/badge/Code%20License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
