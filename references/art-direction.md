# Art Direction and Generation Specification

Use this specification for every output. The uploaded photograph is the sole source of people, objects, setting, palette, light, and narrative.

## 1. Finished Composition

- Default to a vertical 4:5 canvas. Use 3:4 when it better protects a wide photograph or dense scene.
- Place the original photograph in the upper 38-48% of the canvas. Scale proportionally and crop only as much as the vertical layout requires.
- Never redraw, retouch, extend, filter, replace, or recolor the photograph.
- Join the photograph directly to a flat warm-ivory lower panel. Do not use a frame, shadow, tape, mockup, border, gradient, or black separator.
- Place one painterly vignette in the panel, usually 60-78% of the panel width and 42-62% of its height.
- Keep deliberate margins, but make the vignette large enough to carry the scene rather than behave as a decorative stamp.
- Center a single English title beneath the vignette. Use a bookish serif, muted charcoal ink, and accurate spelling.

## 2. Scene Reduction

Reconstruct the photograph as a simplified illustration rather than an abstract diagram.

Preserve:

- the main subject's recognizable outer contour;
- the relative position, size, direction, and overlap of important subjects;
- the source perspective, horizon, structural axes, and depth order;
- the visual center and the strongest light-shadow relationship;
- two to five identity cues such as a hat, ladder, doorway, roof shape, color band, tree canopy, cloud mass, vehicle profile, or body gesture;
- the source palette's dominant roles, not merely approximate decorative colors.

Simplify:

- small surface texture;
- illegible signage and background clutter;
- repeated minor objects that do not affect density or rhythm;
- facial features, tiny hardware, foliage detail, and photographic noise.

Never replace a retained object with a generic icon or disconnected geometric mark.

## 3. Painterly Language

Use a restrained editorial mixture of matte gouache, tempera, and transparent watercolor:

- broad opaque color shapes for architecture, clothing, machinery, terrain, and major shadows;
- thin translucent passages for atmosphere, sky, distant depth, and soft light;
- slightly irregular hand-painted contours;
- subtle pigment pooling, dry-brush breakup, and paper interaction inside the vignette only;
- limited detail concentrated around the focal subject;
- calm, observational, contemporary editorial illustration rather than nostalgic decoration.

Keep the panel background smooth and quiet. Do not cover the entire panel with a heavy paper scan, grunge texture, stains, or distressed effects.

## 4. Subject Guidance

### People

Keep a readable head-body relationship, gesture, orientation, and clothing mass. A hat, coat, backpack, stance, or interaction may be essential. Faces may remain blank or minimally indicated. Do not turn people into bars, dots, capsules, or identical pictograms.

### Crowds

Preserve crowd density, foreground-background layering, important gaps, and the dominant figure. Individual figures may merge at the edges, but the crowd must still read as people occupying a real space.

### Architecture

Keep the overall mass, door and window placement, roofline, perspective, and distinctive color blocks. Suppress masonry and ornament only after the building remains identifiable.

### Landscapes

Keep continuous landforms, horizon height, cloud masses, major trees, water edges, and any focal structure. Simplify leaf and cloud texture without breaking them into unrelated floating shapes.

### Machines and Vehicles

Keep the profile, scale, working direction, operator relationship, and one to three characteristic parts. Preserve functional geometry even when surface detail is removed.

## 5. Title

Write two to six English words. Ground the title in visible subject matter, spatial tension, light, weather, movement, work, waiting, gathering, or quiet observation. Prefer specific restraint over generic sentiment.

Good title patterns:

- `Where Evening Settles`
- `Under the Painted Hull`
- `The Room Holds Still`
- `Before the Rain Returns`

Do not add a subtitle, date, location, signature, logo, or explanation unless the user explicitly requests it.

## 6. Internal Generation Brief

When an image-generation or image-editing tool needs a prompt, construct it from the inspected photo and use this structure:

```text
Create a vertical editorial composition from the supplied photograph. Keep the original photograph unchanged in the upper section. Below it, on a clean warm-ivory panel, paint a clearly recognizable simplified reconstruction of the same scene.

Retain these observed scene anchors: [list the actual anchors]. Preserve their positions, proportions, orientation, overlap, perspective, dominant color relationships, and light-shadow hierarchy. Remove only incidental clutter.

The lower image must remain representational and immediately traceable to the photograph, with roughly 60-80% visual recognizability. Simplify detail through broad matte gouache and tempera shapes, transparent watercolor atmosphere, soft hand-painted edges, restrained pigment texture, and selective focal detail. Keep complete simplified silhouettes for the primary subjects. Do not convert people or objects into abstract bars, dots, capsules, icons, or unrelated geometry.

Place the vignette at a substantial editorial scale with calm ivory margins. Add one accurately spelled poetic English serif title beneath it: [title]. No other text, borders, shadows, interface elements, logos, or watermarks.
```

## 7. Negative Constraints

Apply these as constraints rather than relying on a separate negative-prompt field:

```text
non-representational abstraction, pure geometric composition, disconnected color blocks, symbolic diagram, icon set, infographic, logo, capsule people, dot people, bar figures, lost silhouette, lost perspective, incorrect subject placement, invented focal objects, generic landscape icon, clean vector graphics, anime, cartoon, 3D render, photorealistic repaint, tiny motif, excessive empty space, multiple panels, heavy grunge, distressed paper scan, random text, misspelled title, watermark, phone UI, close button, page counter, black bars
```

## 8. Final Check

Before delivery, answer yes to all of the following:

1. Is the upper photograph faithful to the upload?
2. Can the lower scene be matched to the photograph immediately?
3. Are at least four scene anchors clearly preserved?
4. Are the primary silhouettes and perspective intact?
5. Does the rendering feel hand-painted rather than geometric or template-driven?
6. Is the title accurate, restrained, and the only text?
7. Is the final composition clean, vertical, and free of interface artifacts?

Revise the image if any answer is no.
