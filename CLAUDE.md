# WinBack App — Project Context for Claude

## App Overview
WinBack is a Shopify app that helps merchants manage and fight chargebacks/disputes.
It only works with merchants on **Shopify Payments** (not third-party processors).

---

## WinBack Logo

**ALWAYS use this logo** in all screenshots, mockups, and UI elements. Never substitute a plain circle or placeholder.

The logo is:
- **Outer container**: Dark navy blue rounded square background (~#1c2f6e)
- **Shield**: Green shield shape (~#2e7d52) centered on the background
- **Arrow**: White upward-pointing arrow inside the shield

### Inline SVG for the nav icon (28×28 area, positioned at top-left nav):

```svg
<!-- WinBack logo icon (use in nav, replace any purple circle placeholder) -->
<g transform="translate(8, 8)">
  <!-- Navy rounded square background -->
  <rect width="24" height="24" rx="5" fill="#1c2f6e"/>
  <!-- Green shield -->
  <path d="M12 3 L19 6 L19 14 Q19 19 12 22 Q5 19 5 14 L5 6 Z" fill="#2e7d52"/>
  <!-- White arrow -->
  <path d="M12 7 L15.5 11.5 L13.2 11.5 L13.2 16.5 L10.8 16.5 L10.8 11.5 L8.5 11.5 Z" fill="#ffffff"/>
</g>
```

For larger icon placements (e.g. 40×40), scale accordingly.

---

## Screenshot Specs (Shopify App Store)

- **Desktop**: 1280×720 PNG (`winback-desktop-1/2/3.png`)
- **Mobile**: 750×1334 PNG (`winback-mobile-1/2/3.png`)
- Export tool: `shopify-screenshot.html` — open in Chrome and click download buttons

---

## Brand Colors

| Name | Hex |
|------|-----|
| Navy (background) | `#1c2f6e` |
| Green (shield/accent) | `#2e7d52` |
| White | `#ffffff` |
| Shopify UI gray | `#f1f2f3` |
| Shopify nav dark | `#1a1a1a` |
| Shopify purple accent | `#5c6ac4` |
