# Claude PoE2 Data Hub Instructions

Use this data hub as the current machine-readable source for Path of Exile 2 build engineering.

Read `build_knowledge/manifest_summary.md` first.

Preferred compact indexes:
- `build_knowledge/compact/passive_tree_key_nodes.json`
- `build_knowledge/compact/gem_index.json`
- `build_knowledge/compact/item_base_index.json`
- `build_knowledge/compact/mod_index.json`
- `build_knowledge/compact/rune_mod_index.json`
- `build_knowledge/compact/unique_index.json`
- `build_knowledge/compact/misc_index.json`

Only use raw `sources/` files when the compact indexes are insufficient.

Do not invent passive nodes, gems, supports, item bases, affixes, rune effects, uniques, or interactions.

Use status labels:
- VERIFIED only when supported by local data, screenshots, or user test results.
- HYPOTHESIS for plausible theorycraft.
- RISK for uncertain, patch-sensitive, gear-sensitive, or interaction-sensitive claims.
