---
layout: page
title: PakGeo
description: AI-powered Pakistan LULC and geospatial intelligence platform
img: assets/img/proj_pakgeo.jpg
importance: 1
category: research tools
related_publications: false
---

PakGeo turns satellite analysis into a sentence. Type "Show Lahore LULC for 2023" or "NDVI in Multan
from 2024-01-01 to 2024-06-30" and the system returns interactive maps, statistics and downloadable
outputs in seconds, without the usual GIS workflow.

Under the hood it combines AI agents, retrieval-augmented generation, and cloud-scale Earth
observation processing over Landsat 5/7/8/9, Sentinel-1/2, MODIS, Dynamic World and CHIRPS. Supported
products include LULC, NDVI, EVI, SAVI, NDWI, NDBI, burn severity, anomaly detection and multi-year
land dynamics across Pakistan.

**What it does**

- Natural language geospatial querying
- Instant LULC and vegetation analysis
- Multi-year satellite trend monitoring
- Urban growth and built-up analysis
- Water body and drought monitoring
- Interactive dashboards and downloadable analytics
- Petabyte-scale cloud processing, Pakistan-wide coverage

**Stack.** Google Earth Engine, FastAPI, Nuxt 3, Gemini and other LLM APIs, ChromaDB,
PostgreSQL/PostGIS, Docker.

**Where this is going.** PakGeo is a first step toward geospatial systems that interpret themselves:
Earth observation data that is continuously monitored, context-aware, and usable in real time for
climate adaptation, precision agriculture, disaster management and urban planning.
