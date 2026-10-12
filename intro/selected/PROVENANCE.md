# Selected homepage images

## Current selection — warm robotics

The owner approved both technology proposals and delegated the choice ("all seems good you pick"). Main chose A. `approved-warm-robotics.png` is byte-identical to `outputs/technology-card-proposals/A-warm-robotics.png`, native imagegen output `exec-9b044a11-aafe-4b99-bf11-679c71ae8d71.png` (1774×887). SHA256: `7DBC8900EDCB03A02C7AF768F88C37E094EEF1898EEACF6E2087FC23AF72DAAA`. Prompts are in that proposal folder's `PROMPTS.txt`.

Services uses viewBox `0 0 887 887`; Works uses `887 0 887 887`. Both share this new source through the existing SVG renderer. World keeps `approved-painted.png` and viewBox `1050 180 524 516`. Installation did not regenerate, crop or recolor pixels. The earlier manga source below stays archived and is no longer displayed on the homepage.

## Earlier selection — archived Services/Works, retained World

Owner selected all three artworks and explicitly confirmed their mapping on 2026-10-11:

- Services: the repair illustration from A-deadpan-manga.png.
- Works: the monochrome person/corgi doorway from A-deadpan-manga.png, replacing the notebook.
- World: the colored corgi/workshop gateway from B-painted-cover.png.

approved-manga.png and approved-painted.png are byte-identical copies of those full native imagegen concept outputs in outputs/minimal-homepage-proposals/. The prior generation's exact prompts and input provenance remain in that directory's PROMPTS.txt. The owner's small screenshot crops identify the selection; production uses the larger 1586×992 source files.

No new generation, repainting, image filtering or raster editing occurred in this integration. src/shared/homepageArt.ts supplies display viewports; src/intro renders them as SVG image windows with responsive sizing. Any edge mask is CSS presentation, preserving the source pixels. The viewport deliberately excludes the concepts' old titles and dividers. Browser caching shares the same manga source between Services and Works.

The selected Saitama fan-art depiction is a homepage illustration, not a replacement World avatar. Existing World/background/model/audio assets and credits remain unchanged. Earlier homepage assets remain on disk for history. Selection for this local implementation is not a claim of third-party publication rights.
