---
layout: page
title: Road to CairoSVG 1.0
---

Now that CairoSVG has a quite stable API and a lot of features, it's time to
release a stable version, isn't it?

So, here's the road between 0.3 and 1.0:

- Percentages, em and ex units (done);
- Real opacity for groups (done);
- Character rotations;
- Better tests.

The two missing items need a lot of time:

- The `text` module must be totally rewritten to correctly handle paths,
  letter spacing and rotation;
- New tests must include unit tests (even included in the docstrings for some
  helpers), simple SVG files (to test one specific feature) and complex SVG
  files.

If anyone is interested in one of these tasks, you can contact us whenever you
want!