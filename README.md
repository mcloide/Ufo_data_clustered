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