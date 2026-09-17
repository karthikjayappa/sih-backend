# Alur source data

Place the three licensed Alur GeoJSON exports in this directory:

- `alur_revenue_169.geojson`
- `alur_survey_169.geojson`
- `alur_municipal_169.geojson`

Each file must be a GeoJSON `FeatureCollection` with polygon or multipolygon
features. Feature properties should use the shared source fields where
available: `source`, `record_id`, `survey_number`, `owner_name`, `area_sqm`,
and `land_use`. Feature geometry is ingested directly; it is never replaced
with a centroid-derived square.

The current checkout does not include those source files. Add them only when
their licensing and competition rules permit repository distribution.
