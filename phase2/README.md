## Steps

- Ensure to export with WGS 84 coordinate referencing system (EPSG: 4326)
- In ArcGIS, turn off Z Values when exporting to GeoJSON, in export properties
- Remove the last z coordinate in the data (Manually searched and replaced)
- Use shared-streets extract to parse the data:
  `shst extract dc-small.gdb.geojson --metadata`
- This is the data we will use/
