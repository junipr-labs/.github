# Junipr

**Web automation APIs for developers. Screenshots, PDFs, and metadata extraction — just HTTP.**

---

Junipr provides simple REST APIs for common web automation tasks. No browser infrastructure to manage, no SDKs required — just standard HTTP requests.

### APIs

- **Screenshot API** — Capture full-page or viewport screenshots in PNG, JPEG, or WebP
- **PDF API** — Generate PDFs from any URL or HTML content
- **Metadata API** — Extract structured metadata, Open Graph tags, and page information

### Get Started

```bash
curl -X POST https://api.junipr.io/v1/screenshot \
  -H "X-API-Key: YOUR_KEY" \
  -H "Content-Type: application/json" \
  -d '{"url": "https://example.com", "format": "png"}'
```

Sign up at [junipr.io](https://junipr.io) to get your API key.
