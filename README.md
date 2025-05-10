# Lagos-State-GeoJSON
High-resolution GeoJSON data for **Lagos State, Nigeria**. Includes geojson file, interactive map links, and purchase options. Perfect for GIS applications, urban planning, and environmental analysis.

## 📍 **Features**
- Full Local Government Area (LGA) boundaries
- Accurate polygon mapping
- Ready for integration with Mapbox, Leaflet, Google Earth, and QGIS

## 🌐 **Live Map Preview**
👉 [View the Map on Datawrapper](https://www.datawrapper.de/_/Y6NHD/)

## 💵 **Purchase the Dataset**
Support my work and get instant access to the dataset for **$2** on Gumroad:  
👉 [Buy on Gumroad](https://geodatajade.gumroad.com/l/lagosgeojson?autocomplete=true&layout=discover&query=lagos+state+&recommended_by=search&_gl=1*1kw5f3h*_ga*MjU3MTM4NzQ4LjE3NDY4MDI2OTE.*_ga_6LJN6D94N6*czE3NDY4NzA5MjYkbzQkZzEkdDE3NDY4NzM0MDUkajAkbDAkaDA.)

## 🚀 **How to Use**
You can easily integrate this data into your projects:
```javascript
map.addSource('nasarawa-data', {
  type: 'geojson',
  data: './Nasarawa state.json'
});
map.addLayer({
  id: 'nasarawa-layer',
  type: 'fill',
  source: 'nasarawa-data',
  paint: {
    'fill-color': '#088',
    'fill-opacity': 0.5
  }
});

