# Important 

This dataset and contents are a fork from the original set at https://huggingface.co/datasets/cjc0013/Ufo_data_clustered

# Dataset Preview


| id      | airport_ref | airport_ident | type      | description             | frequency_mhz |
|---------|-------------|----------------|-----------|--------------------------|----------------|
| 70,518  | 6,528       | 00CA           | CTAF      | CTAF                     | 122.9          |
| 307,581 | 6,589       | 01FL           | ARCAL     | null                     | 122.9          |
| 75,239  | 6,589       | 01FL           | CTAF      | CEDAR KNOLL TRAFFIC      | 122.8          |
| 60,191  | 6,756       | 04CA           | CTAF      | CTAF                     | 122.9          |
| 59,287  | 6,779       | 04MS           | UNIC      | UNICOM                   | 122.8          |
| 60,682  | 6,784       | 04NV           | UNIC      | UNICOM                   | 123            |
| 60,091  | 6,812       | 05CL           | CTAF      | CTAF                     | 122.9          |
| 63,835  | 6,853       | 05UT           | UNIC      | UNICOM                   | 122.8          |
| 70,676  | 6,868       | 06FA           | APP       | PALM BEACH APP           | 124.6          |
| 70,677  | 6,868       | 06FA           | GND       | GND                      | 121.65         |
| 70,678  | 6,868       | 06FA           | TWR       | TWR                      | 120.4          |
| 65,868  | 6,887       | 06MO           | CTAF      | CTAF                     | 122.9          |
| 71,176  | 6,924       | 07FA           | UNIC      | UNICOM                   | 122.7          |
| 66,637  | 6,943       | 07MT           | CNTR      | SALT LAKE CITY CNTR      | 126.85         |
| 69,383  | 6,954       | 07TE           | CNTR      | HOUSTON CNTR             | 126.625        |
| 61,673  | 7,008       | 08TE           | UNIC      | UNICOM                   | 122.8          |
| 61,013  | 7,019       | 09CL           | CTAF      | CTAF                     | 122.9          |
| 59,566  | 7,021       | 09FA           | UNIC      | UNICOM                   | 122.8          |
| 68,176  | 7,054       | 09TS           | CNTR      | ALBUQUERQUE CNTR         | 132.65         |
| 59,735  | 7,094       | 0AZ2           | UNIC      | UNICOM                   | 122.95         |
| 328,741 | 7,102       | 0C2            | CTAF      | null                     | 122.9          |
| 62,825  | 7,116       | 0CA9           | CTAF      | CTAF                     | 122.9          |
| 59,296  | 7,213       | 0ID2           | ARTC      | SALT LAKE CITY CNTR      | 128.35         |
| 60,367  | 7,542       | 0TE4           | UNIC      | CTAF/UNICOM              | 122.8          |
| 59,580  | 7,543       | 0TE5           | CNTR      | HOUSTON CNTR             | 126.625        |
| 59,437  | 7,545       | 0TE7           | UNIC      | UNICOM                   | 122.8          |
| 67,677  | 7,569       | 0TX1           | UNIC      | UNICOM                   | 123.05         |
| 59,357  | 7,712       | 11II           | CNTR      | INDIANAPOLIS CNTR        | 134.85         |
| 59,358  | 7,712       | 11II           | CTAF      | CTAF                     | 126.2          |
| 59,360  | 7,712       | 11II           | MISC      | RNG CON                  | 38.9           |
| 59,359  | 7,712       | 11II           | MISC      | ANG RNG CON              | 138.25         |
| 71,354  | 7,781       | 12NC           | APP       | CHERRY POINT APP         | 119.75         |
| 69,316  | 7,789       | 12OK           | UNIC      | UNICOM                   | 123            |
| 70,478  | 7,838       | 13NC           | APP       | CHERRY POINT APP         | 119.35         |
| 333,203 | 7,838       | 13NC           | CTAF      | null                     | 322.1          |
| 70,367  | 7,898       | 14NC           | A/D       | CHERRY POINT APP         | 119.35         |
| 66,604  | 7,917       | 14TS           | CNTR      | HOUSTON CNTR             | 126.625        |
| 59,174  | 7,928       | 15AR           | UNIC      | RDO CTL                  | 122.725        |
| 68,311  | 7,934       | 15FL           | UNIC      | UNICOM                   | 123            |
| 60,025  | 8,028       | 16X            | CNTR      | FORT WORTH CNTR          | 127.45         |
| 70,821  | 8,082       | 18AZ           | UNIC      | UNICOM                   | 122.975        |
| 67,241  | 8,117       | 18TA           | CNTR      | HOUSTON CNTR             | 126.625        |
| 62,339  | 8,118       | 18TE           | UNIC      | UNICOM                   | 122.8          |
| 61,636  | 8,205       | 1AZ0           | UNIC      | UNICOM                   | 122.725        |
| 67,423  | 8,222       | 1CA1           | CTAF      | CTAF                     | 122.9          |
| 59,235  | 8,233       | 1CD2           | APP       | DENVER APP               | 119.3          |
| 59,171  | 8,297       | 1GA0           | UNIC      | UNICOM                   | 122.725        |
| 70,225  | 8,486       | 1MS8           | APP       | MERIDIAN APP             | 31.48          |
| 298,625 | 8,732       | 1WA6           | CTAF      | Fall City Traffic        | 122.9          |
| 59,128  | 8,769       | 1XS8           | CNTR      | HOUSTON CNTR             | 126.625        |
| 70,996  | 8,787       | 20GA           | MULT      | MULT                     | 122.9          |
| 63,036  | 8,924       | 22XS           | A/G       | TWR                      | 143.35         |
| 63,037  | 8,924       | 22XS           | ATIS      | ATIS                     | 118.8          |
| 63,038  | 8,924       | 22XS           | INFO      | RNG CTL                  | 30.45          |
| 63,039  | 8,924       | 22XS           | MISC      | FORT HOOD FLT FLW        | 38.75         |
| 63,040  | 8,924       | 22XS           | OPS       | GRAY OPS                 | 38.7           |
| 63,041  | 8,924       | 22XS           | PMSV      | PMSV GRAY METRO          | 41.2           |
| 63,042  | 8,924       | 22XS           | TWR       | GRAY TWR                 | 120.75         |
| 60,377  | 8,982       | 23XS           | A/G       | LONGHORN AUX TWR         | 143.35         |
| 60,378  | 8,982       | 23XS           | ATIS      | ATIS                     | 118.8          |
| 60,379  | 8,982       | 23XS           | INFO      | RNG CTL                  | 30.45          |
| 60,380  | 8,982       | 23XS           | MISC      | FORT HOOD FLT FLW        | 38.75          |
| 60,381  | 8,982       | 23XS           | OPS       | GRAY OPS                 | 38.7           |
| 60,382  | 8,982       | 23XS           | PMSV      | PMSV GRAY METRO          | 41.2           |
| 60,383  | 8,982       | 23XS           | TWR       | GRAY TWR                 | 120.75         |
| 67,720  | 8,990       | 24CL           | CTAF      | CTAF                     | 122.9          |
| 60,694  | 9,068       | 25NC           | MULT      | MULTICOM                 | 122.9          |
| 60,360  | 9,078       | 25TA           | CNTR      | HOUSTON CNTR             | 126.625        |
| 64,363  | 9,080       | 25TS           | CNTR      | ALBUQUERQUE CNTR         | 132.65         |
| 61,802  | 9,138       | 27AZ           | CTAF      | CTAF                     | 122.9          |
| 59,707  | 9,191       | 28CL           | CTAF      | CTAF                     | 122.8          |
| 63,365  | 9,223       | 28TA           | CNTR      | HOUSTON CNTR             | 126.625        |
| 63,366  | 9,223       | 28TA           | UNIC      | UNICOM                   | 122.8          |
| 69,599  | 9,236       | 29AZ           | UNIC      | UNICOM                   | 122.8          |
| 64,791  | 9,277       | 29TX           | CNTR      | FORT WORTH CNTR          | 127.45         |
| 62,214  | 9,354       | 2CL9           | CTAF      | CTAF                     | 122.9          |
| 71,454  | 14,060      | 2CN4           | CTAF      | CTAF                     | 122.9          |
| 333,743 | 9,368       | 2D7            | APP/DEP   | CLEVELAND APP/DEP        | 125.5          |
| 333,742 | 9,368       | 2D7            | CTAF      | CTAF/UNICOM              | 122.8          |
| 62,263  | 20,770      | 2IG4           | UNIC      | UNICOM                   | 122.8          |
| 60,042  | 9,696       | 2OR1           | UNIC      | UNICOM                   | 122.8          |
| 67,219  | 9,772       | 2TA6           | CNTR      | FORT WORTH CNTR          | 127.45         |
| 63,137  | 9,774       | 2TA8           | CNTR      | HOUSTON CNTR             | 126.625        |
| 71,475  | 9,784       | 2TE8           | CNTR      | HOUSTON CNTR             | 126.625        |
| 70,329  | 9,809       | 2TX3           | CNTR      | HOUSTON CNTR             | 126.625        |
| 60,402  | 9,810       | 2TX4           | CNTR      | HOUSTON CNTR             | 126.625        |
| 69,995  | 9,835       | 2VG2           | UNIC      | UNICOM                   | 122.725        |
| 60,635  | 9,880       | 2XA0           | CNTR      | FORT WORTH CNTR          | 127.45         |
| 60,636  | 9,880             | 2XA0        | CTAF      | CTAF                     | 122.9          |
| 70,047  | 9,891       | 2XS3           | CNTR      | FORT WORTH CNTR          | 127.45         |
| 67,073  | 9,893       | 2XS5           | CNTR      | HOUSTON CNTR             | 126.625        |
| 61,432  | 9,985       | 31VA           | UNIC      | UNICOM                   | 122.75         |
| 68,592  | 10,080      | 34AZ           | UNIC      | UNICOM                   | 122.8          |
| 67,703  | 10,175      | 36CA           | CTAF      | CTAF                     | 122.9          |
| 71,005  | 10,177      | 36CN           | CTAF      | CTAF                     | 122.9          |
| 61,623  | 10,214      | 36WI           | CTAF      | CTAF                     | 122.9          |
| 61,624  | 10,214      | 36WI           | MISC      | LIGHT                    | 122.6          |
| 71,572  | 10,265      | 38AZ           | AWOS      | AWOS 2                   | 119.225        |
| 71,573  | 10,265      | 38AZ           | CTAF      | CTAF                     | 122.8          |
| 58,969  | 10,268      | 38CA           | UNIC      | UNICOM                   | 122.8          |


