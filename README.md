# ThemeAudit (Shopify Theme Performance + A11y Auditor)

ThemeAudit is a dependency-free CLI that scans a Shopify theme folder and reports common performance + accessibility issues:
- Missing `alt` on images
- Render-blocking scripts (non-deferred)
- Large/unoptimized image usage patterns
- Inline script/style bloat signals
- Missing `loading="lazy"` hints
- Excessive asset counts / suspicious duplicates

