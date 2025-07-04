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
![Hard Light](https://docs-assets.developer.apple.com/published/1d03a04d72c25b3351f013a7a656eacb/media-3546419%402x.png)

### Difference  
Subtracts darker colors, creating an inverted or “difference” look.  
![Difference](https://docs-assets.developer.apple.com/published/b8ad8666e41c9d807777fb0511420cc7/media-3546397%402x.png)

### Exclusion  
Similar to Difference but with lower contrast for subtler effects.  
![Exclusion](https://docs-assets.developer.apple.com/published/bcf39409de803bac298bd54e302a84a5/media-3546411%402x.png)

### Color Dodge  
Brightens the background to reflect the source image, increasing contrast.  
![Color Dodge](https://docs-assets.developer.apple.com/published/575af3aae41202604fe04d23b82e50f7/media-3546418%402x.png)

### Color Burn  
Darkens the background to reflect the source image, increasing shadows.  
![Color Burn](https://docs-assets.developer.apple.com/published/f5fddad6ca54b508c4fba656d099fdab/media-3546399%402x.png)

### Linear Dodge  
Adds pixel values, aggressively brightening the image.  
![Linear Dodge](https://docs-assets.developer.apple.com/published/01f2927766f0f3e12cfe1ac43f975f39/media-3546415%402x.png)

### Linear Burn  
Subtracts pixel values, intensely darkening the image.  
![Linear Burn](https://docs-assets.developer.apple.com/published/904c7771377899996781ec8ee9425ca8/media-3546415%402x.png)

### Vivid Light  
Combination of Color Dodge and Color Burn to intensify highlights and shadows.  
![Vivid Light](https://docs-assets.developer.apple.com/published/7a399b3bb44e1bdda387b6c2966a1d99/media-4407307%402x.png)

### Linear Light  
Adds or subtracts pixels based on source brightness, for strong lighting effects.  
![Linear Light](https://docs-assets.developer.apple.com/published/6bdf22ab09bde8745f14009343bb0238/media-4407310%402x.png)

### Pin Light  
Replaces pixels depending on brightness, creating striking contrasts.  
![Pin Light](https://docs-assets.developer.apple.com/published/84129d656aef8aa793587971b553870b/media-3546414%402x.png)

### Hard Mix  
Adds high contrast posterization, turning pixels fully black or white.  
![Hard Mix](https://docs-assets.developer.apple.com/published/37e7215ef3d5a3aa98d8e3999b2656e1/media-3546415%402x.png)

### Hue  
Replaces hue while preserving saturation and brightness.  
![Hue](https://docs-assets.developer.apple.com/published/b6e2d1cf8904120975dd33de34b1d861/media-3546412%402x.png)

### Saturation  
Replaces saturation while preserving hue and brightness.  
![Saturation](https://docs-assets.developer.apple.com/published/714ca45e3700dec0fffcad8ad45cbd39/media-3546404%402x.png)

### Color  
Replaces hue and saturation while preserving brightness.  
![Color](https://docs-assets.developer.apple.com/published/c6d84a8ac4674865d4fede908c976df0/media-3546407%402x.png)

### Luminosity  
Replaces brightness while preserving hue and saturation.  
![Luminosity](https://docs-assets.developer.apple.com/published/d24866f4a3636c88648d2039524eb63b/media-3546410%402x.png)

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
