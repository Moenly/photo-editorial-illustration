---
name: photo-editorial-illustration
description: Turn one uploaded photograph into a finished vertical editorial composition that keeps the original photo intact and pairs it with a freshly repainted, selectively abstracted, open-form gouache vignette plus a short poetic English title. Use for photo-plus-illustration diptychs, representational memory panels, broken-boundary compositions, or artwork whose source connection should come from pose, color, and spatial relationships rather than source-pixel cutouts, posterization, or vector tracing.
---

# Photo Editorial Illustration

Create one finished image from one uploaded photograph. Preserve the source photo as evidence; use semantic observation to repaint only its most meaningful visual relationships below as a recognizable but incomplete editorial illustration.

## Invocation

The user only needs to upload one photograph and ask:

> Use `$photo-editorial-illustration` to turn this photo into a photo-plus-painterly-vignette editorial composition.

Do not ask the user to supply style-reference images or repeat the production prompt.

## Required Reference

Read [references/art-direction.md](references/art-direction.md) completely before generating the artwork. Apply it as the production specification, including its omission logic, open-boundary rules, and rejection checks.

## Workflow

1. Inspect the photograph and identify three to six semantic anchors: the primary subject, gesture or body axis, strongest spatial relationship, one identity cue, dominant color role, and main light-shadow tension. Describe these anchors in words; do not extract them as masks or cutouts.
2. Rank those anchors. Select only three to five for the lower vignette. For portraits and people, omit or reinvent 50-70% of photographed detail. For landscapes, architecture, crowds, and machines, omit 30-60% when it does not carry identity or narrative weight.
3. Crop by meaning rather than by the source aspect ratio. Remove large areas of sky, floor, wall, water, foliage, or side clutter when they only fill the photograph. Retain a background region only when it explains the subject or carries a decisive color or light relationship.
4. Plan a vertical composition with the unmodified photograph above and a warm ivory panel below. Do not place a second rectangular image inside the panel.
5. Generate the lower vignette from scratch from the written semantic anchors. Do not transform, trace, posterize, quantize, blur, vectorize, mask, or reuse pixels from the source photograph. Let two to five broad painterly masses, a few independent brush strokes, and ivory negative space define an irregular footprint.
6. Render with matte gouache, tempera, and light watercolor qualities. Preserve gesture, orientation, color roles, and one identity cue, while freely reinventing internal contours, facial information, hair detail, folds, highlights, and shadow boundaries. Allow a meaningful subject or gesture to project beyond a background mass when the source supports it.
7. Create one original English title of two to six words grounded in visible facts or atmosphere. Set it below the vignette in a quiet editorial serif.
8. Produce the final composite. Keep the upper photograph pixels unchanged. Generate the lower vignette separately, then use a raster compositor only to assemble the photograph, ivory panel, generated vignette, and title. The compositor must never create the artistic transformation.
9. Run every rejection check before returning the image. Revise any failed output.

## Abstraction Standard

Aim for 45-65% visual recognizability. A viewer should connect the vignette to the source through three to five semantic anchors, but should not be able to recover the source photograph's internal tonal map.

- Too literal: facial features, hair strands, clothing folds, highlights, shadow boundaries, or local color patches closely map to the photograph. This is tracing, even when painterly texture is added.
- Correct: pose, silhouette axis, dominant clothing or environmental colors, subject relationship, and one identity cue remain recognizable; most internal detail is omitted or freshly invented.
- Too abstract: the pose, subject category, or key spatial relationship cannot be inferred, or the scene collapses into generic icons and disconnected shapes.

- Preserve the primary subject's identity, orientation, and key relationship rather than every contour.
- Preserve perspective only where it supports the retained anchors; allow omitted regions to become ivory negative space.
- Keep people readable through body axis, head mass, clothing mass, gesture, hair direction, or group density. Leave faces blank or minimally indicated. Figures may merge, taper, or dissolve at their edges.
- Keep architecture through selected massing, openings, rooflines, color bands, or structural axes. Do not reproduce every wall.
- Keep landscapes through only the decisive terrain, canopy, cloud, water, or horizon forms. Omit the sky entirely when it is not essential.
- Keep crowds as an intelligible social field while allowing walls, ceilings, floors, and peripheral figures to disappear.

## Open-Form Standard

- Do not inherit the source photo's square, landscape, or portrait boundary.
- Do not use four complete straight edges, a visible frame, or an evenly filled rectangle.
- Make at least one edge interrupted, dissolved, feathered, dry-brushed, or absorbed into the ivory panel.
- Use selective projection deliberately: a person, ladder, roofline, machine part, tree, shadow, or color stroke may cross beyond the main painted mass.
- Keep boundary breaking traceable to the source scene. Do not add random decorative splashes.

## Tool Boundary

- Use an image-generation or image-editing model to create the lower vignette as new pixels from semantic observation.
- A raster editor or compositor may resize, crop, position, mask the newly generated vignette against the ivory panel, and set the title. It may not derive the vignette from the source photograph.
- Do not use source cutouts, subject masks, silhouette extraction, palette reduction, posterization, quantization, edge tracing, auto-vectorization, or blur as a substitute for generation.
- If no image-generation or image-editing model is available, stop and explain that the lower vignette cannot be produced faithfully in the current session. Offer the production prompt if useful, but never return a traced or filtered fallback as the finished artwork.

## Hard Rejections

Reject and redo the lower panel when any of these are true:

- it reads as a rectangular crop, square thumbnail, photo filter, or full-scene repaint;
- it contains any reused source-photo pixels, cutout fragments, masks, or blurred source regions in the lower panel;
- it resembles Adobe Illustrator Image Trace, vector tracing, posterization, quantization, palette reduction, or hard tonal partitions;
- facial features, hair strands, clothing folds, highlights, shadows, or internal contours map closely to the source photo;
- it uses clean geometric icon construction instead of freshly painted masses and independent brush decisions;
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

Return only the completed image unless the user asks for process notes, title options, or prompt text. Do not require style-reference images from the user. When a faithful fresh repaint cannot be generated, say so explicitly instead of returning a deterministic raster imitation.

## Lineage

This skill was independently written after studying the photo-plus-panel concept demonstrated by [ZzzLc0405/photo-abstract-editorial](https://github.com/ZzzLc0405/photo-abstract-editorial). It changes the lower panel into a selective, open-form painterly reconstruction. Do not copy or redistribute the original project's prompts, example images, payment images, or documentation.
