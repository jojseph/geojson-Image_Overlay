MapLibre Tracer (GeoJSON Image Overlay)

A web-based tool for overlaying floor plan images onto a map and tracing features to generate GeoJSON data. Built with MapLibre GL JS and OpenFreeMap.

🔗 Live Demo: https://jojseph.github.io/geojson-Image_Overlay/

📖 Overview

This project allows users to digitize indoor spaces or map features by overlaying reference images (such as floor plans) onto a geographical map. Users can trace specific areas (like rooms), assign metadata (Name, ID), and export the final geometry as standard GeoJSON.

✨ Features

Interactive 3D Map: Powered by MapLibre, supporting rotation, pitching, and smooth zooming.

Image Overlay: Layer floor plans or reference images over the map with adjustable opacity.

Digitizing Tools: Trace rooms and areas directly on top of the overlay.

Attribute Editing: Assign specific properties (Room Name, ID) to traced features.

GeoJSON Export: Download your traced data instantly for use in GIS software (QGIS, ArcGIS, etc.) or other applications.

🕹️ Controls

Action

Input

Pan Map

Left Click + Drag

Rotate Map

Right Click + Drag

Pitch (3D Tilt)

Ctrl + Drag

Zoom

Scroll Wheel

🚀 Usage Guide

Navigation: Use the mouse controls to position the map over your target area.

Floor Plan Settings:

Use the Floor Plan section in the sidebar to adjust the Opacity of the overlay to see the underlying map or the drawing clearly.

Tracing & Editing:

Draw or select a room/area on the map.

In the Selected Room panel, enter the Room Name and optional ID.

Export:

Click the Export GeoJSON button in the Data section to save your work locally.

🛠️ Tech Stack

Map Engine: MapLibre GL JS

Tiles: OpenFreeMap

Format: GeoJSON

📦 Local Development

To run this project locally:

Clone the repository:

git clone [https://github.com/jojseph/geojson-Image_Overlay.git](https://github.com/jojseph/geojson-Image_Overlay.git)


Navigate into the project directory:

cd geojson-Image_Overlay


Open index.html in your browser or serve it using a simple local server (e.g., Live Server for VS Code, or Python):

# Python 3
python -m http.server


📄 License

MIT License (Assuming standard open source, please verify in repo)
