Test assets for traccar/traccar-web#2016 (POI layer icons).

- `before.png`: stock Traccar 6.16.0 with `poi-test.kml`
- `after.png`: the same file and view with the PR applied
- `poi-test.kml`: icon at `<scale>0.5</scale>`, the same icon unscaled, a placemark
  with no icon, an icon URL that returns 404, a polygon and a line
- `icon.svg`: the 48 px test icon (`poi-test.kml` expects it at `http://localhost:18090/icon.svg`)
