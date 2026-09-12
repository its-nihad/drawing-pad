#  Sketcha

Sketcha is a studio-styled sketch pad that runs entirely in the browser. It's built as a single self-contained HTML file with no external libraries or dependencies, so it can be opened directly or hosted anywhere, including GitHub Pages.

The canvas sits on a dark charcoal drafting board and looks like a sheet of paper clipped in place with a brass clip. On the left is a vertical toolbar with four brushes: pencil, ink pen, marker, and eraser. Each has its own feel, from the slightly textured pencil to the semi-transparent marker that darkens where strokes overlap. A brush size slider and a curated set of color swatches sit below the tools, along with a custom color picker for anything outside the palette.

Drawing works with mouse, pen, or touch input through pointer events, and strokes are smoothed using quadratic curves so lines stay clean at any speed. Undo and redo are available from the top bar or with Ctrl/Cmd+Z and Ctrl/Cmd+Y, and there's a clear button to wipe the canvas. When you're happy with a drawing, the Save button exports it as a PNG with the paper background composited in.

A few keyboard shortcuts speed things up: P, N, M, and E switch between pencil, pen, marker, and eraser, and the bracket keys ([ and ]) shrink or grow the brush size. The layout is responsive, so the toolbar moves to a horizontal strip along the bottom on narrow screens.
