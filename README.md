**▶ Open the tool: https://roxign.github.io/Models/**

# Office Status Slider

A 3D-printable office status sign. Status labels sit along a dovetail track on the plate, and a frame slides along the track to show your current status. It can also carry a name, printed on the plate or on a slide-in tag, or be a name sign on its own.

The page lets you design the sign in your browser and download print-ready STL files.

## What you can change

- **Statuses:** 2–6 labels with your own text and 16 icons (meeting, call, focus, lab, lunch, remote, travel and more), or pick from 81 ready-made statuses and a dozen preset sets.
- **Shape:** 18 designs. **Rail only** is the default (just the rail, frame and the smallest back panel). Others: rounded, pill, **Classic** (English door-plate style with a raised double bead and serif lettering), **Honeycomb** (hexagon-perforated border, holes all the way round), arrow, lozenge, banner, **puzzle** (jigsaw ends so signs can join), pixel, folder, cat ears, ticket, cloud, speech bubble, scallop, wave and arch.
- **Rails:** on Rail only, Classic, Honeycomb, Puzzle, Folder and Wave the rails stop at the ends of the track, inside the border or end features. On every other shape they run out to the edge of the plate and follow its outline, with the left end filled solid; the side margin keeps them back from the edge if you want a border. An optional bevel rounds off the outer edge of the whole base.
- **Size:** by default the plate fits itself to your text at the letter height you choose. You can also set width and height by hand. Either way it's checked against your printer's bed size.
- **Printer rules:** set the nozzle and layer height at the top. Every height the printer builds layer by layer (plate, rails, lettering, tag, bevel steps, magnet pockets, the frame) is a whole number of layers, walls are at least two nozzle widths, and letters, frame bars and clearances have nozzle-based minimums, whether you drag a slider or type a value. Turn on Dynamic to drop the layer rule for adaptive layer heights.
- **Tabs:** Shape (outline and how it mounts), Plate (bevel, size, margins, thickness), Status (the status track, label layout, lettering, the sliding frame and the track) and Name. The status track can be turned off for a sign with only a name.
- **Lettering:** typeface (13 to choose from), raised or engraved. The status labels and the name each have their own thickness.
- **Colors:** the palette button on the 3D view sets every preview color in one place (plate, status lettering, frame, name text, name tag) or applies a ready-made palette. The colors carry into the 3MF. Text prints exactly as typed and supports Latin, Greek, Cyrillic, Vietnamese, Traditional Chinese, Japanese, Korean, Hebrew and Thai. Arabic and Indic scripts need text shaping and are not supported.
- **Mounting:** flat back (optionally with a recess for a tape pad), magnet pockets (size, count and distance from the ends), screw holes (hole and head diameter), desk-stand feet (lean, width, and separate forward and backward extension), a **hang loop** (one or two eyelets above any shape), a **cubicle hook** (two printed hooks that clip onto the sign and hang over the top of a cubicle panel, like an upside-down J; set the panel thickness) or a **cubicle rail** hanger (the same hooks sized to drop behind the front lip of a cubicle accessory rail; set the lip thickness and height). Shape and mounting work together: changing either one changes the final model.
- **Name:** on the Name tab, off, printed on the plate, or on a **slide-in tag**: a separate flat tag in a lipped rail above the track. The tag rail is as long as the main rails; on the shapes whose rails run to the edge, the tag follows the outline at both ends, so it is symmetric whenever the plate is, and the stop at its end follows the outline as an even border, round corners included. It slides in from the right end, like the frame, and stops at the left end; drag it in the preview to see it move. Change the name, download again and print a new tag for the next person; the sign itself stays the same.

## Printing

**Download** opens a dialog with a ZIP of every part, already oriented for printing with no supports needed, plus a README with print and assembly notes. The same dialog offers a single **3MF** file with the parts laid out on your bed and the preview colors, for Bambu Studio, Orca Slicer and PrusaSlicer.

- For a multi-color printer (AMS, MMU), load `base_body` and `base_labels` together as one object.
- For a single nozzle, the page shows which layers to swap filament at.

To assemble, slide the frame into the track from the right end, the open end. There is no stop pin: the frame is held only by the fit of the dovetail, so don't push it past the last status. The name tag, if you made one, slides into its rail from the right end too.

## Notes

- The whole tool is the single file `index.html`. It works on phones too: the preview stays at the top of the screen while you scroll through the settings.
- It loads three.js, Manifold and the label fonts from jsDelivr, so it needs an internet connection.
- **Copy design link** saves your settings in the URL, so you can reopen or share an exact design.
