# UI Frameworks & Islands

## What This Section Covers

**Framework Integrations**
- Installing and configuring framework integrations (React, Vue, Svelte, Solid, Preact)
- Using `@astrojs/react`, `@astrojs/vue`, etc.
- File extensions for framework components (`.jsx`, `.tsx`, `.vue`, `.svelte`)

**Client Directives**
- `client:load` - Load and hydrate immediately
- `client:idle` - Hydrate when browser is idle
- `client:visible` - Hydrate when component enters viewport
- `client:media` - Hydrate based on media query
- `client:only` - Skip server rendering, only render on client

**Using React with Astro**
- Setting up React integration
- Converting React components from Next.js
- Using React hooks in Astro islands
- When to use React vs Astro components

**Island Architecture Patterns**
- Identifying interactive vs static components
- Partial hydration strategy
- Component composition with islands
- Performance optimization through selective hydration

**Sharing State Between Islands**
- Using nano stores or other state management
- Framework-specific state solutions
- Limitations and workarounds
