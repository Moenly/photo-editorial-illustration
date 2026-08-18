# Art Direction and Generation Specification

Use this specification for every output. Treat the uploaded photograph as the sole source of people, objects, setting, palette, light, and narrative, but not as a boundary that the lower illustration must copy.

## Contents

1. Finished composition
2. Editorial selection
3. Open-form boundary
4. Painterly language
5. Subject guidance
6. Title
7. Internal generation brief
8. Negative constraints
9. Final check

## 1. Finished Composition

- Default to a vertical 4:5 canvas. Use 3:4 when it better protects the source photograph.
- Place the original photograph in the upper 38-48% of the canvas. Scale proportionally and crop only as much as the vertical layout requires.
- Never redraw, retouch, extend, filter, replace, or recolor the photograph.
- Join the photograph directly to a flat warm-ivory lower panel. Do not use a frame, shadow, tape, mockup, border, gradient, or black separator.
- Place one selective painterly vignette in the panel. Let its scale follow the retained subject rather than the original aspect ratio; usually use 52-76% of the panel width and 34-60% of its height.
- Keep generous editorial margins, but make the retained anchors large enough to read.
- Center one English title beneath the vignette in a bookish serif with muted charcoal ink and accurate spelling.

## 2. Editorial Selection

Reconstruct the meaning of the photograph, not the complete photographed rectangle.

### Select anchors

Identify three to six candidates, then retain only three to five:

- the primary subject or action;
- one decisive silhouette or gesture;
- one spatial relationship, overlap, axis, or density pattern;
- one or two identity cues such as a hat, ladder, doorway, roof shape, color band, rust streak, tree canopy, or mountain ridge;
- one dominant color role;
- one light-shadow or atmospheric tension.

### Omit deliberately

Remove roughly 30-60% of the source content when it does not support the retained anchors. Omission is a design action, not a failure of fidelity.

- Remove a large sky when it only fills the upper photograph. If its color matters, keep one incomplete wash or narrow atmospheric passage instead of repainting the whole sky.
- Remove floors, walls, ceilings, water, grass, or foliage that provide scale but no identity. Let ivory negative space replace them.
- Remove peripheral people, vehicles, signs, wires, furniture, or repeated objects that do not affect the main action or density.
- Crop asymmetrically when the source's visual center is off-axis.
- Preserve only the portion of a background needed to hold the subject: a color band behind a crowd, a hull behind a worker, a ridge behind a house, or a shadow behind a figure.

### Preserve meaning

- Keep the primary subject's identity, orientation, and relation to the retained environment.
- Keep color roles rather than every local color.
- Keep perspective only inside the retained fragments. Do not rebuild omitted space merely to complete a scene.
- Keep enough evidence for an immediate source connection, targeting 45-65% recognizability.

## 3. Open-Form Boundary

The lower illustration must not look like a second photo, a square crop, or an image placed inside a box.

- Do not inherit the photograph's aspect ratio.
- Do not create four complete straight edges or a uniformly filled rectangular background.
- Build an irregular footprint from the retained subjects and their color masses.
- Interrupt or dissolve at least one edge through dry brush, watercolor fade, tapering figures, incomplete architecture, open negative space, or pigment loss.
- Allow one meaningful element to project beyond the main painted mass when appropriate: a person, ladder, roofline, machine part, tree canopy, shadow, hanging light, rust streak, or directional brush mark.
- Let foreground figures or objects taper, drip, or disappear into the ivory panel when that supports depth or movement.
- Let background color bands end before the subjects, extend unevenly behind them, or break into separate washes.
- Avoid arbitrary splatter. Every protrusion, gap, drip, and brush direction must originate from a visible fact in the source.

## 4. Painterly Language

Use a restrained editorial mixture of matte gouache, tempera, and transparent watercolor:

- broad opaque color masses for selected architecture, clothing, machinery, terrain, and major shadows;
- thin translucent passages for retained atmosphere, light, or distant depth;
- simplified interior detail and slightly irregular hand-painted contours;
- subtle pigment pooling, dry-brush breakup, and paper interaction inside painted areas;
- selective detail concentrated around the main anchor;
- intentional unfinished passages where the image meets negative space;
- calm contemporary editorial illustration rather than nostalgic decoration.

Do not simulate the result by applying a painterly filter to a rectangular photograph. Recompose and omit first; stylize second.

Keep the panel background smooth and quiet. Do not cover the entire panel with a heavy paper scan, grunge texture, stains, or distressed effects.

