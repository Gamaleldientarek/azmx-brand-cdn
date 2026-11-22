# AZMX Brand Assets (newsletter CDN)

Webfonts and logo files for the AZMX internal newsletter, served via jsDelivr.
Proprietary brand assets of AZMX — not for reuse.

## Brand image library (`images/`)

The AZMX brand image library (gradients, abstract blue, recoloured variants), 1600 px wide JPEG at quality 70, moved here from the `azmx-brand` skill so the skill install stays small. Served at:

```
https://gamaleldientarek.github.io/azmx-brand-cdn/images/<section>/<file>.jpg
```

Sections: `gradient`, `blue`, `white`, `orange`, `purple`, `red`, `green`, `yellow`. The catalogue with concept tags and dominant colours is `references/image-index.md` in [azmx-brand](https://github.com/Gamaleldientarek/azmx-brand); add images with that repo's `scripts/add-images.py --cdn-dir <this checkout>`, which writes here and updates the catalogue. The library is served by GitHub Pages: jsDelivr refuses repositories over 50 MB, which this one passed in Nov 2026. Newsletter assets keep their pinned jsDelivr links, which still work.
