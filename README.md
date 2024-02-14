# OXIO Geofeed

This feed is encoded in RFC 8805 format.
This data feed provides approximate geo locations for a subset of OXIO IP space and the data included in this feed may be used only for improving the accuracy of Geo:IP lookups.

## Verify Geofeed

```
poetry run python3 validate-geofeed.py < geofeed.csv
```
