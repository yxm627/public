# SEO Audit Report

> Audited: 2026-05-26
> Pages: `composio-vs-qveris/index.html`, `mcp-server/index.html`

---

## 1. composio-vs-qveris/index.html

### 🔑 Keywords
| Check | Status |
|-------|--------|
| Main keyword in URL slug (`/composio-vs-qveris`) | ✅ |
| Title ≤ 60 chars ("Composio vs QVeris 2026: Which AI Agent Platform Wins?" = 56 chars) | ✅ |
| Meta description ≤ 155 chars | **❌ 172 chars** |
| Only 1 `<h1>` | ✅ |
| Main keyword in first 100 words of body | ✅ |
| Main keyword in ≥ 2 `<h2>` | **❌** Exact phrase "Composio vs QVeris" only in 1 H2 (FAQ). "Composio" and "QVeris" individually appear in "Quick Start: Switching from Composio to QVeris" + FAQ |
| Secondary keywords (e.g. "AI agent platform", "comparison") appear 2-3x | ✅ |

### 📄 Head
| Check | Status |
|-------|--------|
| `<title>` | ✅ |
| `<meta name="description">` | ✅ (172 chars — exceeds 155) |
| `<meta name="robots" content="index, follow">` | ✅ |
| `<link rel="canonical">` (`https://qveris.ai/composio-vs-qveris`) | ✅ |
| `<meta name="viewport">` | ✅ |
| og:title / og:description / og:url / og:image | ✅ |
| og:image:width (1200) / og:image:height (630) | ✅ |
| og:image:alt | ✅ |
| twitter:card / twitter:title / twitter:description / twitter:image | ✅ |

### 🔗 Links
| Check | Status |
|-------|--------|
| Nav links (4) — Product, Pricing, Docs, Get Started | ✅ |
| Internal links (5 related guides — relative paths) | ✅ |
| External links (composio.dev × 4, verify current) | ✅ |
| Footer links (23) | ✅ |
| CTA button links (2 × qveris.ai) | ✅ |
| OG image URL reachable | ⚠️ Cannot verify (domain not in allowlist) |
| Canonical URL accessible | ⚠️ Cannot verify (domain not in allowlist) |

### 🖼 Images
| Check | Status |
|-------|--------|
| `img { max-width: 100%; height: auto; }` in CSS | **❌ Missing** — only `.viz svg` has width:100% |
| At least 3 screenshots in body | **❌** 0 real screenshots (SVG matrix + data URI avatar only) |
| All images have `alt` | ✅ |
| All images have `width` + `height` | ✅ |
| `loading="lazy"` on below-fold images | ✅ (author avatar) |
| `title` attribute on all images | **❌** Missing on all images |
| Single image < 200KB | ✅ (all are external or data URI) |

### 📋 Schema
| Type | Status |
|------|--------|
| Organization | ✅ |
| BreadcrumbList | ✅ |
| Article | ✅ |
| SoftwareApplication | ✅ |

### 📝 Content
| Check | Status |
|-------|--------|
| H hierarchy no skip (H1→H2→H3) | ✅ |
| Word count | ~3,200 words |
| At least 1 comparison table | **⚠️** SVG visual matrix used instead of HTML `<table>` |
| FAQ ≥ 4 questions | ✅ (6: 3 visible + 3 in expandable section) |
| Internal links ≥ 2 other articles | ✅ (5 related guides) |
| CTA button present | ✅ (2 CTAs) |

---

## 2. mcp-server/index.html

### 🔑 Keywords
| Check | Status |
|-------|--------|
| Main keyword in URL slug (`/mcp-server/`) | ✅ |
| Title ≤ 60 chars ("MCP Server: 8 Best Servers & How They Work (2026) \| QVeris" = 57 chars) | ✅ |
| Meta description ≤ 155 chars | **❌ 180 chars** |
| Only 1 `<h1>` | ✅ |
| Main keyword in first 100 words | ✅ |
| Main keyword in ≥ 2 `<h2>` | **⚠️** "MCP Server" appears in 1 exact H2 (What Is an MCP Server?). Appears in 4+ H2s as partial match |
| Secondary keywords (e.g. "MCP servers", "meta-server", "MCP client") appear 2-3x | ✅ |

### 📄 Head
| Check | Status |
|-------|--------|
| `<title>` | ✅ |
| `<meta name="description">` | ✅ (180 chars — exceeds 155) |
| `<meta name="robots" content="index, follow">` | ✅ |
| `<link rel="canonical">` (`https://try.qveris.ai/mcp-server/`) | ✅ |
| `<meta name="viewport">` | ✅ |
| og:title / og:description / og:url / og:image | ✅ |
| og:image:width (1200) / og:image:height (630) | ✅ |
| og:image:alt | ✅ |
| twitter:card / twitter:title / twitter:description / twitter:image | ✅ |
| twitter:image:alt | ✅ |

### 🔗 Links
| Check | Status |
|-------|--------|
| Nav links (4) — Product, Pricing, Docs, Get Started | ✅ |
| Internal links (5 related guides — relative paths) | ✅ |
| External links (GitHub repos, toolradar.io, cdata.ai, lushbinary.com, etc.) | ✅ |
| Footer links | ✅ |
| CTA button links | ✅ |
| OG image URL reachable | ⚠️ Cannot verify |

### 🖼 Images
| Check | Status |
|-------|--------|
| `img { max-width: 100%; height: auto; }` in CSS | **❌ Missing** — only `.viz svg` has width:100% |
| At least 3 screenshots in body | **❌** 2 images in body (`one.png`, `two.png`) |
| All images have `alt` | ✅ (both one.png and two.png have descriptive alt) |
| All images have `width` + `height` | **❌** `one.png` and `two.png` missing width/height attributes |
| `loading="lazy"` on below-fold images | **❌** `one.png` and `two.png` missing loading="lazy" |
| `title` attribute on all images | **❌** Missing on all images (nav logo, one.png, two.png) |
| Single image < 200KB | ⚠️ Cannot verify local files |

### 📋 Schema
| Type | Status |
|------|--------|
| Organization | ✅ |
| BreadcrumbList | ✅ |
| Article | ✅ |
| ItemList (8 servers) | ✅ |
| DefinedTerm (MCP Server) | ✅ |
| FAQPage (6 questions) | ✅ |

### 📝 Content
| Check | Status |
|-------|--------|
| H hierarchy no skip (H1→H2→H3) | ✅ |
| Word count | ~5,500 words |
| At least 1 comparison table | ✅ (metric table + deployment compare table) |
| FAQ ≥ 4 questions | ✅ (6 questions) |
| Internal links ≥ 2 other articles | ✅ (5 related guides) |
| CTA button present | ✅ |

---

## 🔴 Critical Issues (Both Pages)

| # | Issue | composio-vs-qveris | mcp-server |
|---|-------|-------------------|------------|
| 1 | Meta description > 155 chars | **172 chars** | **180 chars** |
| 2 | Missing `img { max-width: 100%; height: auto; }` in CSS | ❌ | ❌ |
| 3 | Missing `title` attributes on all images | ❌ | ❌ |
| 4 | Body screenshots < 3 | ❌ (0) | ❌ (2) |
| 5 | `one.png` / `two.png` missing width, height, lazy | — | ❌ |

## 🟡 Secondary Issues

| # | Issue | composio-vs-qveris | mcp-server |
|---|-------|-------------------|------------|
| A | Main keyword in only 1 `<h2>` | ❌ | ⚠️ |
| B | HTML comparison `<table>` missing (uses SVG instead) | ⚠️ | ✅ |
| C | OG image / canonical URL not verifiable | ⚠️ | ⚠️ |
