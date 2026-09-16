---
title: Venderian World map
draft: false
---
```base
views:
  - type: leaflet-map
    name: map
    mapName: Venderian WorldMap
    height: 480
    image: Mapas/world-map/Venderian state labels.jpeg
    minZoom: -3.6
    maxZoom: 2
    defaultZoom: -3.6
    unit: Km
    scale: 0.42
    layers:
      - Mapas/world-map/Venderian cities labels.jpeg
      - Mapas/world-map/Venderian state.jpeg
```
