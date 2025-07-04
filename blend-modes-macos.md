# Core Image Compositing & Blend Modes

This document covers Core Image compositing and blend filters from Apple’s official composite-operations page, with artistic descriptions and official images grouped by filter type.

---

## Composite Operations

### Clear
Makes pixels transparent where the source image overlaps the background. Effectively punches a hole.
<img src="https://docs-assets.developer.apple.com/published/a3f01b0f1606a38618e47d4e5f7a01d6/media-3546413%402x.png" alt="Clear" width="50%">

### Copy
Replaces the background with the source image entirely, ignoring the background's existing pixels.
<img src="https://docs-assets.developer.apple.com/published/a523a1a9e9a4051a8f94602f23b7b25e/media-3546409%402x.png" alt="Copy" width="50%">

### Source Over
Draws the source image on top of the background. The default blending mode.
<img src="https://docs-assets.developer.apple.com/published/6290d2e8b0124b8988e0b6df423f7d1b/media-3546408%402x.png" alt="Source Over" width="50%">

### Source Atop
Composites the source image atop the background, only displaying where they overlap.
<img src="https://docs-assets.developer.apple.com/published/2b1f81d1136d8d9f10a699a27c1340b9/media-3546395%402x.png" alt="Source Atop" width="50%">

### Destination Over
Draws the background over the source.
<img src="https://docs-assets.developer.apple.com/published/f3e2e3e38d52f3f810dbd3bc2184a9d4/media-3546419%402x.png" alt="Destination Over" width="50%">

### Destination In
Shows the background only where the source exists. The source acts as an inverse mask for the background.
<img src="https://docs-assets.developer.apple.com/published/bb1b8273617304192b00ff3d52601700/media-3546400%402x.png" alt="Destination In" width="50%">

### Destination Out
Shows the background only where the source is transparent. The source cuts a hole in the background.
<img src="https://docs-assets.developer.apple.com/published/3d1c4794e2264ee161ce38f61559e2a3/media-3546405%402x.png" alt="Destination Out" width="50%">

### Destination Atop
Composites the background atop the source, only displaying where they overlap.
<img src="https://docs-assets.developer.apple.com/published/617c0b05b38ed6c06a337f9e8557e0e7/media-3546402%402x.png" alt="Destination Atop" width="50%">

### Xor
Combines source and background, with overlapping areas becoming transparent. Useful for reversible selections.
<img src="https://docs-assets.developer.apple.com/published/0ff01d29381504945118f6c382103f16/media-3546417%402x.png" alt="Xor" width="50%">

### Plus Darker
Adds the source and background pixel values, resulting in a darker combined image.
<img src="https://docs-assets.developer.apple.com/published/77c9803d3683697a216e91f16ed87a55/media-3546408%402x.png" alt="Plus Darker" width="50%">

### Plus Lighter (or Add)
Brightens the image by adding the source and background pixel values, useful for highlights and light effects.
<img src="https://docs-assets.developer.apple.com/published/850255fdcb98366a0fe7ffc82ce931b1/media-3546408%402x.png" alt="Plus Lighter" width="50%">

---

## Blend Modes

### Add  
Brightens the image by adding the source and background pixel values, useful for highlights and light effects.  
<img src="https://docs-assets.developer.apple.com/published/850255fdcb98366a0fe7ffc82ce931b1/media-3546408%402x.png" alt="Add" width="50%">

### Multiply  
Darkens the image by multiplying source and background colors. Great for shadows and shading effects.  
<img src="https://docs-assets.developer.apple.com/published/53f73125ebba05a4dbd91a7bbd735e2d/media-3546403%402x.png" alt="Multiply" width="50%">

### Darken  
Keeps the darker pixels of source or background. Good for layering shadows or textures.  
<img src="https://docs-assets.developer.apple.com/published/26d75f0a4bd011875c3889ea932f478f/media-3546416%402x.png" alt="Darken" width="50%">

### Lighten  
Keeps the lighter pixels of source or background. Useful for brightening and glow effects.  
<img src="https://docs-assets.developer.apple.com/published/d5b0a6807e69a0e688169bf4d166626b/media-3546398%402x.png" alt="Lighten" width="50%">

### Overlay  
Combines Multiply and Screen modes, enhancing contrast and saturation.  
<img src="https://docs-assets.developer.apple.com/published/6a33f91bf21f21594a4a1d2ba71b1c59/media-3546406%402x.png" alt="Overlay" width="50%">

### Screen  
Brightens the image by inversely multiplying the colors. Good for glows and light overlays.  
<img src="https://docs-assets.developer.apple.com/published/9836f664fed2bf605a485e81428868e7/media-3546401%402x.png" alt="Screen" width="50%">

### Soft Light  
Applies a soft diffuse lighting effect, subtly brightening or darkening.  
<img src="https://docs-assets.developer.apple.com/published/463156a516dd903c1f014180b13fccb6/media-3546420%402x.png" alt="Soft Light" width="50%">

### Hard Light  
Combines Multiply and Screen but with stronger contrast, like shining a harsh spotlight.  
<img src="https://docs-assets.developer.apple.com/published/1d03a04d72c25b3351f013a7a656eacb/media-3546419%402x.png" alt="Hard Light" width="50%">

### Difference  
Subtracts darker colors, creating an inverted or “difference” look.  
<img src="https://docs-assets.developer.apple.com/published/b8ad8666e41c9d807777fb0511420cc7/media-3546397%402x.png" alt="Difference" width="50%">

