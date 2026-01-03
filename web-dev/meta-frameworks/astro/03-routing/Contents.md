# Routing

## What This Section Covers

**File-Based Routing**
- How files in `src/pages/` map to routes
- Page naming conventions
- Index routes and nested routes
- Comparison with Next.js App Router and Pages Router

**Dynamic Routes**
- Creating dynamic route parameters with `[param]` syntax
- Accessing route params via `Astro.params`
- Rest parameters with `[...slug]`

**Static Site Generation with getStaticPaths()**
- Using `getStaticPaths()` to generate routes at build time
- Returning params and props for each route
- Fetching data for dynamic routes
- Comparison with Next.js `getStaticPaths` and `getStaticProps`

**Route Priority**
- Understanding route matching order
- Static routes vs dynamic routes priority

**Redirects**
- Client-side redirects with `Astro.redirect()`
- Configuration-based redirects
