---
"@json-render/core": minor
"@json-render/astro": minor
---

Add @json-render/astro SSR HTML renderer

### New:

- **@json-render/astro**: SSR renderer that converts JSON specs into HTML strings on the server. Zero framework dependencies — works in Astro, Cloudflare Workers, Node.js, Deno, Bun, or any server environment.
- `renderToHtml(spec, options)`: synchronous render function producing HTML strings
- `escapeHtml(str)`: XSS prevention utility for user content
- `schema`: SSR-first element schema for `defineCatalog`
- Sub-path exports: `@json-render/astro`, `@json-render/astro/server`, `@json-render/astro/render`
- Astro Islands pattern: static SSR via `@json-render/astro` + interactive islands via `@json-render/react` (or Vue, Svelte, Solid)
- Full support for `$state`, `$cond`, `$item`, `$index`, `visible`, and `repeat` expressions
- Astro example project with SSR demo and React island counter