### Exclusion  
Similar to Difference but with lower contrast for subtler effects.  
<img src="https://docs-assets.developer.apple.com/published/bcf39409de803bac298bd54e302a84a5/media-3546411%402x.png" alt="Exclusion" width="50%">

### Color Dodge  
Brightens the background to reflect the source image, increasing contrast.  
<img src="https://docs-assets.developer.apple.com/published/575af3aae41202604fe04d23b82e50f7/media-3546418%402x.png" alt="Color Dodge" width="50%">

### Color Burn  
Darkens the background to reflect the source image, increasing shadows.  
<img src="https://docs-assets.developer.apple.com/published/f5fddad6ca54b508c4fba656d099fdab/media-3546399%402x.png" alt="Color Burn" width="50%">

### Linear Dodge  
Adds pixel values, aggressively brightening the image.  
<img src="https://docs-assets.developer.apple.com/published/01f2927766f0f3e12cfe1ac43f975f39/media-3546415%402x.png" alt="Linear Dodge" width="50%">

### Linear Burn  
Subtracts pixel values, intensely darkening the image.  
<img src="https://docs-assets.developer.apple.com/published/904c7771377899996781ec8ee9425ca8/media-3546415%402x.png" alt="Linear Burn" width="50%">

### Vivid Light  
Combination of Color Dodge and Color Burn to intensify highlights and shadows.  
<img src="https://docs-assets.developer.apple.com/published/7a399b3bb44e1bdda387b6c2966a1d99/media-4407307%402x.png" alt="Vivid Light" width="50%">

### Linear Light  
Adds or subtracts pixels based on source brightness, for strong lighting effects.  
<img src="https://docs-assets.developer.apple.com/published/6bdf22ab09bde8745f14009343bb0238/media-4407310%402x.png" alt="Linear Light" width="50%">

### Pin Light  
Replaces pixels depending on brightness, creating striking contrasts.  
<img src="https://docs-assets.developer.apple.com/published/84129d656aef8aa793587971b553870b/media-3546414%402x.png" alt="Pin Light" width="50%">

### Hard Mix  
Adds high contrast posterization, turning pixels fully black or white.  
<img src="https://docs-assets.developer.apple.com/published/37e7215ef3d5a3aa98d8e3999b2656e1/media-3546415%402x.png" alt="Hard Mix" width="50%">

### Hue  
Replaces hue while preserving saturation and brightness.  
<img src="https://docs-assets.developer.apple.com/published/b6e2d1cf8904120975dd33de34b1d861/media-3546412%402x.png" alt="Hue" width="50%">

### Saturation  
Replaces saturation while preserving hue and brightness.  
<img src="https://docs-assets.developer.apple.com/published/714ca45e3700dec0fffcad8ad45cbd39/media-3546404%402x.png" alt="Saturation" width="50%">

### Color  
Replaces hue and saturation while preserving brightness.  
<img src="https://docs-assets.developer.apple.com/published/c6d84a8ac4674865d4fede908c976df0/media-3546407%402x.png" alt="Color" width="50%">

### Luminosity  
Replaces brightness while preserving hue and saturation.  
<img src="https://docs-assets.developer.apple.com/published/d24866f4a3636c88648d2039524eb63b/media-3546410%402x.png" alt="Luminosity" width="50%">

---

## Masking Operations

### Source In  
Shows the source only where the background exists; useful for masking.  
<img src="https://docs-assets.developer.apple.com/published/fc624344d8a68faaa285115603f73c27/media-3546393%402x.png" alt="Source In" width="50%">

### Source Out  
Shows the source only where the background is transparent; useful for “cutouts”.  
<img src="https://docs-assets.developer.apple.com/published/12eca8bb9047a812577f7e7e45a56f6b/media-3546394%402x.png" alt="Source Out" width="50%">

### Destination In
Shows the background only where the source exists. The source acts as an inverse mask for the background.
<img src="https://docs-assets.developer.apple.com/published/bb1b8273617304192b00ff3d52601700/media-3546400%402x.png" alt="Destination In" width="50%">

### Destination Out
Shows the background only where the source is transparent. The source cuts a hole in the background.
<img src="https://docs-assets.developer.apple.com/published/3d1c4794e2264ee161ce38f61559e2a3/media-3546405%402x.png" alt="Destination Out" width="50%">

### Source Atop
Composites the source image atop the background, only displaying where they overlap.
<img src="https://docs-assets.developer.apple.com/published/2b1f81d1136d8d9f10a699a27c1340b9/media-3546395%402x.png" alt="Source Atop" width="50%">

### Destination Atop
Composites the background atop the source, only displaying where they overlap.
<img src="https://docs-assets.developer.apple.com/published/617c0b05b38ed6c06a337f9e8557e0e7/media-3546402%402x.png" alt="Destination Atop" width="50%">

### Clear
Makes pixels transparent where the source image overlaps the background. Effectively punches a hole.
<img src="https://docs-assets.developer.apple.com/published/a3f01b0f1606a38618e47d4e5f7a01d6/media-3546413%402x.png" alt="Clear" width="50%">

### Copy
Replaces the background with the source image entirely, ignoring the background's existing pixels.
<img src="https://docs-assets.developer.apple.com/published/a523a1a9e9a4051a8f94602f23b7b25e/media-3546409%402x.png" alt="Copy" width="50%">

### Xor
Combines source and background, with overlapping areas becoming transparent. Useful for reversible selections.
<img src="https://docs-assets.developer.apple.com/published/0ff01d29381504945118f6c382103f16/media-3546417%402x.png" alt="Xor" width="50%">
