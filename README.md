# Test Mock Data

Static mock and approved data artifacts for downstream application tests.

## Client Location Map

The approved client location map is committed at:

```text
public/assets/maps/client-location-map.geojson
```

The file is a GeoJSON `FeatureCollection` with one point feature per client. Each feature includes the embedded client name, physical address, phone number, email address, and related operational metadata from the approved source file.
