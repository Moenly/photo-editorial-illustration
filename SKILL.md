---
name: photo-editorial-illustration
description: Turn one uploaded photograph into a finished vertical editorial composition that keeps the original photo intact and pairs it with a selectively reconstructed, open-form painterly vignette plus a short poetic English title. Use for photo-plus-illustration diptychs, representational editorial vignettes, gouache memory panels, broken-boundary compositions, or artwork that should remain recognizable without becoming a rectangular thumbnail or full-scene repaint.
---

# Photo Editorial Illustration

Create one finished image from one uploaded photograph. Preserve the source photo as evidence; reinterpret only its most meaningful visual relationships below as a recognizable but incomplete editorial illustration.

## Invocation

The user only needs to upload one photograph and ask:

> Use `$photo-editorial-illustration` to turn this photo into a photo-plus-painterly-vignette editorial composition.

Do not ask the user to supply style-reference images or repeat the production prompt.

## Required Reference

Read [references/art-direction.md](references/art-direction.md) completely before generating the artwork. Apply it as the production specification, including its omission logic, open-boundary rules, and rejection checks.

## Workflow

1. Inspect the photograph and identify three to six scene anchors: the primary subject, its gesture or silhouette, the strongest spatial relationship, one or two identity cues, the dominant color role, and the main light-shadow tension.
2. Rank those anchors. Select only three to five for the lower vignette. Omit 30-60% of the photographed content when it does not carry identity or narrative weight.
3. Crop by meaning rather than by the source aspect ratio. Remove large areas of sky, floor, wall, water, foliage, or side clutter when they only fill the photograph. Retain a background region only when it explains the subject or carries a decisive color or light relationship.
4. Plan a vertical composition with the unmodified photograph above and a warm ivory panel below. Do not place a second rectangular image inside the panel.
5. Reconstruct the selected anchors as an open-form painterly vignette. Let silhouettes, color bands, dry-brush edges, and washes define an irregular footprint. Allow a meaningful subject or gesture to project beyond a background mass when the source supports it.
6. Render with matte gouache, tempera, and light watercolor qualities. Simplify structure and detail while preserving enough evidence to connect the vignette to the photograph.
7. Create one original English title of two to six words grounded in visible facts or atmosphere. Set it below the vignette in a quiet editorial serif.
8. Produce the final composite. Keep the original photo pixels unchanged whenever possible. If an image model cannot preserve the photo accurately, generate only the lower vignette and assemble the photo, panel, vignette, and title with a raster compositor.
9. Run every rejection check before returning the image. Revise any failed output.

## Recognition Standard

Aim for 45-65% visual recognizability. A viewer should connect the vignette to the source through three to five retained anchors, but should not see a filtered thumbnail or a complete scene repaint.

- Preserve the primary subject's identity, orientation, and key relationship rather than every contour.
- Preserve perspective only where it supports the retained anchors; allow omitted regions to become ivory negative space.
- Keep people readable through selected heads, torsos, clothing masses, gestures, or group density. Figures may merge, taper, or dissolve at their edges.
- Keep architecture through selected massing, openings, rooflines, color bands, or structural axes. Do not reproduce every wall.
- Keep landscapes through only the decisive terrain, canopy, cloud, water, or horizon forms. Omit the sky entirely when it is not essential.
- Keep crowds as an intelligible social field while allowing walls, ceilings, floors, and peripheral figures to disappear.

## Open-Form Standard

- Do not inherit the source photo's square, landscape, or portrait boundary.
- Do not use four complete straight edges, a visible frame, or an evenly filled rectangle.
- Make at least one edge interrupted, dissolved, feathered, dry-brushed, or absorbed into the ivory panel.
- Use selective projection deliberately: a person, ladder, roofline, machine part, tree, shadow, or color stroke may cross beyond the main painted mass.
- Keep boundary breaking traceable to the source scene. Do not add random decorative splashes.

## Hard Rejections

Reject and redo the lower panel when any of these are true:

- it reads as a rectangular crop, square thumbnail, photo filter, or full-scene repaint;
- it preserves nearly all of the original background instead of making editorial omissions;
- the main subject cannot be inferred from the retained anchors;
- people become generic bars, dots, capsules, or identical pictograms;
- perspective, orientation, or key subject relationships materially change;
- invented objects, colors, splashes, or brush strokes become focal elements;
- all four vignette edges are closed, straight, and regular;
- the vignette is too small to carry the retained scene anchors;
- the result looks like a logo, infographic, vector icon set, generic poster template, anime scene, 3D render, or photorealistic duplicate;
- the final image contains interface chrome, page counters, watermarks, malformed text, or extra captions.

## Output

Return only the completed image unless the user asks for process notes, title options, or prompt text. Do not require style-reference images from the user.

## Lineage

This skill was independently written after studying the photo-plus-panel concept demonstrated by [ZzzLc0405/photo-abstract-editorial](https://github.com/ZzzLc0405/photo-abstract-editorial). It changes the lower panel into a selective, open-form painterly reconstruction. Do not copy or redistribute the original project's prompts, example images, payment images, or documentation.
