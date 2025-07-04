# Core Image Compositing & Blend Modes

This document covers Core Image compositing and blend filters from Apple’s official composite-operations page, with artistic descriptions and official images grouped by filter type.

---

## Table of Contents

* [Addition](#addition)
* [Color](#color)
* [Color Burn](#color-burn)
* [Color Dodge](#color-dodge)
* [Darken](#darken)
* [Difference](#difference)
* [Divide](#divide)
* [Exclusion](#exclusion)
* [Hard Light](#hard-light)
* [Hue](#hue)
* [Lighten](#lighten)
* [Linear Burn](#linear-burn)
* [Linear Dodge](#linear-dodge)
* [Linear Light](#linear-light)
* [Luminosity](#luminosity)
* [Maximum](#maximum)
* [Minimum](#minimum)
* [Multiply](#multiply)
* [Overlay](#overlay)
* [Pin Light](#pin-light)
* [Saturation](#saturation)
* [Screen](#screen)
* [Soft Light](#soft-light)
* [Source Atop](#source-atop)
* [Source In](#source-in)
* [Source Out](#source-out)
* [Source Over](#source-over)
* [Subtract](#subtract)
* [Vivid Light](#vivid-light)

---

## Composite Operations

### Source Atop
Composites the source image atop the background, only displaying where they overlap.<br>
<img src="https://docs-assets.developer.apple.com/published/eb145f55ccfa8509818269eb5531f393/media-3546396%402x.png" alt="Source Atop" width="50%">

### Source In
Shows the source image only where it overlaps the background. The background acts as a mask for the source.<br>
<img src="https://docs-assets.developer.apple.com/published/fc624344d8a68faaa285115603f73c27/media-3546393%402x.png" alt="Source In" width="50%">

### Source Out
Shows the source image only where it does not overlap the background (i.e., where the background is transparent).<br>
<img src="https://docs-assets.developer.apple.com/published/12eca8bb9047a812577f7e7e45a56f6b/media-3546394%402x.png" alt="Source Out" width="50%">

### Source Over
Draws the source image on top of the background. The default blending mode.<br>
<img src="https://docs-assets.developer.apple.com/published/6d9377d9cdb80cb42d9fdd83f3de78b9/media-3546395%402x.png" alt="Source Over" width="50%">

---

## Blend Modes

### Addition
Brightens the image by adding the source and background pixel values, useful for highlights and light effects.<br>
<img src="https://docs-assets.developer.apple.com/published/850255fdcb98366a0fe7ffc82ce931b1/media-3546408%402x.png" alt="Addition" width="50%">

### Color
Replaces hue and saturation while preserving brightness.<br>
<img src="https://docs-assets.developer.apple.com/published/c6d84a8ac4674865d4fede908c976df0/media-3546407%402x.png" alt="Color" width="50%">

### Color Burn
Darkens the background to reflect the source image, increasing shadows.<br>
<img src="https://docs-assets.developer.apple.com/published/f5fddad6ca54b508c4fba656d099fdab/media-3546399%402x.png" alt="Color Burn" width="50%">

### Color Dodge
Brightens the background to reflect the source image, increasing contrast.<br>
<img src="https://docs-assets.developer.apple.com/published/575af3aae41202604fe04d23b82e50f7/media-3546418%402x.png" alt="Color Dodge" width="50%">

### Darken
Keeps the darker pixels of source or background. Good for layering shadows or textures.<br>
<img src="https://docs-assets.developer.apple.com/published/26d75f0a4bd011875c3889ea932f478f/media-3546416%402x.png" alt="Darken" width="50%">

### Difference
Subtracts darker colors, creating an inverted or “difference” look.<br>
<img src="https://docs-assets.developer.apple.com/published/b8ad8666e41c9d807777fb0511420cc7/media-3546397%402x.png" alt="Difference" width="50%">

### Divide
Brightens the image by dividing the background pixel values by the source. Can create intense light effects or invert colors.<br>
<img src="https://docs-assets.developer.apple.com/published/01b57f7f37deb7b6dccddde7c0f7a890/media-3546405%402x.png" alt="Divide" width="50%">

### Exclusion
Similar to Difference but with lower contrast for subtler effects.<br>
<img src="https://docs-assets.developer.apple.com/published/bcf39409de803bac298bd54e302a84a5/media-3546411%402x.png" alt="Exclusion" width="50%">

### Hard Light
Combines Multiply and Screen but with stronger contrast, like shining a harsh spotlight.<br>
<img src="https://docs-assets.developer.apple.com/published/1d03a04d72c25b3351f013a7a656eacb/media-3546419%402x.png" alt="Hard Light" width="50%">

### Hue
Replaces hue while preserving saturation and brightness.<br>
<img src="https://docs-assets.developer.apple.com/published/b6e2d1cf8904120975dd33de34b1d861/media-3546412%402x.png" alt="Hue" width="50%">

### Lighten
Keeps the lighter pixels of source or background. Useful for brightening and glow effects.<br>
<img src="https://docs-assets.developer.apple.com/published/d5b0a6807e69a0e688169bf4d166626b/media-3546398%402x.png" alt="Lighten" width="50%">

### Linear Burn
Subtracts pixel values, intensely darkening the image.<br>
<img src="https://docs-assets.developer.apple.com/published/904c7771377899996781ec8ee9425ca8/media-3546415%402x.png" alt="Linear Burn" width="50%">

### Linear Dodge
Adds pixel values, aggressively brightening the image.<br>
<img src="https://docs-assets.developer.apple.com/published/821dcc6a7d8d623d24fa3a47a60e1898/media-3546417%402x.png" alt="Linear Dodge" width="50%">

### Linear Light
Adds or subtracts pixels based on source brightness, for strong lighting effects.<br>
<img src="https://docs-assets.developer.apple.com/published/6bdf22ab09bde8745f14009343bb0238/media-4407310%402x.png" alt="Linear Light" width="50%">

### Luminosity
Replaces brightness while preserving hue and saturation.<br>
<img src="https://docs-assets.developer.apple.com/published/d24866f4a3636c88648d2039524eb63b/media-3546410%402x.png" alt="Luminosity" width="50%">

### Maximum
Compares the pixel values of the source and background and keeps the lightest (maximum) value for each color channel.<br>
<img src="https://docs-assets.developer.apple.com/published/26d75f0a4bd011875c3889ea932f478f/media-3546413%402x.png" alt="Maximum" width="50%">

### Minimum
Compares the pixel values of the source and background and keeps the darkest (minimum) value for each color channel.<br>
<img src="https://docs-assets.developer.apple.com/published/5597b559b45973fa33491e579485c6a3/media-3546409%402x.png" alt="Minimum" width="50%">

### Multiply
Darkens the image by multiplying source and background colors. Great for shadows and shading effects.<br>
<img src="https://docs-assets.developer.apple.com/published/53f73125ebba05a4dbd91a7bbd735e2d/media-3546403%402x.png" alt="Multiply" width="50%">

### Overlay
Combines Multiply and Screen modes, enhancing contrast and saturation.<br>
<img src="https://docs-assets.developer.apple.com/published/6a33f91bf21f21594a4a1d2ba71b1c59/media-3546406%402x.png" alt="Overlay" width="50%">

### Pin Light
Replaces pixels depending on brightness, creating striking contrasts.<br>
<img src="https://docs-assets.developer.apple.com/published/84129d656aef8aa793587971b553870b/media-3546414%402x.png" alt="Pin Light" width="50%">

### Saturation
Replaces saturation while preserving hue and brightness.<br>
<img src="https://docs-assets.developer.apple.com/published/714ca45e3700dec0fffcad8ad45cbd39/media-3546404%402x.png" alt="Saturation" width="50%">

### Screen
Brightens the image by inversely multiplying the colors. Good for glows and light overlays.<br>
<img src="https://docs-assets.developer.apple.com/published/9836f664fed2bf605a485e81428868e7/media-3546401%402x.png" alt="Screen" width="50%">

### Soft Light
Applies a soft diffuse lighting effect, subtly brightening or darkening.<br>
<img src="https://docs-assets.developer.apple.com/published/463156a516dd903c1f014180b13fccb6/media-3546420%402x.png" alt="Soft Light" width="50%">

### Subtract
Darkens the image by subtracting the source pixel values from the background. Useful for creating inverse or negative effects.<br>
<img src="https://docs-assets.developer.apple.com/published/6dd0d4f944026ff01958436ea7fffd86/media-3546402%402x.png" alt="Subtract" width="50%">

### Vivid Light
Combination of Color Dodge and Color Burn to intensify highlights and shadows.<br>
<img src="https://docs-assets.developer.apple.com/published/7a399b3bb44e1bdda387b6c2966a1d99/media-4407307%402x.png" alt="Vivid Light" width="50%">
