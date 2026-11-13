# Provenance ledger

`provenance/sources.json` is the catalogued list of every source known to the
ingestion team. Each record has the following fields:

- `source_id` — stable identifier used in citations and audits.
- `display_name` — human-readable name.
- `kind` — `dataset` or `model`.
- `source_class` — registry classification assigned by the ingestion team
  (`direct_source` or `reference_only`).
- `records_in_v4_release` — number of records from this source included in
  release v4.
- `records_all_versions` — total number of records ever ingested from this
  source across all releases.
- `license` / `license_terms` — the declared license identifier and a
  human-readable summary of its terms.
- `card_url` — public dataset/model card when one exists.