# UFO Sightings – Cleaned & Unified Dataset (~327k rows)

This dataset merges several publicly available UFO sighting datasets from Kaggle into one cleaned, standardized, and enriched file. The goal is simply to provide a consolidated dataset instead of many fragmented sources with inconsistent formatting.

This release contains a single `JSONL` file with approximately 327,000 records.

No private or identifying information was present in the original data.

# 📦 Source

## All entries originate from publicly available UFO sighting datasets on Kaggle. Each row corresponds to a single reported sighting. Source Files located in source folder
#### 🧹 Cleaning / Normalization Performed

All rows in this unified file were standardized using the same basic rules:

- timestamps parsed and converted into a consistent t_utc (ISO-8601, UTC)
- city/state/country fields harmonized where possible
- latitude/longitude coerced to floats
- basic HTML/unicode cleanup in free-text descriptions (text)
- invalid or fully unparseable rows removed
- source field preserved as src

No interpretation or filtering based on content was performed.

# ✨ Added Contextual Fields

A small number of lightweight “sidecar” fields were added based on timestamp + coordinates:

- `moon_illum` — moon illumination fraction
- `moon_alt_deg` — moon altitude in degrees
- `nearest_airport_code` — closest airport (ICAO)
- `nearest_airport_km` — distance to that airport in km
- `wx_bucket` — rough weather bucket (coarse category)

