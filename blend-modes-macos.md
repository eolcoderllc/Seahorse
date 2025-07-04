# Core Image Compositing Modes

This document explains the main compositing modes available in Core Image on macOS/iOS, with artistic descriptions and linked examples hosted on Apple’s developer site.

---

## Add

Brightens the image by adding the source and background pixel values. Useful for highlights and light effects.

![Add](https://docs-assets.developer.apple.com/published/850255fdcb98366a0fe7ffc82ce931b1/media-3546408%402x.png)

---

## Multiply

Darkens the image by multiplying source and background colors. Great for shadows and shading effects.

![Multiply](https://docs-assets.developer.apple.com/published/53f73125ebba05a4dbd91a7bbd735e2d/media-3546403%402x.png)

---

## Darken

Keeps the darker pixels of source or background. Good for layering shadows or textures.

![Darken](https://docs-assets.developer.apple.com/published/26d75f0a4bd011875c3889ea932f478f/media-3546416%402x.png)

---

## Lighten

Keeps the lighter pixels of source or background. Useful for brightening and glow effects.

![Lighten](https://docs-assets.developer.apple.com/published/d5b0a6807e69a0e688169bf4d166626b/media-3546398%402x.png)

---

## Overlay

Combines Multiply and Screen modes, enhancing contrast and saturation.

![Overlay](https://docs-assets.developer.apple.com/published/6a33f91bf21f21594a4a1d2ba71b1c59/media-3546406%402x.png)

---

## Screen

Brightens the image by inversely multiplying the colors. Good for glows and light overlays.

![Screen](https://docs-assets.developer.apple.com/published/9836f664fed2bf605a485e81428868e7/media-3546401%402x.png)

---

## Soft Light

Applies a soft diffuse lighting effect, subtly brightening or darkening.

![Soft Light](https://docs-assets.developer.apple.com/published/07a2fae08611be9c2cb8c1f5f40ccae7/media-3546420%402x.png)

---

## Hard Light

Combines Multiply and Screen but with stronger contrast, like shining a harsh spotlight.

![Hard Light](https://docs-assets.developer.apple.com/published/6b416b4a2214a6ee65c3c9687b40cf2c/media-3546423%402x.png)

---

## Difference

Subtracts darker colors, creating an inverted or “difference” look.

![Difference](https://docs-assets.developer.apple.com/published/2224d8579bcd143eb74e52a960f1a5f8/media-3546421%402x.png)

---

## Exclusion

Similar to Difference but with lower contrast for subtler effects.

![Exclusion](https://docs-assets.developer.apple.com/published/5d62ee738f032bab9910c2a547af4f1b/media-3546422%402x.png)

---

## Source In

Shows the source only where the background exists; useful for masking.

![Source In](https://docs-assets.developer.apple.com/published/f6a4ff8bb3d27d76367f5ef1719d59b7/media-3546418%402x.png)

---

## Source Out

Shows the source where the background is transparent; useful for “cutouts”.

![Source Out](https://docs-assets.developer.apple.com/published/8e7f71af9425b2f7cb45b7a233ff12f3/media-3546417%402x.png)

---

## Destination Over

Draws the background over the source.

![Destination Over](https://docs-assets.developer.apple.com/published/f66b607f7c5b06da9bbba9c82cc6b04a/media-3546419%402x.png)
