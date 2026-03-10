![image displaying Latin text, numbers, and symbols](/images/arcomp_mono_demonstration.svg)
# Installation
The otf files can be found in the releases folder [HERE](https://github.com/GraphiXS6/Arcomp_mono/tree/main/releases) and the FontForge file (SFD) can be found [HERE](https://github.com/GraphiXS6/Arcomp_mono/tree/main/Arcomp_mono_git).
# Arcomp Mono
Arcomp Mono is a free, open source, monospace font designed around particular constraints with good readability in mind.
All characters are the exact same width, with few exceptions, with the width being the x-height.
The ascenders and descenders, along with the tops of capital letters, are 50% of the midline x-height above and below.  
This typeface is metrically compatible with Courier New, and can thus be a drop in replacement for documents.
This typeface has near complete accent support, and should be able to fully write all Latin, Germanic, and Scandinavian languages.
Along with those languages, Arcomp Mono also has full Greek support, and Japanese kana.
![image displaying Greek text](/images/arcomp_mono_greek_demo.svg)
![image displaying Japanese text](/images/arcomp_mono_japanese_demo.svg)
## Editing Typeface
### File Structure
In the Arcomp_mono_git folder are an Inkscape SVG with the underline grid, and various curves used in making the glyphs.
There is also the FontForge file.
In the wip_files folder are all characters as Inkscape SVGs with the grid and all characters as strokes.
in the final_files folder are all characters as Inkscape SVGs with no grid and all characters as filled paths.
### Editing Glyphs
All glyphs are arranged with nodes aligned on the grid.  Curves are primarily Bézier representations of arcs with some derived from NURBS.
In the FontForge file, most diacritics are handled as references, so if you edit them, accented characters should automatically be adjusted.
## Roadmap
There are still several features to be added including:
- Improved bold support
- Proper italic/oblique support
- Additional Archaic Latin and IPA characters
- Complete Archaic Greek characters
- Various arrows and misc. symbols
- Coding ligatures
- Supporting common Japanese Kanji
- Misc. glyph adjustments
