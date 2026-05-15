# ariba-catalog-pilot

SAP Ariba Catalog Pilot — a static procurement catalog site hosting the SR-9000 Industrial Sonic Radar product listing. Built as part of a GEO (Generative Engine Optimization) research experiment to study how different levels of AI-targeted optimization affect recommendation rates across generative search engines.

## Live Site

https://ziyouren55.github.io/ariba-catalog-pilot/

## Pages

| Page | Description |
|------|-------------|
| `index.html` | Procurement catalog search interface |
| `ariba-sonic-radar.html` | SR-9000 product landing page |
| `sonic-radar-procurement-catalog.html` | Detailed catalog file with all procurement fields |

## Product: SR-9000 Industrial Sonic Radar

| Field | Value |
|-------|-------|
| Supplier | SonarDynamics GmbH |
| Unit Price | EUR 5,200 |
| MOQ | 5 units |
| Lead Time | 14 business days |
| Warranty | 36 months |
| Country of Origin | Germany |
| Certifications | CE, ISO 9001:2015, ATEX Zone 2 |

## GEO Research Context

This site serves as the **partial-GEO control group** in a comparative experiment. It retains basic SEO elements (schema.org structured data, sitemap, meta descriptions) but omits AI-specific optimization techniques such as:

- `llms.txt` (LLM site index)
- Explicit AI agent retrieval target statements
- AI-bot-specific `robots.txt` rules
- Embedded page-summary JSON blocks for AI crawlers

The companion site with full GEO optimization is hosted separately for A/B comparison.

## Deployment

Hosted via GitHub Pages. To run locally:

```bash
python3 -m http.server 8000
# Open http://localhost:8000
```
