# PoE2 Data Manifest Summary

- Generated UTC: `2026-06-16T13:55:45+00:00`
- Source priority: GGG passive tree -> RePoE PoE2 -> PoB-data PoE2 -> community sources only as benchmarks

## Download results

| Status | File | Records | Size | Source |
|---|---|---:|---:|---|
| OK | `sources/ggg/passive_tree_data.json` | 11 | 5,141,380 | https://raw.githubusercontent.com/grindinggear/poe2-skilltree-export/main/data.json |
| OK | `sources/repoe_poe2/skill_gems.json` | 1,188 | 1,352,735 | https://repoe-fork.github.io/poe2/skill_gems.json |
| OK | `sources/repoe_poe2/skills.json` | 8,339 | 27,714,191 | https://repoe-fork.github.io/poe2/skills.json |
| OK | `sources/repoe_poe2/gem_tags.json` | 67 | 1,711 | https://repoe-fork.github.io/poe2/gem_tags.json |
| OK | `sources/repoe_poe2/active_skill_types.json` | 290 | 6,285 | https://repoe-fork.github.io/poe2/active_skill_types.json |
| OK | `sources/repoe_poe2/cost_types.json` | 18 | 1,769 | https://repoe-fork.github.io/poe2/cost_types.json |
| OK | `sources/repoe_poe2/keywords.json` | 978 | 244,208 | https://repoe-fork.github.io/poe2/keywords.json |
| OK | `sources/repoe_poe2/base_items.json` | 5,239 | 7,827,106 | https://repoe-fork.github.io/poe2/base_items.json |
| OK | `sources/repoe_poe2/item_classes.json` | 117 | 15,850 | https://repoe-fork.github.io/poe2/item_classes.json |
| OK | `sources/repoe_poe2/tags.json` | 1,325 | 28,580 | https://repoe-fork.github.io/poe2/tags.json |
| OK | `sources/repoe_poe2/tag_details.json` | 1,325 | 98,934 | https://repoe-fork.github.io/poe2/tag_details.json |
| OK | `sources/repoe_poe2/mods.json` | 16,788 | 12,980,566 | https://repoe-fork.github.io/poe2/mods.json |
| OK | `sources/repoe_poe2/mods_by_base.json` | 74 | 5,105,198 | https://repoe-fork.github.io/poe2/mods_by_base.json |
| OK | `sources/repoe_poe2/characters.json` | 12 | 7,233 | https://repoe-fork.github.io/poe2/characters.json |
| OK | `sources/repoe_poe2/ascendancies.json` | 37 | 17,135,310 | https://repoe-fork.github.io/poe2/ascendancies.json |
| OK | `sources/repoe_poe2/uniques.json` | 449 | 171,109 | https://repoe-fork.github.io/poe2/uniques.json |
| OK | `sources/repoe_poe2/stats_by_file.json` | 25,999 | 14,263,487 | https://repoe-fork.github.io/poe2/stats_by_file.json |
| OK | `sources/repoe_poe2/stat_value_handlers.json` | 73 | 374,369 | https://repoe-fork.github.io/poe2/stat_value_handlers.json |
| OK | `sources/pob_data_poe2/Gems.json` | 965 | 549,444 | https://repoe-fork.github.io/pob-data/poe2/Gems.json |
| OK | `sources/pob_data_poe2/ModItem.json` | 2,549 | 1,134,707 | https://repoe-fork.github.io/pob-data/poe2/ModItem.json |
| OK | `sources/pob_data_poe2/ModRunes.json` | 287 | 184,957 | https://repoe-fork.github.io/pob-data/poe2/ModRunes.json |
| OK | `sources/pob_data_poe2/ModJewel.json` | 377 | 164,030 | https://repoe-fork.github.io/pob-data/poe2/ModJewel.json |
| OK | `sources/pob_data_poe2/ModCharm.json` | 51 | 18,999 | https://repoe-fork.github.io/pob-data/poe2/ModCharm.json |
| OK | `sources/pob_data_poe2/ModFlask.json` | 78 | 33,291 | https://repoe-fork.github.io/pob-data/poe2/ModFlask.json |
| OK | `sources/pob_data_poe2/QueryMods.json` | 8 | 695,080 | https://repoe-fork.github.io/pob-data/poe2/QueryMods.json |
| OK | `sources/pob_data_poe2/SkillStatMap.json` | 957 | 193,412 | https://repoe-fork.github.io/pob-data/poe2/SkillStatMap.json |
| OK | `sources/pob_data_poe2/TradeSiteStats.json` | 10 | 1,103,592 | https://repoe-fork.github.io/pob-data/poe2/TradeSiteStats.json |
| OK | `sources/pob_data_poe2/Costs.json` | 19 | 2,419 | https://repoe-fork.github.io/pob-data/poe2/Costs.json |
| OK | `sources/pob_data_poe2/Misc.json` | 21 | 20,045 | https://repoe-fork.github.io/pob-data/poe2/Misc.json |
| OK | `sources/pob_data_poe2/Minions.json` | 32 | 33,519 | https://repoe-fork.github.io/pob-data/poe2/Minions.json |

## Generated compact indexes

| Index | Records | Size | Recommended for Claude Project Knowledge? |
|---|---:|---:|---|
| `CLAUDE_DATA_HUB_INSTRUCTIONS.md` | 1 | 951 | YES |
| `gem_index.json` | 11,806 | 2,247,328 | YES |
| `item_base_index.json` | 8,006 | 1,664,482 | YES |
| `manifest_summary.md` | 1 | 4,490 | YES |
| `misc_index.json` | 27,695 | 5,529,498 | OPTIONAL |
| `mod_index.json` | 19,429 | 5,421,826 | YES, if size allows |
| `passive_tree_edges.json` | 5,129 | 236,338 | ONLY when exact pathing is needed |
| `passive_tree_full_compact.json` | 5,151 | 698,278 | ONLY when exact small-node routing is needed |
| `passive_tree_key_nodes.json` | 4,922 | 687,851 | YES |
| `rune_mod_index.json` | 287 | 32,725 | YES |
| `unique_index.json` | 449 | 58,594 | YES |

## Claude Project Knowledge recommendation

Add these first:

- `build_knowledge/manifest_summary.md`
- `build_knowledge/CLAUDE_DATA_HUB_INSTRUCTIONS.md`
- `build_knowledge/compact/passive_tree_key_nodes.json`
- `build_knowledge/compact/gem_index.json`
- `build_knowledge/compact/item_base_index.json`
- `build_knowledge/compact/rune_mod_index.json`
- `build_knowledge/compact/unique_index.json`

Add only if space allows:

- `build_knowledge/compact/mod_index.json`
- `build_knowledge/compact/misc_index.json`
- `build_knowledge/compact/passive_tree_edges.json`

Do not add raw `sources/ggg/passive_tree_data.json` to Claude Project Knowledge unless absolutely necessary; it is large.

## Usage rules

- Passive claims: use GGG source data or compact passive indexes.
- Skill/gem claims: use `gem_index.json` and relevant raw source files if needed.
- Gear/mod/rune/unique claims: use item, mod, rune, and unique indexes.
- If the local data does not support a claim, label it unverified.