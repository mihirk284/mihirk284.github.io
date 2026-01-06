# Gallery Template Documentation

## Overview

The `gallery` shortcode displays a collection of images in a responsive grid. It uses Zola's block shortcode syntax and requires images to be specified within the block.

## Correct Syntax

> [!IMPORTANT]
> The gallery MUST use `{%` delimiters and be closed with `{% end %}`.

```markdown
{% gallery(title="My Photo Collection", columns=3) %}
gallery/image1.jpg | Description of image 1
gallery/image2.jpg | Description of image 2
{% end %}
```

## Parameters

| Parameter | Type | Default | Description |
|-----------|------|---------|-------------|
| `title` | String | `""` | Optional title displayed above the gallery |
| `columns` | Integer | `3` | Number of columns in the grid (desktop) |
| `gap` | String | `"1rem"` | Spacing between images (CSS units) |

## Image Paths

- Use paths relative to the `content` directory (e.g., `gallery/photo.jpg`).
- If using remote images, start with `http`.

## Features
- **Responsive**: Auto-adjusts columns for mobile and tablet.
- **Aspect Ratio**: 1:1 square thumbnails by default.
- **Hover Effects**: Subtle lift and scale animation.
- **Lazy Loading**: Enabled by default for performance.
