# GeoGram Explorer 🌍
**Developed by meedow**

GeoGram Explorer is a lightweight OSINT tool designed to automate the extraction of geolocation metadata (EXIF) from images and visualize them on an interactive map.

## 🛠 Features
- **Batch Processing**: Scans entire directories for images containing GPS metadata.
- **GPS Deciphering**: Converts raw DMS (Degrees, Minutes, Seconds) data into decimal coordinates.
- **Visual Mapping**: Generates a standalone `.html` map with markers using the Google Maps plotter (gmplot).
- **Lightweight**: Minimal dependencies, easy to integrate into larger OSINT workflows.

## 🚀 Installation
```bash
git clone https://github.com
cd geogram-explorer
pip install -r requirements.txt
```

## 📈 Usage
1. Place your target images in a folder.
2. Run the script:
   ```bash
   python geogram.py
   ```
3. Enter the folder path.
4. Open `map_results.html` in your browser to see the results.

## ⚖️ Disclaimer
This tool is for educational and ethical OSINT purposes only. Do not use for stalking or unauthorized tracking.

## 👤 Author
- **GitHub**: [@silmeedow]
