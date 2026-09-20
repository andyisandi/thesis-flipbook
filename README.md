# MOVE — interactive flipbook

A browser flipbook of *MOVE*, the thesis book of Andi Zhang (Boston University, Graphic Design).

Click the right page to turn forward, the left page to go back. Arrow keys, swipe,
and the scrubber under the header also work.

- `index.html` — the whole viewer, no build step and no dependencies
- `pages/` — 236 page images (AVIF), one per sheet, loaded on demand

Regenerate from the source PDF with `build/make_site.py` in the working copy.
