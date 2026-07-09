# Prompt Templates

Use these snippets when generating image-to-image packaging finish mockups.

## Clean Portfolio Aesthetic (must include in every prompt)

```text
Design portfolio quality, Behance showcase standard, clean and crisp product photography.
Pure white or very light neutral background (#F5F5F5), generous negative space around the product.
Bright airy studio lighting with large softbox and white reflector, soft diffused clean drop shadow on ground.
Crisp sharp packaging edges, pure accurate colors with no color cast, no grey haze over the image.
No muddy shadows, no HDR over-processing, no vignette, no noise or grain, no dirty background.
Minimalist presentation, professional packaging design portfolio aesthetic, fresh and clean look.
```

## Two-Image Workflow

```text
Image 1 is the finish annotation/reference only. Image 2 is the protected original/base image. Use Image 2 as the final composition, camera angle, bottle/box geometry, label placement, artwork, typography, and layout. Use Image 1 only to understand which regions need finishing. Do not include annotation boxes or red outlines.

Image style: clean studio lighting, pure white background, soft diffused shadow, design portfolio quality, no muddy tones, no color cast, no HDR over-processing.
```

## Original Protection

```text
Preserve the exact original packaging artwork: all Chinese text, English text, logo, product name, small copy, colors, icons, label proportions, bottle shape, cap shape, perspective, and lighting composition. Do not redesign, rewrite, translate, simplify, hallucinate, or distort any text.
```

## Chinese Text Safety

```text
No fake Chinese characters, no warped Chinese text, no misspelled text, no random letters, no invented copy, no typography changes. Apply finish to the existing printed contours only.
```

## Silver Dragon PET + Spot UV

```text
Material: silver dragon PET label, satin metallic silver film, subtle cool pearlescent sheen, fine PET film texture, realistic adhesive label edge. Apply transparent clear spot UV varnish only to the specified artwork elements. The UV should create angle-dependent glossy highlights and slight raised thickness while preserving the base print colors.

Image style: clean bright studio lighting, pure white background, soft diffused shadow, design portfolio quality, fresh and crisp look, no muddy tones.
```

## Specialty Paper + Foil + UV

```text
Material: textured specialty paper with fine visible fibers and matte tactile surface. Add restrained champagne gold foil on the specified logo/accent areas, with directional metallic reflection and crisp edges. Add clear spot UV on selected patterns for gloss/matte contrast. Keep all finishes physically attached to the paper surface.

Image style: clean bright studio lighting, pure white background, soft diffused shadow, design portfolio quality, fresh and crisp look, no muddy tones.
```

## Bottle Body + Label Combined Prompt

Use when generating a bottle packaging effect image with both body finish and label.

```text
Bottle body material: [glass/PET/acrylic/PP-PE/aluminum/ceramic].
Bottle body finish: [matte spray/glossy spray/soft-touch spray/gradient spray/electroplating/frosted/silk screen on bottle/hot stamp on bottle/decal/laser engraving/mold finish/none].
The bottle surface has a [matte/glossy/metallic/frosted/clear] appearance.
The finish must wrap naturally around the 3D cylindrical/curved bottle surface, following the bottle's contour and perspective.
Label type: [self-adhesive label/shrink sleeve/IML in-mold label/direct silk screen/heat transfer].
Label material: [silver PET/clear PET/white PET/pearlescent PET/coated paper/specialty paper/synthetic paper].
Label finish: [spot UV/hot foil/matte varnish/emboss/none].
Do not alter the bottle shape, cap/pump design, label position, or artwork content.
Preserve all Chinese text, logo, and layout on the label.
The bottle body finish and label must look physically compatible — no floating labels, no finish bleeding onto label area, realistic material interaction.

Image style: clean studio lighting, bright and airy, pure white or very light neutral background,
soft diffused drop shadow, design portfolio quality, crisp edges, pure colors, no muddy tones,
no HDR over-processing, no dirty background, fresh and clean look.
```

## Flexible Pouch Prompt

Use when generating a soft pouch/bag packaging effect image.

```text
Pouch type: [stand-up pouch (doypack) / 3-side seal pouch / quad-seal box pouch / zipper bag / spout pouch / tissue soft pack / hygiene pillow pack].
Pouch structure: [bottom gusset / side gussets / flat / pillow-shaped].
The pouch should appear naturally filled with product, showing soft natural folds and gentle creases — not rigid like a paper box.
Laminate material: [PET/PE / PET/AL/PE aluminum foil / PET/VMPET/PE metallized / OPP/CPP / MATT OPP/PE / kraft paper/PE / pure PE film].
The material surface has a [matte/glossy/metallic/natural kraft/transparent] appearance with subtle film texture.
Print finish: [matte/gloss varnish contrast / spot UV on film / cold foil stamping / holographic film effect / simple flexo print / none].
Functional features: [zipper/resealable strip at top / spout with screw cap / tear notch / hang hole (Euro slot) / transparent window / none].
The functional features must look like welded attachments, not floating elements.
Heat seal edges (5-10mm on sides and bottom) must remain clean and unprinted — no finish crossing the seal area.
Do not alter the pouch shape, artwork content, or label position.
Preserve all Chinese text, logo, and layout on the pouch surface.
No rigid emboss/deboss effects (not physically possible on flexible film).

Image style: clean studio lighting, bright and airy, pure white or very light neutral background,
soft diffused drop shadow, design portfolio quality, crisp edges where applicable,
the pouch should have natural soft contours and gentle film creases,
no muddy tones, no HDR over-processing, no dirty background, fresh and clean look.
```

## Negative Constraints

```text
No annotation marks, no red boxes, no arrows, no masks, no redesigned packaging, no changed product name, no fake text, no distorted Chinese, no floating stickers, no glowing foil, no excessive gloss, no finish outside selected regions, no full flat label compressed onto the front.

No grey haze over entire image, no muddy dirty shadows (black/yellow/grainy), no color cast (warm yellow / cool blue / grey-green tint), no HDR over-processing (crushed blacks / blown highlights), no noise or grain (unless specialty paper texture), no dirty or uneven background (vignette / gradient stains / color patches), no white areas appearing grey or yellow (white must be pure white), no saturation anomalies (over-saturated neon or washed-out faded), no dark areas lacking detail (shadows must be airy with visible gradation), no cheap mockup feel.
```
