MapLibre Tracer (GeoJSON Image Overlay)

A web-based tool for overlaying floor plan images onto a map and tracing features to generate GeoJSON data. Built with MapLibre GL JS and OpenFreeMap.

🔗 Live Demo
https://jojseph.github.io/geojson-Image_Overlay/

📖 Overview

MapLibre Tracer allows users to digitize indoor spaces or geographic features by placing reference images (such as building floor plans) onto a map. Users can trace polygons, edit attributes, and export the final features as standard GeoJSON files for use in GIS applications.

✨ Features

Interactive 3D Map
Powered by MapLibre GL JS, supporting smooth zooming, rotation, and pitch.

Image Overlay
Import and display floor plan or reference images with adjustable opacity.

Digitizing Tools
Trace rooms, buildings, or any areas directly over the overlay.

Attribute Editing
Assign metadata such as Room Name and ID.

GeoJSON Export
Save your traced work instantly for use in software like QGIS, ArcGIS, and more.

🕹️ Controls
Action	Input
Pan Map	Left Click + Drag
Rotate Map	Right Click + Drag
Pitch (3D Tilt)	Ctrl + Drag
Zoom	Mouse Scroll Wheel
🚀 Usage Guide
1. Navigation

Use the mouse controls to move and orient the map to the target location.

2. Floor Plan Settings

Use the sidebar to adjust the overlay image settings, such as:

Opacity – for improving map or drawing visibility.

3. Tracing & Editing

Draw or select a room/area.

In the Selected Room panel, enter metadata (e.g., Room Name, ID).

4. Export

Click Export GeoJSON in the Data section to download your geometry.

🛠️ Tech Stack

Map Engine: MapLibre GL JS

Tiles: OpenFreeMap

Output Format: GeoJSON

📦 Local Development

To run this project locally:

# Clone the repository
git clone https://github.com/jojseph/geojson-Image_Overlay.git

# Enter the directory
cd geojson-Image_Overlay

Open index.html in your browser, or run a lightweight local server:

# Python 3
python -m http.server
