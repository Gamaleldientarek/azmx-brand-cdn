# AZMX Brand Assets (newsletter CDN)

Webfonts and logo files for the AZMX internal newsletter, served via jsDelivr.
Proprietary brand assets of AZMX — not for reuse.

## Brand image library (`images/`)

The 240-image AZMX brand library (gradients, abstract blue, recoloured variants), 1600 px wide JPEG at quality 70, moved here from the `azmx-brand` skill so the skill install stays small. Served at:

```
https://cdn.jsdelivr.net/gh/Gamaleldientarek/azmx-brand-cdn@main/images/<section>/<file>.jpg
```

Sections: `gradient`, `blue`, `white`, `orange`, `purple`, `red`, `green`, `yellow`. The catalogue with concept tags and dominant colours is `references/image-index.md` in [azmx-brand](https://github.com/Gamaleldientarek/azmx-brand); add images with that repo's `scripts/add-images.py --cdn-dir <this checkout>`, which writes here and updates the catalogue. jsDelivr caches `@main` for up to 12 hours; purge a file with `https://purge.jsdelivr.net/gh/Gamaleldientarek/azmx-brand-cdn@main/images/<section>/<file>.jpg`.
