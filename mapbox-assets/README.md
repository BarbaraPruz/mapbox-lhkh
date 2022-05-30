# Creating Map Style Symbol/Marker Layers in Mapbox Studio

## Create the Dataset and Tileset

1. Select `Datasets` option and `New Dataset`
2. Select `Upload` and upload a geojson file (ex. lhkh-places). Select `Confirm` and `Create` and `Start Editing`.
3. Optional - if needed, geojson data can be further customized at this time included adding new points. If updating, make sure to select `Save`.
4. Select `Export` and export new tileset. Wait for completion notification.

## Add To Map Style

1. If needed, create a new map style. If map style already exists, just open it in studio.
2. Select `Layers` and `+` to add a new layer
3. For data source, select the tileset that was previously created. If tileset isn't visible from map view, select `Go to data`.
4. In Layer - Select Data tab, set `Type` to `Symbol`.
5. In Layer - Style tab. Select `Icon` tab.
6. If icon images haven't been uploaded for this style, select `Add or remove images` and then `Upload images` and `Confirm`. Images should be svg files.
7. To use same image for all points in the layer, just select the image. Alternatively, if dataset geojson included icon properties, select `Insert a data field` and select `Icon`.
8. In Layer - Style tab select `Placement` tab. Set `Allow icon overlap` to `True`

Icons should be visible on map. You may need to refresh map.
