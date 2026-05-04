# Abacus Marketing Assets

Public repository hosting marketing imagery for Abacus Brands product showcases, served via [jsDelivr](https://www.jsdelivr.com/) CDN.

## Usage

Reference any asset in HTML or markdown using the jsDelivr URL pattern:

```
https://cdn.jsdelivr.net/gh/blakeradacus/abacus-marketing-assets@main/<folder>/<filename>
```

### Example

```html
<img src="https://cdn.jsdelivr.net/gh/blakeradacus/abacus-marketing-assets@main/pixicade/pixicade-core-render.png" alt="Pixicade">
```

## Structure

| Folder | Contents |
|--------|----------|
| `pixicade/` | Pixicade product line — core, Plus, Star Wars, Alan Becker editions, displays |

Additional brand folders will be added as needed (Radical Games, Barbie Magic Style Studio, Bill Nye, NatGeo, etc.).

## Asset guidelines

- **Format**: PNG for product renders with transparency; JPEG for photographic content
- **Compression**: All images should be compressed before commit (target <500KB per file, <200KB preferred)
- **Naming**: lowercase, hyphen-separated, descriptive (e.g. `pixicade-plus-package.png`, not `IMG_4837.png`)
- **No proprietary content**: This repo is public. Sales decks, internal docs, and unreleased product imagery do not belong here.

## Versioning

For stable references that won't break if assets are updated, pin to a tag instead of `@main`:

```
https://cdn.jsdelivr.net/gh/blakeradacus/abacus-marketing-assets@v1.0.0/pixicade/...
```

## Maintained by

Abacus Brands — [abacusbrands.com](https://www.abacusbrands.com)
