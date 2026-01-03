# Content Collections

## What This Section Covers

**Defining Collections**
- Setting up collections in `src/content/config.ts`
- Collection schemas with Zod
- TypeScript type generation for content
- Organizing content in `src/content/` directory

**Collection Schemas**
- Defining frontmatter structure
- Required vs optional fields
- Custom field types and validation
- Image fields in frontmatter

**Querying Collections**
- Using `getCollection()` to fetch all entries
- Using `getEntry()` for single entries
- Filtering and sorting collection data
- Type-safe queries with inferred types

**Rendering Content**
- Using the `render()` function
- Extracting and rendering MDX/Markdown
- Accessing frontmatter data
- Rendering in SSG vs SSR modes

**Content Types**
- Markdown (`.md`) files
- MDX (`.mdx`) files for component integration
- JSON and YAML data files
- Using components in MDX content

**Dynamic Routes from Collections**
- Generating pages from collection entries
- Using `getStaticPaths()` with collections
- SEO and metadata from content
