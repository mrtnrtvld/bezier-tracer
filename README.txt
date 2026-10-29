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
In Edit mode: drag to move, box-select on empty space, drag the selection box corners to scale
and its round handle to rotate. The Object menu has copy/paste/duplicate, group, align and
distribute, rotate and flip, lock, "Combine shapes" to cut holes, and "Convert text to
shapes" (works with Google fonts, and with installed fonts in Chrome or Edge). The Layers panel (L)
shows everything front to back; drag rows to restack, use the eye to hide and the padlock to lock.

Sketch
Sketch > Load sketch puts an image under your drawing to trace over. Unlock it to move or resize
it, Shift+S hides it, and Auto-trace sketch turns its dark areas into editable shapes.

Export
Export gives you an SVG (with fonts embedded where possible) or a PNG at 1-4x. Files are named
after the drawing. File > Import SVG (or dropping/pasting an SVG) brings shapes back in.

Development (auto-reload)

Run `npm install` once, then `npm run dev`. It opens the app at http://localhost:5173 and
reloads the page whenever you save a change. Drawings are kept separately here from the
double-clicked file, because the browser stores them per address.