These values are approximate and should be treated as exploratory metadata only.

# 🧩 Clustering Fields (Included in the File)
The dataset includes two fields that come from text-similarity grouping:

- `cluster_id` — numeric label
- `prob` — membership confidence

These reflect text similarity, not verified categories or event types. They are included because they were already part of the cleaned file.

# 📝 Field Reference
Each row has the following structure (example):

```json
{
  "uid": "scrubbed/row327047",
  "t_utc": "2013-09-09T09:51:00.000Z",
  "lat": 32.7152778,
  "lon": -117.1563889,
  "text": "2 white lights zig-zag over Qualcomm Stadium...",
  "src": "scrubbed",
  "city": "san diego",
  "state": "ca",
  "country": "US",

  "cluster_id": 725,
  "prob": 1.0,

  "moon_illum": 0.163603127,
  "moon_alt_deg": -67.0003509521,
  "nearest_airport_km": 3.7174715996,
  "nearest_airport_code": "KSAN",
  "reports_z": null,
  "wx_bucket": "unknown"
}
```

# Field descriptions

| Field                | Type    | Notes                                           |
|----------------------|---------|-------------------------------------------------|
| uid                  | string  | Stable row identifier                           |
| t_utc                | string  | Event timestamp, ISO-8601 UTC                   |
| lat, lon             | float   | Approximate coordinates                         |
| city, state, country | string  | Cleaned location fields (best-effort)           |
| text                 | string  | Free-text sighting description                  |
| src                  | string  | Original Kaggle dataset source                  |
| cluster_id           | int     | Text-similarity cluster (for research use only) |
| prob                 | float   | Cluster membership probability                  |
| moon_illum           | float   | Moon illumination (0–1)                         |
| moon_alt_deg         | float   | Moon altitude in degrees                        |
| nearest_airport_km   | float   | Distance to nearest airport                     |
| nearest_airport_code | string  | ICAO code                                       |
| wx_bucket            | string  | Approximate weather category                    |
| reports_z            | float / null | Unused placeholder field (kept for completeness) |


# ⚠️ Notes & Limitations

- Accuracy of timestamps and locations depends entirely on original reporting.
- Weather buckets are coarse (not NOAA-grade).
- Airport distances are approximate nearest-neighbor lookups.
- Cluster labels are based solely on text similarity and do not reflect event reality.
- No claims are made about the nature or validity of any sighting.

# 📄 License

Source data was public on Kaggle. This cleaned, merged, and lightly enriched version is released for research and educational use. Users should follow the original dataset licensing terms.
