# Street Studio

A Pattern Book prototype for sketching a street in section and seeing it in 3D: lanes, planting, crossings and building frontages on both sides of a 120 m stretch.

Open `index.html` in a browser, or visit this folder on the repository's GitHub Pages site.

## What's in v1.10

- **Building types that look like their names.** Victorian brick terraces with bay windows and chimney stacks, Parisian limestone blocks with mansards and iron balconies, mid-century stucco flats, curtain-wall offices, converted warehouses, contemporary apartments, painted townhouses and Art Deco mansion blocks.
- **Species-specific trees.** London plane, small-leaved lime, silver birch, rowan and hornbeam each have their own height, crown shape, bark and foliage.
- **Shrubs with their own habits.** Box, hawthorn, lavender, dogwood, marigold and bougainvillea; plus jacaranda, ash and Canary palm among the trees.
- **A layout library.** Twelve ready-made streets under Saves → Library, including four drawn from photographs of Mexico City.

## Adding your own layouts to the library

Layouts saved in the tool live in that browser only. To share some with everyone who opens the site:

1. In the Saves tab, press the download button to back up your layouts as JSON.
2. Rename the file to `library.json` and commit it to this repository, replacing the existing one.

Those layouts then appear in the Library list beneath the built-in ones.

## Files

- `index.html` – the whole tool
- `library.json` – optional shared layouts
- `vendor/three.min.js` – three.js r128 (MIT licence), bundled so the 3D view works without a CDN
