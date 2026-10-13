**▶ Open the tool: https://roxign.github.io/Models/**

# Office Status Slider

A 3D-printable office status sign. Status labels sit along a dovetail track on the plate, and a frame slides along the track to show your current status.

The page lets you design the sign in your browser and download print-ready STL files.

## What you can change

- **Statuses:** 2–6 labels with your own text and 15 icons (meeting, call, focus, lunch, remote, travel and more), or start from a preset set.
- **Shape:** rounded, pill, badge, ticket, cloud, speech bubble, scallop, wave or arch.
- **Size:** by default the plate fits itself to your text at the letter height you choose. You can also set width and height by hand. Either way it's checked against your printer's bed size.
- **Labels and frame:** layout, typeface (Noto Sans or Serif), raised or engraved text, optional header text, frame bar width, window corners and slide clearance. Text prints exactly as typed and supports Latin, Greek, Cyrillic, Vietnamese, Traditional Chinese, Japanese, Korean, Hebrew and Thai. Arabic and Indic scripts need text shaping and are not supported.
- **Mounting:** flat back for tape, magnet pockets, screw holes or desk-stand feet.

## Printing

**Download STL files** gives you a ZIP with every part already oriented for printing, with no supports needed, plus a README with print and assembly notes.

- For a multi-color printer (AMS, MMU), load `base_body` and `base_labels` together as one object.
- For a single nozzle, the page shows which layers to swap filament at.

To assemble, slide the frame into the track from the left end, then press in the stop pin.

## Notes

- The whole tool is the single file `index.html`.
- It loads three.js, Manifold and the label fonts from jsDelivr, so it needs an internet connection.
- **Copy design link** saves your settings in the URL, so you can reopen or share an exact design.
