# nba-commish-portraits

Newgen procedural portrait pack for [NBA Commish Sim](https://github.com/aljohnpolyglot/nba-commish).

- **14,000** PNG portraits, 256×256
- Naming: `portrait_<gender>-<a>-<b>-<c>-<d>-<e>.png` (gender + 5 feature indices)
- See `manifest.json` for the full index (`{ id, name, width, height, path_id }[]`)

## Usage (jsDelivr CDN)

```
https://cdn.jsdelivr.net/gh/aljohnpolyglot/nba-commish-portraits@main/portrait_male-6-11-12-6-1.png
```

## Source

Extracted from a Unity AssetBundle via [UnityPy](https://github.com/K0lb3/UnityPy).
See `../nba-commish/scripts/extract-newgen-portraits.py`.
