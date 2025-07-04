# Core Image Compositing & Blend Modes

This document covers Core Image compositing and blend filters from Apple’s official composite-operations page, with artistic descriptions and official images grouped by filter type.

---

## Composite Operations

### Add  
Brightens the image by adding the source and background pixel values, useful for highlights and light effects.  
![Add](https://docs-assets.developer.apple.com/published/850255fdcb98366a0fe7ffc82ce931b1/media-3546408%402x.png)

### Multiply  
Darkens the image by multiplying source and background colors. Great for shadows and shading effects.  
![Multiply](https://docs-assets.developer.apple.com/published/53f73125ebba05a4dbd91a7bbd735e2d/media-3546403%402x.png)

### Darken  
Keeps the darker pixels of source or background. Good for layering shadows or textures.  
![Darken](https://docs-assets.developer.apple.com/published/26d75f0a4bd011875c3889ea932f478f/media-3546416%402x.png)

### Lighten  
Keeps the lighter pixels of source or background. Useful for brightening and glow effects.  
![Lighten](https://docs-assets.developer.apple.com/published/d5b0a6807e69a0e688169bf4d166626b/media-3546398%402x.png)

### Overlay  
Combines Multiply and Screen modes, enhancing contrast and saturation.  
![Overlay](https://docs-assets.developer.apple.com/published/6a33f91bf21f21594a4a1d2ba71b1c59/media-3546406%402x.png)

### Screen  
Brightens the image by inversely multiplying the colors. Good for glows and light overlays.  
![Screen](https://docs-assets.developer.apple.com/published/9836f664fed2bf605a485e81428868e7/media-3546401%402x.png)

---

## Blend Modes

### Soft Light  
Applies a soft diffuse lighting effect, subtly brightening or darkening.  
![Soft Light](https://docs-assets.developer.apple.com/published/463156a516dd903c1f014180b13fccb6/media-3546420%402x.png)

### Hard Light  
Combines Multiply and Screen but with stronger contrast, like shining a harsh spotlight.  
![Hard Light](https://docs-assets.developer.apple.com/published/1cfa5f0a3702e584b3a804b46d4a7e94/media-3546423%402x.png)

### Difference  
Subtracts darker colors, creating an inverted or “difference” look.  
![Difference](https://docs-assets.developer.apple.com/published/691a36c10e1f6e4c243d7f7e1e4f00bf/media-3546421%402x.png)

### Exclusion  
Similar to Difference but with lower contrast for subtler effects.  
![Exclusion](https://docs-assets.developer.apple.com/published/79e2a1920dfd1c425f681726390098e9/media-3546422%402x.png)

### Color Dodge  
Brightens the background to reflect the source image, increasing contrast.  
![Color Dodge](https://docs-assets.developer.apple.com/published/b09b20b7ef0d788441fafff56443bc8b/media-3546415%402x.png)

### Color Burn  
Darkens the background to reflect the source image, increasing shadows.  
![Color Burn](https://docs-assets.developer.apple.com/published/ca62e83c254f7a96f3fcdac167a27e0f/media-3546410%402x.png)

### Linear Dodge  
Adds pixel values, aggressively brightening the image.  
![Linear Dodge](https://docs-assets.developer.apple.com/published/01f2927766f0f3e12cfe1ac43f975f39/media-3546415%402x.png)

### Linear Burn  
Subtracts pixel values, intensely darkening the image.  
![Linear Burn](https://docs-assets.developer.apple.com/published/7af230e01bc69c46f54ae7069654c3d8/media-3546410%402x.png)

### Vivid Light  
Combination of Color Dodge and Color Burn to intensify highlights and shadows.  
![Vivid Light](https://docs-assets.developer.apple.com/published/8d726a29d4945e9a1a24a33168b1b38f/media-3546415%402x.png)

### Linear Light  
Adds or subtracts pixels based on source brightness, for strong lighting effects.  
![Linear Light](https://docs-assets.developer.apple.com/published/f415b76ce70e9b098fe816c0954d65ec/media-3546415%402x.png)

### Pin Light  
Replaces pixels depending on brightness, creating striking contrasts.  
![Pin Light](https://docs-assets.developer.apple.com/published/6a4d345508d43b85b2e58038468cc0ee/media-3546415%402x.png)

### Hard Mix  
Adds high contrast posterization, turning pixels fully black or white.  
![Hard Mix](https://docs-assets.developer.apple.com/published/37e7215ef3d5a3aa98d8e3999b2656e1/media-3546415%402x.png)

### Hue  
Replaces hue while preserving saturation and brightness.  
![Hue](https://docs-assets.developer.apple.com/published/17a4f2b5d0492e86ab1a01b4607b94f8/media-3546415%402x.png)

### Saturation  
Replaces saturation while preserving hue and brightness.  
![Saturation](https://docs-assets.developer.apple.com/published/cf01d07f019db4e0dbd2b0ec44f57f31/media-3546415%402x.png)

### Color  
Replaces hue and saturation while preserving brightness.  
![Color](https://docs-assets.developer.apple.com/published/c8b7ed379bc811787cd2768e4d9e8d97/media-3546415%402x.png)

### Luminosity  
Replaces brightness while preserving hue and saturation.  
![Luminosity](https://docs-assets.developer.apple.com/published/9d79054892d43a3810ff2a6a3a3e31b7/media-3546415%402x.png)

---

## Masking Operations

### Source In  
Shows the source only where the background exists; useful for masking.  
![Source In](https://docs-assets.developer.apple.com/published/fbe77ebf330b4ed9aa2628f1ab5df57d/media-3546409%402x.png)

### Source Out  
Shows the source only where the background is transparent; useful for “cutouts”.  
![Source Out](https://docs-assets.developer.apple.com/published/c716c8d9966b2d738b28f10f73a2a18c/media-3546407%402x.png)

### Destination Over  
Draws the background over the source.  
![Destination Over](https://docs-assets.developer.apple.com/published/f3e2e3e38d52f3f810dbd3bc2184a9d4/media-3546419%402x.png)
