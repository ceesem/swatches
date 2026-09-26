# Swatches

A small page for looking at a color palette: names for each color, sample charts, optional snapping to nicer nearby colors, color-blindness checks, and export as code.

Click a color to edit it with lightness, saturation, and hue sliders; drag colors to reorder them. The built-in library has about 170 palettes: categorical sets, plus sequential and diverging colormaps that can be sampled at any number of colors.

Put colors in the link after `#`, separated by dashes:

https://csdashm.com/swatches/#264653-2a9d8f-e9c46a-f4a261-e76f51

The colors live in the part of the link after `#`, which browsers never send to the server.

## What this is (and isn't)

A middle ground between a single hard-coded palette and catalogs with thousands of options. It's for judging one palette at a time and getting it into a plot.

**What goes in the library:** palette families made with the same care as CARTOColors, each designed for a purpose (maps, color-blind safety, perceptual uniformity, a specific kind of data). Each family has a one-line reason it's here. Seaborn and matplotlib built-ins stay only for comparison. "It's popular" or "it's pretty" isn't enough; the catalogs already cover that.

**What features go in:** things that help you judge or use the palette on screen. For example, seeing it in charts, checking it for color blindness, adjusting a color, or exporting it as code.

**What stays out:** accounts, saved palette collections, community galleries, palette generators, and search across thousands of palettes. The link is the save file.

## Credits

Color names come from [color-names](https://github.com/meodai/color-names) (MIT). The Tailwind snap palette comes from [Tailwind CSS](https://tailwindcss.com) v3 (MIT). Built-in palettes:

- [CARTOColors](https://carto.com/carto-colors/) by CARTO (CC BY 4.0)
- [Paul Tol](https://personal.sron.nl/~pault/), via [tol-colors](https://pypi.org/project/tol-colors/) (BSD-3-Clause)
- [Scientific Colour Maps](https://www.fabiocrameri.ch/colourmaps/) by Fabio Crameri (MIT), via [cmcrameri](https://pypi.org/project/cmcrameri/)
- [cmocean](https://matplotlib.org/cmocean/) by Kristen Thyng (MIT)
- [MetBrewer](https://github.com/BlakeRMills/MetBrewer) (CC0) and [wesanderson](https://github.com/karthik/wesanderson) (MIT), via [pypalettes](https://github.com/JosephBARBIERDARNAL/pypalettes)
- [ggsci](https://nanx.me/ggsci/) journal palettes (GPL-3.0) and Tableau palettes from [ggthemes](https://github.com/jrnold/ggthemes), via pypalettes
- Observable 10 from [d3-scale-chromatic](https://github.com/d3/d3-scale-chromatic) (ISC)
- Okabe & Ito (2008) and the IBM Design Library accessible palette
- [seaborn](https://seaborn.pydata.org) (BSD-3-Clause) and [matplotlib](https://matplotlib.org) built-ins
