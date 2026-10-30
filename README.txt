Bézier Tracer

Double-click index.html to open it in your browser. No install needed. An internet connection
is only used for the Figtree font and for embedding web fonts when you export.

Saving
Your drawings, sketches and settings are saved in the browser and come back the next time you
open this same file. File > Open drawing lists them. To keep a copy or move a drawing to another
computer, use File > Save project file (one .json file with everything, including the sketch).

Drawing
Tools: Pen (P), Rectangle (R), Circle (C), Polygon (Y), Star (S), Line (\), Text (T), Edit (V),
Pan (H or hold Space). The style bar sets stroke, dash, line ends, fill, opacity, text font,
size, bold/italic, rectangle corners, polygon sides and star points, for the selection and for
new items. Snapping and a grid are in the View menu; hold Cmd/Ctrl while dragging to skip snapping.

Editing
In Edit mode: drag an item, or anywhere inside the selection box, to move the selection; box-select on empty space, drag the selection box corners to scale
and its round handle to rotate. The Object menu has copy/paste/duplicate, group, align and
distribute, rotate and flip, lock, "Combine shapes" to cut holes, and "Convert text to
shapes" (works with Google fonts, and with installed fonts in Chrome or Edge). The Layers panel (L)
shows everything front to back; drag rows to restack, use the eye to hide and the padlock to lock.
With the Text tool, drag existing text to move it, or click it to retype it.

Artboards
A drawing can have several artboards (Artboards menu): new, duplicate (with its artwork), rename,
delete, and fit to artwork. Click an artboard to make it current; the size boxes, Fit (0),
single-item alignment and export use the current one. Drag an artboard's name to move it with its
artwork, double-click the name to rename it, and press Shift+0 to see them all.

Sketch
Sketch > Load sketch puts an image under your drawing to trace over. Unlock it to move or resize
it, Shift+S hides it, and Auto-trace sketch turns its dark areas into editable shapes.

Export
Export gives you an SVG (with fonts embedded where possible) or a PNG at 1-4x, one artboard per
file. Pick the artboard in the dialog, or use "Download all artboards" to save each one as its own
file. Files are named after the drawing (and the artboard, when there are several). File > Import SVG (or dropping/pasting an SVG) brings shapes back in.

Development (auto-reload)

Run `npm install` once, then `npm run dev`. It opens the app at http://localhost:5173 and
reloads the page whenever you save a change. Drawings are kept separately here from the
double-clicked file, because the browser stores them per address.