## 5. Subject Guidance

### People

Keep only the heads, torsos, clothing masses, gestures, and interactions needed to read the action. Faces may remain blank or minimally indicated. Figures may overlap, merge, crop, taper, or dissolve, but must not become generic bars, dots, capsules, or identical pictograms.

### Crowds

Preserve density, foreground-background layering, important gaps, and the dominant figure. Replace most walls, ceilings, and floors with negative space or a few incomplete color bands. Allow outer figures and lower bodies to fade or trail into brush marks.

### Architecture

Keep selected massing, openings, rooflines, structural axes, or distinctive colors. Partial architecture is preferable to a complete building thumbnail. Allow walls and roof planes to stop, break, or dissolve once identity is established.

### Landscapes

Keep only decisive landforms, horizons, tree masses, water edges, clouds, or focal structures. A mountain ridge can survive without a complete sky; a house can survive with only one tree mass and a short ground wash. Omit the sky entirely when it is not a narrative or color anchor.

### Machines and Vehicles

Keep the working profile, scale, operator relationship, movement, and one to three characteristic parts. A worker, ladder, color band, and rust streak may carry the whole scene without a complete machine or industrial background.

## 6. Title

Write two to six English words. Ground the title in visible subject matter, spatial tension, light, weather, movement, work, waiting, gathering, or quiet observation. Prefer specific restraint over generic sentiment.

Good title patterns:

- `Where Evening Settles`
- `Under the Painted Hull`
- `The Room Holds Still`
- `Before the Rain Returns`

Do not add a subtitle, date, location, signature, logo, or explanation unless the user explicitly requests it.

## 7. Internal Generation Brief

When an image-generation or image-editing tool needs a prompt, construct it from the inspected photo and use this structure:

```text
Create a vertical editorial composition from the supplied photograph. Keep the original photograph unchanged in the upper section. Below it, on a clean warm-ivory panel, create a selectively reconstructed, open-form painterly vignette derived only from the same scene.

Retain only these three to five observed anchors: [list the actual anchors]. Omit 30-60% of the source, including [name the specific nonessential sky, floor, wall, foliage, vehicles, people, or clutter]. Crop by meaning rather than by the source aspect ratio. Preserve the selected anchors' identity, orientation, overlap, dominant color roles, and key light-shadow relationship.

Target 45-65% visual recognizability. The lower illustration must not be a filtered thumbnail, full-scene repaint, square crop, or closed rectangle. Build an irregular footprint from broad matte gouache and tempera masses, transparent watercolor passages, dry-brush interruptions, soft pigment loss, and ivory negative space. Break or dissolve at least one boundary. Let [name one source-grounded subject or gesture] project beyond the main painted mass when appropriate.

Keep selected subjects readable without rebuilding omitted background. Add one accurately spelled poetic English serif title beneath the vignette: [title]. No other text, borders, shadows, interface elements, logos, or watermarks.
```

## 8. Negative Constraints

Apply these as constraints rather than relying only on a separate negative-prompt field:

```text
rectangular thumbnail, square illustration, framed image, four complete straight edges, closed boundary, source aspect ratio copied, full-scene repaint, complete background reconstruction, all sky preserved, all floor preserved, photographic completeness, painterly photo filter, posterized photograph, postcard composition, evenly filled background, strict centered symmetry, literal scene tracing, photorealistic duplicate, non-representational abstraction, disconnected geometry, generic symbols, capsule people, dot people, bar figures, lost subject relationship, invented focal objects, random splatter, decorative brush marks unrelated to the source, clean vector graphics, anime, cartoon, 3D render, tiny motif, random text, misspelled title, watermark, phone UI, close button, page counter, black bars
```

## 9. Final Check

Before delivery, answer yes to all of the following:

1. Is the upper photograph faithful to the upload?
2. Does the lower vignette retain only three to five decisive anchors?
3. Has 30-60% of nonessential source content been omitted?
4. Can the vignette still be connected to the photograph at roughly 45-65% recognizability?
5. Does the vignette avoid the source aspect ratio and a closed rectangular boundary?
6. Is at least one edge interrupted or dissolved, and is any projection grounded in the source?
7. Does the result feel recomposed and hand-painted rather than filtered?
8. Is the title accurate, restrained, and the only text?
9. Is the final composition free of interface artifacts, arbitrary decoration, and invented focal content?

Revise the image if any answer is no.
