# Vicar Oil - Stock Photos & Assets

## Color Palette
- **Dark Blue**: #003366
- **Gold**: #FFD700  
- **White**: #FFFFFF

---

## Recommended Stock Photos for Hero Section

### Refinery at Golden Hour

| # | Source | URL | Notes |
|---|--------|-----|-------|
| 1 | Unsplash | https://unsplash.com/photos/steel-oil-pipes-from-refinery-in-desert-during-sunset-TIrP4DTKJoc | Steel oil pipes, desert sunset |
| 2 | Unsplash | https://unsplash.com/photos/oil-and-gas-refinery-during-sunset-lJQ-ecj4CAs | Oil and gas refinery sunset |
| 3 | Unsplash | https://unsplash.com/photos/a-view-of-an-oil-refinery-at-dusk-3svqKKUUDRY | Aerial view at dusk |
| 4 | Pexels | https://www.pexels.com/photo/aerial-view-of-an-oil-refinery-at-sunset-10407692/ | Aerial view, sunset |
| 5 | Unsplash | https://unsplash.com/photos/pump-jack-silhouette-against-a-sunset-sky-with-reflections-in-the-water-3KrvzDGtvQU | Pump jack silhouette |
| 6 | Pexels | https://www.pexels.com/photo/oil-well-at-sunset-16862261/ | Oil well at sunset |

---

## SVG Patterns (15% opacity overlays)

### Oil Droplet Pattern
```svg
<pattern id="oil-droplet" width="60" height="60" patternUnits="userSpaceOnUse">
  <circle cx="30" cy="30" r="12" fill="#003366" opacity="0.15"/>
  <ellipse cx="30" cy="32" rx="8" ry="10" fill="#003366" opacity="0.1"/>
</pattern>
```

### Pipeline Pattern
```svg
<pattern id="pipeline" width="80" height="40" patternUnits="userSpaceOnUse">
  <line x1="0" y1="20" x2="80" y2="20" stroke="#FFD700" stroke-width="2" opacity="0.15"/>
  <line x1="0" y1="20" x2="80" y2="20" stroke="#003366" stroke-width="8" opacity="0.1"/>
  <circle cx="0" cy="20" r="4" fill="#FFD700" opacity="0.15"/>
  <circle cx="80" cy="20" r="4" fill="#FFD700" opacity="0.15"/>
</pattern>
```

### Geometric Grid Pattern
```svg
<pattern id="grid-pattern" width="40" height="40" patternUnits="userSpaceOnUse">
  <path d="M0 20 L40 20 M20 0 L20 40" stroke="#FFD700" stroke-width="0.5" opacity="0.15"/>
  <rect width="40" height="40" fill="none" stroke="#003366" stroke-width="0.5" opacity="0.1"/>
</pattern>
```

---

## Usage in CSS

```css
/* Apply patterns as background overlays */
.hero-section {
  background: 
    url('pattern.svg'),
    linear-gradient(...);
}

/* Or inline in CSS */
body {
  background-image: url("data:image/svg+xml,%3Cpattern id='oil-droplet'...");
}
```

---

## Image Dimensions Required

| Element | Dimensions | Aspect Ratio |
|---------|-------------|--------------|
| Hero BG | 1920x1080 | 16:9 |
| Fuel Cards | 400x250 | 16:10 |
| Service Images | 400x250 | 16:10 |
| Logo | 108x108 | 1:1 |
| Partner Logos | 42x42 | 1:1 |
| Icon Cards | 108x64 | ~1.7:1 |

---

## License Notes
- **Unsplash**: Free, no attribution required
- **Pexels**: Free, no attribution required  
- **Vecteezy**: Some free, check license
