---
title: Background Layers
url: /utilities/background-layers
menu:
  design_system:
    parent: Utilities
    weight: 40
type: doc
---

Background are handled differently in Version 3. In prior versions, background images would be applied via CSS to the container element of a component. Now images are included via `<img>` tags in the DOM.

Other background elements have been de-coupled from the background image. This allows. are also layered on top of the image rather than... Also mask other colors. More possibilities.

To use... wrap all background elements using the `wvu-bg-img` utility.

Use in section components. Column components give you fewer options.

Will be relevant to the first parent element with its `position` set e.g. `position-relative`. If you notice your background layers are floating at the top of your page, it’s likely because you’re creating a custom component and haven’t set the parent element’s position. All standard section components include a `position-relative` utility class by default in order to prevent this from happening.

## Base Color

- Color
- Gradient

{{< readfile file="headless/color.html" label="Sunset" padding="p-3" >}}

{{< readfile-code file="headless/color.html" code="true" >}}

## Background Image

{{< readfile file="headless/bg-img.html" label="Sunset" padding="p-3" >}}

{{< readfile-code file="headless/bg-img.html" code="true" >}}

Since the `wvu-bg-img` utility... Bootstrap’s `object-fit-` utility... Must have a `height` and `width` attribute.

Anything layered on top should have a `wvu-z-index-content` utility.

Use `srcset`.

## Background Position

## Image Filters

{{< readfile file="headless/bg-img-blend-mode-luminosity.html" label="Sunset" padding="p-3" >}}

{{< readfile-code file="headless/bg-img-blend-mode-luminosity.html" code="true" >}}

{{< readfile file="headless/bg-img-blend-mode-lighten.html" label="Sunset" padding="p-3" >}}

{{< readfile-code file="headless/bg-img-blend-mode-lighten.html" code="true" >}}

## Patterns and Texture

- Patterns
  - Half
  - Quarter
- Texture

Use full when no photo. Do not place patterns or textures entirely over subject’s face. If you want to layer a pattern or texture over a background photo, match the grid of your content (these exist independently, so you will have to make sure to match them up).

Patterns can go underneath or over the top of photos. Use appropriate `z-index-` utility.

## Mask Layer

Can be one of

- Thick Border
- Mountains Top
- Mountains Bottom
- Mountains Top and Bottom
- Diagonals

{{< readfile file="headless/mask-slash.html" label="Sunset" padding="p-3" >}}

{{< readfile-code file="headless/mask-slash.html" code="true" >}}

{{< readfile file="headless/mask-slash-blend-mode-color.html" label="Sunset" padding="p-3" >}}

{{< readfile-code file="headless/mask-slash-blend-mode-color.html" code="true" >}}

Make sure you’re using the same background color as adjacent sections. Should not be used when adjacent sections have a photo as their background, or a pattern applied, only solid color.

Add an accent.

Shadow.

Outline.

You can have multiple diagonals. To do half, use `h-50` utility.

Unless the only diagonal, the front layer(s) should be a solid color with no blend mode or filter. Only the 'closest' layer to the photo should have a filter applied.

## Can Be Extended

## Mobile Devices

## Putting It All Together

Here are some recommended combinations.