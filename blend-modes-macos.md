# Core Image Compositing Modes

This document explains the main compositing modes available in Core Image on macOS/iOS, with artistic descriptions and linked examples hosted on Apple’s developer site.

---

## Add

Brightens the image by adding the source and background pixel values. Useful for highlights and light effects.

![Add](https://docs-assets.developer.apple.com/published/850255fdcb98366a0fe7ffc82ce931b1/media-3546408%402x.png)

---

## Multiply

Darkens the image by multiplying source and background colors. Great for shadows and shading effects.

![Multiply](https://developer.apple.com/library/archive/documentation/GraphicsImaging/Reference/CoreImageFilterReference/Art/CIMultiplyCompositing.png)

---

## Darken

Keeps the darker pixels of source or background. Good for layering shadows or textures.

![Darken](https://developer.apple.com/library/archive/documentation/GraphicsImaging/Reference/CoreImageFilterReference/Art/CIDarkenBlendMode.png)

---

## Lighten

Keeps the lighter pixels of source or background. Useful for brightening and glow effects.

![Lighten](https://developer.apple.com/library/archive/documentation/GraphicsImaging/Reference/CoreImageFilterReference/Art/CILightenBlendMode.png)

---

## Overlay

Combines Multiply and Screen modes, enhancing contrast and saturation.

![Overlay](https://developer.apple.com/library/archive/documentation/GraphicsImaging/Reference/CoreImageFilterReference/Art/CIOverlayBlendMode.png)

---

## Screen

Brightens the image by inversely multiplying the colors. Good for glows and light overlays.

![Screen](https://developer.apple.com/library/archive/documentation/GraphicsImaging/Reference/CoreImageFilterReference/Art/CIScreenBlendMode.png)

---

## Soft Light

Applies a soft diffuse lighting effect, subtly brightening or darkening.

![Soft Light](https://developer.apple.com/library/archive/documentation/GraphicsImaging/Reference/CoreImageFilterReference/Art/CISoftLightBlendMode.png)

---

## Hard Light

Combines Multiply and Screen but with stronger contrast, like shining a harsh spotlight.

![Hard Light](https://developer.apple.com/library/archive/documentation/GraphicsImaging/Reference/CoreImageFilterReference/Art/CIHardLightBlendMode.png)

---

## Difference

Subtracts darker colors, creating an inverted or “difference” look.

![Difference](https://developer.apple.com/library/archive/documentation/GraphicsImaging/Reference/CoreImageFilterReference/Art/CIDifferenceBlendMode.png)

---

## Exclusion

Similar to Difference but with lower contrast for subtler effects.

![Exclusion](https://developer.apple.com/library/archive/documentation/GraphicsImaging/Reference/CoreImageFilterReference/Art/CIExclusionBlendMode.png)

---

## Source In

Shows the source only where the background exists; useful for masking.

![Source In](https://developer.apple.com/library/archive/documentation/GraphicsImaging/Reference/CoreImageFilterReference/Art/CISourceInCompositing.png)

---

## Source Out

Shows the source where the background is transparent; useful for “cutouts”.

![Source Out](https://developer.apple.com/library/archive/documentation/GraphicsImaging/Reference/CoreImageFilterReference/Art/CISourceOutCompositing.png)

---

## Destination Over

Draws the background over the source.

![Destination Over](https://developer.apple.com/library/archive/documentation/GraphicsImaging/Reference/CoreImageFilterReference/Art/CIDestinationOverCompositing.png)
