# Awesome-Cemetery-Management

# Top Cemetery Management Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Plot Mapping, Burial Records, Interment Tracking, GIS Cemetery Maps, Work Orders & Genealogy Search*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Cemetery Management**. These systems help cemeteries, municipalities, and memorial parks manage plot inventory, burial records, digital maps, contracts, maintenance, and public search.

**Examples** include Chronicle Cemetery, Memorial Business Systems, CemSites, Cemify, CemeteryPro, PlotBox, Legacy Mark, Memorial Mapping, CemeteryFind, and Cemetery Office (the category leaders).

**Open-source emphasis**: Full-featured commercial cemetery platforms dominate, especially for GIS mapping and multi-site operations. Strong open options exist—**Sunrise CMS**, **TEKSI Cemetery** (QGIS/PostGIS), and related GIS + records projects. This section expands those while remaining realistic about feature gaps versus enterprise SaaS.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Chronicle Cemetery](https://chronicle.software/)**  
  Cloud cemetery management focused on digital mapping, burial records, and done-for-you digitization—popular with smaller cemeteries and councils.

- **[Memorial Business Systems](https://www.memorialbusinesssystems.com/)**  
  Cemetery and memorial park management software covering records, sales, and operational workflows.

- **[CemSites](https://www.cemsites.com/)**  
  Cloud platform for cemeteries, funeral homes, and crematories—plot mapping, records, work orders, and combined death-care operations.

- **[Cemify](https://www.cemify.com/)**  
  Cemetery management with grave search, lot mapping, work orders, documents, inventory, and flexible mapping options for small to mid-sized cemeteries.

- **[CemeteryPro](https://www.cemeterypro.com/)**  
  Cemetery operations software for records, mapping, and day-to-day administrative management.

- **[PlotBox](https://www.plotbox.io/)**  
  Leading enterprise cemetery platform with GIS mapping, digitized records, contracts, multi-site support, and modules for crematory/funeral integration.

- **[Legacy Mark](https://www.legacymark.com/)**  
  Cemetery and memorial management tools focused on records, mapping, and legacy documentation.

- **[Memorial Mapping](https://www.memorialmapping.com/)**  
  Mapping-centric solutions for digitizing cemetery grounds and linking plots to records.

- **[CemeteryFind](https://www.cemeteryfind.com/)**  
  Cemetery search and management features for locating graves and maintaining public-facing records.

- **[Cemetery Office](https://www.cemeteryoffice.com/)**  
  Administrative software for cemetery offices covering records, plots, and operational tracking.

## Open-Source GitHub Projects
- **[Sunrise CMS](https://github.com/cityssm/sunrise-cms)**  
  Completely free, open-source, web-based Cemetery Management System—records, optional maps, work orders, Find a Grave integration, and unlimited users (MIT). Designed for municipalities moving off legacy systems.

- **[TEKSI Cemetery](https://github.com/teksi/cemetery)**  
  Open-source cemetery administration built on QGIS and PostGIS—plots, graves, columbaria, deceased records, sectors, and contacts with visual GIS management (GPL-3.0).

- **[OpenGravestones](https://github.com/OpenGravestones/OpenGravestones)**  
  Open-source / open-data project providing public-domain cemetery and burial data schemas based on open standards (GeoJSON-LD, Schema.org, etc.).

- **[SJC Cemitério](https://github.com/issagomesdev/sjc-cemiterio)**  
  Open cemetery management platform for municipalities—hierarchical structure (cemeteries → sectors → blocks → plots/ossuaries), death records, transfers, auditing, and reports.

- **[QGIS + PostGIS cemetery stacks](https://qgis.org/)**  
  General open-source GIS foundation used by TEKSI and similar projects for georeferenced plot maps, inventory status, and spatial analysis.

- **[Gramps and open genealogy tools](https://github.com/gramps-project/gramps)**  
  Open-source genealogy software that can complement cemetery records with family relationships and historical research.

- **[GeoJSON / OGC open mapping standards](https://geojson.org/)**  
  Open geospatial formats widely used for plot boundaries, public map layers, and integration with cemetery GIS systems.

- **[Find a Grave community data practices](https://www.findagrave.com/)**  
  Public memorial database frequently linked from open and commercial cemetery systems for photographs and community-sourced details.

- **[Self-hosted records + map open prototypes](https://github.com/)**  
  Smaller community projects combining databases, simple web UIs, and map libraries for local cemetery digitization.

- **[Documentation and municipal open-cemetery playbooks](https://github.com/cityssm/sunrise-cms)**  
  Guides and patterns for deploying Sunrise CMS or QGIS-based cemetery registers in public-sector environments.

### Additional Strong Open-Source Options
- Deploying **Sunrise CMS** for web-based records, contracts, and work orders without mandatory mapping.
- Using **TEKSI Cemetery / QGIS + PostGIS** when accurate geospatial plot maps are the priority.
- Combining open GIS standards with simple databases for low-cost digitization of historic cemeteries.
- Accepting that enterprise GIS, multi-site financials, crematory modules, polished public portals, and vendor support still favor commercial platforms (PlotBox, Chronicle, CemSites, Cemify, etc.).
- Focusing open-source efforts on transparency of records, municipal cost control, and interoperability with genealogy communities.

**Frameworks for building custom systems**: Store records in a relational database → optionally layer QGIS/PostGIS maps → expose search via a simple web UI (Sunrise-style) → link to public memorial sites. Suitable for municipalities, religious cemeteries, and volunteer-run grounds. Larger commercial and multi-site operations typically adopt SaaS cemetery platforms.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Cemetery systems handle sensitive personal and historical data. Open-source deployments require proper access control, backups, and respect for privacy and cultural practices. This list is not legal or operational advice.

---
**Made for cemetery managers, municipal staff, genealogists, and open-source advocates.**
Let's keep burial records accurate, searchable, and as open as practical.
