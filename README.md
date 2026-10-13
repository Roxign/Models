**▶ Open the tool: https://roxign.github.io/Models/**

# Office Status Slider

A 3D-printable office status sign. Status labels sit along a dovetail track on the plate, and a frame slides along the track to show your current status.

The page lets you design the sign in your browser and download print-ready STL files.

## What you can change

- **Statuses:** 2–6 labels with your own text and 16 icons (meeting, call, focus, lab, lunch, remote, travel and more), or pick from 50 ready-made statuses and a dozen preset sets.
- **Shape:** 19 designs. **Rail only** is the default (just the rail, frame and the smallest back panel). Others: rounded, pill, **Classic** (English door-plate style with a raised double bead and serif lettering), **Honeycomb** (hexagon-perforated border), arrow, lozenge, banner, **puzzle** (jigsaw ends so signs can join), pixel, folder, cat ears, ticket, cloud, speech bubble, scallop, wave and arch.
- **Size:** by default the plate fits itself to your text at the letter height you choose. You can also set width and height by hand. Either way it's checked against your printer's bed size.
- **Labels and frame:** layout, typeface (13 to choose from), raised or engraved text, optional header text, frame bar width, window corners and slide clearance. Text prints exactly as typed and supports Latin, Greek, Cyrillic, Vietnamese, Traditional Chinese, Japanese, Korean, Hebrew and Thai. Arabic and Indic scripts need text shaping and are not supported.
- **Mounting:** flat back (optionally with a recess for a tape pad), magnet pockets (size, count and distance from the ends), screw holes (hole and head diameter), desk-stand feet (lean, width and depth), or a **hang loop** (one or two eyelets above any shape). Shape and mounting work together: changing either one changes the final model.
- **Name tag rail:** on the Labels tab, a slide-in rail above the track and a separate flat tag that carries the header text. Change the name, download again and print a new tag for the next person; the sign itself stays the same.

## Printing

**Download STL files** gives you a ZIP with every part already oriented for printing, with no supports needed, plus a README with print and assembly notes. The Print guide also offers a single **3MF** file with the parts laid out on your bed and the preview colors, for Bambu Studio, Orca Slicer and PrusaSlicer.

- For a multi-color printer (AMS, MMU), load `base_body` and `base_labels` together as one object.
- For a single nozzle, the page shows which layers to swap filament at.

To assemble, slide the frame into the track from the left end, then press in the stop pin.

## Notes

- The whole tool is the single file `index.html`.
- It loads three.js, Manifold and the label fonts from jsDelivr, so it needs an internet connection.
- **Copy design link** saves your settings in the URL, so you can reopen or share an exact design.
