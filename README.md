# Convex Spectra Explorer

An interactive visualizer for the *Convex Spectra Set of Dissected Regular Polygons*
by Yoshiaki Araki and Teruhisa Sugimoto (April 2021, Japan Tessellation Design Association,
[one-pager](https://www.t3puzzle.com/convexspectraset.html)), which answers Erich Friedman's
[Convex Spectra](https://erich-friedman.github.io/mathmagic/0499.html) problem.

The convex spectrum of a shape is the set of numbers *n* such that *n* congruent copies of it
can form a convex shape. For each Type on the sheet, pick the piece with **k** (and **j** where
it applies), then grow (**r**) and stretch (**s** / **N**) the arrangement; the page draws the
arrangement and the count.

## Types

- Type 1-even, Type 1-odd
- Type 2, 2-sliced, 2-double, 2-half, 2-double-mod
- **Type 2-double-trim** — not on the sheet; contributed by Andrew Bayly. Trimming a small
  triangle off the Type 2-double piece keeps its old arrangements and adds every even count
  from 2k+2 (every count from 2 when k = 1).
- Type 3, 3-half, 3-special, 3-half-special, 3-double-sliced, 3-double-sliced-special, 3-triple
- Type 4

Each arrangement in the page was checked numerically (all pieces congruent, mirror images
allowed; no overlaps; the union equals its convex hull) for the parameter ranges noted in the
page's notes.

## Running it

It is a single self-contained file: open `index.html` in a browser. No build step.
