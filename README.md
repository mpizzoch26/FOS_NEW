# Bulk Closure Process — Walkthrough

Interactive, stage-by-stage walkthrough of the Fedegari bulk closure process
(loading → washing → sterilization/drying/cooling → aseptic unloading →
transfer tank → docking & parking → connection to the fill/finish line).

Built as a single self-contained `index.html` (no build step, no dependencies
beyond Google Fonts). The wash cycle is illustrated with an SVG animation:
closures rest as a ~30° bed at the bottom while the basket turns at ~1 rpm,
with washing / overflowing / final-rinsing phases.

## Run it
Just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Structure
```
index.html      # the whole app (HTML + CSS + JS inline)
img/            # slide graphics + Fedegari logo used in the page
```

> Illustrative graphics for presentation purposes — not a validated operating procedure.
