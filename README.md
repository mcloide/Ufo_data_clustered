UFO Sightings – Cleaned & Unified Dataset (~327k rows)

This dataset merges several publicly available UFO sighting datasets from Kaggle into one cleaned, standardized, and enriched file.
The goal is simply to provide a consolidated dataset instead of many fragmented sources with inconsistent formatting.

This release contains a single JSONL file with approximately 327,000 records.

No private or identifying information was present in the original data.

📦 Source

All entries originate from publicly available UFO sighting datasets on Kaggle.
Each row corresponds to a single reported sighting.

🧹 Cleaning / Normalization Performed

All rows in this unified file were standardized using the same basic rules:

timestamps parsed and converted into a consistent t_utc (ISO-8601, UTC)

city/state/country fields harmonized where possible

latitude/longitude coerced to floats

basic HTML/unicode cleanup in free-text descriptions (text)

invalid or fully unparseable rows removed

source field preserved as src

No interpretation or filtering based on content was performed.

✨ Added Contextual Fields

A small number of lightweight “sidecar” fields were added based on timestamp + coordinates:

moon_illum — moon illumination fraction

moon_alt_deg — moon altitude in degrees

nearest_airport_code — closest airport (ICAO)

nearest_airport_km — distance to that airport in km

wx_bucket — rough weather bucket (coarse category)

These values are approximate and should be treated as exploratory metadata only.

🧩 Clustering Fields (Included in the File)

The dataset includes two fields that come from text-similarity grouping:

cluster_id — numeric label

prob — membership confidence

These reflect text similarity, not verified categories or event types.
They are included because they were already part of the cleaned file.

📝 Field Reference

Each row has the following structure (example):

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


Field descriptions

Field	Type	Notes

uid	string	Stable row identifier

t_utc	string	Event timestamp, ISO-8601 UTC

lat, lon	float	Approximate coordinates

city, state, country	string	Cleaned location fields (best-effort)

text	string	Free-text sighting description

src	string	Original Kaggle dataset source

cluster_id	int	Text-similarity cluster (for research use only)

prob	float	Cluster membership probability

moon_illum	float	Moon illumination (0–1)

moon_alt_deg	float	Moon altitude in degrees

nearest_airport_km	float	Distance to nearest airport

nearest_airport_code	string	ICAO code

wx_bucket	string	Approximate weather category

reports_z	float/null	Unused placeholder field (kept for completeness)