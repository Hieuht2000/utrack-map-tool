# OSM Tile Builder

A simple browser-based tool to download OpenStreetMap tiles and build offline map images for embedded devices.

## Usage

Open [https://hieuht2000.github.io/utrack-map-tool/](https://hieuht2000.github.io/utrack-map-tool/) in your browser.

1. Search for a location or click on the map
2. Select an area using radius or draw box mode
3. Choose zoom level
4. Click Download & Build
5. Save the `.bin` flash image and `.h` header file

## Notes

- Uses OpenStreetMap data © OpenStreetMap contributors
- Maximum ~511 tiles per image (64MB flash limit)
- Zoom 14 recommended for trail/cycling use
