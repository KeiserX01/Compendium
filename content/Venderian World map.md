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
    image: Mapas/MapaMundi/Venderian state labels.jpeg
    minZoom: -3.6
    maxZoom: 2
    defaultZoom: -3.6
    unit: Km
    scale: 0.42
    layers:
	    - Mapas/MapaMundi/Venderian cities labels.jpeg
		- Mapas/MapaMundi/Venderian state.jpeg
```
