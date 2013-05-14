# Esri Leaflet

Leaflet wrappers for Esri Services. Currenly only supports loading Esri map tiles.

```js
map = L.map("map").setView([37.8065289741725, -122.3631477355957], 12);
L.esri.tileLayer("Topographic").addTo(map);
```

## TileLayer

`L.esri.TileLayer(style, options)` - accepts a sting mapping to a set of Esri tiles. Valid options are `Streets`, `Topographic`, `Oceans`, `NationalGeographic`, `Gray`, `GrayLabels`, `Imagery` or `ImageryLabels`. The options parameter can be any options that you could normally pass to [L.TileLayer]http://leafletjs.com/reference.html#tilelayer.

# The Future!
* FeatureLayer