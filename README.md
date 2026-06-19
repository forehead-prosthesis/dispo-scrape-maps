# dispo-scrape-maps

Published coverage maps for the **dispensary_scraper** pipeline — a national map plus
per-state maps of licensed/located dispensaries.

**View:** https://forehead-prosthesis.github.io/dispo-scrape-maps/

These are **generated artifacts**, regenerated from the pipeline's database with
`scripts/dispensary_maps.py` and published here so they can be viewed remotely. The
pipeline code lives in a separate (private) repository; this repo holds only the
rendered output (HTML/SVG/PDF), so it is intentionally not tracked in the code repo.

To refresh: regenerate `maps/` in the pipeline, then push the new files here.
