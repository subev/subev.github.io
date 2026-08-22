# reference

Effects built for this site and kept around, but not currently live.

## cursor-smoke.html

A cursor trail: expanding, noise-crumpled rings that fade like evaporating
smoke. One fullscreen WebGL fragment shader — 12 points in a uniform array,
no fluid simulation.

Ported from the `RippleBackground` component on vuilabs.ai (de-minified from
their bundle; the original is dark-only and composites with `screen`). The
version here adds `uBase`/`uTint` so it also works on a light background via
`multiply`, driven by `data-theme`.

Was live on the site until the order/chaos particle field took over as the
background. Open the file directly — it is self-contained.
