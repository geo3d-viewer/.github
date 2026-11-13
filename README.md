# Geo3D Loader

## Overview

The Geo3D Loader is a collaborative project between the  **British Geological Survey (BGS)**  and the  **Polish Geological Institute (PGI)** designed to publish geological and subsurface datasets within the  **Geo3D Viewer**  platform. Geo3D Viewer is a web-based 3D visualisation environment that allows users to explore, interrogate, and analyse geological models through tools such as cross-sections, virtual boreholes, measurements, map overlays, and layer controls.

Version 1 of the Geo3D Loader focuses on converting  **ASCII Grid** geological surfaces into Geo3D-compatible formats, enabling the publication of interactive 3D geological models through a simple and repeatable workflow.

## Workflow

The loading process consists of two main stages:

1.  **Surface Conversion** – ASCII Grid surfaces are converted into Geo3D (.g3d) files using the  **asc-to-g3d**  tool, generating the configuration required to describe model geometry and structure.
2.  **Project Configuration** – The  **Project Configurator**  is used to define geological units, colours, stratigraphy, metadata, coordinate systems, viewer settings, and analysis tools, preparing models for publication within Geo3D Viewer.

Together these tools provide a consistent workflow for creating professional, interactive 3D geological visualisations.

## Future Development

It is envisaged that future versions of the Geo3D Loader will support a wider range of geological and geospatial data, including OBJ, GOCAD TSurf, voxel and block models, boreholes, geophysical data, geological linework, faults, cross-sections, and infrastructure datasets. The long-term vision is to provide a comprehensive publication framework that brings geological models and their supporting evidence together within a single 3D environment.

Both Geo3D Loader and Geo3D Viewer are under active development by BGS and PGI. Features, workflows, and configuration options may evolve as the platform matures, and users should refer to the latest documentation and release notes for the most up-to-date guidance.

- **Geo3D Programme:** [https://geo3d.pgi.gov.pl/en/program-geo3d](https://geo3d.pgi.gov.pl/en/program-geo3d)  
- **Geo3D Viewer:**  [https://geo3d.pgi.gov.pl/en](https://geo3d.pgi.gov.pl/en)
