---
name: photo-editorial-illustration
description: Turn one uploaded photograph into a finished vertical editorial composition that keeps the original photo intact and pairs it with a recognizable, simplified painterly reconstruction plus a short poetic English title. Use when asked for a photo-plus-illustration diptych, representational editorial vignette, painterly memory panel, gouache photo interpretation, or a less-abstract alternative to geometric photo abstraction.
---

# Photo Editorial Illustration

Create one finished image from one uploaded photograph. Preserve the source photo as evidence; reinterpret the same scene below as a restrained but clearly recognizable editorial illustration.

## Invocation

The user only needs to upload one photograph and ask:

> Use `$photo-editorial-illustration` to turn this photo into a photo-plus-painterly-vignette editorial composition.

Do not ask the user to supply style-reference images or repeat the production prompt.

## Required Reference

Read [references/art-direction.md](references/art-direction.md) completely before generating the artwork. Apply it as the production specification, including its rejection checks.

## Workflow

1. Inspect the uploaded photo and identify five to nine scene anchors:
   - the primary subject and its silhouette;
   - subject count, position, scale, orientation, and overlap;
   - horizon, perspective, depth, or dominant structural axes;
   - two to five identifying details;
   - dominant color fields and the main light-shadow pattern.
2. Separate anchors from clutter. Keep everything needed to recognize the scene; remove incidental wires, signs, tiny objects, and texture only when they do not carry identity.
3. Plan a vertical composition with the unmodified photograph above and a warm ivory editorial panel below. Adapt the section proportions to the photo rather than forcing an equal split.
4. Build the lower vignette as a representational scene reconstruction. Simplify the rendering, not the scene logic. Preserve the anchors, perspective, subject arrangement, and dominant colors.
5. Render the vignette with matte gouache, tempera, and light watercolor qualities: broad color shapes, restrained pigment variation, soft hand-painted edges, and selective detail.
6. Create one original English title of two to six words based only on visible facts or atmosphere in the photo. Set it below the vignette in a quiet editorial serif.
7. Produce the final composite. Keep the original photo pixels unchanged whenever possible. If an image model cannot preserve the photo accurately, generate only the lower vignette and assemble the photo, panel, vignette, and title with a raster compositor.
8. Run the rejection checks before returning the image. Revise any failed output.

## Recognition Standard

Aim for 60-80% visual recognizability, not photorealism. A viewer should connect the lower vignette to the source photo immediately without seeing a second reference.

- Retain at least four of the identified scene anchors.
- Preserve complete, simplified silhouettes for primary subjects.
- Preserve the direction of gaze, movement, machinery, architecture, terrain, or other defining forms.
- Represent people with simplified heads, torsos, clothing masses, and gestures. Omit facial detail unless identity depends on it.
- Preserve architecture with its massing, openings, roofline, and distinctive color relationships.
- Preserve landscapes with continuous terrain, canopy, cloud, water, or horizon shapes rather than floating marks.
- Preserve crowds as a coherent field of individual simplified figures with matching density and focal hierarchy.

## Hard Rejections

Reject and redo the lower panel when any of these are true:

- the main subject cannot be named from the vignette;
- people become dots, capsules, bars, or generic symbols;
- architecture or landscape becomes unrelated geometry;
- perspective, orientation, subject count, or spatial hierarchy materially changes;
- invented objects or colors become focal elements;
- the vignette is tiny, decorative, or dominated by empty space;
- the result looks like a logo, infographic, clean vector icon set, generic poster template, anime scene, 3D render, or photorealistic duplicate;
- the final image contains interface chrome, page counters, watermarks, malformed text, or extra captions.

## Output

Return only the completed image unless the user asks for process notes, title options, or prompt text. Do not require style-reference images from the user.

## Lineage

This skill was independently written after studying the photo-plus-panel concept demonstrated by [ZzzLc0405/photo-abstract-editorial](https://github.com/ZzzLc0405/photo-abstract-editorial). It intentionally changes the lower panel from non-representational abstraction to a recognizable painterly reconstruction. Do not copy or redistribute the original project's prompts, example images, payment images, or documentation.
